# Astronomía

## El azufre que en Marte no debería estar suelto

*Science* · En Marte el azufre siempre viene agarrado a otra cosa. En el valle de Gediz, Curiosity le apuntó el espectrómetro a un parche de **2.100 m²** de piedras claras y una rueda del rover partió una. **El hallazgo:** en 10 análisis sobre cinco piedras el azufre llega a **83,28 wt%** de media contra **16,39** en las rocas vecinas (**5,08x**, d = 18,87) — y falta todo lo demás: hierro a **0,07** de su valor vecino, calcio a **0,18**. Los cationes que un sulfato necesitaría no están, y la razón Compton/Rayleigh (**1,39 vs 1,83**) lo confirma por una vía independiente. ⚠️ La columna del CSV se llama `SO3_pct` y **eso no quiere decir sulfato**: el APXS reporta el azufre *como si fuera* SO₃ por convención de calibración. ⚠️ El origen —vapor magmático atrapado en la criosfera— es lo que los autores **proponen**, no lo que el rover midió.

[Ver notebook](../papers/2026-08-22-azufre-nativo-gale-marte/notebook) · [Leer más](../papers/2026-08-22-azufre-nativo-gale-marte/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-08-22-azufre-nativo-gale-marte/notebook.ipynb)

---

## La fusión que se nos había escondido

*Nature Astronomy* · Los cúmulos globulares son escombros que no se borran: si la Vía Láctea se tragó una galaxia, sus cúmulos siguen orbitando. Massari et al. datan 39 con el Hubble a **0,26** miles de millones de años de error (contra 0,91 y 0,43 de los catálogos previos) y los ven ordenarse en secuencias distintas del plano edad–metalicidad. **El hallazgo:** los dos progenitores dejaron de formar cúmulos con **1,76 mil millones de años de diferencia**, y **13 de 14 candidatos** al nuevo progenitor —bautizado LKH— quedaron dentro de los **6 kiloparsecs interiores**, frente a **0 de 14** en Gaia-Sausage-Enceladus (d = 2,72, p = 7,5e-06). ⚠️ El 1,8 del titular **no es el hueco entre las curvas**: es la resta de dos parámetros ajustados, y propagada da **+0,81/−0,89**. ⚠️ Con las etiquetas públicas la **edad sola no separa** LKH de GSE (p = 0,077). ⚠️ Nuestros grupos son un **proxy** de la clasificación bayesiana del paper, y las edades son **relativas**, no absolutas.

[Ver notebook](../papers/2026-08-19-fusion-lkh-cumulos-globulares/notebook) · [Leer más](../papers/2026-08-19-fusion-lkh-cumulos-globulares/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-08-19-fusion-lkh-cumulos-globulares/notebook.ipynb)

---

## El techo que no existe: regresión a la media en las tormentas solares

*Nature* · Durante casi 40 años, la respuesta magnética de la Tierra al viento solar parecía chocar contra un techo cuando el empuje era extremo — la llamada **saturación**, con una decena de teorías físicas para explicarla. Este re-análisis muestra que el techo nunca existió: es **regresión a la media**, el sesgo que aparece al medir valores extremos con instrumentos imprecisos. Reproducimos su Monte Carlo (semilla 42) y reunimos **9 estudios** de 1981 a 2005. **El hallazgo:** una respuesta perfectamente **lineal** más error de medición basta para doblar la curva; en el **decil más extremo** cae **~30%** por debajo de la recta real (hasta **~41%** en la punta). Corregido el sesgo, el impacto de las tormentas extremas **podría acercarse al doble**. ⚠️ La parte cuantitativa vive en la **simulación**, no en observaciones crudas: muestra que el artefacto *puede* explicar la saturación, no que sea la única causa. ⚠️ La tendencia de los 9 estudios es **sugestiva, no significativa** (ρ=0,64, p≈0,06, n=9). ⚠️ El **2x** es la corrección máxima estimada por el paper ('can be twice'), no un hecho cerrado.

[Ver notebook](../papers/2026-07-15-regresion-media-geomagnetica/notebook) · [Leer más](../papers/2026-07-15-regresion-media-geomagnetica/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-15-regresion-media-geomagnetica/notebook.ipynb)

---

## El asteroide que era un cometa disfrazado

*Nature Astronomy* · **875163 (1998 SH2)** está catalogado como asteroide potencialmente peligroso, pero su órbita se desvía año tras año como si algo la empujara desde adentro. Abrimos las tablas de la **NASA/JPL** con **42.007** asteroides y **208** cometas cercanos a la Tierra, más el registro de 1998 SH2. **El hallazgo:** dos pistas dinámicas lo delatan como cometa — su parámetro de Tisserand **T_J = 2,91** cae bajo la frontera clásica de 3 (donde viven los cometas), y tiene una aceleración no-gravitacional **|A₂| = 6,96·10⁻¹³ au/día²** ajustada a **14σ**, unas **10 veces** la de una roca típica. Pero es un **cometa débil**: su empujón queda **~316 veces** por debajo del cometa promedio. Y no está solo — **2.120 de 42.007** "asteroides" (5,05%) tienen órbita de cometa. ⚠️ El A₂ es **consistente con** una fuga de gas, no una medición directa: la prueba (una cola tenue) la aportan los autores con telescopios de gran apertura y **no** se reproduce en el notebook. ⚠️ T_J es un discriminante estadístico, no una prueba: 6 cometas conocidos viven sobre la frontera. ⚠️ El A₂ de 1998 SH2 es solo transversal (sin componente radial ajustada).

[Ver notebook](../papers/2026-07-10-neo-1998-sh2-cometa/notebook) · [Leer más](../papers/2026-07-10-neo-1998-sh2-cometa/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-10-neo-1998-sh2-cometa/notebook.ipynb)

---

## GW250114: la huella del horizonte de un agujero negro

*Nature* · Un agujero negro arrastra el espacio a su alrededor: cualquier cosa que cruza su horizonte parece girar a una misma velocidad, la del propio horizonte. GW250114, una de las fusiones más ruidosas jamás detectadas, trajo escondida una "onda directa" que lleva esa firma. **El hallazgo:** la onda aparece con **SNR de filtro adaptado ≈ 15,8 (Hanford) / 17,1 (Livingston)**, y sus dos cocientes característicos convergen en **1** cerca de la fusión — la onda oscila a la velocidad de arrastre del horizonte (2·Ω_H) y se apaga a su gravedad superficial (κ), la firma de un agujero negro de Kerr. El remanente: **~63 masas solares** girando a **dos tercios** del máximo, tras radiar **~3,12 masas solares** en ondas gravitacionales. ⚠️ Es un solo evento, de los más fuertes registrados; la onda directa es tenue y solo se ve por esa potencia excepcional. ⚠️ Los cocientes de la huella salen del modelo analítico del paper normalizado con el espín del remanente (χ_f = 0,6725), no de una medición independiente del horizonte. ⚠️ El paper la enmarca como *primera evidencia* observacional de su clase, aún no repetida en muchos eventos.

[Ver notebook](../papers/2026-06-24-gw250114-horizonte-agujero-negro/notebook) · [Leer más](../papers/2026-06-24-gw250114-horizonte-agujero-negro/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-24-gw250114-horizonte-agujero-negro/notebook.ipynb)

---

## El carbono de 3I/ATLAS es casi el doble de primitivo que el del Sol

*Nature* · 3I/ATLAS es apenas el tercer objeto interestelar que cruza el sistema solar, y con JWST midieron la huella isotópica de su gas. **El hallazgo:** su ¹²C/¹³C ronda **147–166**, casi el doble del solar (**89**) — y ningún lugar de la Vía Láctea actual llega tan alto: el gradiente galáctico se queda en **~97** (para alcanzar 141 harían falta 25 kpc, fuera de la galaxia poblada). Su agua además rebosa deuterio: **D/H = 0,98%**, más de 10 veces el de cualquier cometa conocido. Ocho pistas independientes apuntan a lo mismo: nació **frío y muy antiguo**. ⚠️ No hay dataset descargable: las cifras se destilaron del abstract y el Supplementary revisado por pares. ⚠️ La edad de hasta **~12.000 millones de años** es dependiente de modelos de evolución química galáctica — el paper dice *may*, y la edad dinámica independiente da ~3–11 Gyr. ⚠️ La temperatura de formación (≲30 K) es inferencia, no medición directa.

[Ver notebook](../papers/2026-06-22-3i-atlas-isotopos-origen-frio/notebook) · [Leer más](../papers/2026-06-22-3i-atlas-isotopos-origen-frio/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-22-3i-atlas-isotopos-origen-frio/notebook.ipynb)

---

## La atmósfera de un planeta que orbita una enana blanca

*Nature* · Cuando una estrella como el Sol muere, deja una enana blanca del tamaño de la Tierra. WD 1856 b es un planeta gigante que sobrevivió a esa muerte y hoy la orbita tan de cerca que, al pasar por delante, **tapa 51–56% de su luz** — el tránsito más profundo conocido, porque el planeta es más grande que la estrella. El James Webb aprovechó ese eclipse descomunal para leer su atmósfera. **El hallazgo:** el espectro revela aerosoles e hidrocarburos, acota la masa a **4,3–10,9 masas de Júpiter** y mide una temperatura efectiva de **~390–412 K**, unos **242 K por encima** de los 160 K de equilibrio esperados. ⚠️ El metano es el candidato preferido con evidencia moderada (odds 17:1–30:1), no una detección confirmada. ⚠️ Masa y temperatura salen de ajustar modelos al espectro (por eso dos pipelines independientes). ⚠️ Todo apunta a un recalentamiento hace 3,0–5,5 Gyr, pero es una inferencia de modelos de enfriamiento, no una medición.

[Ver notebook](../papers/2026-07-01-atmosfera-enana-blanca-wd1856/notebook) · [Leer más](../papers/2026-07-01-atmosfera-enana-blanca-wd1856/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-01-atmosfera-enana-blanca-wd1856/notebook.ipynb)

---

## El universo no se ve igual en todas las direcciones (hasta donde alcanzamos a mirar)

*Nature* · El principio cosmológico —base de casi toda la cosmología— asume que, si te alejas lo suficiente, el universo se ve igual hacia cualquier dirección. Un equipo mapeó **150.136 galaxias** de DESI DR1 en cinco profundidades, del vecindario cósmico hasta **~1 gigaparsec** (mil millones de pársecs), y midió si hay direcciones preferidas. **El hallazgo:** la distribución de galaxias muestra **estructuras anisotrópicas que persisten hasta escalas de un gigaparsec**, con significancia conservadora **>3σ** según el estadístico ADPD del paper frente a catálogos simulados ΛCDM. En nuestro proxy didáctico, el cosmos cercano es **7× más direccional** que el azar; las muestras profundas mantienen un exceso más leve. ⚠️ El notebook usa un **proxy ilustrativo**, no el ADPD del paper: su razón (×) nunca es una significancia σ. ⚠️ 3σ no es 5σ (el umbral de descubrimiento): una señal fuerte que **reta** el supuesto de isotropía, no que refute ΛCDM. ⚠️ Un solo estudio observacional, sobre la proyección 2D de rebanadas finas.

[Ver notebook](../papers/2026-06-24-anisotropia-cosmica-gigaparsec/notebook) · [Leer más](../papers/2026-06-24-anisotropia-cosmica-gigaparsec/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-24-anisotropia-cosmica-gigaparsec/notebook.ipynb)

---

## ¿A los astrobiólogos los convence más Marte o K2-18 b?

*Nature Astronomy* · Tras los dos anuncios de posible vida de 2025 —gases raros en el exoplaneta **K2-18 b** (abril) y la roca marciana **Cheyava Falls** (septiembre)— alguien encuestó a la comunidad: **920 astrobiólogos** votaron qué tan de acuerdo estaban con que cada anuncio fuera evidencia de vida. **El hallazgo:** Marte convenció más —confianza media **41% vs 28%** para K2-18 b, **+12 puntos** (Cohen's *d* = 0,57, Mann-Whitney p=3,8·10⁻¹⁷)—, pero aun en el caso más persuasivo **3 de cada 4** expertos (sin contar indecisos) siguieron sin verlo como vida; con K2-18 b fueron **9 de cada 10**. ⚠️ La encuesta mide **opinión/confianza experta**, no la validez física de cada evidencia. ⚠️ Son **dos encuestas independientes** (distintos respondientes y fechas), no una comparación pareada. ⚠️ Tasas de respuesta 39% y 33%: posible sesgo de autoselección.

[Ver notebook](../papers/2026-06-05-astrobiologos-vida-extraterrestre/notebook) · [Leer más](../papers/2026-06-05-astrobiologos-vida-extraterrestre/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-05-astrobiologos-vida-extraterrestre/notebook.ipynb)

---

## Un agujero negro de 6.000 millones de soles a redshift 2

*Science* · El telescopio **James Webb** midió la masa del agujero negro inactivo de la galaxia **MRG-M0138**, a *redshift* **1,95** (su luz salió hace ~10.300 millones de años). Una **lente gravitacional** amplió la imagen lo suficiente para asomarse a su corazón. **El hallazgo:** pesa **6,0 ⁺²·¹₋₁·₇ × 10⁹ masas solares** —rivaliza con M87*—, y su firma está en los datos: las estrellas del centro (~60 pc) se mueven a ~459 km/s, un **~21% más rápido** que la meseta exterior (~380 km/s). ⚠️ La masa viene de modelos dinámicos del paper que corren en clúster de cómputo; el notebook reproduce el *observable* (el campo de velocidades V_rms), no recalcula la masa. ⚠️ El abstract dice que es 'consistente con' la relación M–σ (no igualdad exacta) — lo respetamos.

[Ver notebook](../papers/2026-06-04-masa-agujero-negro-redshift-2/notebook) · [Leer más](../papers/2026-06-04-masa-agujero-negro-redshift-2/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-04-masa-agujero-negro-redshift-2/notebook.ipynb)

---

## Agujeros negros donde no deberían existir

*Nature Astronomy* · Antonini et al. (2026) combinan **153 fusiones de agujeros negros** del catálogo LIGO-Virgo-KAGRA (GWTC-1+2+3+4) con inferencia jerárquica Bayesiana para acotar el borde inferior del *mass gap* por inestabilidad de pares en **44,3 +5,9/−3,5 M_⊙** (90% CI) y la sección eficaz de la reacción ¹²C(α,γ)¹⁶O en **S₃₀₀ = 268 +195/−116 keV b**. Los datos revelan **dos poblaciones** con factor de Bayes B > 10⁴: una de espín bajo sin agujeros sobre el gap, otra de espín alto con orientación aleatoria que se extiende en todo el rango de masa — consistente con fusiones jerárquicas en cúmulos densos. En el subconjunto O4a (**84 BBHs** nuevos) verificamos: 30 eventos (35,7 %) tienen m₁ mediana por encima del borde del gap, y los **6 con m₁ > 70 M_⊙** tienen mediana de χ_eff = **+0,27** (nueve veces la mediana global de +0,03). Bootstrap p ≈ 0,0006. ⚠️ Diseño observacional — claims solo de asociación. ⚠️ El paper usa modelo de mixtura jerárquica; aquí mostramos un cross-check visual sobre el subset O4a. ⚠️ El S-factor del paper no se replica — requiere inferencia conjunta GW + evolución estelar.

[Ver notebook](../papers/2026-05-13-pair-instability-mass-gap/notebook) · [Leer más](../papers/2026-05-13-pair-instability-mass-gap/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-13-pair-instability-mass-gap/notebook.ipynb)

---

## LAP1-B: la galaxia más químicamente primitiva conocida

*Nature* · Nakajima et al. (2026) presentan observaciones del James Webb (NIRSpec/PRISM) sobre **LAP1-B**, una galaxia ultra-débil a redshift espectroscópico **z = 6,625 ± 0,001** — 800 millones de años después del Big Bang. La galaxia está amplificada **98 veces** por una lente gravitacional; sin esa amplificación no la habríamos visto. La abundancia de oxígeno gas-phase es **(4,2 ± 1,8) × 10⁻³ veces el valor solar** — unas 240 veces menos oxígeno por átomo de H que el sistema solar, y la convierte en la galaxia formadora de estrellas más químicamente primitiva conocida. Nuestro cross-check con λ_obs(Hα) = 5,0052 μm recupera z = 6,626 (diferencia 0,0014 con el paper, atribuible a la precisión del pico en el CSV). De las 9 líneas analizadas, **4 superan S/N = 3** (Hα, Lyα, [O III] 5007, Hβ). El log ξ_ion observado (≥26,1) se acerca al máximo teórico de Pop III zero-age (26,2). ⚠️ Una sola galaxia — no se puede generalizar. ⚠️ La masa estelar < 3.300 M☉ es un **límite superior 3σ**, no medición (el continuo estelar no se detecta). ⚠️ HeII/Hβ < 2,5 no distingue Pop III pura de Pop II extremadamente pobre en metales.

[Ver notebook](../papers/2026-05-13-lap1-b-galaxia-reionizacion/notebook) · [Leer más](../papers/2026-05-13-lap1-b-galaxia-reionizacion/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-13-lap1-b-galaxia-reionizacion/notebook.ipynb)

---

## Diversidad molecular como biosignatura: la vida se delata por cómo reparte sus aminoácidos

*Nature Astronomy* · Yoffe et al. (2026) proponen una bisagra para distinguir vida de química abiótica: no por **cuántos** tipos de moléculas hay, sino por **cómo se reparten**. Sobre **69 muestras de aminoácidos** (30 abióticas + 28 bióticas + 11 mixtas) la entropía de Shannon separa los grupos con un **Cohen's d = 2,06** (Mann-Whitney U one-sided, **p = 3,8 × 10⁻⁸**). La paradoja: las muestras abióticas tienen **más tipos** distintos en promedio (16,3 vs 14,1), pero los meteoritos como **Bennu** están dominados por **glicina al 64,2%** del total, mientras *E. coli* reparte sus 18 aminoácidos parejo (H = 2,78). ⚠️ Estudio observacional — los datos muestran asociación, no causalidad mecanística. ⚠️ Las 28 muestras bióticas son mayoritariamente microbios y fósiles de la Tierra; vida bioquímicamente exótica con 2-3 aminoácidos dominantes sería marcada como abiótica. ⚠️ Para ácidos grasos, con entropía de Shannon cruda el patrón **no replica** (p=0,76) — el paper usa un marco probabilístico con propagación de incertidumbres que excede el alcance del notebook.

[Ver notebook](../papers/2026-05-12-diversidad-molecular-biosignatura/notebook) · [Leer más](../papers/2026-05-12-diversidad-molecular-biosignatura/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-12-diversidad-molecular-biosignatura/notebook.ipynb)

---

## Una superficie oscura, plana y aburrida — y eso lo dice todo

*Nature Astronomy* · Whittaker et al. (2026) tomaron el primer espectro infrarrojo medio (5–12 μm) del planeta rocoso **LHS 3844 b** con el James Webb durante 3 eclipses secundarios. La cara diurna está a **985 K** (~712 °C) y refleja apenas el 22% de la luz que recibe — más oscura que Marte, comparable a la Luna o Mercurio. Pero el resultado clave es lo que el espectro **no** muestra: **χ²_red = 1.30 contra un modelo lineal** en 12 bandas espectrales — un espectro plano, sin features detectables. Eso descarta una atmósfera densa de CO₂ (**< 100 mbar a 5σ**), disfavorece SO₂ volcánico (**< 10 μbar a 3σ**), y descarta polvo basáltico fresco. El mejor ajuste cualitativo del paper: superficie tipo basalto oscuro o material rico en olivino, meteorizado por intemperismo espacial. ⚠️ El ajuste lineal verifica que el espectro es plano, pero "plano" no implica "basalto" — la identificación composicional viene del cruce con la base RELAB de >100 espectros de laboratorio, no replicado aquí. ⚠️ Las bandas 11.4 y 12.1 μm tienen barras de error 5× mayores que las primeras (>190 ppm vs ~35 ppm), dominando la incertidumbre.

[Ver notebook](../papers/2026-05-04-lhs-3844b-superficie-jwst/notebook) · [Leer más](../papers/2026-05-04-lhs-3844b-superficie-jwst/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-04-lhs-3844b-superficie-jwst/notebook.ipynb)

---

## Una atmósfera donde los modelos no la esperaban

*Nature Astronomy* · Arimatsu et al. (2026) registraron una **ocultación estelar** del 10 de enero de 2024 en (612533) 2002 XV93 —un *plutino* de **~250 km de radio**— desde tres telescopios en Japón: Kyoto, Kiso y Fukushima. La curva de luz no cae en escalón: la luz se atenúa de forma gradual, y eso solo lo hace el aire. Derivan una **presión superficial de 100–200 nbar**, **50–100 veces menor** que la de Plutón pero por encima del techo previo de 1–100 nbar establecido para TNOs > 500 km. Tres composiciones (N₂, CH₄, CO) ajustan la curva con calidad similar — la curva sola no decide qué se respira. Kiso es la curva crítica: con σ ≈ 0,06 es **5,2 veces más precisa** que las otras dos, y el ajuste χ² del paper se hace contra ella sola. ⚠️ Los autores presentan dos hipótesis especulativas para el origen — *criovulcanismo activo* o *un impacto reciente* — sin medirlas. ⚠️ Una sola ocultación de ~10 minutos no distingue entre atmósfera estable y transitoria.

[Ver notebook](../papers/2026-05-04-atmosfera-tno-2002-xv93/notebook) · [Leer más](../papers/2026-05-04-atmosfera-tno-2002-xv93/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-04-atmosfera-tno-2002-xv93/notebook.ipynb)

---

## ASTERIS — una IA aprende a separar señal de ruido en imágenes JWST

*Science* · Guo et al. (2026) entrenan un transformer self-supervised que aprende cómo se comporta el ruido entre exposiciones distintas del James Webb y lo descuenta sin tocar la señal de las galaxias reales. El catálogo final post-ASTERIS publicado en el Supplementary tiene **163 candidatos** a galaxias de alto redshift en un parche de 0.09° × 0.07° del campo profundo GOODS-South — más pequeño que la Luna llena vista desde la Tierra. **El 95.1% (155/163) está en zphot ≥ 9** (universo ≤ 540 Myr post Big Bang), incluyendo **3 candidatos extremos en zphot ≥ 18** (universo ≤ 250 Myr, todos F200W dropouts). El **87.1% (142/163) son más débiles que M_UV = −18**, el umbral típico de búsquedas previas a ASTERIS — coherente con la afirmación del paper de detectar galaxias 1.0 magnitud más débiles. ⚠️ Las afirmaciones "3× más candidatos" y "1.0 magnitud de mejora" vienen del benchmarking del paper con mock data; data_s1 contiene solo el catálogo final post-ASTERIS, no el baseline pre-ASTERIS.

[Ver notebook](../papers/2026-05-02-asteris-denoising-imagenes-jwst/notebook) · [Leer más](../papers/2026-05-02-asteris-denoising-imagenes-jwst/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-02-asteris-denoising-imagenes-jwst/notebook.ipynb)

---

## Jet de Cygnus X-1 doblado por viento estelar

*Nature Astronomy* · Miller-Jones et al. (2026), 18 años de observaciones VLBI revelan que el viento estelar dobla el jet de Cygnus X-1. Mediante inferencia bayesiana, miden por primera vez la potencia cinética instantánea del jet: log₁₀(L_jet) = 37,28 erg/s — comparable a la luminosidad en rayos X. El jet viaja a ~68% de la velocidad de la luz con un desalineamiento de ~5° respecto al eje orbital.

[Ver notebook](../papers/2026-04-17-jet-cygnus-x1-viento-estelar/notebook) · [Leer más](../papers/2026-04-17-jet-cygnus-x1-viento-estelar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-17-jet-cygnus-x1-viento-estelar/notebook.ipynb)

---

## 🪐 Planetas húmedos sin migrar desde lejos

*Nature* · Luo et al. (2025), experimentos de alta presión (8–42 GPa, 2.725–3.924 K) que simulan el interior de sub-Neptunos. Al comprimir una mezcla primordial (~5% H₂ + ~76% silicato + ~19% Fe), el hidrógeno reduce el silicato y produce 18,1 ± 0,5 wt% de H₂O — ~1.800× más que las predicciones previas (0,01 wt%). Una aleación Fe₀,₇₃Si₀,₂₇ confirma la reducción. Un sub-Neptuno de 5 M⊕ con 5% de envolvente podría generar 2–4 wt% H₂O sin migrar desde órbitas lejanas.

[Ver notebook](../papers/2026-04-15-agua-sub-neptunos-reaccion-magma/notebook) · [Leer más](../papers/2026-04-15-agua-sub-neptunos-reaccion-magma/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-15-agua-sub-neptunos-reaccion-magma/notebook.ipynb)

---

## 🌍 ¿De qué está hecha la Tierra? De nada que conozcamos

*Nature Astronomy* · Render et al. (2026), 10 anomalías isotópicas nucleosintéticas en 17 cuerpos del Sistema Solar. La Tierra es el endmember del array no-carbonáceo: z₀ = −2,37, más extremo que cualquier meteorito conocido. 0% de material del Sistema Solar exterior. Mercurio y Venus serían aún más extremos.

[Ver notebook](../papers/2026-04-15-acrecion-homogenea-tierra-sistema-solar/notebook) · [Leer más](../papers/2026-04-15-acrecion-homogenea-tierra-sistema-solar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-15-acrecion-homogenea-tierra-sistema-solar/notebook.ipynb)

---

## ⭐ Una estrella casi prístina de la Nube de Magallanes

*Nature Astronomy* · Ezzeddine et al. (2026), J0715−7334 tiene 20.000× menos hierro que el Sol — la única estrella ultra metal-poor que NO tiene exceso de carbono, huella de una supernova primordial de 30 M☉

[Ver notebook](../papers/2026-04-04-estrella-pristina-nube-magallanes/notebook) · [Leer más](../papers/2026-04-04-estrella-pristina-nube-magallanes/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-04-estrella-pristina-nube-magallanes/notebook.ipynb)

---

## TRAPPIST-1 b y c: rocas desnudas a 40 años-luz

*Nature Astronomy* · El JWST observó 52 horas continuas los dos planetas más cercanos a TRAPPIST-1. Resultado: rocas desnudas sin atmósfera. 490 K de día, cero de noche.

[Ver notebook](../papers/2026-04-03-trappist-1-sin-atmosfera-jwst/notebook) · [Leer más](../papers/2026-04-03-trappist-1-sin-atmosfera-jwst/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-03-trappist-1-sin-atmosfera-jwst/notebook.ipynb)

---

## 🧬 Las 5 bases del ADN en un asteroide

*Nature Astronomy* · A, G, C, T y U detectadas en Ryugu (Hayabusa2) — comparación con Bennu, Orgueil y Murchison, ratios purina/pirimidina distintos por cuerpo

[Ver notebook](../papers/2026-03-20-adn-bases-asteroide-ryugu/notebook) · [Leer más](../papers/2026-03-20-adn-bases-asteroide-ryugu/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-20-adn-bases-asteroide-ryugu/notebook.ipynb)

---

## ⭐ Estrellas naciendo fuera de la Vía Láctea

*Nature Astronomy* · 32 estrellas en 2 cúmulos abiertos (Emei-1 y Emei-2) dentro del Complejo H, Gaia DR3, isócronas PARSEC 11,2 Myr, metalicidad 0,05 Z⊙, distancia 13,8 kpc

[Ver notebook](../papers/2026-03-19-estrellas-fuera-via-lactea/notebook) · [Leer más](../papers/2026-03-19-estrellas-fuera-via-lactea/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-19-estrellas-fuera-via-lactea/notebook.ipynb)

---

## Primera eyección de masa coronal fuera del Sol

*Nature* · Callingham et al. (2025) reportan, con LOFAR, la primera detección directa de un análogo de **type II radio burst** desde una estrella distinta del Sol — la M dwarf temprana **StKM 1-1262** a ~32 años luz. El burst dura ~4 minutos en banda HBA (120-167 MHz) y muestra deriva en frecuencia + polarización Stokes V idénticas a las CMEs solares (la firma física de una onda de choque saliendo de la corona). El equipo descarta una explicación alternativa (loop magnético cerrado, modelo ECMI) ajustando con MCMC **6.356 muestras posteriores × 9 parámetros** y mostrando que recupera la deriva pero NO la sub-estructura del burst. La tasa derivada de eventos similares es **0,84 × 10⁻³ por día por estrella M** (rango asimétrico -0,69 / +1,94, basado en n=1 detección en ~10.500 h de monitoreo) — en promedio una vez cada ~3 años por estrella, con varianza enorme. ⚠️ El paper enmarca la implicación para erosión atmosférica de exoplanetas como hipótesis (*implies*), no demostración: una detección no establece estadística poblacional.

[Ver notebook](../papers/2026-01-17-primera-eyeccion-estelar-fuera-sol/notebook) · [Leer más](../papers/2026-01-17-primera-eyeccion-estelar-fuera-sol/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-primera-eyeccion-estelar-fuera-sol/notebook.ipynb)

---

## Un destello 40 veces más brillante de un agujero negro

*Nature Astronomy* · Hinkle et al. (2025) describen el destello más luminoso jamás registrado de un agujero negro supermasivo: el núcleo galáctico activo **J224554.84+374326.5** (z = 2,6) brilló más de **40×** sobre su nivel normal en 2018 y liberó ~**10⁵⁴ erg** en UV+óptico — equivalente a convertir una masa solar entera en radiación. En ZTF g (filtro más azul) la amplitud alcanza **151×** pico→mínimo; el eco infrarrojo de WISE es apenas **1,9×**. Seis años después, todavía se está apagando.

[Ver notebook](../papers/2026-01-17-destello-agujero-negro-extremo/notebook) · [Leer más](../papers/2026-01-17-destello-agujero-negro-extremo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-destello-agujero-negro-extremo/notebook.ipynb)

---

## Theia se formó en el Sistema Solar interior

*Science* · Hopp et al. (2025) midieron isótopos de hierro (μ⁵⁴Fe) en **41 muestras** — 15 terrestres, 6 lunares, 14 enstatitas, 4 condritas ordinarias y 2 Rumuruti — y los cruzaron con cinco sistemas isotópicos más (O, Ti, Cr, Zr, Mo). Tras filtrar la exposición a rayos cósmicos galácticos, **la Luna y la Tierra son indistinguibles isotópicamente** y caen juntas en el extremo no carbonáceo del mapa meteorítico. El equipo usó balance de masas para reconstruir Theia bajo **12 escenarios** (4 mantos pre-impacto × 3 tamaños de impactor): solo las recetas no carbonáceas dan una Theia que existe en la naturaleza — las recetas CI (μ⁵⁴Cr=−766) y CV (−409) caen a cientos de ppm fuera del rango observado. **El 15% del Cr terrestre y el 85% del Mo provienen de Theia** bajo el escenario canónico. ⚠️ La conclusión "Theia se formó más cerca del Sol que la Tierra" es una inferencia bajo el modelo (el paper la enmarca con *suggest...might*), no una medición directa.

[Ver notebook](../papers/2025-11-20-theia-sistema-solar-interior/notebook) · [Leer más](../papers/2025-11-20-theia-sistema-solar-interior/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-11-20-theia-sistema-solar-interior/notebook.ipynb)
