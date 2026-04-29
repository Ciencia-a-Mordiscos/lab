# Ciencia a Mordiscos

**La ciencia que contamos en video, aquí se puede tocar.**

![Dataciones de Monte Verde por estrato](papers/2026-03-27-monte-verde-fecha-mal/figuras/dataciones_por_estrato.png)

Un video de 90 segundos engancha. Pero no puedes ver los datos, no puedes cuestionar los números, no puedes explorar por tu cuenta.

Aquí sí. Cada notebook toma un paper de Nature, Science o revistas similares, carga los datos originales, genera las gráficas, y te deja cambiar lo que quieras. No necesitas saber programar — abre en Google Colab, dale "Ejecutar todo", y los datos hablan solos.

---

## Notebooks
### Primera eyección de masa coronal fuera del Sol

**Astronomía** · *Nature* · Callingham et al. (2025) reportan, con LOFAR, la primera detección directa de un análogo de **type II radio burst** desde una estrella distinta del Sol — la M dwarf temprana **StKM 1-1262** a ~32 años luz. El burst dura ~4 minutos en banda HBA (120-167 MHz) y muestra deriva en frecuencia + polarización Stokes V idénticas a las CMEs solares (la firma física de una onda de choque saliendo de la corona). El equipo descarta una explicación alternativa (loop magnético cerrado, modelo ECMI) ajustando con MCMC **6.356 muestras posteriores × 9 parámetros** y mostrando que recupera la deriva pero NO la sub-estructura del burst. La tasa derivada de eventos similares es **0,84 × 10⁻³ por día por estrella M** (rango asimétrico -0,69 / +1,94, basado en n=1 detección en ~10.500 h de monitoreo) — en promedio una vez cada ~3 años por estrella, con varianza enorme. ⚠️ El paper enmarca la implicación para erosión atmosférica de exoplanetas como hipótesis (*implies*), no demostración: una detección no establece estadística poblacional.

[Ver notebook](papers/2026-01-17-primera-eyeccion-estelar-fuera-sol/notebook) · [Leer más](papers/2026-01-17-primera-eyeccion-estelar-fuera-sol/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-primera-eyeccion-estelar-fuera-sol/notebook.ipynb)

---

### El castigo no siempre promueve cooperación: depende mucho de las reglas

**Psicología** · *Science* · Alsobay et al. (2026) corrieron un mega-experimento de **360 versiones** del juego de bienes públicos: **7.100 personas, 147.618 decisiones**, variando 14 parámetros del juego (rondas, magnitud del castigo, posibilidad de chatear, contribución todo-o-nada, etc.) para responder una pregunta vieja: ¿el castigo a quien no coopera realmente promueve cooperación? El paper encuentra **heterogeneidad masiva**: el efecto del castigo va **de +43% (mejora) a -44% (destruye)** en bienestar según los parámetros — y en los datos crudos pareados (170 condiciones) la nube va aún más lejos: de **+26% a -77,5%**. El **57,6% (98/170)** de las condiciones muestran que añadir castigo EMPEORA el bienestar; solo **42,4% (72/170)** lo mejora. El paper afirma que la **comunicación** emerge como el factor más predictivo, pero la **diferencia simple de medias entre con/sin chat es pequeña** (Cohen d=0,19, Mann-Whitney p=0,35) — la importancia surge en interacciones con los otros 13 parámetros, no como pendiente directa. ⚠️ Datos de Mechanical Turk (EE.UU.); el "factor #1 comunicación" es feature importance del modelo predictivo, no un efecto univariado significativo.

[Ver notebook](papers/2026-04-28-castigo-cooperacion-bienes-publicos/notebook) · [Leer más](papers/2026-04-28-castigo-cooperacion-bienes-publicos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-28-castigo-cooperacion-bienes-publicos/notebook.ipynb)

---

### Expansiones STR a escala poblacional revelan atrofia cerebral preclínica

**Medicina** · *Nature* · Regeneron Genetics Center et al. (2026) cruzan **37 loci STR patogénicos** con 7.671 rasgos clínicos en **1.020.833 muestras** de 5 cohortes (UK Biobank, GHS, Mayo, Penn, MCPS). El método recupera las asociaciones canónicas con OR enormes — **HTT-Huntington OR=1.396** (p=3·10⁻¹²²), DMPK-distrofia miotónica OR=601, C9ORF72-motoneurona OR=99 — lo que da licencia para mirar el hallazgo más fuerte: en una sub-cohorte con imagen cerebral (~58k–63k normales), los **9 portadores patogénicos de HTT** muestran un **22,1% menos de volumen del putamen** (p=1,4·10⁻¹⁸) y los **10 de CACNA1A** un **24,6% menos de volumen del cerebelo**, todos sin diagnóstico clínico aún. NfL en sangre sube **1,9× en HTT** (p=2,1·10⁻¹²) — biomarcador validado de daño neuronal. El gap más dramático: **44 portadores de C9orf72 por cada paciente diagnosticado** con motoneurona. ⚠️ Estudio observacional **transversal**: el abstract dice *"occur earlier than diagnosis"* (parece preceder), NO "comienza antes" — sin seguimiento longitudinal individual. Penetrancia incompleta + edad de aparición tardía + subdiagnóstico no se separan. n=9 y n=10 son señales fuertes pero muestras chicas. Sub-cohorte de imagen es ~98% europea.

[Ver notebook](papers/2026-04-08-repeticiones-str-atrofia-cerebral/notebook) · [Leer más](papers/2026-04-08-repeticiones-str-atrofia-cerebral/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-08-repeticiones-str-atrofia-cerebral/notebook.ipynb)

---

### 5 pacientes con β-talasemia, 23 meses sin transfusiones

**Medicina** · *Nature* · Lai et al. (2026) reportan el primer trial Fase 1 (NCT06024876, **N=5**) de un *base editor* clínico (CS-101) que desactiva el sitio donde el represor BCL11A apaga la hemoglobina fetal. Tras la infusión de células CD34+ propias editadas, los **5 pacientes dejaron las transfusiones** (mediana 18 días a la última). La hemoglobina total a 3 meses fue **12,4 ± 1,0 g/dl** (cálculo propio reproduce: 12,44 ± 1,04), dentro del rango normal adulto. La HbF subió **31×** desde el baseline (0,41 → 12,77 g/dl al mes 12). En las réplicas pareadas in vitro, la edición pasó de **4 alelos por cada 10.000 (NT) a 6 de cada 10 (Editadas)** — Wilcoxon signed-rank pareado: W=15, p=0,031 unilateral, Cohen's dz=68,7. La edición se mantiene estable en sangre periférica entre **26-54%** durante 21 meses, lo que sugiere que las células madre verdaderas heredaron el cambio. **3 de los 5 pacientes son β0/β0** (no producen ninguna β-globina endógena): su sangre es **99-100% hemoglobina fetal** y aun así viven sin transfusiones — un regreso evolutivo dirigido. ⚠️ N=5, single-arm, sin grupo control: eficacia clara dentro del trial pero NO comparable contra otras terapias (Casgevy, lentiviral, alogénico) sin head-to-head. Mediana 23 meses → seguimiento intermedio, no "a largo plazo". Eventos adversos consistentes con busulfán mieloablativo (no triviales). 0 muertes y 0 cánceres en el seguimiento.

[Ver notebook](papers/2026-04-08-edicion-bases-beta-talasemia-clinico/notebook) · [Leer más](papers/2026-04-08-edicion-bases-beta-talasemia-clinico/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-08-edicion-bases-beta-talasemia-clinico/notebook.ipynb)

---

### Las plantas absorben menos CO₂ desde 2001 — y son las tierras secas las culpables

**Ecología** · *Nature Geoscience* · Li et al. (2026) cruzan **40 años de torres FLUXNET con machine learning satelital (1982–2022)** y detectan que la absorción de carbono vegetal del planeta se está frenando, pero el frenado no se reparte por igual: en las regiones húmedas la fotosíntesis sigue subiendo casi al mismo ritmo (slope cae solo **−12,6%**, p=4×10⁻⁷), mientras que en las **tierras secas** el ritmo cayó **−71,7%** (de **+2,73 a +0,77 gC/m²/año**, y el segundo slope ya no es significativo: p=0,21). El sospechoso climático es el **VPD** ("sed del aire"): en esas mismas zonas su tendencia se aceleró **×12** después de 2001 (de +0,35 a +4,31 Pa/año por año). Los **ESMs CMIP6** (los modelos del IPCC) predicen lo contrario de lo observado: **+0,48 vs −1,95** en cambio de tendencia — divergencia de signo, no solo de magnitud. ⚠️ El paper habla de "atribuido principalmente a", **no causalidad** — es estudio observacional, los autores son cuidadosos y el notebook lo respeta.

[Ver notebook](papers/2026-04-01-tierras-secas-frenan-co2-vegetal/notebook) · [Leer más](papers/2026-04-01-tierras-secas-frenan-co2-vegetal/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-01-tierras-secas-frenan-co2-vegetal/notebook.ipynb)

---

### Un vidrio con la fuerza del diamante y la tenacidad de un metal

**Tecnología** · *Nature* · Cai et al. (2026) sintetizan **5 vidrios metálicos masivos** Re-Co-Ta-B y miden una combinación que llevaba décadas vacía en el plano resistencia-tenacidad: **6,43 GPa de fuerza** (cerca del diamante policristalino, 6,9-7,0 GPa) con **30 MPa·m^1/2 de tenacidad** — **3,4×** la mejor cerámica de su nivel de resistencia (PCD K1C=8,8). A **900 K** mantiene **4,4 GPa** (caída del **31,6%**, mejor que la mayoría de BMGs comparables). En los 8 materiales del dataset con σy ≥ 5 GPa, la mediana de tenacidad es 5,97 — el Re-Co-Ta-B la quintuplica. Más renio sube la temperatura de transición vítrea (Tg, 1001-1113 K) pero baja el espesor crítico de colada (3-4 mm). ⚠️ El mecanismo atómico (orden de corto rango heredado del Re7B3 + enlaces Re-B direccionales) viene de DFT computacional — el paper lo presenta como hipótesis (*suggests*), no como observación directa. Renio ~1500 USD/kg: investigación, no producción a escala.

[Ver notebook](papers/2026-04-22-vidrio-metalico-resistencia-ceramica/notebook) · [Leer más](papers/2026-04-22-vidrio-metalico-resistencia-ceramica/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-22-vidrio-metalico-resistencia-ceramica/notebook.ipynb)

---

### +23,9% más genes de resistencia a antibióticos en un suelo calentado 3°C

**Ecología** · *Nature* · Wu et al. (2026) calientan parcelas de pradera en Oklahoma a **+3°C constantes durante 11 años (2010–2020)** y secuencian el ADN del suelo en 88 muestras finales. La abundancia de genes de resistencia a antibióticos sube **+23,9%** vs control (LMM ajustado; nuestra mediana directa da +23,6%, coincide a 0,3 puntos). Cohen's d = 0,24 — efecto pequeño pero consistente: en los 11 de los 11 años la mediana del calentado supera a la control. Las clases más afectadas son **glicopéptidos (+24,4%, p=0,023) y rifamicinas (+25,6%, p=0,003)** — dos antibióticos que los hospitales reservan para infecciones difíciles. MLS/macrólidos sube más que ambas (+31,8%, p=0,0008) pero el abstract no lo destaca. Mann-Whitney unilateral en abundancia total: p=0,009. ⚠️ El paper enmarca la transferencia horizontal de genes como hipótesis especulativa (*could be further amplified*), no como observación directa — la sostenemos ahí, no escalamos.

[Ver notebook](papers/2026-04-27-calentamiento-resistencia-suelos/notebook) · [Leer más](papers/2026-04-27-calentamiento-resistencia-suelos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-27-calentamiento-resistencia-suelos/notebook.ipynb)

---

### La huella humana en las mareas: 25 ríos cambiados

**Ecología** · *Nature Geoscience* · Beemster et al. (2026) cruzan registros históricos (s. XIX–XX) y modernos (1990–2024) de **25 estuarios** en 9 países. **16 de 25 amplificaron** su rango máximo de marea (mediana **+8,6%**, rango de **+38,5%** en Coos Bay a **−17,2%** en James). La onda de marea entra y se transforma: la velocidad sube **~35%** (paper: 38%) en 21 de 24 estuarios. Pero el dato que reordena la intuición está en la geografía del cambio: **0 de 25 estuarios** tienen su máximo cambio en la boca. La mediana del punto de máximo cambio está a **94 km tierra adentro** (IQR 55–147 km), y la mediana del cambio interior es **57 cm** vs **6 cm** en la boca — casi un orden de magnitud. ¿Quién pone esa marca? Una huella humana cuantificada: **233 intervenciones** documentadas, lideradas por profundización de canales (113 eventos en **22 de 25 estuarios** — 88%) y recuperación de tierra (25 eventos en 14 de 25). ⚠️ Diseño observacional longitudinal: la concordancia espacio-temporal entre intervenciones y cambios respalda la lectura causal del paper, pero no la prueba como un experimento.

[Ver notebook](papers/2026-04-27-mareas-estuarios-huella-humana/notebook) · [Leer más](papers/2026-04-27-mareas-estuarios-huella-humana/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-27-mareas-estuarios-huella-humana/notebook.ipynb)

---

### 1,65 MJ/kg en una pirimidona: cinco veces más densidad que el azobenceno

**Tecnología** · *Science* · Nguyen et al. (2026) sintetizan **4 pirimidonas** (P-1 a P-4, bases del ADN modificadas) y las irradian con UV a **310 nm** para forzarlas al isómero Dewar — un anillo tensionado, como un resorte molecular. Los datos de las Tablas S1-S7 del Supporting muestran que **D-3 almacena 1,65 MJ/kg** medido por DSC, **5,2×** la densidad energética del cis-azobenceno (0,318 MJ/kg) que llevaba 40 años siendo el referente MOST. Una gota de HCl en 1 mL de agua sobre 106 mg de D-3 sube la temperatura **75,76 K** por cámara IR — alcanza ~100°C desde temperatura ambiente. La eficiencia de transferencia es **87% (vs 42% en azobenceno)**, y el control sin Dewar (P-3 directo) apenas calienta 7 K — el calor viene de la reversión, no del ácido. P-3 ganó la carrera entre las 4 candidatas a pesar de no tener el Φ más alto (5,4% vs 7,8% de P-4) porque P-4 es líquido inmiscible. ⚠️ ΔG‡ = 117 kJ/mol extrapolado por Eyring desde mediciones a 85-95°C; la estabilidad real a temperatura ambiente no se midió directamente. El paper cierra con hedge T2 explícito ("apuntan el camino" hacia almacenamiento solar descentralizado).

[Ver notebook](papers/2026-04-27-pirimidona-dewar-energia-solar/notebook) · [Leer más](papers/2026-04-27-pirimidona-dewar-energia-solar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-27-pirimidona-dewar-energia-solar/notebook.ipynb)

---

### El Amazonas que enfría: 6.8 W/m² de paradoja

**Ecología** · *Science* · Dror et al. (2026) cruzan dos décadas de satélites CERES y MODIS sobre el Amazonas, separando el flujo radiativo en el techo de la atmósfera (TOA) por fracción de pérdida de bosque. Los datos resumidos del NOAA Chemical Sciences Laboratory (122 bins de f_loss, 24 valores de feedback) muestran que en zonas de alta deforestación (f_loss ≥ 0,5) el flujo de onda corta saliente sube **6,76 ± 0,60 W/m²** vs bosque intacto — coincidiendo al 0,6% con el headline del paper (6,8 ± 0,6). Las nubes amplifican ese efecto: la amplificación de albedo es **× 2,2** vs el cambio de suelo desnudo, y la del flujo SW **× 3,4**. La onda corta domina sobre la onda larga por **× 12**. La pendiente OLS contra f_loss llega a **11 W/m² por unidad** (R² = 0,61, p ≈ 0, n = 122). ⚠️ Solo balance radiativo — NO incluye carbono liberado, humedad atmosférica ni ciclo hidrológico continental. El propio abstract dice que estos resultados *"apoyan"* (no *"demuestran"*) su uso en políticas climáticas.

[Ver notebook](papers/2026-04-23-amazon-forest-cooling-feedback/notebook) · [Leer más](papers/2026-04-23-amazon-forest-cooling-feedback/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-23-amazon-forest-cooling-feedback/notebook.ipynb)

---

### Una red biohíbrida que se mueve y captura nanoplásticos

**Tecnología** · *Nature Water* · Fan et al. (2026) construyen una red diminuta — fibrillas amiloides de **lisozima** (la proteína de la clara del huevo) decoradas con nanopartículas de óxido de hierro: las **LAF-IONPs**. Bajo un campo magnético alterno, la red se sacude y caza nanoplásticos. Los datos de los Source Data MOESM8/10/11 muestran que el truco está en el movimiento: estática captura solo **40,1%**, dinámica **99,3%** (×2,47, Cohen d ≈ 71). La eficiencia se mantiene entre **94,6%** (10 mg/L) y **99,6%** (500 mg/L), aguanta **100 ciclos** de reuso cayendo apenas **4,3 puntos porcentuales** (de 100,1% a 95,8%), y reduce un **91,5%** del plástico bioacumulado en ratones C57BL/6. ⚠️ Solo ratones — no hay datos clínicos humanos; las eficiencias del 99% son sobre agua sintética con poliestireno puro.

[Ver notebook](papers/2026-04-23-nanonets-amiloide-nanoplasticos/notebook) · [Leer más](papers/2026-04-23-nanonets-amiloide-nanoplasticos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-23-nanonets-amiloide-nanoplasticos/notebook.ipynb)

---

### La cooperación cae cada vez más rápido

**Psicología** · *Nature* · Sabin et al. (2026) siguen durante 5 años a 7.108 prestatarios en Sierra Leona — 47.931 pagos de microcréditos en grupo (joint-liability). Los datos de los Source Data MOESM4-MOESM10 muestran que la cooperación cae cada vez más rápido: el ciclo 4 cae **3,37×** más empinado que el ciclo 1 (-19,07 pp vs -5,66 pp en 6 rondas). Cuando el préstamo reinicia, la cooperación rebota — y el rebote crece: reinicio 1 = -0,33σ, reinicio 2 = +5,47σ, reinicio 3 = **+15,9σ** (5,4× su error estándar). Y la motivación económica, la que la teoría racional clásica predice como dominante, es la **menos** mencionada por los entrevistados (17,2% vs 54,7% solidaridad). ⚠️ Diseño observacional con atrición fuerte (-81% de los grupos no llegan al ciclo 4): el patrón es robusto, la causa sigue abierta.

[Ver notebook](papers/2026-04-22-punctuated-decline-cooperation/notebook) · [Leer más](papers/2026-04-22-punctuated-decline-cooperation/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-22-punctuated-decline-cooperation/notebook.ipynb)

---

### Un implante cerebral sin cirugía: 5.8x más células donde hay inflamación

**Neurociencia** · *Nature Biotechnology* · Yadav et al. (2025) diseñan un implante cerebral **sin cirugía**: macrófagos recubiertos con proteína conductora cargados con fotodiodos del tamaño de bacterias (SWEDs), inyectados en sangre y activados con luz infrarroja desde fuera del cráneo. Los datos del Source Data MOESM3 (Fig 4f, 5f, 2g) muestran que los híbridos con luz se concentran **5,76× más** que el control completo en la zona inflamada (315 vs 55 cells/mm²) — Cohen's d = 4,24, p = 0,029 (Mann-Whitney, n=4 vs n=4). Bootstrap de 10.000 re-muestreos: el 100% supera el umbral de "efecto grande". Los SWEDs persisten 6 meses sin decaimiento detectable (aunque n=2-3 limita el test formal: U=1, p=0,40 entre 1d y 6m). Y el cráneo de ratón apenas atenúa la luz NIR — solo **11,6% de pérdida** a 46 mW/mm². Prueba de concepto en ratones con inflamación inducida por LPS — distancia regulatoria significativa antes de aplicación clínica.

[Ver notebook](papers/2025-11-05-implantes-cerebrales-circulatronics/notebook) · [Leer más](papers/2025-11-05-implantes-cerebrales-circulatronics/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-11-05-implantes-cerebrales-circulatronics/notebook.ipynb)

---

### Nanotubos al 41% del cobre con la mitad del peso

**Tecnología** · *Science* · de Isidro-Gómez et al. (2026) reportan fibras de nanotubos de carbono dobles intercaladas con aniones de tetracloroaluminato (AlCl₄⁻) en los huecos entre tubos. Los aniones aceptan **0,65 electrones por unidad** (DFT del paper, n=4 unidades en el unit cell — coincidencia exacta con el abstract), dejando huecos en el nanotubo exterior que aumentan los portadores de carga. Resultado: la conductividad pasa de **1,4 a 24,4 MS/m** en la mejor muestra individual — un factor 17,5× sobre la fibra pristine, y **41,6% del cobre puro**. La media del proceso ronda los 16 MS/m. Lo más relevante para aplicaciones: la conductividad específica (17.350 S·m²/kg) **supera a la del aluminio comercial (13.130) por factor 1,32**. Trabajamos con las 6 tablas del Supplementary del paper. ⚠️ El cable de 18 mm propuesto es proyección, no construido.

[Ver notebook](papers/2026-04-23-nanotubos-carbono-conductividad/notebook) · [Leer más](papers/2026-04-23-nanotubos-carbono-conductividad/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-23-nanotubos-carbono-conductividad/notebook.ipynb)

---

### Pulpos gigantes del Cretácico: ¿quiénes eran?

**Biología** · Science · Ikegami et al. (2026) describen dos fósiles cretácicos de cefalópodos del Pacífico canadiense (~100–72 Ma), con tamaños estimados de **7 a 19 metros**. Durante 370 millones de años los apex marinos han sido vertebrados — entonces, ¿qué linaje de pulpos eran estos invertebrados gigantes? Abrimos los datos morfológicos públicos (Figshare, CC BY 4.0): **PCoA sobre 19 caracteres mandibulares en 21 taxa** — 9 cirrados modernos (linaje Dumbo), 10 incirrados (linaje *Octopus*), 2 fósiles. PC1 + PC2 explican **81,1% de la varianza**. Resultado: los fósiles caen pegados al cluster cirrado. **9 de 9 cirrados modernos están más cerca morfológicamente de los fósiles que cualquiera de los 10 no-cirrados** (mediana 0,129 vs 0,351; ratio 2,72×; Mann-Whitney p=0,0003; Cohen's d=4,5). Sin solape entre grupos. El tamaño 7–19 m viene del paper, no de los CSVs públicos.

[Ver notebook](papers/2026-04-25-octopodos-gigantes-cretacico/notebook) · [Leer más](papers/2026-04-25-octopodos-gigantes-cretacico/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-25-octopodos-gigantes-cretacico/notebook.ipynb)

---

### ¿Puede una IA entender el mundo sin haberlo vivido?

**Tecnología** · PNAS · Xu et al. (2025) tomaron **66 modelos de lenguaje** — de 70 millones a 47 mil millones de parámetros — y midieron qué tan parecida era su representación interna de conceptos a la humana. Con datos abiertos de Zenodo, reproducimos dos de los tres claims: (1) cuanto más alineado con humanos es un modelo, mejor razona en 8 benchmarks (**Spearman ρ = 0,83, n = 66**), y (2) dentro de Llama-3-70B, la representación converge con más ejemplos *in-context* y la precisión sube en paralelo (**ρ = 0,98, n = 8 demos**). El giro incómodo: el modelo más alineado no es el más grande. **Llama-3 8B (0,74) gana a Mistral 8x7B de 47 mil millones de parámetros (0,72)**. El tercer claim del paper — similitud con actividad cerebral fMRI — no se reproduce aquí (requiere datos adicionales).

[Ver notebook](papers/2025-10-31-ia-conceptos-humanos-sin-vivir/notebook) · [Leer más](papers/2025-10-31-ia-conceptos-humanos-sin-vivir/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-10-31-ia-conceptos-humanos-sin-vivir/notebook.ipynb)

---

### Ultrasonido tomográfico del corte completo del cuerpo

**Medicina** · Nature Biomedical Engineering · Yang et al. (2026) construyen un aro de **60 cm con 512 receptores** y un transmisor que gira. El sujeto se sienta con el torso en un tanque de agua, y el sistema genera una imagen del corte transversal completo — como una TAC, pero con ultrasonido y sin radiación. Lo validan en cadena: líquido conocido (5 mezclas etanol-agua, error promedio 0,52%), fantasma de grasa sintética (sobreestima ~3%), y humanos contra MRI 3T (**Pearson r = 0,987, diferencia máxima 3 mm en n=6 líneas**). Y algo incómodo: un caliper de consulta subestima la grasa **40,6%** en un voluntario promedio — pellizcar comprime 1,3 cm de tejido que la imagen sí ve.

[Ver notebook](papers/2026-04-24-ultrasonido-tomografia-corte-completo/notebook) · [Leer más](papers/2026-04-24-ultrasonido-tomografia-corte-completo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-24-ultrasonido-tomografia-corte-completo/notebook.ipynb)

---

### Un robot le ganó 3 de 5 partidos a jugadores de élite en tenis de mesa

**Tecnología** · Nature · D'Ambrosio et al. (2026) construyeron **Ace**, un robot autónomo de Sony con dos brazos KUKA y un controlador entrenado con aprendizaje por refuerzo. En abril de 2025 lo enfrentaron bajo reglas oficiales ITTF a siete humanos — **cinco élite de club amateur y dos profesionales japoneses**. Contra los élite **ganó 3 de 5 partidos (7/13 sets)**. Contra los profesionales **perdió ambos (1/7 sets)**. Abrimos los **4.024 eventos** grabados (99 rallies, 1.953 golpes) y vemos la brecha: el techo operativo de Ace vive en **13,3 m/s** (su percentil 95); el **26% de los golpes humanos viven por encima** de ese umbral. Entre élite y pro hay un salto que los datos no esconden.

[Ver notebook](papers/2026-04-24-robot-tenis-mesa-elite/notebook) · [Leer más](papers/2026-04-24-robot-tenis-mesa-elite/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-24-robot-tenis-mesa-elite/notebook.ipynb)

---

### 333 piezas del cerebro: el atlas que está reescribiendo cómo medimos lo que hay dentro

**Neurociencia** · Nature · Iglesias et al. (2025) tomaron **5 hemisferios cerebrales completos**, los seccionaron en cerca de **10.000 láminas histológicas**, las alinearon en 3D con métodos de IA y delinearon manualmente **333 regiones de interés**. El error medio de registro 3D **baja un 31% (de 1,44 a 0,99 mm)** frente al pipeline anterior — y los 5 hemisferios mejoran a la vez, sin un solo caso donde el método previo gane. En la prueba clínica con 383 escáneres ADNI, **NextBrain clasifica Alzheimer vs control con AUROC 0,953 (acierto 90,3%)**, por encima de FreeSurfer (0,911) y Allen MNI (0,929). Pero atención: **AUROC no es diagnóstico** — es capacidad de ranking.

[Ver notebook](papers/2025-11-05-nextbrain-atlas-333-regiones/notebook) · [Leer más](papers/2025-11-05-nextbrain-atlas-333-regiones/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-11-05-nextbrain-atlas-333-regiones/notebook.ipynb)

---

### 128 Genomas Indígenas Americanos: Dos Pistas Inesperadas

**Biología** · Nature · Castro e Silva et al. (2026) presentan el **mayor conjunto de genomas indígenas americanos secuenciados hasta hoy**: 128 individuos de 45 poblaciones, 8 países. Dos pistas inesperadas en los datos: **(1)** el aislamiento por distancia *global* (Spearman ρ = 0,50) es una **paradoja de Simpson** — dentro de Sudamérica la correlación cae a 0,15 y entre Norte y Sudamérica es *negativa* (ρ = −0,29); **(2)** la señal genética compartida con Papúa/Australia (*Ypykuéra*) aparece en muestras pre-colombinas de **~6.800 años** y está concentrada en unos pocos individuos antiguos.

[Ver notebook](papers/2026-04-22-genomas-indigenas-americanos/notebook) · [Leer más](papers/2026-04-22-genomas-indigenas-americanos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-22-genomas-indigenas-americanos/notebook.ipynb)

---

### 151 vertederos del mundo, 1085 detecciones satelitales

**Ecología** · Nature · Dogniaux et al. (2025) observaron 151 vertederos en 6 continentes con el satélite **GHGSat** durante 2021-2022 y cruzaron las emisiones medidas con los reportes nacionales y el inventario **Climate TRACE**. El resultado: **a escala de instalación, las tres estimaciones no se correlacionan** (Spearman ρ=0,12, p=0,21, n=109). En un vertedero de Turquía el satélite ve **240 veces más metano** del que estima el modelo; en dos vertederos de Corea del Sur, el modelo estima **76 y 186 veces más** de lo que mide el satélite. Solo **41 de 109 sitios (38%)** acuerdan dentro de un factor 2.

[Ver notebook](papers/2026-01-17-metano-151-vertederos-satelite/notebook) · [Leer más](papers/2026-01-17-metano-151-vertederos-satelite/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-metano-151-vertederos-satelite/notebook.ipynb)

---

### Un termitero inspira cómo recuperar 83% del vapor industrial

**Tecnología** · Nature Water · Zhang et al. (2026) copiaron la arquitectura pasiva de los termiteros africanos —cámaras, chimeneas y canales que enfrían sin perder humedad— para recuperar el vapor que las torres de enfriamiento industriales tiran al aire. El sistema de **cuatro capas apiladas** retiene **83,5%** del vapor a los 24 minutos, contra 27,2% sin tratamiento. **Una sola capa** (el recubrimiento de microesferas FAUTO) carga con +43,7 puntos porcentuales de la mejora; las otras tres capas juntas apenas suman +12,6 pp. Proyectado a una planta de 300 MW en China: **2,7×10⁸ toneladas de agua recuperadas al año** — equivalente al consumo doméstico de 2,2 millones de hogares.

[Ver notebook](papers/2026-04-21-vapor-agua-termitero-industrial/notebook) · [Leer más](papers/2026-04-21-vapor-agua-termitero-industrial/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-21-vapor-agua-termitero-industrial/notebook.ipynb)

---

### Una proteína viral le devolvió la memoria a ratones con deterioro cognitivo

**Neurociencia** · Science · Reineke et al. (2026) muestran que una variante humana del gen **PPP1R15B (R658C)** mantiene encendida una respuesta de estrés celular llamada **ISR** — y eso solo basta para deteriorar la memoria. La proteína viral **DP71L** la apaga y revierte los déficits cognitivos en ratones con Down, Alzheimer y envejecimiento. Este notebook usa el dataset público **GSE310398** para verificar la firma molecular: **ATF4 sube su eficiencia traduccional 53% en el cerebro mutante** (p ≈ 0,005, Cohen's d ≈ 5), **CHOP +41%**, y solo **1,6% de los 10.908 genes expresados** cambian — el ISR es un escalpelo molecular, no un mazo.

[Ver notebook](papers/2026-04-06-viral-dp71l-reverso-deterioro-cognitivo/notebook) · [Leer más](papers/2026-04-06-viral-dp71l-reverso-deterioro-cognitivo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-06-viral-dp71l-reverso-deterioro-cognitivo/notebook.ipynb)

---

### Un satélite ve temperatura. ¿Puede ver las corrientes del océano?

**Ecología** · Nature Geoscience · Lenain et al. (2026) introducen **GOFLOW**, una red neuronal U-Net que recibe tres imágenes térmicas consecutivas de satélite geostacionario (GOES-East, 1 hora de separación) y devuelve el campo de velocidad superficial del océano. Validada contra la simulación de referencia LLC4320 en **41 snapshots del Gulf Stream**, alcanza correlación **r ≈ 0,97** para velocidades (u, v) y preserva la asimetría positiva de la vorticidad — el hallmark del régimen submesoscale. La divergencia, en cambio, es la variable más difícil: los autores lo admiten ("somewhat less accurately reproduced") y aquí se ve explícito en los datos.

[Ver notebook](papers/2026-04-13-goflow-corrientes-submesoscale/notebook) · [Leer más](papers/2026-04-13-goflow-corrientes-submesoscale/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-13-goflow-corrientes-submesoscale/notebook.ipynb)

---

### Un destello 40 veces más brillante de un agujero negro

**Astronomía** · Nature Astronomy · Hinkle et al. (2025) describen el destello más luminoso jamás registrado de un agujero negro supermasivo: el núcleo galáctico activo **J224554.84+374326.5** (z = 2,6) brilló más de **40×** sobre su nivel normal en 2018 y liberó ~**10⁵⁴ erg** en UV+óptico — equivalente a convertir una masa solar entera en radiación. En ZTF g (filtro más azul) la amplitud alcanza **151×** pico→mínimo; el eco infrarrojo de WISE es apenas **1,9×**. Seis años después, todavía se está apagando.

[Ver notebook](papers/2026-01-17-destello-agujero-negro-extremo/notebook) · [Leer más](papers/2026-01-17-destello-agujero-negro-extremo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-destello-agujero-negro-extremo/notebook.ipynb)

---

### La brújula del cerebro en murciélagos

**Neurociencia** · Science · Palgi et al. (2025) registraron **97 neuronas brújula** en el presubículo de murciélagos volando libres sobre la selva de Zanzíbar — sin jaula, sin pistas controladas. La dirección preferida de esas neuronas drifteaba **1,72°/s la primera noche** y solo **0,20°/s la sexta**: una estabilización 8,4× con la experiencia (Spearman ρ = −0,60, p < 1e-8). Los datos sugieren que la brújula funciona igual con o sin luna.

[Ver notebook](papers/2025-10-16-brujula-cerebral-murcielagos-isla/notebook) · [Leer más](papers/2025-10-16-brujula-cerebral-murcielagos-isla/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-10-16-brujula-cerebral-murcielagos-isla/notebook.ipynb)

---

### 64 canales de ARN en una sola imagen

**Biología** · Nature Biotechnology · Los microscopios de fluorescencia solo distinguen 4 colores, pero PRISM logra imagen espacial de **64 ARNs en una sola ronda** codificando cada uno con una combinación de 4 canales e intensidad. El equipo elige 64 codewords de un espacio de **1.296** posibles (4,9%) con separación mínima de **√2 ≈ 1,414** — la distancia que un píxel ruidoso no puede cruzar.

[Ver notebook](papers/2025-10-30-prism-64-barcodes/notebook) · [Leer más](papers/2025-10-30-prism-64-barcodes/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-10-30-prism-64-barcodes/notebook.ipynb)

---

### Reparar una mitocondria enferma — célula por célula

**Medicina** · Nature · Un equipo desarrolló **MitoCatch**, un sistema que dirige mitocondrias sanas solo a las células enfermas. Lo probaron en 127 neuronas derivadas de un paciente con ceguera hereditaria (LHON). En las tratadas, la mediana de ADN mitocondrial sano saltó de 0% a **43,5%** (IQR 25,9 – 65,6). Sin los *binders*, la captación es literalmente cero (n=19).

[Ver notebook](papers/2026-04-15-transplante-mitocondrial-dirigido/notebook) · [Leer más](papers/2026-04-15-transplante-mitocondrial-dirigido/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-15-transplante-mitocondrial-dirigido/notebook.ipynb)

---

### Una cámara grabó un terremoto desde la falla

**Geología** · Science · Una cámara CCTV a metros de la falla de Sagaing grabó la ruptura superficial durante el terremoto Mw 7,7 de Mandalay (Myanmar, 28 de marzo de 2025). Del video extrajeron la primera medición directa de la velocidad de deslizamiento: un pulso de 1,4 s, velocidad pico de 3,5 m/s y ~3 m de desplazamiento acumulado. Dos modelos con distinta velocidad de ruptura ajustan los datos igual de bien, pero implican un stress drop 5× diferente.

[Ver notebook](papers/2025-10-30-terremoto-cctv-falla-myanmar/notebook) · [Leer más](papers/2025-10-30-terremoto-cctv-falla-myanmar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-10-30-terremoto-cctv-falla-myanmar/notebook.ipynb)

---

### LEDs de superretículas de quantum dots pixeladas

**Tecnología** · Nature · Quantum dots de perovskita (CsPbBr₃) organizados en superretículas hexagonales: 30,9% EQE, 117.144 cd/m², 5.080 PPI. Vida media extrapolada de 12.411 horas (~1,4 años), 1.460× más que el mejor LED pixelado de perovskita anterior. La clave: un ligando (BHOA+F) que permite transporte de banda con movilidad 17× mayor a temperatura ambiente.

[Ver notebook](papers/2026-04-17-pixelated-quantum-dot-superlattice-leds/notebook) · [Leer más](papers/2026-04-17-pixelated-quantum-dot-superlattice-leds/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-17-pixelated-quantum-dot-superlattice-leds/notebook.ipynb)

---


### Jet de Cygnus X-1 doblado por viento estelar

**Astronomía** · Nature Astronomy · Miller-Jones et al. (2026), 18 años de observaciones VLBI revelan que el viento estelar dobla el jet de Cygnus X-1. Mediante inferencia bayesiana, miden por primera vez la potencia cinética instantánea del jet: log₁₀(L_jet) = 37,28 erg/s — comparable a la luminosidad en rayos X. El jet viaja a ~68% de la velocidad de la luz con un desalineamiento de ~5° respecto al eje orbital.

[Ver notebook](papers/2026-04-17-jet-cygnus-x1-viento-estelar/notebook) · [Leer más](papers/2026-04-17-jet-cygnus-x1-viento-estelar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-17-jet-cygnus-x1-viento-estelar/notebook.ipynb)

---

### Músculos artificiales con ultrasonido: 714× de salto en escala

**Tecnología** · Nature · Shi et al. (2025), más de 10.000 microburbujas programables forman músculos artificiales controlados por ultrasonido. Benchmark de 74 actuadores en 3 dimensiones (agarre, fuerza, natación). El stingraybot acústico de 50 mm es 714 veces más grande que la mediana de nadadores acústicos previos.

[Ver notebook](papers/2025-10-30-musculos-artificiales-ultrasonido-microburbujas/notebook) · [Leer más](papers/2025-10-30-musculos-artificiales-ultrasonido-microburbujas/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-10-30-musculos-artificiales-ultrasonido-microburbujas/notebook.ipynb)

---

### 🧬 ADN antiguo revela selección direccional masiva en Eurasia

**Biología** · Nature · Reich et al. (2026), 15.836 genomas antiguos de Eurasia occidental (10.016 nuevos). 77 señales poligénicas Bonferroni-significativas entre 696 rasgos. La pigmentación domina (γ = −1,80, p = 5,7 × 10⁻⁷⁴). Disminución en grasa corporal (16 medidas) y esquizofrenia. Aumento en inteligencia fluida — con el caveat de que estos rasgos se midieron en sociedades industrializadas actuales.

[Ver notebook](papers/2026-04-16-adn-antiguo-seleccion-direccional-eurasia/notebook) · [Leer más](papers/2026-04-16-adn-antiguo-seleccion-direccional-eurasia/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-16-adn-antiguo-seleccion-direccional-eurasia/notebook.ipynb)

---

### 🌊 ¿Tuvo Marte un océano? La firma que dejó en el suelo

**Geología** · Nature · Benjamin et al. (2026), análisis topográfico de 408.690 puntos de elevación en Marte. Las shorelines propuestas varían hasta 6,7 km — demasiado para ser playas reales. La verdadera firma de un océano es una zona plana circunglobal entre −3.800 m y −1.800 m: una plataforma costera 5× más ancha que la terrestre. El 77% de los deltas convergen ahí.

[Ver notebook](papers/2026-04-15-firma-topografica-oceanos-marte/notebook) · [Leer más](papers/2026-04-15-firma-topografica-oceanos-marte/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-15-firma-topografica-oceanos-marte/notebook.ipynb)

---

### 🪐 Planetas húmedos sin migrar desde lejos

**Astronomía** · Nature · Luo et al. (2025), experimentos de alta presión (8–42 GPa, 2.725–3.924 K) que simulan el interior de sub-Neptunos. Al comprimir una mezcla primordial (~5% H₂ + ~76% silicato + ~19% Fe), el hidrógeno reduce el silicato y produce 18,1 ± 0,5 wt% de H₂O — ~1.800× más que las predicciones previas (0,01 wt%). Una aleación Fe₀,₇₃Si₀,₂₇ confirma la reducción. Un sub-Neptuno de 5 M⊕ con 5% de envolvente podría generar 2–4 wt% H₂O sin migrar desde órbitas lejanas.

[Ver notebook](papers/2026-04-15-agua-sub-neptunos-reaccion-magma/notebook) · [Leer más](papers/2026-04-15-agua-sub-neptunos-reaccion-magma/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-15-agua-sub-neptunos-reaccion-magma/notebook.ipynb)

---

### 🌍 ¿De qué está hecha la Tierra? De nada que conozcamos

**Astronomía** · Nature Astronomy · Render et al. (2026), 10 anomalías isotópicas nucleosintéticas en 17 cuerpos del Sistema Solar. La Tierra es el endmember del array no-carbonáceo: z₀ = −2,37, más extremo que cualquier meteorito conocido. 0% de material del Sistema Solar exterior. Mercurio y Venus serían aún más extremos.

[Ver notebook](papers/2026-04-15-acrecion-homogenea-tierra-sistema-solar/notebook) · [Leer más](papers/2026-04-15-acrecion-homogenea-tierra-sistema-solar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-15-acrecion-homogenea-tierra-sistema-solar/notebook.ipynb)

---

### 🧠 Tu cerebro reutiliza el mismo código para ver e imaginar

**Neurociencia** · Science (2026) · 367 neuronas individuales grabadas en la corteza temporal ventral (VTC) de 16 pacientes epilépticos. Al imaginar un objeto sin verlo, el 74% de las neuronas reactivan el mismo código que usaron al percibirlo (ρ = 0,56 a nivel de población, n = 338). Evidencia directa de un modelo generativo en el cerebro humano.

[Ver notebook](papers/2026-04-15-codigo-neural-percepcion-imaginacion/notebook) · [Leer más](papers/2026-04-15-codigo-neural-percepcion-imaginacion/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-15-codigo-neural-percepcion-imaginacion/notebook.ipynb)

---

### ⚗️ Membranas selectivas de litio: 60 veces más que la competencia

**Química** · Nature Water · Chen et al. (2026), membrana ISGC (polímero + ZIF-8 30%) logra selectividad K⁺/Li⁺ = 410,1 en salmueras multi-iónicas — 60× la mediana de los 10 competidores comparados. Poro óptimo a 2,686 Å (entre Li⁺ hidratado y K⁺ hidratado). Consumo energético: 1,02 kWh/kg, el menor entre 6 métodos de extracción. CAPEX total: 2.528 USD.

[Ver notebook](papers/2026-04-14-membranas-selectivas-litio/notebook) · [Leer más](papers/2026-04-14-membranas-selectivas-litio/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-14-membranas-selectivas-litio/notebook.ipynb)

---

### ☀️ Celdas solares de perovskita: cuando la IA fabrica mejor que el humano

**Tecnología** · Nature (2026) · 756 celdas solares fabricadas por una plataforma autónoma de IA (optimización bayesiana + ML) vs. 36 controles manuales. Las 20 condiciones automatizadas superan al control: +2,9 pp de eficiencia (22,4% → 25,3%), Cohen's d = 6,54. La ganancia viene del voltaje (VOC) y el factor de llenado (FF), no de la corriente.

[Ver notebook](papers/2026-04-14-celulas-solares-perovskita-ia-autonoma/notebook) · [Leer más](papers/2026-04-14-celulas-solares-perovskita-ia-autonoma/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-14-celulas-solares-perovskita-ia-autonoma/notebook.ipynb)

---

### 🐍 8 moléculas contra 17 serpientes letales

**Medicina** · Nature · Ahmadi et al. (2025), proteómica de venenos de 16 elapidos africanos (133 entradas de toxinas). Las cobras escupidoras (Afronaja) producen citotoxinas (CTx, 85% de sus 3FTx) que destruyen tejido, mientras mambas y cobras de capa producen neurotoxinas (sNTx, lNTx). Un cocktail de 8 nanobodies de alpaca cubre 7 subfamilias de toxinas, protegiendo contra 17/18 especies en ratones — superando al antiveneno comercial de plasma en modelos preclínicos.

[Ver notebook](papers/2026-01-17-nanobodies-antivenom-serpientes/notebook) · [Leer más](papers/2026-01-17-nanobodies-antivenom-serpientes/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-nanobodies-antivenom-serpientes/notebook.ipynb)

---

### 🧬 ¿Por qué un ajolote regenera su pata y tú no?

**Biología** · Science · Tsissios et al. (2026), scRNA-seq de 21.000+ células de 5 especies. Las especies regenerativas (Xenopus, ajolote) expresan hasta 29× menos los sensores de oxígeno (VHL, EGLN1, HIF1AN), dejando activo a HIF1A — el factor que enciende la regeneración. Factores AER remodelan la composición celular del ratón en ±18 puntos porcentuales.

[Ver notebook](papers/2026-04-12-oxigeno-regeneracion-extremidades-vertebrados/notebook) · [Leer más](papers/2026-04-12-oxigeno-regeneracion-extremidades-vertebrados/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-12-oxigeno-regeneracion-extremidades-vertebrados/notebook.ipynb)

---

### 🐒 Conflicto letal tras la fisión de chimpancés salvajes

**Biología** · Science · Sandel et al. (2026), 30 años de datos del grupo de chimpancés más grande conocido (~200 individuos) en Ngogo, Uganda. La conectividad social cayó 67,7% (de 35,8 a 11,5 conexiones/individuo) tras la fisión de 2015-2018. Los machos Western lanzaron 24 ataques letales contra el grupo Central: ≥7 machos adultos y 17 crías muertos (2018-2024).

[Ver notebook](papers/2026-04-10-conflicto-letal-chimpances-fision/notebook) · [Leer más](papers/2026-04-10-conflicto-letal-chimpances-fision/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-10-conflicto-letal-chimpances-fision/notebook.ipynb)

---

### ⛰️ Fantasmas de 241 millones de años revelan un secreto

**Geología** · Nature Communications · Slater et al. (2025), fósiles fantasma de cocolitóforos en rocas del Triásico Medio (Suiza y Austria). El récord fósil se extiende ~26 millones de años hacia atrás (de ~215 Ma a ~241 Ma). Más de 100 huellas preservadas en heces de zooplancton fosilizadas. Las muestras con alta materia orgánica amorfa (media 73%) contienen los fantasmas.

[Ver notebook](papers/2026-01-17-fantasmas-cocolitoforos-triasico/notebook) · [Leer más](papers/2026-01-17-fantasmas-cocolitoforos-triasico/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-fantasmas-cocolitoforos-triasico/notebook.ipynb)

---

### 🦠 Comercio de fauna silvestre y patógenos zoonóticos

**Ecología** · Science · Gippet et al. (2026), 6.456 especies de mamíferos silvestres cruzadas con 40 años de datos de comercio internacional (CITES, LEMIS). Las especies comerciadas tienen 1,5x más probabilidad de compartir patógenos con humanos (ajustado). El comercio ilegal dispara el riesgo: 72,4% de las especies ilegales son zoonóticas vs 30,6% de las solo legales (Cohen's h = 0,86).

[Ver notebook](papers/2026-04-11-comercio-fauna-patogenos-zoonoticos/notebook) · [Leer más](papers/2026-04-11-comercio-fauna-patogenos-zoonoticos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-11-comercio-fauna-patogenos-zoonoticos/notebook.ipynb)

---

### 🌳 2,7 millones de árboles: ¿compiten o cooperan?

**Ecología** · Nature · Detto et al. (2026), datos de 17 parcelas ForestGEO (~2,7 millones de árboles, >5.400 especies). La facilitación relativa cae de 46% en el trópico a 7% en Utah (ρ = −0,82, p < 0,001). La competencia domina en 15/17 parcelas. Temperatura del suelo y riqueza de especies son los predictores clave.

[Ver notebook](papers/2026-04-10-competencia-facilitacion-diversidad-arboles/notebook) · [Leer más](papers/2026-04-10-competencia-facilitacion-diversidad-arboles/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-10-competencia-facilitacion-diversidad-arboles/notebook.ipynb)

---

### 🏔️ El agua que sostiene los ríos de Colorado tiene 15 años

**Geología** · Nature Geoscience · Siirila-Woodburn et al. (2026), modelo hidrogeológico de alta resolución (ParFlow-CLM + EcoSLIM) en la cuenca del East River. Con +4 °C, el pico de nieve cae 21%, la edad media del agua subterránea sube y el sistema empieza a consumir reservas de décadas. 114 años de datos USGS confirman que el caudal ya lleva décadas bajando (p = 0,009).

[Ver notebook](papers/2026-04-10-agua-subterranea-vieja-colorado/notebook) · [Leer más](papers/2026-04-10-agua-subterranea-vieja-colorado/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-10-agua-subterranea-vieja-colorado/notebook.ipynb)

---

### 💊 GLP1: tu ADN decide los efectos secundarios

**Medicina** · Nature · Aschebrook-Kilfoy et al. (2026), GWAS con 27.885 personas en tratamiento con semaglutida o tirzepatida. Una variante en GIPR (rs1800437) triplica el riesgo de vómitos con tirzepatida (CC 11,8% vs GG 3,9%, p = 2,2×10⁻¹⁰) pero no tiene efecto con semaglutida. Un modelo predictivo con genética mejora la predicción de vómitos (ΔAUC = +0,022) pero apenas mueve la eficacia (ΔR² = 0,001).

[Ver notebook](papers/2026-04-09-predictores-geneticos-glp1-perdida-peso/notebook) · [Leer más](papers/2026-04-09-predictores-geneticos-glp1-perdida-peso/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-09-predictores-geneticos-glp1-perdida-peso/notebook.ipynb)

---

### Biodiversidad resiliente en un bosque tropical

¿Cuánto tarda un bosque tropical en volver a la vida? 16 grupos taxonómicos en Ecuador — desde bacterias hasta murciélagos. La abundancia recupera >90% en 30 años, pero la composición de especies se queda en ~75%.

[Notebook](papers/2026-04-09-biodiversidad-resiliencia-bosque-tropical/notebook.ipynb) · [README](papers/2026-04-09-biodiversidad-resiliencia-bosque-tropical/README.md) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-09-biodiversidad-resiliencia-bosque-tropical/notebook.ipynb)

---


### 🏭 Una Industria Causa el 86% de Estos Contaminantes

**Ecología** · Nature Sustainability · Yang et al. (2025), inventario global de emisiones de Cl/BrPAHs usando XGBoost: 5.143 kg en 184 países, la sinterización de mineral de hierro genera el 86,1% del total. Australia lidera con 1.393 kg (27% global, 47 g/persona — 236× la mediana)

[Ver notebook](papers/2026-01-17-industria-86-contaminantes-emergentes/notebook) · [Leer más](papers/2026-01-17-industria-86-contaminantes-emergentes/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-industria-86-contaminantes-emergentes/notebook.ipynb)

---

### 🤖 ¿Puede una IA Entrenada con Imágenes Inventadas Superar a 9 Radiólogos?

**Tecnología** · Nature Biomedical Engineering · Chen et al. (2026), BUSGen — primer modelo generativo fundacional para ecografía mamaria, pre-entrenado con 3,5 millones de imágenes. A partir de 25K imágenes sintéticas, el modelo supera a los entrenados con datos reales (AUC 0,932 vs 0,925). Evaluado contra 9 radiólogos certificados: +15,9 pp de sensibilidad

[Ver notebook](papers/2026-04-08-busgen-ecografia-mama-ia/notebook) · [Leer más](papers/2026-04-08-busgen-ecografia-mama-ia/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-08-busgen-ecografia-mama-ia/notebook.ipynb)

---

### 🌊 Agricultura Circular con Agua de Mar y Sol

**Ecología** · Nature Water · Sun et al. (2026), ensayo de campo de 3 meses en Hainan — desalinización solar + agricultura circular: las sojas crecen +134% vs evaporación natural, +49% más semilla que con ósmosis inversa industrial, el sistema elimina 99,99% del sodio y alimenta a 47 personas por 0,6 ha

[Ver notebook](papers/2026-04-08-desalinizacion-solar-agricultura-circular/notebook) · [Leer más](papers/2026-04-08-desalinizacion-solar-agricultura-circular/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-08-desalinizacion-solar-agricultura-circular/notebook.ipynb)

---

### 🌿 Los Bosques Tropicales Ahora Liberan Carbono

**Ecología** · Nature · Carle et al. (2025), 48 años de censos forestales en 20 parcelas de Queensland, Australia — los bosques pasaron de absorber +0,62 Mg C ha⁻¹ yr⁻¹ a liberar −0,93, impulsados por mortalidad extrema sin evidencia de fertilización por CO₂

[Ver notebook](papers/2026-01-17-bosques-tropicales-liberan-carbono/notebook) · [Leer más](papers/2026-01-17-bosques-tropicales-liberan-carbono/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-bosques-tropicales-liberan-carbono/notebook.ipynb)

---

### 🦴 Discontinuidad Genética en la Cuenca de París al Final del Neolítico

**Arqueología** · Nature Ecology & Evolution · Tallman et al. (2026), 132 genomas antiguos de una tumba colectiva cerca de París — dos fases de entierro separadas por ~316 años revelan un recambio poblacional completo: de un grupo diverso a uno casi clonal con más ancestría agrícola, evidencia de *Yersinia pestis* y *Borrelia recurrentis*

[Ver notebook](papers/2026-04-07-discontinuidad-paris-neolitico/notebook) · [Leer más](papers/2026-04-07-discontinuidad-paris-neolitico/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-07-discontinuidad-paris-neolitico/notebook.ipynb)

---

### ⚡ Renovables Fortalecen a Ecuador Contra la Sequía

**Ecología** · Nature Water · Sterl et al. (2026), 14 años de datos hidrológicos y factores de capacidad renovable — el río Paute cayó 42,4% en 2024 pero solar y eólica habrían seguido generando, revelando una "sinergia de año extremo"

[Ver notebook](papers/2026-04-07-renovables-fortalecen-ecuador-sequia/notebook) · [Leer más](papers/2026-04-07-renovables-fortalecen-ecuador-sequia/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-07-renovables-fortalecen-ecuador-sequia/notebook.ipynb)

---

### 🧬 9 Billones de Bases de ADN Enseñaron a una IA a Escribir Vida

**Tecnología** · Nature · Nguyen et al. (2026), 705 benchmarks de predicción de variantes genéticas — Evo 2 (40B parámetros) compite con modelos especializados sin entrenamiento específico y lidera en BRCA1 (AUROC 0,901)

[Ver notebook](papers/2026-03-09-evo2-ia-adn-escribir-vida/notebook) · [Leer más](papers/2026-03-09-evo2-ia-adn-escribir-vida/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-09-evo2-ia-adn-escribir-vida/notebook.ipynb)

---

### 🌊 Las Olas de Calor Cambian 176% la Vida en el Océano

**Ecología** · Nature Ecology & Evolution · Blowes et al. (2026), 702.037 estimaciones de biomasa en 1.566 especies de peces — las olas de calor crean ganadores (+176%) en el borde frío y perdedores (-43,4%) en el borde cálido

[Ver notebook](papers/2026-02-27-olas-calor-biomasa-peces-oceano/notebook) · [Leer más](papers/2026-02-27-olas-calor-biomasa-peces-oceano/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-02-27-olas-calor-biomasa-peces-oceano/notebook.ipynb)

---


### 🌊 La circulación oceánica más débil en 1.300 años

**Geología** · Nature Geoscience · Thresher et al. (2026), corales bambú del Pacífico suroeste revelan que la circulación del Océano Sur y del Atlántico Norte están en mínimos del último milenio — y el Sur se mueve primero, con 20-50 años de ventaja

[Ver notebook](papers/2026-04-06-circulacion-atlantico-oceano-sur/notebook) · [Leer más](papers/2026-04-06-circulacion-atlantico-oceano-sur/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-06-circulacion-atlantico-oceano-sur/notebook.ipynb)

---

### ⭐ Una estrella casi prístina de la Nube de Magallanes

**Astronomía** · Nature Astronomy · Ezzeddine et al. (2026), J0715−7334 tiene 20.000× menos hierro que el Sol — la única estrella ultra metal-poor que NO tiene exceso de carbono, huella de una supernova primordial de 30 M☉

[Ver notebook](papers/2026-04-04-estrella-pristina-nube-magallanes/notebook) · [Leer más](papers/2026-04-04-estrella-pristina-nube-magallanes/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-04-estrella-pristina-nube-magallanes/notebook.ipynb)

---

### TRAPPIST-1 b y c: rocas desnudas a 40 años-luz

El JWST observó 52 horas continuas los dos planetas más cercanos a TRAPPIST-1. Resultado: rocas desnudas sin atmósfera. 490 K de día, cero de noche.

[Notebook](papers/2026-04-03-trappist-1-sin-atmosfera-jwst/notebook.ipynb) · [README](papers/2026-04-03-trappist-1-sin-atmosfera-jwst/README.md) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-03-trappist-1-sin-atmosfera-jwst/notebook.ipynb)

### 📊 ¿Se puede confiar en un solo análisis?

**Tecnología** · Nature · Kovács et al. (2025), 504 reanálisis de 100 estudios sociales, solo 34% coinciden en tamaño del efecto (±0,05 d), 74% llegan a la misma conclusión

[Ver notebook](papers/2026-04-05-robustez-analitica-ciencias-sociales/notebook) · [Leer más](papers/2026-04-05-robustez-analitica-ciencias-sociales/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-05-robustez-analitica-ciencias-sociales/notebook.ipynb)

---

### ✈️ Las estelas de los aviones limpios siguen calentando el planeta

**Ecología** · Nature · Voigt et al. (2026), motores lean-burn con bajo hollín forman estelas masivas, datos de mediciones in-flight y modelo ACM (Zenodo)

[Ver notebook](papers/2026-04-04-estelas-aviones-hollin-bajo/notebook) · [Leer más](papers/2026-04-04-estelas-aviones-hollin-bajo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-04-estelas-aviones-hollin-bajo/notebook.ipynb)

---

### 🔬 ¿Se puede replicar la ciencia social?

**Tecnología** · Nature · Protzko et al. (2025), 274 claims de 164 papers replicados, 55,1% se replica, efecto mediano se reduce a la mitad

[Ver notebook](papers/2026-04-05-replicabilidad-ciencias-sociales/notebook) · [Leer más](papers/2026-04-05-replicabilidad-ciencias-sociales/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-05-replicabilidad-ciencias-sociales/notebook.ipynb)

---

### 🔬 ¿Se puede confiar en la ciencia social?

**Tecnología** · Nature · 600 papers de 62 revistas (2009–2018), 573 claims evaluados, 55,5% precisamente reproducible, solo 19,6% comparte datos

[Ver notebook](papers/2026-04-04-reproducibilidad-ciencias-sociales/notebook) · [Leer más](papers/2026-04-04-reproducibilidad-ciencias-sociales/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-04-reproducibilidad-ciencias-sociales/notebook.ipynb)

---

### 🤖 La IA aduladora reduce la intención prosocial

**Tecnología** · Science · 1.604 participantes, diseño experimental, IA aduladora vs directa, repair d = 0,92, convicción d = 1,26

[Ver notebook](papers/2026-04-04-ia-aduladora-reduce-intencion-prosocial/notebook) · [Leer más](papers/2026-04-04-ia-aduladora-reduce-intencion-prosocial/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-04-ia-aduladora-reduce-intencion-prosocial/notebook.ipynb)

---


### 🌧️ Nadie sabe cuánto llueve en casi todo el planeta

**Ecología** · Nature · 221.483 pluviómetros, 15.386 tiles globales, 68,7% sin cobertura, solo 13,4% cumple WMO

[Ver notebook](papers/2026-04-02-lluvia-pluviometros-planeta/notebook) · [Leer más](papers/2026-04-02-lluvia-pluviometros-planeta/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-02-lluvia-pluviometros-planeta/notebook.ipynb)

---

### 🤖 ¿Puede una IA revisar papers como un humano?

**Tecnología** · Nature · 500 papers ICLR 2024, Claude-3.5-Sonnet vs GPT-4o vs revisores humanos, confusion matrix, Spearman ρ = 0,323

[Ver notebook](papers/2026-04-02-ia-scientist-paper-autonomo/notebook) · [Leer más](papers/2026-04-02-ia-scientist-paper-autonomo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-02-ia-scientist-paper-autonomo/notebook.ipynb)

---

### 🐕 Los mismos perros cruzaron toda Europa

**Biología** · Nature · 148 cánidos antiguos (74 perros, 73 lobos) de 25 países, genomas nucleares y mitocondriales, isótopos estables δ¹³C/δ¹⁵N

[Ver notebook](papers/2026-04-01-perros-cruzaron-europa/notebook) · [Leer más](papers/2026-04-01-perros-cruzaron-europa/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-01-perros-cruzaron-europa/notebook.ipynb)

---

### 🧬 Descubrieron 74 Antibióticos Imposibles de Encontrar

**Tecnología** · Nature Biomedical Engineering · HMD-AMP detecta 100% de AMPs remotos (vs 0% otros métodos), 91 validados experimentalmente, 74 activos, 4 de amplio espectro, MIC 1-4 µg/mL

[Ver notebook](papers/2026-03-31-antibioticos-imposibles-ia-proteinas/notebook) · [Leer más](papers/2026-03-31-antibioticos-imposibles-ia-proteinas/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-31-antibioticos-imposibles-ia-proteinas/notebook.ipynb)

---

### 🧠 Hambre después de estudiar

**Neurociencia** · Nature · Memoria en *Drosophila* por tipo de entrenamiento, silenciamiento Gr43a, preferencia por sucrosa post-aprendizaje

[Ver notebook](papers/2026-03-30-hambre-despues-estudiar/notebook) · [Leer más](papers/2026-03-30-hambre-despues-estudiar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-30-hambre-despues-estudiar/notebook.ipynb)

---

### 🧬 Hormona alimenta tumores en niños

**Medicina** · Nature · Respuesta dosis-efecto de testosterona en 6 líneas PFA, comparación de hormonas, control en otros tumores cerebrales

[Ver notebook](papers/2026-03-30-hormona-alimenta-tumores-ninos/notebook) · [Leer más](papers/2026-03-30-hormona-alimenta-tumores-ninos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-30-hormona-alimenta-tumores-ninos/notebook.ipynb)

---

### 🧫 Cáncer despierta armas contra tu cerebro

**Medicina** · Nature · Tumores TNBC expresan receptores NMDA del cerebro, anticuerpos anti-tumor causan encefalitis autoinmune — trade-off inmunidad vs neurotoxicidad

[Ver notebook](papers/2026-03-29-cancer-despierta-armas-cerebro/notebook) · [Leer más](papers/2026-03-29-cancer-despierta-armas-cerebro/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-29-cancer-despierta-armas-cerebro/notebook.ipynb)

---

### 🌲 Carbono de los bosques vírgenes de Suecia

**Ecología** · Science · 324 parcelas primarias vs 28,580 secundarias, carbono en vegetación + madera muerta + suelo, análisis pareado por humedad

[Ver notebook](papers/2026-03-28-carbono-bosques-virgenes/notebook) · [Leer más](papers/2026-03-28-carbono-bosques-virgenes/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-28-carbono-bosques-virgenes/notebook.ipynb)

---

### 🧊 Rocas atrapadas en el hielo de Groenlandia

**Geología** · Nature Geoscience · 4,946 ubicaciones de escombros rocosos en el manto de hielo, 11 modelos de extensión durante el último interglacial, radar 3D aerotransportado

[Ver notebook](papers/2026-03-28-rocas-hielo-groenlandia/notebook) · [Leer más](papers/2026-03-28-rocas-hielo-groenlandia/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-28-rocas-hielo-groenlandia/notebook.ipynb)

---

### 🌊 Océano dispara olas de calor

**Ecología** · Nature Geoscience · 42 años de olas de calor húmedo, mapa global de tendencias, comparación por décadas

[Ver notebook](papers/2026-03-28-oceano-dispara-olas-de-calor/notebook) · [Leer más](papers/2026-03-28-oceano-dispara-olas-de-calor/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-28-oceano-dispara-olas-de-calor/notebook.ipynb)

---

### 🏛️ Monte Verde: la fecha estaba mal

**Arqueología** · Science · 23 dataciones ¹⁴C + 6 de luminiscencia, tefra volcánica debajo de la capa arqueológica, re-datación del sitio pre-Clovis más icónico de Sudamérica

[Ver notebook](papers/2026-03-27-monte-verde-fecha-mal/notebook) · [Leer más](papers/2026-03-27-monte-verde-fecha-mal/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-27-monte-verde-fecha-mal/notebook.ipynb)

---

### 🎵 Música: preferencias compartidas con animales

**Biología** · Science · 48,567 trials, 16 especies, 4196 participantes globales — los humanos coinciden con las preferencias acústicas de ranas, grillos y aves un 54% de las veces

[Ver notebook](papers/2026-03-26-musica-preferencias-animales/notebook) · [Leer más](papers/2026-03-26-musica-preferencias-animales/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-26-musica-preferencias-animales/notebook.ipynb)

---

### 🏔️ Las cumbres cambian 5 veces más rápido

**Ecología** · Nature · 6,067 parcelas europeas re-visitadas (12-78 años), termofilización 4.8x mayor en cumbres alpinas que bosques, deuda climática acumulada de 0.37°C

[Ver notebook](papers/2026-03-24-termofilizacion-cumbres-alpinas/notebook) · [Leer más](papers/2026-03-24-termofilizacion-cumbres-alpinas/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-24-termofilizacion-cumbres-alpinas/notebook.ipynb)

---

### 🧊 CO₂ estable 3 millones de años

**Geología** · Nature · Hielo antártico de 3 Ma, ciclos glaciales, correlación CO₂-CH₄, histograma de anomalía

[Ver notebook](papers/2026-03-23-co2-estable-3-millones-anos/notebook) · [Leer más](papers/2026-03-23-co2-estable-3-millones-anos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-23-co2-estable-3-millones-anos/notebook.ipynb)

---

### 🌊 165,000 km de ríos donde el océano manda

**Ecología** · Nature · 41,910 tramos SWORD, satélite SWOT — 49.9% tidal, amplitud mediana 0.78 m, 3 tipos de marea (semidiurna/mixta/diurna)

[Ver notebook](papers/2026-03-22-rios-mareas-swot-satelite/notebook) · [Leer más](papers/2026-03-22-rios-mareas-swot-satelite/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-22-rios-mareas-swot-satelite/notebook.ipynb)

---

### 🧪 248 químicos sintéticos en el océano

**Ecología** · Nature Geoscience · 2,315 muestras de agua de mar, 21 datasets, 248 xenobióticos — ftalatos, protector solar, fármacos y pesticidas desde arrecifes hasta mar abierto

[Ver notebook](papers/2026-03-21-oceano-248-quimicos-sinteticos/notebook) · [Leer más](papers/2026-03-21-oceano-248-quimicos-sinteticos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-21-oceano-248-quimicos-sinteticos/notebook.ipynb)

---

### 🌊 El océano profundo y la promesa de emisiones cero

**Ecología** · Nature Geoscience · 14 modelos CMIP6, 300 años de simulación — 12/14 muestran rebound de temperatura post net-zero por calor devuelto del océano profundo

[Ver notebook](papers/2026-03-21-oceano-profundo-emisiones-cero/notebook) · [Leer más](papers/2026-03-21-oceano-profundo-emisiones-cero/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-21-oceano-profundo-emisiones-cero/notebook.ipynb)

---

### 🧬 Las 5 bases del ADN en un asteroide

**Astronomía** · Nature Astronomy · A, G, C, T y U detectadas en Ryugu (Hayabusa2) — comparación con Bennu, Orgueil y Murchison, ratios purina/pirimidina distintos por cuerpo

[Ver notebook](papers/2026-03-20-adn-bases-asteroide-ryugu/notebook) · [Leer más](papers/2026-03-20-adn-bases-asteroide-ryugu/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-20-adn-bases-asteroide-ryugu/notebook.ipynb)

---

### ⌚ Tu reloj ya predice diabetes tipo 2

**Tecnología** · Nature · 1.165 participantes WEAR-ME, wearables + biomarcadores sanguíneos, HOMA-IR, redes neuronales profundas, AUROC 0,80

[Ver notebook](papers/2026-03-20-reloj-predice-diabetes/notebook) · [Leer más](papers/2026-03-20-reloj-predice-diabetes/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-20-reloj-predice-diabetes/notebook.ipynb)

---

### ⭐ Estrellas naciendo fuera de la Vía Láctea

**Astronomía** · Nature Astronomy · 32 estrellas en 2 cúmulos abiertos (Emei-1 y Emei-2) dentro del Complejo H, Gaia DR3, isócronas PARSEC 11,2 Myr, metalicidad 0,05 Z⊙, distancia 13,8 kpc

[Ver notebook](papers/2026-03-19-estrellas-fuera-via-lactea/notebook) · [Leer más](papers/2026-03-19-estrellas-fuera-via-lactea/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-19-estrellas-fuera-via-lactea/notebook.ipynb)

---

### 🌡️ Ola de calor vs 32 especies

**Ecología** · Nature Ecology & Evolution · Meta-análisis de 25 especies, ola de calor 2021 Norteamérica, tamaños de efecto (log response ratio), incendios MODIS 2000-2021

[Ver notebook](papers/2026-03-17-ola-calor-32-especies/notebook) · [Leer más](papers/2026-03-17-ola-calor-32-especies/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-17-ola-calor-32-especies/notebook.ipynb)

---

### 🧪 Los "forever chemicals" fabrican baterías

**Química** · Nature Water · 10 tipos de PFAS degradados >99,8%, fluorinación electrotérmica, recuperación de litio ~82% yield, ΔG de 5 cloruros metálicos, solubilidad 275× LiF vs NaCl

[Ver notebook](papers/2026-03-17-pfas-fabrican-baterias-litio/notebook) · [Leer más](papers/2026-03-17-pfas-fabrican-baterias-litio/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-17-pfas-fabrican-baterias-litio/notebook.ipynb)

---

### 🐠 2.795 arrecifes: ¿sirve protegerlos?

**Ecología** · Nature Ecology & Evolution · 2.795 arrecifes tropicales, 22 contribuciones de peces, modelo bayesiano contrafactual, MPAs compensan ~5% de degradación, Cohen's d = 0,33 (protección total vs sin)

[Ver notebook](papers/2026-03-16-arrecifes-mpa-solo-5-porciento/notebook) · [Leer más](papers/2026-03-16-arrecifes-mpa-solo-5-porciento/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-16-arrecifes-mpa-solo-5-porciento/notebook.ipynb)

---

### 🐟 Descubrieron un Pez Imposible de 436 Millones de Años

**Biología** · Nature · 163 taxa × 709 caracteres morfológicos, matriz filogenética NEXUS, Eosteus 30,5% completitud, similitud 90,6% con actinopterigios

[Ver notebook](papers/2026-03-13-pez-imposible-436-millones-anos/notebook) · [Leer más](papers/2026-03-13-pez-imposible-436-millones-anos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-13-pez-imposible-436-millones-anos/notebook.ipynb)

---

### 🛰️ 126.674 ríos: SWOT mide el agua del mundo

**Ecología** · Nature · 126.674 tramos fluviales medidos por SWOT, ΔRSA global 313,1 ± 129,5 km³, 28% menos que modelos, Amazon 55% de variabilidad, Nilo −91% vs predicho

[Ver notebook](papers/2026-03-12-rios-swot-126mil-volumen/notebook) · [Leer más](papers/2026-03-12-rios-swot-126mil-volumen/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-12-rios-swot-126mil-volumen/notebook.ipynb)

---

### 🌫️ En 1 minuto esta IA destruye décadas de pronósticos del aire

**Tecnología** · Nature · AI-GAMFS vs CAMS y GEOS-FP, 289 estaciones AERONET, 42 años MERRA-2, Vision Transformer + U-Net, AOD r = 0,978

[Ver notebook](papers/2026-03-12-ia-pronostico-aerosoles/notebook) · [Leer más](papers/2026-03-12-ia-pronostico-aerosoles/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-12-ia-pronostico-aerosoles/notebook.ipynb)

---

### 🌊 Nadie midió bien el nivel del mar y 132 millones lo pagarán

**Ecología** · Nature · 386 evaluaciones de riesgo costero, offset MDT vs geoide EGM96/EGM2008, 4 DEMs, 77–132M personas bajo nivel del mar con +1 m de subida

[Ver notebook](papers/2026-03-11-nivel-mar-132-millones/notebook) · [Leer más](papers/2026-03-11-nivel-mar-132-millones/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-11-nivel-mar-132-millones/notebook.ipynb)

---

### 💎 Crearon el diamante imposible que solo existía en meteoritos

**Física** · Nature · Diamante hexagonal (lonsdaleíta) puro a escala milimétrica, dureza Vickers 280 GPa, XRD con 9 picos hexagonales, TGA estabilidad térmica

[Ver notebook](papers/2026-03-11-diamante-hexagonal-meteoritos/notebook) · [Leer más](papers/2026-03-11-diamante-hexagonal-meteoritos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-11-diamante-hexagonal-meteoritos/notebook.ipynb)

---

## ¿Cómo funciona?

1. **Elige un paper** de la lista
2. **Click en "Abrir en Colab"** — el botón azul de cada notebook
3. **Runtime → Run all**
4. **Explora** — cambia valores, haz zoom, cuestiona cada número

Cada notebook tiene una sección **"Ahora tú"** con preguntas para explorar y código listo para arrancar.

---

## Lo que nos diferencia

- **Datos reales** — descargados directamente de los papers y repositorios públicos
- **Verificable** — cada notebook incluye una tabla de "¿qué soportan los datos?" con limitaciones explícitas
- **Transparente** — si una correlación es débil, lo decimos. Si hay un outlier sospechoso, lo mostramos
- **Reproducible** — un click en Colab y puedes ejecutar todo tú mismo

---

```{tableofcontents}
```

---

*[YouTube](https://youtube.com/@CienciaaMordiscos) · [TikTok](https://tiktok.com/@cienciaamordiscos) · [Ko-fi](https://ko-fi.com/samumirandam)*
