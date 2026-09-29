# Neurociencia

## Le apretaron la tibia y el cerebro se recuperó

*Nature Neuroscience* · Comprimir la tibia una vez al día acorta de 8,46 s a 5,46 s lo que tarda un
ratón con daño cerebral en bajar de un poste; los sanos tardan 5,62 s
(d = 1,94, n = 24 por grupo). La memoria espacial va detrás (+8,96 s en el
cuadrante diana, d = 1,38, coincide con los 8,953 s que reporta el paper), el
beneficio se apaga si se quita PIEZO1 de los osteocitos (d de 1,26–2,46 cae a
0,10–0,57) y el suero de un ratón comprimido lo reproduce en otro que nunca
pisó la máquina (d = 1,34). ⚠️ Solo ratones y cerdos, cero datos humanos; a
4 semanas quedan 3 cerdos por grupo y el Mann-Whitney no baja de p = 0,1 con
ese n; las cuantificaciones de hipocampo no traen unidad declarada.

[Ver notebook](../papers/2026-09-22-compresion-tibia-cerebro/notebook) · [Leer más](../papers/2026-09-22-compresion-tibia-cerebro/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-09-22-compresion-tibia-cerebro/notebook.ipynb)

---

## Un ratón con el córtex casi entero de células humanas. ¿Camina igual?

*Nature* · Vaciaron el córtex de un ratón de sus neuronas excitadoras y lo rellenaron con organoides humanos: a los 3 meses el 91,9% del tejido cortical era humano y el injerto había crecido 4,7× en un mes (mediana 3,77×). La velocidad de carrera no cambia (p = 0,85) pero sí la coordinación de las patas (p = 0,0039), y los xenocorticales alternan en el laberinto por encima del azar. ⚠️ El mapa espacial MERFISH de Zenodo se descartó: anotación colapsada por bloques.

[Ver notebook](../papers/2026-09-16-xenocortex-organoides-humanos-raton/notebook) · [Leer más](../papers/2026-09-16-xenocortex-organoides-humanos-raton/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-09-16-xenocortex-organoides-humanos-raton/notebook.ipynb)

---

## Para llegar a su sitio en el cerebro, una neurona se rompe el ADN

*Nature* · Para migrar a su capa final en el cerebelo, las neuronas recién nacidas se apretujan por pasadizos más estrechos que su propio núcleo — y el apretón les parte las dos cadenas del ADN. **El hallazgo:** durante la migración, **el 41% de las neuronas** tienen el ADN roto (día 4); en el cerebro adulto el daño baja a **0,2%** (día 30). El culpable es mecánico: en corredores de **3 µm** el daño llega al 42%, contra 8% en los de 5 µm (unas 5 veces más). Y la neurona no muere — repara cada corte en una o dos horas (mediana **82 min**). Cuando apagan la Ligasa IV que sella los cortes, el ratón camina de adulto con las patas **+17% más abiertas**. ⚠️ La curva de daño por desarrollo es descriptiva: muestra cuándo ocurre el daño, no prueba el mecanismo (eso lo aporta el experimento de corredores). ⚠️ El andar Control vs mutante está pseudorreplicado (varias huellas por ratón, sin IDs). ⚠️ El salto a "riesgo de enfermedad" es del paper, en modo condicional; el déficit motor global es leve.

[Ver notebook](../papers/2026-07-02-neuronas-migracion-dano-adn/notebook) · [Leer más](../papers/2026-07-02-neuronas-migracion-dano-adn/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-02-neuronas-migracion-dano-adn/notebook.ipynb)

---

## ¿El miedo te rompe el sueño? Lo que se ve en ratones

*Science* · Le dieron un susto a un ratón (un protocolo estándar de miedo) y le grabaron el sueño antes y después. Bajamos los datos por animal de los episodios de vigilia y micro-despertar. **El hallazgo:** tras el miedo, el sueño se fragmenta — **+37 micro-despertares, un 22%** (*d* pareado = 1,13, Wilcoxon p=0,016), y **los 7 de 7 ratones** reaccionaron igual. El golpe es específico: el sueño REM no se movió (Δ≈0). ⚠️ Muestra pequeña (miedo n=7, Control n=5). ⚠️ El contraste entre grupos es significativo sobre los cambios (p=0,010), pero con n pequeño el resultado robusto es el cambio dentro de cada animal. ⚠️ Estudio en ratones — no se extrapola a insomnio ni a estrés postraumático humano.

[Ver notebook](../papers/2026-06-04-reactivacion-memoria-sueno/notebook) · [Leer más](../papers/2026-06-04-reactivacion-memoria-sueno/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-04-reactivacion-memoria-sueno/notebook.ipynb)

---

## Tu cerebro tiene 72 autopistas blancas. Ahora hay un mapa de cómo cambian del nacimiento a los 90 años

*Nature* · Kim et al. (2026) procesaron **35.120 escáneres cerebrales** de estudios globales para construir los primeros charts normativos lifespan de **72 vías de sustancia blanca**, de 0 a 100 años — el equivalente para los "cables" del cerebro de las curvas de crecimiento pediátrico. Bajamos los datos derivados (Zenodo) y los desmenuzamos en tres actos. **Acto 1:** el volumen del Fascículo Arcuato izquierdo (vía clave del lenguaje) pica cerca de los **16 años** y se mantiene en meseta hasta los 40 antes de declinar. **Acto 2:** en una cohorte de validación (38 controles + 33 pacientes con esclerosis múltiple), la **Radiación Óptica** muestra un efecto **grande** (Cohen's d = **1,21**, p < 0,001) mientras que los **tractos motores** (cortico-espinal) están **preservados** (d = 0,02, p = 0,96). **Acto 3:** el volumen del Fascículo Arcuato izquierdo NO discrimina MS de controles — 35/38 controles y 32/33 pacientes caen dentro de la banda normativa. La señal clínica vive en la microestructura por tracto, no en el volumen agregado. ⚠️ Cohorte clínica pequeña (n = 71) con desbalance de sexo. ⚠️ Estudio observacional transversal — asociación entre MS y baja FA, no causalidad establecida en un solo corte. ⚠️ El dataset público derivado cubre 1 de los 72 tractos del chart normativo.

[Ver notebook](../papers/2026-05-25-white-matter-brain-charts/notebook) · [Leer más](../papers/2026-05-25-white-matter-brain-charts/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-25-white-matter-brain-charts/notebook.ipynb)

---

## Las píldoras anti-obesidad pasan por la amígdala

*Nature* · Las nuevas píldoras anti-obesidad (Danuglipron, Orforglipron) actúan sobre el mismo receptor que Ozempic — pero solo se unen a la versión humana. Para estudiarlas, el equipo creó ratones humanizados (S33W: una sola letra del aminoácido 33 cambiada). **Acto 1:** Liraglutide funciona en ambos genotipos (≈−52% a 2h, *d* = −1.94 en WT). Danuglipron solo en S33W (−51.5%, *d* = −1.39) — en WT no hay efecto (*d* = +0.31). **Acto 2:** las pastillas activan más Fos en CeA (amígdala central, *d* = 0.45, *p* = 0.030), NTS y AP — pero **no** en DMH (saturado por GLP-1 endógeno). **Acto 3:** rescate AAV región-específica revela la disociación causal: devolver el receptor solo en CeA basta para suprimir comida palatable (−29%, *p* = 0.031, *d* pareado = −1.03), pero no afecta el chow normal (*p* = 0.94). El hipotálamo hace lo opuesto: controla la ingesta homeostática (*d* pareado = −1.12), no la hedónica. ⚠️ Modelo S33W humaniza UN aminoácido — la arquitectura del circuito en cerebros humanos está por confirmar. ⚠️ *n* pequeños (6-10) en pareados de Fig 4.

[Ver notebook](../papers/2026-05-06-glp1-amigdala-recompensa-ratones/notebook) · [Leer más](../papers/2026-05-06-glp1-amigdala-recompensa-ratones/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-06-glp1-amigdala-recompensa-ratones/notebook.ipynb)

---

## Dopamina y cerebro maternal

*Nature* · Un grupo demuestra que silenciar la liberación de **dopamina** en el **hipocampo dorsal** de una hembra virgen es **suficiente** para que recoja crías como una madre experimentada. Bajamos los datos conductuales del Supplementary (MOESM5) — 34 hembras en el test de aprendizaje contextual y 51 en el de recogida de crías — y los analizamos célula por celda. Acto 1: la maternidad casi duplica el aprendizaje contextual (Cohen *d* = 1,22, *p* = 0,021). Acto 2: el estrés postparto crónico tiende a borrar esa ventaja, con alta variabilidad individual (*d* = -0,50). Acto 3 — el golpe: **8 de 13 vírgenes con control viral nunca recogen cría** antes del cutoff de 900 s; con dopamina silenciada químicamente, **14 de 15 lo hacen en mediana 102 s** (Cohen *d* = -1,50, *p* = 0,0018). Y silenciar dopamina en madres **no** cambia su conducta — control de especificidad limpio. ⚠️ Estudio en ratón; la validación humana del paper es solo molecular, no conductual. ⚠️ Cutoff a 900 s introduce censura administrativa: subestima la diferencia real.

[Ver notebook](../papers/2026-05-20-dopamina-cerebro-maternal/notebook) · [Leer más](../papers/2026-05-20-dopamina-cerebro-maternal/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-20-dopamina-cerebro-maternal/notebook.ipynb)

---

## Hipocampo bajo anestesia: oddball, plasticidad y predicción semántica

*Nature* · Saponati et al. (2026) registraron actividad neuronal con electrodos Neuropixels en el **hipocampo de 7 pacientes** con epilepsia anestesiados con propofol antes de su lobectomía. Tres pacientes escucharon una secuencia de tonos con *oddballs* (sonidos raros entre tonos repetidos); cuatro escucharon habla natural. Resultado: **43 de 150 unidades (28,7%)** discriminaron el oddball bajo anestesia (p<0,05 en p5 y p6); el effect size **creció en los ~10 minutos del experimento** — plasticidad representacional medible. Para el lenguaje, la correlación semántica all-words fue **0,397 en anestesiados (n=368 unidades) vs 0,226 en despiertos (n=356)** — un factor de **1,76×**. Las bandas alpha y beta concentran el encoding (45% de canales en alpha para oddball; 46% en beta para tono). ⚠️ La comparación anaesth vs awake usa hardware distinto (Neuropixels vs microcables EMU): es informativa, no controlada — el paper lo enmarca como "comparable", no como superioridad. ⚠️ Solo propofol — no generaliza a otras anestesias. ⚠️ Los autores enmarcan los resultados de lenguaje como *indicate* (no *demonstrate*).

[Ver notebook](../papers/2026-05-06-hipocampo-anestesia-lenguaje/notebook) · [Leer más](../papers/2026-05-06-hipocampo-anestesia-lenguaje/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-06-hipocampo-anestesia-lenguaje/notebook.ipynb)

---

## 🧠 Tu cerebro reutiliza el mismo código para ver e imaginar

*Science* · 367 neuronas individuales grabadas en la corteza temporal ventral (VTC) de 16 pacientes epilépticos. Al imaginar un objeto sin verlo, el 74% de las neuronas reactivan el mismo código que usaron al percibirlo (ρ = 0,56 a nivel de población, n = 338). Evidencia directa de un modelo generativo en el cerebro humano.

[Ver notebook](../papers/2026-04-15-codigo-neural-percepcion-imaginacion/notebook) · [Leer más](../papers/2026-04-15-codigo-neural-percepcion-imaginacion/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-15-codigo-neural-percepcion-imaginacion/notebook.ipynb)

---

## Una proteína viral le devolvió la memoria a ratones con deterioro cognitivo

*Science* · Reineke et al. (2026) muestran que una variante humana del gen **PPP1R15B (R658C)** mantiene encendida una respuesta de estrés celular llamada **ISR** — y eso solo basta para deteriorar la memoria. La proteína viral **DP71L** la apaga y revierte los déficits cognitivos en ratones con Down, Alzheimer y envejecimiento. Este notebook usa el dataset público **GSE310398** para verificar la firma molecular: **ATF4 sube su eficiencia traduccional 53% en el cerebro mutante** (p ≈ 0,005, Cohen's d ≈ 5), **CHOP +41%**, y solo **1,6% de los 10.908 genes expresados** cambian — el ISR es un escalpelo molecular, no un mazo.

[Ver notebook](../papers/2026-04-06-viral-dp71l-reverso-deterioro-cognitivo/notebook) · [Leer más](../papers/2026-04-06-viral-dp71l-reverso-deterioro-cognitivo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-06-viral-dp71l-reverso-deterioro-cognitivo/notebook.ipynb)

---

## 🧠 Hambre después de estudiar

*Nature* · Memoria en *Drosophila* por tipo de entrenamiento, silenciamiento Gr43a, preferencia por sucrosa post-aprendizaje

[Ver notebook](../papers/2026-03-30-hambre-despues-estudiar/notebook) · [Leer más](../papers/2026-03-30-hambre-despues-estudiar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-30-hambre-despues-estudiar/notebook.ipynb)

---

## 333 piezas del cerebro: el atlas que está reescribiendo cómo medimos lo que hay dentro

*Nature* · Iglesias et al. (2025) tomaron **5 hemisferios cerebrales completos**, los seccionaron en cerca de **10.000 láminas histológicas**, las alinearon en 3D con métodos de IA y delinearon manualmente **333 regiones de interés**. El error medio de registro 3D **baja un 31% (de 1,44 a 0,99 mm)** frente al pipeline anterior — y los 5 hemisferios mejoran a la vez, sin un solo caso donde el método previo gane. En la prueba clínica con 383 escáneres ADNI, **NextBrain clasifica Alzheimer vs control con AUROC 0,953 (acierto 90,3%)**, por encima de FreeSurfer (0,911) y Allen MNI (0,929). Pero atención: **AUROC no es diagnóstico** — es capacidad de ranking.

[Ver notebook](../papers/2025-11-05-nextbrain-atlas-333-regiones/notebook) · [Leer más](../papers/2025-11-05-nextbrain-atlas-333-regiones/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-11-05-nextbrain-atlas-333-regiones/notebook.ipynb)

---

## Un implante cerebral sin cirugía: 5.8x más células donde hay inflamación

*Nature Biotechnology* · Yadav et al. (2025) diseñan un implante cerebral **sin cirugía**: macrófagos recubiertos con proteína conductora cargados con fotodiodos del tamaño de bacterias (SWEDs), inyectados en sangre y activados con luz infrarroja desde fuera del cráneo. Los datos del Source Data MOESM3 (Fig 4f, 5f, 2g) muestran que los híbridos con luz se concentran **5,76× más** que el control completo en la zona inflamada (315 vs 55 cells/mm²) — Cohen's d = 4,24, p = 0,029 (Mann-Whitney, n=4 vs n=4). Bootstrap de 10.000 re-muestreos: el 100% supera el umbral de "efecto grande". Los SWEDs persisten 6 meses sin decaimiento detectable (aunque n=2-3 limita el test formal: U=1, p=0,40 entre 1d y 6m). Y el cráneo de ratón apenas atenúa la luz NIR — solo **11,6% de pérdida** a 46 mW/mm². Prueba de concepto en ratones con inflamación inducida por LPS — distancia regulatoria significativa antes de aplicación clínica.

[Ver notebook](../papers/2025-11-05-implantes-cerebrales-circulatronics/notebook) · [Leer más](../papers/2025-11-05-implantes-cerebrales-circulatronics/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-11-05-implantes-cerebrales-circulatronics/notebook.ipynb)

---

## La brújula del cerebro en murciélagos

*Science* · Palgi et al. (2025) registraron **97 neuronas brújula** en el presubículo de murciélagos volando libres sobre la selva de Zanzíbar — sin jaula, sin pistas controladas. La dirección preferida de esas neuronas drifteaba **1,72°/s la primera noche** y solo **0,20°/s la sexta**: una estabilización 8,4× con la experiencia (Spearman ρ = −0,60, p < 1e-8). Los datos sugieren que la brújula funciona igual con o sin luna.

[Ver notebook](../papers/2025-10-16-brujula-cerebral-murcielagos-isla/notebook) · [Leer más](../papers/2025-10-16-brujula-cerebral-murcielagos-isla/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-10-16-brujula-cerebral-murcielagos-isla/notebook.ipynb)
