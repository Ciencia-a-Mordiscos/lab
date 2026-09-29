# Tecnología

## Un robot de cuatro patas corrió una maratón con una sola batería

*Nature* · RAIBO2, un cuadrúpedo de 43 a 45 kg, completó una maratón oficial en 4 h 19 min 52 s
con una sola carga: la telemetría muestra 1.241,6 Wh gastados de salida a meta
(el 86 % de la batería) y un voltaje que baja de 67,0 a 57,2 V sin saltos. El
coste de transporte recalculado, 0,251, coincide con el 0,248 del paper (+1,4 %).
⚠️ Es menor que el de un humano caminando (0,377), no el de uno corriendo (0,467);
la autonomía proyectada es 2,61 veces la del mejor cuadrúpedo de la tabla (B2),
no «más de tres veces» todos; una sola carrera, sin réplicas.

[Ver notebook](../papers/2026-09-23-robot-cuadrupedo-maraton-una-carga/notebook) · [Leer más](../papers/2026-09-23-robot-cuadrupedo-maraton-una-carga/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-09-23-robot-cuadrupedo-maraton-una-carga/notebook.ipynb)

---

## Una IA que nunca vio un hospital de Stanford lee sus tomografías mejor que la IA entrenada allí

*Science* · RADAR, un modelo visión-lenguaje entrenado con 424.911 TC abdominales y sus
informes, clasifica 21 hallazgos en las 5.125 TC del test set de Merlin
(Stanford) con AUC medio 0,883 sin haber visto ninguna; Merlin, entrenado
allí, da 0,812. Gana en 17 de 21 (d = 0,73, p = 0,006, n = 21). En casa:
0,913 en 146 hallazgos, mejor de cuatro modelos en 138. ⚠️ Los AUC en
Stanford son de la Tabla S8 (etiquetas bajo acuerdo de uso); el "+10 % de
sensibilidad" de los radiólogos y el nivel experto son solo del paper.

[Ver notebook](../papers/2026-09-18-radar-ia-generalista-tc-abdominal/notebook) · [Leer más](../papers/2026-09-18-radar-ia-generalista-tc-abdominal/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-09-18-radar-ia-generalista-tc-abdominal/notebook.ipynb)

---

## IA explicable en un coche autónomo: ayuda solo cuando el coche hace algo raro

*Nature* · Un coche autónomo hace algo inesperado y quien lo mira acierta el porqué el 16,7 % de las veces.
Con las explicaciones de CW-Net encima, 36,9 %: +20,3 puntos porcentuales, d = 1,00. Reproducimos
las 6 comparaciones del estudio aleatorizado (n = 99) y las réplicas coinciden con el paper a tres
decimales. ⚠️ El efecto vive entero en las situaciones sorprendentes: en las rutinarias no hay
ninguna mejora, y la comprensión llega a bajar 8,1 pp desde un techo del 94,1 %. ⚠️ Aun con
explicaciones, dos de cada tres respuestas siguen siendo incorrectas. ⚠️ Toda la estadística sale
de repeticiones en pantalla: el despliegue en el coche real fue 1 conductor y 3 situaciones.

[Ver notebook](../papers/2026-09-02-ia-explicable-coche-autonomo/notebook) · [Leer más](../papers/2026-09-02-ia-explicable-coche-autonomo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-09-02-ia-explicable-coche-autonomo/notebook.ipynb)

---

## Sol, agua de mar y una torre de seis pisos

*Nature Water* · El resumen anuncia 11,6 veces más uranio bajo un sol de laboratorio. Los datos
publicados dicen 11,5x — y que son dos efectos multiplicándose: ×3,27 por la luz
y ×3,51 por apilar seis cámaras. ⚠️ Todo medido en solución dopada con 2,5 mg/L,
unas 750 veces el uranio real del mar; sin dopar la mejora baja a 1,6x. ⚠️ Y en
la jornada exterior de Shenzhen ninguna de las 389 mediciones de sol llegó al
«1 sol» de referencia.

[Ver notebook](../papers/2026-09-01-separador-solar-litio-uranio/notebook) · [Leer más](../papers/2026-09-01-separador-solar-litio-uranio/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-09-01-separador-solar-litio-uranio/notebook.ipynb)

---

## Un robot con cilios que destapa arterias

*Nature Biomedical Engineering* · Cuando una arteria se tapa, detrás del tapón la sangre casi deja de moverse y el fármaco que disuelve coágulos llega solo por difusión. Fang et al. construyeron un robot blando de silicona con partículas magnéticas y un tapete de cilios que baten en ola coordinada: se navega con un imán desde fuera, se para junto al coágulo y empuja sangre. **El hallazgo:** en cerdos vivos el vaso se destapó en **45,0 min** frente a **163,3** sin robot (**−72,4%**), y en phantom en **40,4** frente a **95,0** (**−57,5%**), con separación total entre grupos. Por debajo hay dos sorpresas de diseño: cambiar el **sentido** en que viaja la ola de cilios triplica el flujo (**3,16x**, gana en las 10 frecuencias), y forrar el tubo **entero** de cilios da **4,34 veces menos** flujo que forrar la mitad — los de un lado empujan contra los del otro. ⚠️ Con **3 animales por grupo**, ningún test de permutación a dos colas puede bajar de **p = 0,10**: el efecto es enorme (d = 9,5), pero "significativo" no se puede escribir. ⚠️ Los Source Data publican **medias ± desviación**, no valores crudos, salvo en las dos figuras de recanalización. ⚠️ **Phantoms y cerdos: no hay datos en personas** ni es un tratamiento disponible.

[Ver notebook](../papers/2026-08-17-robot-endovascular-cilios-flujo/notebook) · [Leer más](../papers/2026-08-17-robot-endovascular-cilios-flujo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-08-17-robot-endovascular-cilios-flujo/notebook.ipynb)

---

## El pronóstico de huracanes ganó 23 horas en una década

*Nature* · Google DeepMind dice que su modelo de IA adelanta el aviso de un ciclón un día o más. Reconstruimos la vara: una década entera de progreso del centro de huracanes de EE. UU. compró 22,9 horas.

[Ver notebook](../papers/2026-08-06-ciclones-tropicales-ia/notebook) · [Leer más](../papers/2026-08-06-ciclones-tropicales-ia/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-08-06-ciclones-tropicales-ia/notebook.ipynb)

---

## Una memoria hecha de un solo electrón

*Science* · El sueño de la miniaturización es guardar un bit con **un solo electrón**. El problema: al encoger el dispositivo, la *capacitancia de borde* se dispara y ahoga la señal del electrón. Un equipo esquivó ese muro con una estructura 2D coplanar (drenaje-canal-fuente en el mismo plano). **El hallazgo:** cambiar **un electrón** desplaza el voltaje umbral **~0,5 V** de forma no volátil. Los datos lo confirman de tres formas: a 100 nm² el canal 2D conserva **91 %** de la señal frente al **13 %** de un canal grueso (~7×); el desplazamiento avanza en **escalones enteros** (un electrón por escalón); y los cuatro estados de carga se mantienen separados ~1 V\* con un ruido 16 veces menor, de 1 a 5.000 s. Frente a dispositivos bulk industriales, la señal por electrón es ~**14×** mayor (cálculo propio sobre el dataset). ⚠️ Es la caracterización de **un** dispositivo de laboratorio (retención medida hasta 5.000 s, no años). ⚠️ V\* es una unidad normalizada (1 V\* ≈ 1 electrón), no voltios físicos.

[Ver notebook](../papers/2026-07-18-memoria-un-electron-cuantica/notebook) · [Leer más](../papers/2026-07-18-memoria-un-electron-cuantica/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-18-memoria-un-electron-cuantica/notebook.ipynb)

---

## Un cable que mejora al encogerse: nanohilos de NbAs

*Science* · Los cables de cobre de un chip empeoran al adelgazarlos: los electrones rebotan contra las paredes y la resistencia sube. Un equipo probó lo contrario con nanohilos de arseniuro de niobio (**NbAs**), un semimetal de Weyl. **El hallazgo:** un nanohilo de **40 nm** baja su resistividad a **10,5 ± 1,9 µΩ·cm**, ~**70 % menos** que el material en bloque — encoger el cable lo mejoró. Y bota el calor como un metal: **109,68 W/m·K**, en la liga del rutenio (117) y el cobalto (100). Los cuatro nanohilos son NbAs estequiométrico (Nb:As ≈ **1,012** por EDX). ⚠️ La curva resistividad-vs-diámetro (el hallazgo central) se **cita del abstract**: su figura vive tras muro de pago. ⚠️ El mecanismo de "conducción por superficie" lo **atribuyen cálculos DFT**, no se midió. ⚠️ El cobre todavía gana en corriente de ruptura (100–145 vs mediana 42 MA/cm²) y en conductividad térmica absoluta.

[Ver notebook](../papers/2026-07-16-nbas-nanowires-interconnects/notebook) · [Leer más](../papers/2026-07-16-nbas-nanowires-interconnects/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-16-nbas-nanowires-interconnects/notebook.ipynb)

---

## Un ave que vuela y bucea con las mismas alas — pero cambia de marcha

*Science* · Hay aves —frailecillos, araos, pingüinos— que bucean con las alas (*wing-propelled*), no con las patas, y usan **las mismas alas** en dos fluidos que difieren ~800 veces en densidad. Abrimos los datos de campo de **13 especies** y los del **robot de alas batientes** que el equipo construyó para probar el principio. **El hallazgo:** todas frenan bajo el agua — el batido cae de **8,41 Hz** en aire a **2,84 Hz** en agua, una **mediana de 3 veces más lento** (Wilcoxon pareado P=0,0002, d de Cohen=3,2); ninguna de las 13 especies acelera. El robot reproduce el truco: alas más grandes suman sustentación en el aire (**1,48 → 2,49 N**) sin perder casi empuje al nadar. ⚠️ La comparación entre aves es **observacional**: el porqué del cambio de marcha se infiere, no se manipula. ⚠️ Los experimentos de envergadura vienen de **un robot**, no de aves. ⚠️ El robot gasta **~10x más energía** nadando que un ave real (costo de transporte 5,1 vs 0,46 J/Nm): demuestra el principio, no iguala la biología.

[Ver notebook](../papers/2026-07-09-leaping-out-water-flapping-wings/notebook) · [Leer más](../papers/2026-07-09-leaping-out-water-flapping-wings/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-09-leaping-out-water-flapping-wings/notebook.ipynb)

---

## ¿Puede una IA adivinar cómo reaccionará la gente antes de preguntarle?

*Nature* · Un equipo le pidió a GPT-4 que predijera el resultado de **70 experimentos sociales reales** —sin correr ninguno, solo leyendo el diseño— y comparó lo predicho con lo que de verdad pasó con **119.330 participantes** (**469 efectos**, 3.356 contrastes). **El hallazgo:** las predicciones se correlacionan fuerte con los efectos reales (**r = 0,80** en nuestro cálculo pooled; **0,85 crudo / 0,92 ajustado** a nivel de estudio en el paper), **a la altura de los pronósticos humanos** (r ajustado 0,89–0,93). Y algo revelador: los estudios que la IA **no pudo leer** —posteriores a su corte de entrenamiento— se predijeron incluso mejor (**r = 0,87**) que los ya publicados (**r = 0,69**), evidencia contra la mera memorización. Pero hay una trampa honesta: la IA **sobreestima** el tamaño de los efectos un **39%** en promedio (pendiente de regresión 0,55). ⚠️ En megastudios de campo el acierto baja a **r ≈ 0,34**, comparable al de expertos humanos (**0,26**). ⚠️ Solo experimentos de encuesta de EE. UU.; la correlación de rangos (Spearman 0,68) es más conservadora. ⚠️ Correlación ≠ exactitud: ordena bien pero no estima el tamaño exacto de un efecto.

[Ver notebook](../papers/2026-07-10-llm-predice-experimentos-sociales/notebook) · [Leer más](../papers/2026-07-10-llm-predice-experimentos-sociales/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-10-llm-predice-experimentos-sociales/notebook.ipynb)

---

## ¿Qué tan bien opera un robot humanoide? Lo midieron contra el da Vinci

*Nature* · Investigadores montaron un sistema de teleoperación sobre un humanoide comercial y le pusieron las mismas dos pruebas del examen de laparoscopia (FLS) que hace un cirujano para certificarse, midiéndolo contra el **da Vinci** (el robot quirúrgico dedicado) y la **laparoscopia manual**. **El hallazgo:** el humanoide es **~3,4× más lento que el da Vinci**, pero **~2× más rápido que la mano humana** con instrumentos (medianas de peg transfer: 102 s / 351 s / 696 s). Y la sorpresa está en la precisión: **empata con el dVRK** —la diferencia de error por intento no es estadísticamente distinguible (**p=0,72**)— y comete menos error que la técnica manual (**p=0,022**). La experiencia pesa: con el humanoide, los cirujanos tardan **menos de la mitad** que los novatos (mediana 41,9 s vs 108,7 s por intento). ⚠️ Son tareas de laboratorio (*dry-lab*), no cirugía en un paciente. ⚠️ El humanoide es **teleoperado** —una persona lo dirige, no opera solo—. ⚠️ Es un estudio de **viabilidad técnica, no de eficacia clínica**; los estudios in vivo en cerdos que menciona el abstract no están en el dataset público.

[Ver notebook](../papers/2026-07-08-humanoides-cirugia-laparoscopica/notebook) · [Leer más](../papers/2026-07-08-humanoides-cirugia-laparoscopica/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-08-humanoides-cirugia-laparoscopica/notebook.ipynb)

---

## ¿Puede una IA manejar un caso clínico mejor que un médico?

*Nature* · MIRA es un agente de IA que no solo conversa: opera dentro de una historia clínica electrónica simulada, pide análisis, lee imágenes y propone tratamientos. **El hallazgo:** en una simulación sobre casos reales pero retrospectivos de MIMIC-IV, acertó **el 87,8% de los diagnósticos frente al 78,1% de los médicos certificados** (+9,7 pp), igualando o superándolos en los 8 diagnósticos (la mayor brecha en neumonía, +19,2 pp). Y no solo diagnostica: 0 de 56 escenarios inseguros al recetar, y en decisiones de ingreso nunca omitió uno necesario (sensibilidad 100%, aunque ingresó de más 9 veces). Pero no es una goleada: en **radiología ganan los médicos** (61,5% vs 55,3%), y en sangre y microbiología ambos rinden bajo. ⚠️ La trampa está en la palabra *simulación*: casos ya cerrados, sin paciente enfrente, con los médicos bajo las mismas restricciones. ⚠️ La sensibilidad del 100% se midió sobre 80 casos y solo 2 diagnósticos. ⚠️ El propio paper pide estudios prospectivos del mundo real antes de hablar de generalización, seguridad y gobernanza.

[Ver notebook](../papers/2026-07-03-mira-ia-medica-autonoma/notebook) · [Leer más](../papers/2026-07-03-mira-ia-medica-autonoma/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-07-03-mira-ia-medica-autonoma/notebook.ipynb)

---

## ¿Una IA lee tu radiografía dental mejor que el dentista?

*Nature Biomedical Engineering* · Interpretar una radiografía panorámica dental toma tiempo y faltan especialistas, así que los reportes salen incompletos. Un equipo entrenó DentFound, un modelo de visión y lenguaje, sobre más de **101.000 pacientes** (98 enfermedades, 11 categorías post-tratamiento). **El hallazgo:** DentFound queda #1 en F1 en las 4 cohortes hospitalarias (84,78% a 94,20%) y escribe reportes **más completos** que un radiólogo humano — Recall **0,811 vs 0,518 (+56,6%)**, porque el humano se centra en la queja principal y omite hallazgos incidentales. La máscara *instance-guidance* que da nombre al método casi duplica el CIDEr (**+86%**). ⚠️ 'Más completo' no es 'mejor': en los ratings subjetivos de expertos el humano queda arriba en **10 de 12** pares. ⚠️ Es **apoyo diagnóstico**, no diagnóstico certificado — el título dice *towards clinical-level*. ⚠️ Las imágenes clínicas no son públicas; los datos vienen del Source Data de figuras.

[Ver notebook](../papers/2026-06-26-dentfound-panoramica-dental/notebook) · [Leer más](../papers/2026-06-26-dentfound-panoramica-dental/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-26-dentfound-panoramica-dental/notebook.ipynb)

---

## Cargar rápido una batería nueva la hace durar más

*Nature* · Toda la industria "forma" sus baterías cargándolas despacio la primera vez, para no maltratarlas. Este equipo probó lo contrario en cátodos ricos en litio (LLO): subir la corriente de esa primera carga de 0.2C a 2C. **El hallazgo:** la formación rápida da **+20% de capacidad** y retiene **98% tras 200 ciclos**, frente al **87%** de la lenta — y pierde menos de la mitad de litio irreversible (**34 vs 79 mAh/g**). La ventaja no está al inicio: **crece de +7% (ciclo 1) a +21%** con el uso. ⚠️ El **+36% de vida útil** del titular no es reproducible con este panel de 200 ciclos. ⚠️ El mecanismo (litio residual que ancla la red, *self-pinning*) lo muestra el paper por sincrotrón, no estas series. ⚠️ Datos de celdas tipo moneda de laboratorio.

[Ver notebook](../papers/2026-06-24-formacion-rapida-catodos-litio/notebook) · [Leer más](../papers/2026-06-24-formacion-rapida-catodos-litio/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-24-formacion-rapida-catodos-litio/notebook.ipynb)

---

## Un sticker en la piel que lee tu nutrición en el sudor

*Nature Biomedical Engineering* · Medir folato hoy pide un pinchazo en el brazo y un laboratorio. Un equipo construyó una microcápsula que se pega a la piel, recoge microlitros de sudor limpio y los pasa a un *lab-on-a-disc* portátil que corre el ensayo completo. La pregunta de fondo: ¿el folato del sudor refleja el de la sangre? **El hallazgo:** sí lo sigue — **Spearman ρ = 0,84** entre folato en sudor y en suero (33 pares de 7 personas), con pico a la **1–2 h** tras la ingesta en ambos fluidos, y el disco portátil concuerda con el ELISA de laboratorio (**r = 0,97**). ⚠️ Validado en **7 adultos sanos (3 hombres, 4 mujeres), ninguna embarazada**: lo "prenatal" es la meta a futuro, no algo probado aquí. ⚠️ El seguimiento diario es de **solo 2 personas** (descriptivo, no test poblacional). ⚠️ El disco lee algo más bajo en concentraciones altas: sigue la tendencia, requiere calibración.

[Ver notebook](../papers/2026-06-17-folato-sudor-prenatal/notebook) · [Leer más](../papers/2026-06-17-folato-sudor-prenatal/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-17-folato-sudor-prenatal/notebook.ipynb)

---

## Tu hígado es gelatina. Tu hueso es piedra.

*Nature Biomedical Engineering* · Tu **hígado es casi líquido** y tu **hueso casi piedra**: entre ambos hay **135.417 veces** de diferencia en rigidez, y un solo pegamento médico no sirve para los dos. Un equipo usó **machine learning** para diseñar un pegamento distinto a la medida de cada tejido —los **TuneGlues**—. **El hallazgo:** el modelo predice el módulo elástico del tejido con **R²=0,97** y cada pegamento cae en el **régimen mecánico de su tejido** (5 de 6 dentro de ~2x, a lo largo de 5 órdenes de magnitud); en un hígado lesionado, el TuneGlue bajó el sangrado de **363 a 30 s** (~12x). ⚠️ Todo lo *in vivo* es en **modelos animales**, no humanos ni clínica. ⚠️ La hemostasia es **n=3 por grupo** (p=0,10 es el mínimo posible con ese n, no es significancia). ⚠️ El match tejido-pegamento es de **régimen, no exacto** (la piel queda a 2,1x).

[Ver notebook](../papers/2026-06-11-bioglues-ml-multitejido-trauma/notebook) · [Leer más](../papers/2026-06-11-bioglues-ml-multitejido-trauma/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-11-bioglues-ml-multitejido-trauma/notebook.ipynb)

---

## Aprendizaje profundo de cuatro décadas de migración humana

*Nature* · Los datos de migración son escasos y cada país los define distinto. Un equipo entrenó un **conjunto de redes neuronales** para reconstruir, año por año, cuánta gente se movió entre **231 países** desde 1990 — con una **banda de incertidumbre** pegada a cada cifra. **El hallazgo:** el flujo migratorio global anual **pasó de 15,2 a 34,7 millones** de personas (1990→2023, **x2,28**), con un pico de **35,6 M en 2022**; la emigración de Ucrania se **multiplicó por 13,9** en 2022 con la invasión rusa. Y la incertidumbre, de apenas **2% global**, se **multiplica por 7 país por país** (mediana 15%): se cancela al sumar. ⚠️ Toda cifra es **estimación de un modelo**, no un conteo directo. ⚠️ El modelo supera estimaciones previas de 5 años en datos reservados, pero la **magnitud exacta no se extrajo**. ⚠️ Los flujos describen **cuánta gente se movió, no por qué** — sin causalidad.

[Ver notebook](../papers/2026-06-10-deep-learning-migracion-humana/notebook) · [Leer más](../papers/2026-06-10-deep-learning-migracion-humana/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-10-deep-learning-migracion-humana/notebook.ipynb)

---

## Agua del aire, con sol: 1,3 litros en un día

*Nature Water* · Un equipo armó una **maleta solar portátil** que saca agua potable **del aire** con telas-gel que atrapan vapor de noche y lo sueltan de día bajo sol concentrado. La probaron en dos climas opuestos. **El hallazgo:** cosechó **1,3 L en Austin** (dual módulo, ~62% humedad) y rindió en pleno **desierto de Chihuahua** (~26% humedad) — la humedad cae a **menos de la mitad** pero la tasa por área baja solo **~9%** (4,7→4,3 L/m²/día). Hasta nublado (~0,4 sol) saca **310 mL por módulo, el 54% de un día típico**. El motor: la capa exterior llega a **100 °C** mientras el condensador se mantiene frío. ⚠️ Son **dos jornadas de campo**, no un despliegue largo. ⚠️ La relación sol-rendimiento es **moderada** (Spearman r≈0,64, n=10). ⚠️ La 'palanca de equidad para el ODS 6' es **aspiración de los autores**; el geoespacial es asociación, no impacto medido.

[Ver notebook](../papers/2026-06-09-cosecha-agua-atmosferica-solar/notebook) · [Leer más](../papers/2026-06-09-cosecha-agua-atmosferica-solar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-09-cosecha-agua-atmosferica-solar/notebook.ipynb)

---

## Una cápsula que potabiliza agua solo agitándola

*Nature Water* · Una **cápsula flotante** del tamaño de un pulgar detecta y desinfecta agua **sin pilas ni químicos**: la energía sale de **agitarla a mano** (inducción electromagnética). Mide los sólidos disueltos (TDS) y, si pasa el filtro, mata microbios por **electroporación** —campos eléctricos que rompen su membrana—. **El hallazgo:** logra **desinfección completa (6 log = sin microbios vivos detectables)** en **20–25 min** —la espora *B. subtilis* es la más dura, necesita 25 min frente a 20 de *E. coli* y MS2— y la sostiene **120 ciclos sin degradarse**; su sensor casero acierta con **2,33 mg/L de error** frente a un medidor comercial. ⚠️ Todo es **laboratorio** con microbios de referencia y aguas recolectadas, no despliegue real en campo. ⚠️ Los '≥6 log' son **límites de detección** (sin microbios vivos detectables), no un conteo exacto. ⚠️ El TDS es un **sustituto** de contaminación química; no detecta todos los contaminantes específicos.

[Ver notebook](../papers/2026-06-08-capsula-flotante-agua/notebook) · [Leer más](../papers/2026-06-08-capsula-flotante-agua/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-08-capsula-flotante-agua/notebook.ipynb)

---

## Tu teléfono ya te toma el pulso

*Nature* · Liu et al. (2026) entrenaron PHRM, un modelo de deep learning que mide frecuencia cardíaca leyendo el rubor sutil que tu pulso le imprime a la piel desde la cámara frontal del celular — *remote photoplethysmography* (rPPG). El problema histórico de esta técnica: fallaba casi 4× más en piel oscura (MAE 3,4 → 13,6 bpm de Fitzpatrick I-V a VI según el meta-análisis Dasari 2021). Tomamos las cifras del Supplementary y las miramos una por una. **Acto 1:** PHRM-full logra **MAPE 3,8% / 4,4% / 8,9%** (piel clara / media / oscura, laboratorio) — los tres grupos cumplen el estándar industria <10% por primera vez en rPPG sobre smartphone. **Acto 2:** comparado con Savur (método previo), PHRM mide piel oscura **3,2× mejor en vida cotidiana** (24,8% → 7,8% MAPE). Y lo hace con **498K parámetros** — el modelo más pequeño del benchmark de 8 modelos rPPG (14,8× menos que PhysFormer). **Acto 3:** corre en Pixel 3 (2018) a **402 ms por ventana de 10 s** y en Pixel 7 a **133 ms** — 3× más rápido en 4 generaciones, sigue siendo portable a hardware viejo. ⚠️ El modelo **liberado** (PHRM-mini) no es el del abstract — cruza el 10% MAPE en 2 de 3 grupos en vida cotidiana (11,1% piel clara, 13,1% piel oscura). ⚠️ El 31,5% Fitzpatrick VI aplica a la cohorte de 340 personas con tono declarado, no al cohorte de 485 del abstract. ⚠️ El dataset crudo está restringido por el comité de ética (IRB) — no se reproduce desde cero. ⚠️ Validación observacional: PHRM se asocia con factores de riesgo cardiovascular pero NO los predice ni diagnostica.

[Ver notebook](../papers/2026-06-01-monitoreo-pasivo-fc-smartphone/notebook) · [Leer más](../papers/2026-06-01-monitoreo-pasivo-fc-smartphone/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-06-01-monitoreo-pasivo-fc-smartphone/notebook.ipynb)

---

## Litio para baterías sin tostar la roca

*Science* · Mowbray et al. (2026) plantean otra ruta para sacar litio del espodumeno — el mineral más abundante de Li para baterías. En vez de tostarlo a más de 1.000 °C y atacarlo con ácido sulfúrico, lo disuelven con fluoruro de amonio (NH₄F) en agua, a menos de 100 °C, en un circuito cerrado que regenera el reactivo. Bajamos las 7 tablas del Supplementary y desmenuzamos. **Acto 1:** el proceso opera a **<100 °C vs >1.000 °C** del incumbente — factor ~12× en temperatura operativa, diferencia categórica entre hidro y pirometalurgia. **Acto 2:** lo probaron en **17 muestras de 4 países** (Australia, USA, Brasil, Canadá) y **13 tipos de feedstock** — desde tailings con 0,8% Li₂O hasta concentrados premium con 7,2% — con **recuperación de litio mediana del 99%** (rango 95–103%, 17/17 ≥95%). **Acto 3:** el balance termodinámico de las 11 reacciones balanceadas es **−7.657 kJ/mol neto exotérmico** — el proceso libera más calor del que necesita, lo que explica fisicoquímicamente por qué funciona sin horno externo. La pureza del Li₂CO₃ resultante es **99 ± 0,6%**, equivalente al Alfa Aesar 99,999% que midieron en 98,9%. ⚠️ El TEA proyecta **>40% reducción de costo**, pero es proyección — *may reduce*, sin planta piloto que confirme. ⚠️ Los yields >100% en Al (hasta 132%) y Si (hasta 103%) son artefactos de inhomogeneidad del feedstock, no exceso real. ⚠️ La sensibilidad al precio del NH₄F es alta — si sube a 1.500 USD/t, los márgenes se comprimen.

[Ver notebook](../papers/2026-05-29-spodumene-litio-bajo-temperatura/notebook) · [Leer más](../papers/2026-05-29-spodumene-litio-bajo-temperatura/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-29-spodumene-litio-bajo-temperatura/notebook.ipynb)

---

## Diseñaron una proteína desde cero. Funcionó en un ratón vivo

*Nature* · Vázquez Torres et al. (2026) diseñaron *de novo* miniproteínas (~50-80 aminoácidos) que se pegan a 4 receptores GPCR distintos (MRGPRX1, CXCR4, GLP1R, GIPR) usando los modelos generativos RFdiffusion y ProteinMPNN. Bajamos las 5 tablas del Source Data MOESM3 (Figs. 2, 3, 4, 5) y las desmenuzamos. **Acto 1:** una de las miniproteínas, dCX1_001, bloquea el receptor CXCR4 *in vitro* prácticamente al 100% — la respuesta a 100 nM del ligando natural CXCL12 cae de **50,6% a -1,4%** con la miniproteína a 1 µM. **Acto 2:** en ratones vivos, dCX1_001 moviliza **células madre hematopoyéticas** a un nivel que el abstract describe como *comparable* al fármaco FDA AMD3100 (Mozobil): la mediana del fold-change a lo largo de 9 puntos temporales es **1,71×**, queda por encima del fármaco en **6 de 9** tiempos (pico **3,71× a la 1 h**, Cohen's d=1,09), por debajo en 3. **Acto 3:** la palabra "comparable" del paper aguanta — los datos la sostienen sin escalar. ⚠️ n=5 ratones por grupo por timepoint — IC al 95% amplios. ⚠️ Bloqueo *in vitro* no garantiza efecto *in vivo* (farmacocinética, vida media). ⚠️ Claim "fewer adverse effects" del abstract no verificable con Source Data MOESM3.

[Ver notebook](../papers/2026-05-28-miniproteinas-gpcr-diseno-de-novo/notebook) · [Leer más](../papers/2026-05-28-miniproteinas-gpcr-diseno-de-novo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-28-miniproteinas-gpcr-diseno-de-novo/notebook.ipynb)

---

## Algoritmos que distorsionan lo que crees que piensan los demás

*Nature* · Brady et al. (2026) construyeron dos feeds de redes sociales desde cero —uno ordenado por engagement como las plataformas reales, otro cronológico simple— y asignaron al azar a **1.818 personas** a usar uno u otro durante **8 semanas**, antes y después de las elecciones de Estados Unidos en 2024. **Acto 1:** la dieta cambia — el feed algorítmico casi **duplica** la exposición al contenido del propio bando alabándose (de **14% a 24,6%**) y reduce a un tercio la exposición al otro bando (de **28% a 9,9%**). **Acto 2:** cambia lo que la gente CREE — con un efecto medio (**Cohen's d = 0,346**, p = 1,1 × 10⁻¹³), los usuarios del feed algorítmico creen que más gente alaba públicamente al propio bando. **Acto 3:** dos sorpresas — el algoritmo **redujo** la percepción de extremismo del entorno (d = -0,19) y la polarización afectiva (d = -0,13). Direcciones inesperadas, pequeñas pero significativas. ⚠️ Solo Estados Unidos, una elección, 8 semanas. ⚠️ Los participantes sabían que estaban en un experimento. ⚠️ La tercera condición del paper (algoritmo "diversified extremity") no está en el CSV abierto.

[Ver notebook](../papers/2026-05-27-algoritmos-redes-percepcion-normas/notebook) · [Leer más](../papers/2026-05-27-algoritmos-redes-percepcion-normas/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-27-algoritmos-redes-percepcion-normas/notebook.ipynb)

---

## LiDAR de US$100 ve detrás de las paredes

*Nature* · Somasundaram et al. (2026) demuestran **NLOS imaging (imaging non-line-of-sight)** sobre un sensor de mercado — el ST VL53L8CX, un multizone time-of-flight de menos de US$100, no el LiDAR del iPhone — para localizar objetos ocultos detrás de una pared con un error promedio de **3,8 cm** (vs 6,4 cm de *backprojection* y 15,7 cm de *phasor field*, los dos baselines clásicos del campo). El truco: el modelo MAS (*motion-induced aperture sampling*) que combina muchos cuadros aprovechando que cámara y objeto se mueven. Abrimos las dos tablas del Supplementary (errores por método y por dimensión) más el histograma SPAD y la trayectoria del particle filter sobre 475 cuadros (95 s a 5 fps). El titular esconde un matiz importante: los 3,8 cm son el promedio sobre 25.000 ensayos — la incertidumbre en un cuadro individual ronda los **24 cm**. La diferencia es estadística pura (el error promedio escala con √N) y el notebook la separa explícitamente. ⚠️ Solo 2 baselines comparados. ⚠️ Objetos planos en escenas controladas. ⚠️ Conocer la forma del objeto reduce el error hasta 2,5× (efecto fuerte en objetos no convexos como la "U").

[Ver notebook](../papers/2026-05-21-lidar-objetos-ocultos-celular/notebook) · [Leer más](../papers/2026-05-21-lidar-objetos-ocultos-celular/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-21-lidar-objetos-ocultos-celular/notebook.ipynb)

---

## Co-Scientist: el AI que propone 78 hipótesis y los humanos eligen una

*Nature* · Gottweis et al. (2026) lanzan **Co-Scientist** — un sistema multi-agente AI sobre Gemini que genera, critica y refina hipótesis científicas en torneos internos. El paper lo valida en biomedicina, generando ideas para **reposicionar medicamentos (drug-repurposing)** contra **16 tipos de cáncer**. Abrimos las dos tablas cuantitativas del Supplementary (119 páginas) y la pregunta incómoda salta a la vista: de **78 propuestas totales**, **13 (17%)** fueron para leucemia mieloide aguda (LAML) — el único cáncer que el equipo llevó a validación in vitro (3 líneas celulares: MOLM-13, HL-60, NOMO-1). La distribución por cáncer no es neutral: mediana 3.5 propuestas/cáncer, LAML con 13 es outlier a **+2.67×** la media uniforme. En las ablations, **7/7 métricas mejoran** con los agentes activos, pero **2/7** lo hacen con deltas <2% (los AUCs sobre GPQA — benchmark externo). Las mejoras fuertes (Evolution calidad +19%, Reflection corrigiendo falso novelty +61%) aparecen en benchmarks construidos por el equipo. ⚠️ Validación solo in vitro, no clínica. ⚠️ Sistema sobre Gemini (de código cerrado), no reproducible de punta a punta. ⚠️ El paper usa *potential to accelerate* — el sistema propone, los humanos eligieron.

[Ver notebook](../papers/2026-05-19-co-scientist/notebook) · [Leer más](../papers/2026-05-19-co-scientist/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-19-co-scientist/notebook.ipynb)

---

## IA escribe software científico expert-level

*Nature* · Aygün et al. (2026) presentan **ERA** (*Empirical Research Assistance*) — un sistema que combina un modelo de lenguaje (LLM) con búsqueda en árbol (*Tree Search*) para escribir software científico que maximiza una métrica de calidad. Probaron ERA en **6 tareas** y abrimos las tablas del Supplementary para ponerle números a "expert-level". En **GIFT-Eval** (pronóstico de series temporales), **ERA Per-dataset queda #1 entre 32 modelos** con **MASE = 0.671**, por **1.19 % delante del segundo puesto humano** (TTM-R2-Finetuned, 0.679). ERA Unified ocupa el #6. Los 30 puestos restantes son sistemas diseñados por equipos humanos: foundation models, deep learning, modelos estadísticos clásicos. En **DLRSD** (segmentación de imágenes satelitales), **las 3 soluciones de ERA (mIoU 0.80–0.82)** superan al mejor paper previo (RE-Net 2021, **mIoU = 0.762**) por **5–7.6 % relativo**. ⚠️ El leaderboard GIFT-Eval es snapshot del 2025-05-18; otros releases pueden tener un nuevo #1. ⚠️ Dos claims del abstract (40 métodos single-cell, 14 modelos COVID que baten al ensemble CDC) no tienen tabla numérica completa reproducible en el Supplementary. ⚠️ "Expert-level" es la caracterización de los autores, no test ciego de comité independiente.

[Ver notebook](../papers/2026-05-19-ia-software-cientifico-experto/notebook) · [Leer más](../papers/2026-05-19-ia-software-cientifico-experto/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-19-ia-software-cientifico-experto/notebook.ipynb)

---

## Cómo una membrana flexible saca agua del aire 5 veces más rápido

*Nature Water* · Bai et al. (2026) imprimieron en 3D una membrana de nanoláminas de zeolita EMM-8 dentro de una matriz flexible de poliuretano (TPU). El cuello de botella histórico de la captura atmosférica de agua —la cinética se desploma cuando apilas el sorbente en un dispositivo real— se rompe: la membrana llega al **50% de su capacidad en 4.6 minutos**, entre **2.4× y 10.5× más rápido** que cualquier sorbente publicado (rango 11-48 min). Productividad máxima: **13.79 g de agua por g de sorbente y día** a 59.3% RH (vs 8.96 del mejor competidor previo, CAL, que necesita 72.5% RH). A humedades bajas (38.1% RH, condiciones casi desérticas) ya alcanza **11.81 g/g/d**. En 24 h corren **72 ciclos** estables (CV ≈ 3%) acumulando **11.78 veces el peso de la membrana en agua** (≈ 13.29 L/m²). Desorción a 80°C deja residual ≈ 0% en 20 min. ⚠️ La proyección de escalabilidad industrial ("*promising routes*") es proyección de los autores, no resultado validado a escala de planta. ⚠️ Ciclado medido solo 24 h continuas — degradación de la matriz TPU a meses/años requiere otro estudio. ⚠️ La comparación con sorbentes de literatura usa publicaciones independientes (no se remidieron en el mismo aparato).

[Ver notebook](../papers/2026-05-14-zeolitas-agua-aire/notebook) · [Leer más](../papers/2026-05-14-zeolitas-agua-aire/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-14-zeolitas-agua-aire/notebook.ipynb)

---

## Perovskita estable a 100°C: una IA de cuatro agentes encontró la receta

*Science* · Lin et al. (2026) entrenaron una IA colaborativa de **cuatro agentes** que diseñó, pieza por pieza, las tres capas críticas de una celda solar de perovskita: el absorbente (FA₀.₉₂Cs₀.₀₈PbI₃, con apenas **8% de cesio**), la capa que transporta huecos (una molécula sintetizada ad hoc, MeO-DPPACz) y la interfaz dual de óxidos metálicos. El resultado: la celda retiene **97% del rendimiento inicial tras 1000 horas a 100°C** — un régimen donde, de **51 estudios previos** (44 DOIs únicos) que revisamos, **solo 1 había llegado** y aguantó 60%. Diferencia: 37 puntos porcentuales. Los datos confirman el porqué a nivel atómico: Cs₈ tiene **~74% menos defectos** (trampas) que la composición sin cesio, con Cohen's d ≈ 12,8 entre n=3 réplicas. La predicción del agente AI sobre la composición óptima cayó dentro de su propia banda de confianza 80%. ⚠️ El test se cortó a 1000 h; comportamiento de largo plazo desconocido. ⚠️ La curva clave son trazas single-device por composición — sin error bars inter-dispositivo en esa figura. ⚠️ La molécula HTM custom fue sintetizada ad hoc; escalabilidad no reportada.

[Ver notebook](../papers/2026-05-14-perovskita-ia-multiagente-100c/notebook) · [Leer más](../papers/2026-05-14-perovskita-ia-multiagente-100c/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-14-perovskita-ia-multiagente-100c/notebook.ipynb)

---

## Imprimir circuitos de cobre a 150 °C

*Science* · Anonymous et al. (2026) presentan una tinta de cobre que se funde en conductor a **150 °C, al aire**, con resistividad de **12,8 µΩ·cm** — cuatro veces mejor que cualquiera de los 3 métodos previos que operan a esa temperatura (mediana 52 µΩ·cm en n=30 papers de literatura), y muy por debajo de los 250 °C que pide la mediana global. La clave: catecoles, la misma familia química de la dopamina. Las simulaciones DFT muestran que catecol/dopamina se une al Cu⁺ con **E_int = -0,757 eV**, 13,8× más fuerte que el ácido cítrico clásico (-0,055 eV). EXAFS confirma partículas Cu(0) cristalinas (bond length 2,537 Å, idéntico al cobre macizo) pero pequeñas (coordinación 5,4 vs 10,4 del foil). El paper reporta además estabilidad de **>1000 h en ácido, >200 h en sulfuro, >240 h a 140 °C**. ⚠️ Las cinéticas de corrosión y los datos de impresión sobre PET viven en las figuras del paper que no extrajimos. ⚠️ DFT con n=5 ligandos: orden cualitativo informativo, no ranking estadístico. ⚠️ La curva resistividad-temperatura tiene 4 puntos — suficiente para la tendencia, no para modelo físico detallado.

[Ver notebook](../papers/2026-05-14-cobre-corrosion-catecol/notebook) · [Leer más](../papers/2026-05-14-cobre-corrosion-catecol/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-14-cobre-corrosion-catecol/notebook.ipynb)

---

## LLMs y control estatal de medios

*Nature* · Bing et al. (2026) auditan **45 idiomas en 36 países** para mapear cómo el control estatal de medios se filtra en los modelos grandes de lenguaje. El dato que abre la historia: el **chino representa el 5,30%** de Common Crawl — la base de entrenamiento más usada por los LLMs comerciales — mientras el **noruego solo el 0,33%**. China tiene un puntaje RSF de libertad de prensa de **23/100** (categoría "muy grave"); Noruega, **92/100** (la mejor). Pero la correlación cruda entre los 45 idiomas (Spearman **ρ=0,215, p=0,156**) **no es estadísticamente significativa**. Y hay un giro incómodo: si excluyes el chino, la correlación **cambia de signo** (ρ=0,299, p=0,049) — más libertad de prensa se asocia con MÁS peso en Common Crawl, al revés de la hipótesis. ⚠️ El paper sostiene su tesis causal con un **experimento de fine-tuning aparte** (no replicado aquí), no con esta correlación observacional. ⚠️ Vietnam tiene **RSF=22,31**, peor que China — la pinza causal idioma↔régimen es más sucia que el titular. ⚠️ El RSF se asigna por país principal del idioma; un mismo idioma puede hablarse en países con regímenes opuestos.

[Ver notebook](../papers/2026-05-13-llm-control-estatal-medios/notebook) · [Leer más](../papers/2026-05-13-llm-control-estatal-medios/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-13-llm-control-estatal-medios/notebook.ipynb)

---

## Un drone vuelve a casa con una red de 3,4 kB

*Nature* · Ou et al. (2026) entrenaron un drone Crazyflie de **32 gramos** para regresar a casa después de vuelos de hasta **600 m** sin GPS, usando una red neuronal de **3,4 kB** (la `compact`) o **42,3 kB** (la `attention`, con mecanismo de atención visual). La inspiración: el *learning flight* de la abeja melífera. El drone solo necesita explorar el **3,84%** del área total — cerca del **3,4%** estimado para abejas y por debajo del **7,6%** de las hormigas del desierto. En vuelos cortos exteriores (30–110 m) aterriza a menos de medio metro de casa el **100%** de las veces; en vuelos largos (200–600 m con viento variable), el **70%**. El viento alto recorta la tasa **30 puntos porcentuales** (de 80% a 50%) en el mismo rango. ⚠️ El LHA% de abeja y hormiga son **estimaciones derivadas** de comportamiento natural, no medidas directas — el paper lo enmarca como *verificación preliminar* de la estrategia bio-inspirada, no como equivalencia funcional. ⚠️ Las 800 simulaciones se corrieron en bosques sintéticos uniformes (40 árboles en 50×50 m).

[Ver notebook](../papers/2026-05-13-bee-nav-navegacion-drones-abejas/notebook) · [Leer más](../papers/2026-05-13-bee-nav-navegacion-drones-abejas/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-13-bee-nav-navegacion-drones-abejas/notebook.ipynb)

---

## Un LLM pasó 5.390 de 5.400 preguntas trampa de encuestas online

*PNAS* · Kane (2025) levantó **300 personas sintéticas** con OpenAI o4-mini y las pasó por las tres defensas estándar de las encuestas online. Resultado: el bot acertó el **99,81% de attention checks** (5.390/5.400 trials), declinó el **97,67% de reverse shibboleth** (1.758/1.800 — citar la Constitución, traducir mandarín, FORTRAN) y rechazó el **100% de preguntas absurdas** (1.800/1.800 — ¿fue presidente?, ¿pasó dos semanas sin dormir?). De **21 tareas testeadas, una sola** queda por debajo del 95%: cálculo matemático (88,3% decline) — los LLMs no pueden evitar resolverlo cuando se les pide. La triple coherencia — acertar, declinar y rechazar como humano al mismo tiempo — vuelve obsoletos los métodos de detección actuales. ⚠️ Single-author paper sin réplica independiente todavía. ⚠️ Sin grupo control humano emparejado en las MISMAS 21 tareas — la "indistinguibilidad" se infiere por construcción, no se compara directamente. ⚠️ Un único modelo (o4-mini, junio 2025).

[Ver notebook](../papers/2026-05-08-llm-evade-anti-bots-encuestas/notebook) · [Leer más](../papers/2026-05-08-llm-evade-anti-bots-encuestas/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-08-llm-evade-anti-bots-encuestas/notebook.ipynb)

---

## Super-nano dominios en láminas de cobre — fuerza y conductividad sin sacrificar ninguna

*Science* · Tao et al. (2024) reportan láminas de cobre de **10 micras** que combinan **~900 MPa de resistencia** y **90% IACS de conductividad** — una pareja considerada incompatible — fabricadas por electrodeposición industrial. La clave: **dos escalas estructurales independientes** dentro del mismo material — granos cristalinos de **60-80 nm** con **dominios super-nano de ~3 nm** distribuidos periódicamente (ratio promedio **22×**). Verificamos los datos del Supplementary: el aditivo orgánico (gelatina + HEC + MBI con KCl) controla el grano (Spearman ρ = -1.0 con n=3) sin tocar el dominio. La estabilidad térmica es donde la diferencia se siente: **GSD-113 pierde 3,6% de dureza en 720 horas (un mes)**, mientras un cobre nanogranulado convencional pierde **43,6% en sólo 24 horas** — los dominios anclan los bordes de grano e impiden el engrosamiento. ⚠️ Los valores 900 MPa / 90% IACS provienen del abstract; el paper está paywalled y no pudimos cruzarlos contra datos crudos. La correlación aditivo→grano es estadísticamente marginal (n=3, p=0,037), aunque la dirección es inequívoca.

[Ver notebook](../papers/2026-04-16-super-nano-domains-copper-foils/notebook) · [Leer más](../papers/2026-04-16-super-nano-domains-copper-foils/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-16-super-nano-domains-copper-foils/notebook.ipynb)

---

## IA multiagente diseña catalizador que destruye PFOA en 5 minutos

*Nature Water* · Bao et al. (2026) presentan **ECOMATS**, un sistema multiagente con 7 LLMs fine-tuneados que diseñó autónomamente un catalizador para degradar **PFOA** — uno de los "químicos eternos". El catalizador focal `(FeTCPP)Co2(MeIm)2` degrada **90,5% del PFOA en 5 minutos** (verificado a 90,52% sobre 6 réplicas independientes, CV=8%). Su constante de velocidad **k=0,465 min⁻¹** es **45× la mediana** de 9 catalizadores reportados — pero solo **1,4× el mejor competidor previo** (P-Fe/Co/N@BC, k=0,330). En aguas residuales reales de **31 provincias de China**, mantiene remoción ≥85% en **28 de 31** (mediana 89,4%). El sistema multiagente separa con limpieza los buenos candidatos del ruido (Cohen's d = 2,60). En este Lab abrimos los CSVs del Source Data (MOESM4) y verificamos cada cifra. ⚠️ El paper dice "surpassing most reported analogues" — no "el más rápido del mundo". La revolución es el método (IA diseñando), no necesariamente el resultado bruto.

[Ver notebook](../papers/2026-05-02-ai-multiagente-catalizadores-agua/notebook) · [Leer más](../papers/2026-05-02-ai-multiagente-catalizadores-agua/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-05-02-ai-multiagente-catalizadores-agua/notebook.ipynb)

---

## ¿Está la IA superando a los médicos en razonamiento clínico?

*Science* · Brodeur et al. (2026) pusieron al modelo o1-preview de OpenAI a competir con cientos de médicos en **seis tareas de razonamiento clínico**, desde los casos clinico-patológicos del NEJM hasta diagnóstico en urgencias reales. El titular: la IA ganó casi todas. En CPCs del NEJM, **o1 alcanzó 66.3% top-1 vs 24.3% de los médicos en los 101 casos solapados** (gap 42 pp, ratio 2.73×). Pero el gap se cierra cuando los médicos tienen información completa: en urgencias reales con n=76 pacientes, la ventaja sobre el médico de planta cae de **+11.8 pp en triage a +2.7 pp en admisión** (no significativo). Y en el experimento *Landmark*, el equipo humano-IA (médicos+GPT-4 = 76%) no fue mejor que el médico solo (74%, p=0.055) — la dyad asistida no mejoró al clínico. ⚠️ Las rúbricas aditivas premian enumeración (Grey Matters: gap 55 pp, en parte artefacto de medición). ⚠️ El test de blinding es de 3 opciones (humano/IA/no puedo decir), no binario: los raters mayoritariamente se abstuvieron (83.6% y 94.4%); al menos uno discriminaba muy bien cuando se atrevía (92.6%). ⚠️ El propio paper pide *"urgent need for prospective trials"*.

[Ver notebook](../papers/2026-04-30-llm-razonamiento-medico/notebook) · [Leer más](../papers/2026-04-30-llm-razonamiento-medico/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-30-llm-razonamiento-medico/notebook.ipynb)

---

## Modelos cálidos: más errores cuando más importa

*Nature* · Ibrahim et al. (2026) entrenan **5 modelos de lenguaje** (Llama-3 70B/8B, Mistral Small, Qwen-32B, GPT-4o) para sonar cálidos y empáticos, y los evalúan en **4 datasets** (consejo médico, desinformación, trivia, afirmaciones engañosas) bajo **9 modificaciones interpersonales** del usuario. Los modelos cálidos cometen entre **+10 y +30 puntos porcentuales** más errores — el peor caso individual llega a **+34 pp**. Lo que hace al hallazgo creíble es el control: una versión **cold-FT** del mismo entrenamiento, sin el objetivo de calidez, no se mueve del cero (mediana −0,4 pp). El **Cohen's d entre warm-FT y cold-FT es 1,78** — un efecto enorme, casi el doble del umbral de 'efecto grande' en estudios psicológicos. Y los benchmarks estándar de la industria (MMLU, GSM8K, AdvBench) **no detectan el problema** (Wilcoxon p = 0,18). En este Lab descargamos los CSVs públicos del paper, reproducimos las medianas por dataset/modelo/modificación, calculamos el d efecto a partir de los datos, y mostramos en un histograma cómo la misma intervención produce dos respuestas opuestas según qué se mida.

[Ver notebook](../papers/2026-04-29-warm-models-sycophancy/notebook) · [Leer más](../papers/2026-04-29-warm-models-sycophancy/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-29-warm-models-sycophancy/notebook.ipynb)

---

## 25 imágenes por segundo revelan el metabolismo de un cuerpo completo

*Nature Communications* · Wang et al. (2025) presentan **3D-PanoPACT**, un sistema de imagen fotoacústica panorámica con **1024 transductores** en anillo hemiesférico que reconstruye un volumen 3D del cuerpo de un ratón en cada pulso láser, sin escanear ni rotar. Eso desbloquea **25 cuadros por segundo** sobre el hígado completo (FOV 60 mm) y **5 modos** distintos con un rango de **125x en velocidad** (de 25 Hz a 0,2 Hz para cuerpo completo, 120 mm). La demostración funcional: una sonda fluorescente NIR-II (A1094) recorre 6 órganos del ratón vivo en menos de **10 minutos**, con picos temporales bien separados — corazón a **120 s** (C_max 14%) e hígado a **505 s** (C_max **75%**, casi el doble del promedio del resto: 38,6%). El compromiso ingenieril clave: el radio del transductor de 2,5 mm es **2,78x más sensible** que r=1,5 mm y **25x** más que r=0,5 mm, según simulaciones k-Wave + Field II. ⚠️ La sección farmacocinética es n=1 ratón, ventana 10 min: prueba de concepto técnica, no estudio poblacional ni clínico.

[Ver notebook](../papers/2026-04-29-panopact-metabolismo-cuerpo-completo/notebook) · [Leer más](../papers/2026-04-29-panopact-metabolismo-cuerpo-completo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-29-panopact-metabolismo-cuerpo-completo/notebook.ipynb)

---

## 1,65 MJ/kg en una pirimidona: cinco veces más densidad que el azobenceno

*Science* · Nguyen et al. (2026) sintetizan **4 pirimidonas** (P-1 a P-4, bases del ADN modificadas) y las irradian con UV a **310 nm** para forzarlas al isómero Dewar — un anillo tensionado, como un resorte molecular. Los datos de las Tablas S1-S7 del Supporting muestran que **D-3 almacena 1,65 MJ/kg** medido por DSC, **5,2×** la densidad energética del cis-azobenceno (0,318 MJ/kg) que llevaba 40 años siendo el referente MOST. Una gota de HCl en 1 mL de agua sobre 106 mg de D-3 sube la temperatura **75,76 K** por cámara IR — alcanza ~100°C desde temperatura ambiente. La eficiencia de transferencia es **87% (vs 42% en azobenceno)**, y el control sin Dewar (P-3 directo) apenas calienta 7 K — el calor viene de la reversión, no del ácido. P-3 ganó la carrera entre las 4 candidatas a pesar de no tener el Φ más alto (5,4% vs 7,8% de P-4) porque P-4 es líquido inmiscible. ⚠️ ΔG‡ = 117 kJ/mol extrapolado por Eyring desde mediciones a 85-95°C; la estabilidad real a temperatura ambiente no se midió directamente. El paper cierra con hedge T2 explícito ("apuntan el camino" hacia almacenamiento solar descentralizado).

[Ver notebook](../papers/2026-04-27-pirimidona-dewar-energia-solar/notebook) · [Leer más](../papers/2026-04-27-pirimidona-dewar-energia-solar/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-27-pirimidona-dewar-energia-solar/notebook.ipynb)

---

## Un robot le ganó 3 de 5 partidos a jugadores de élite en tenis de mesa

*Nature* · D'Ambrosio et al. (2026) construyeron **Ace**, un robot autónomo de Sony con dos brazos KUKA y un controlador entrenado con aprendizaje por refuerzo. En abril de 2025 lo enfrentaron bajo reglas oficiales ITTF a siete humanos — **cinco élite de club amateur y dos profesionales japoneses**. Contra los élite **ganó 3 de 5 partidos (7/13 sets)**. Contra los profesionales **perdió ambos (1/7 sets)**. Abrimos los **4.024 eventos** grabados (99 rallies, 1.953 golpes) y vemos la brecha: el techo operativo de Ace vive en **13,3 m/s** (su percentil 95); el **26% de los golpes humanos viven por encima** de ese umbral. Entre élite y pro hay un salto que los datos no esconden.

[Ver notebook](../papers/2026-04-24-robot-tenis-mesa-elite/notebook) · [Leer más](../papers/2026-04-24-robot-tenis-mesa-elite/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-24-robot-tenis-mesa-elite/notebook.ipynb)

---

## Nanotubos al 41% del cobre con la mitad del peso

*Science* · de Isidro-Gómez et al. (2026) reportan fibras de nanotubos de carbono dobles intercaladas con aniones de tetracloroaluminato (AlCl₄⁻) en los huecos entre tubos. Los aniones aceptan **0,65 electrones por unidad** (DFT del paper, n=4 unidades en el unit cell — coincidencia exacta con el abstract), dejando huecos en el nanotubo exterior que aumentan los portadores de carga. Resultado: la conductividad pasa de **1,4 a 24,4 MS/m** en la mejor muestra individual — un factor 17,5× sobre la fibra pristine, y **41,6% del cobre puro**. La media del proceso ronda los 16 MS/m. Lo más relevante para aplicaciones: la conductividad específica (17.350 S·m²/kg) **supera a la del aluminio comercial (13.130) por factor 1,32**. Trabajamos con las 6 tablas del Supplementary del paper. ⚠️ El cable de 18 mm propuesto es proyección, no construido.

[Ver notebook](../papers/2026-04-23-nanotubos-carbono-conductividad/notebook) · [Leer más](../papers/2026-04-23-nanotubos-carbono-conductividad/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-23-nanotubos-carbono-conductividad/notebook.ipynb)

---

## Una red biohíbrida que se mueve y captura nanoplásticos

*Nature Water* · Fan et al. (2026) construyen una red diminuta — fibrillas amiloides de **lisozima** (la proteína de la clara del huevo) decoradas con nanopartículas de óxido de hierro: las **LAF-IONPs**. Bajo un campo magnético alterno, la red se sacude y caza nanoplásticos. Los datos de los Source Data MOESM8/10/11 muestran que el truco está en el movimiento: estática captura solo **40,1%**, dinámica **99,3%** (×2,47, Cohen d ≈ 71). La eficiencia se mantiene entre **94,6%** (10 mg/L) y **99,6%** (500 mg/L), aguanta **100 ciclos** de reuso cayendo apenas **4,3 puntos porcentuales** (de 100,1% a 95,8%), y reduce un **91,5%** del plástico bioacumulado en ratones C57BL/6. ⚠️ Solo ratones — no hay datos clínicos humanos; las eficiencias del 99% son sobre agua sintética con poliestireno puro.

[Ver notebook](../papers/2026-04-23-nanonets-amiloide-nanoplasticos/notebook) · [Leer más](../papers/2026-04-23-nanonets-amiloide-nanoplasticos/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-23-nanonets-amiloide-nanoplasticos/notebook.ipynb)

---

## Un vidrio con la fuerza del diamante y la tenacidad de un metal

*Nature* · Cai et al. (2026) sintetizan **5 vidrios metálicos masivos** Re-Co-Ta-B y miden una combinación que llevaba décadas vacía en el plano resistencia-tenacidad: **6,43 GPa de fuerza** (cerca del diamante policristalino, 6,9-7,0 GPa) con **30 MPa·m^1/2 de tenacidad** — **3,4×** la mejor cerámica de su nivel de resistencia (PCD K1C=8,8). A **900 K** mantiene **4,4 GPa** (caída del **31,6%**, mejor que la mayoría de BMGs comparables). En los 8 materiales del dataset con σy ≥ 5 GPa, la mediana de tenacidad es 5,97 — el Re-Co-Ta-B la quintuplica. Más renio sube la temperatura de transición vítrea (Tg, 1001-1113 K) pero baja el espesor crítico de colada (3-4 mm). ⚠️ El mecanismo atómico (orden de corto rango heredado del Re7B3 + enlaces Re-B direccionales) viene de DFT computacional — el paper lo presenta como hipótesis (*suggests*), no como observación directa. Renio ~1500 USD/kg: investigación, no producción a escala.

[Ver notebook](../papers/2026-04-22-vidrio-metalico-resistencia-ceramica/notebook) · [Leer más](../papers/2026-04-22-vidrio-metalico-resistencia-ceramica/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-22-vidrio-metalico-resistencia-ceramica/notebook.ipynb)

---

## Un termitero inspira cómo recuperar 83% del vapor industrial

*Nature Water* · Zhang et al. (2026) copiaron la arquitectura pasiva de los termiteros africanos —cámaras, chimeneas y canales que enfrían sin perder humedad— para recuperar el vapor que las torres de enfriamiento industriales tiran al aire. El sistema de **cuatro capas apiladas** retiene **83,5%** del vapor a los 24 minutos, contra 27,2% sin tratamiento. **Una sola capa** (el recubrimiento de microesferas FAUTO) carga con +43,7 puntos porcentuales de la mejora; las otras tres capas juntas apenas suman +12,6 pp. Proyectado a una planta de 300 MW en China: **2,7×10⁸ toneladas de agua recuperadas al año** — equivalente al consumo doméstico de 2,2 millones de hogares.

[Ver notebook](../papers/2026-04-21-vapor-agua-termitero-industrial/notebook) · [Leer más](../papers/2026-04-21-vapor-agua-termitero-industrial/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-21-vapor-agua-termitero-industrial/notebook.ipynb)

---

## LEDs de superretículas de quantum dots pixeladas

*Nature* · Quantum dots de perovskita (CsPbBr₃) organizados en superretículas hexagonales: 30,9% EQE, 117.144 cd/m², 5.080 PPI. Vida media extrapolada de 12.411 horas (~1,4 años), 1.460× más que el mejor LED pixelado de perovskita anterior. La clave: un ligando (BHOA+F) que permite transporte de banda con movilidad 17× mayor a temperatura ambiente.

[Ver notebook](../papers/2026-04-17-pixelated-quantum-dot-superlattice-leds/notebook) · [Leer más](../papers/2026-04-17-pixelated-quantum-dot-superlattice-leds/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-17-pixelated-quantum-dot-superlattice-leds/notebook.ipynb)

---

## Músculos artificiales con ultrasonido: 714× de salto en escala

*Nature* · Shi et al. (2025), más de 10.000 microburbujas programables forman músculos artificiales controlados por ultrasonido. Benchmark de 74 actuadores en 3 dimensiones (agarre, fuerza, natación). El stingraybot acústico de 50 mm es 714 veces más grande que la mediana de nadadores acústicos previos.

[Ver notebook](../papers/2025-10-30-musculos-artificiales-ultrasonido-microburbujas/notebook) · [Leer más](../papers/2025-10-30-musculos-artificiales-ultrasonido-microburbujas/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-10-30-musculos-artificiales-ultrasonido-microburbujas/notebook.ipynb)

---

## ☀️ Celdas solares de perovskita: cuando la IA fabrica mejor que el humano

*Nature* · 756 celdas solares fabricadas por una plataforma autónoma de IA (optimización bayesiana + ML) vs. 36 controles manuales. Las 20 condiciones automatizadas superan al control: +2,9 pp de eficiencia (22,4% → 25,3%), Cohen's d = 6,54. La ganancia viene del voltaje (VOC) y el factor de llenado (FF), no de la corriente.

[Ver notebook](../papers/2026-04-14-celulas-solares-perovskita-ia-autonoma/notebook) · [Leer más](../papers/2026-04-14-celulas-solares-perovskita-ia-autonoma/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-14-celulas-solares-perovskita-ia-autonoma/notebook.ipynb)

---

## 🤖 ¿Puede una IA Entrenada con Imágenes Inventadas Superar a 9 Radiólogos?

*Nature Biomedical Engineering* · Chen et al. (2026), BUSGen — primer modelo generativo fundacional para ecografía mamaria, pre-entrenado con 3,5 millones de imágenes. A partir de 25K imágenes sintéticas, el modelo supera a los entrenados con datos reales (AUC 0,932 vs 0,925). Evaluado contra 9 radiólogos certificados: +15,9 pp de sensibilidad

[Ver notebook](../papers/2026-04-08-busgen-ecografia-mama-ia/notebook) · [Leer más](../papers/2026-04-08-busgen-ecografia-mama-ia/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-08-busgen-ecografia-mama-ia/notebook.ipynb)

---

## 📊 ¿Se puede confiar en un solo análisis?

*Nature* · Kovács et al. (2025), 504 reanálisis de 100 estudios sociales, solo 34% coinciden en tamaño del efecto (±0,05 d), 74% llegan a la misma conclusión

[Ver notebook](../papers/2026-04-05-robustez-analitica-ciencias-sociales/notebook) · [Leer más](../papers/2026-04-05-robustez-analitica-ciencias-sociales/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-05-robustez-analitica-ciencias-sociales/notebook.ipynb)

---

## 🔬 ¿Se puede replicar la ciencia social?

*Nature* · Protzko et al. (2025), 274 claims de 164 papers replicados, 55,1% se replica, efecto mediano se reduce a la mitad

[Ver notebook](../papers/2026-04-05-replicabilidad-ciencias-sociales/notebook) · [Leer más](../papers/2026-04-05-replicabilidad-ciencias-sociales/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-05-replicabilidad-ciencias-sociales/notebook.ipynb)

---

## 🔬 ¿Se puede confiar en la ciencia social?

*Nature* · 600 papers de 62 revistas (2009–2018), 573 claims evaluados, 55,5% precisamente reproducible, solo 19,6% comparte datos

[Ver notebook](../papers/2026-04-04-reproducibilidad-ciencias-sociales/notebook) · [Leer más](../papers/2026-04-04-reproducibilidad-ciencias-sociales/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-04-reproducibilidad-ciencias-sociales/notebook.ipynb)

---

## 🤖 La IA aduladora reduce la intención prosocial

*Science* · 1.604 participantes, diseño experimental, IA aduladora vs directa, repair d = 0,92, convicción d = 1,26

[Ver notebook](../papers/2026-04-04-ia-aduladora-reduce-intencion-prosocial/notebook) · [Leer más](../papers/2026-04-04-ia-aduladora-reduce-intencion-prosocial/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-04-ia-aduladora-reduce-intencion-prosocial/notebook.ipynb)

---

## 🤖 ¿Puede una IA revisar papers como un humano?

*Nature* · 500 papers ICLR 2024, Claude-3.5-Sonnet vs GPT-4o vs revisores humanos, confusion matrix, Spearman ρ = 0,323

[Ver notebook](../papers/2026-04-02-ia-scientist-paper-autonomo/notebook) · [Leer más](../papers/2026-04-02-ia-scientist-paper-autonomo/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-04-02-ia-scientist-paper-autonomo/notebook.ipynb)

---

## 🧬 Descubrieron 74 Antibióticos Imposibles de Encontrar

*Nature Biomedical Engineering* · HMD-AMP detecta 100% de AMPs remotos (vs 0% otros métodos), 91 validados experimentalmente, 74 activos, 4 de amplio espectro, MIC 1-4 µg/mL

[Ver notebook](../papers/2026-03-31-antibioticos-imposibles-ia-proteinas/notebook) · [Leer más](../papers/2026-03-31-antibioticos-imposibles-ia-proteinas/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-31-antibioticos-imposibles-ia-proteinas/notebook.ipynb)

---

## ⌚ Tu reloj ya predice diabetes tipo 2

*Nature* · 1.165 participantes WEAR-ME, wearables + biomarcadores sanguíneos, HOMA-IR, redes neuronales profundas, AUROC 0,80

[Ver notebook](../papers/2026-03-20-reloj-predice-diabetes/notebook) · [Leer más](../papers/2026-03-20-reloj-predice-diabetes/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-20-reloj-predice-diabetes/notebook.ipynb)

---

## 🌫️ En 1 minuto esta IA destruye décadas de pronósticos del aire

*Nature* · AI-GAMFS vs CAMS y GEOS-FP, 289 estaciones AERONET, 42 años MERRA-2, Vision Transformer + U-Net, AOD r = 0,978

[Ver notebook](../papers/2026-03-12-ia-pronostico-aerosoles/notebook) · [Leer más](../papers/2026-03-12-ia-pronostico-aerosoles/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-12-ia-pronostico-aerosoles/notebook.ipynb)

---

## 🧬 9 Billones de Bases de ADN Enseñaron a una IA a Escribir Vida

*Nature* · Nguyen et al. (2026), 705 benchmarks de predicción de variantes genéticas — Evo 2 (40B parámetros) compite con modelos especializados sin entrenamiento específico y lidera en BRCA1 (AUROC 0,901)

[Ver notebook](../papers/2026-03-09-evo2-ia-adn-escribir-vida/notebook) · [Leer más](../papers/2026-03-09-evo2-ia-adn-escribir-vida/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-03-09-evo2-ia-adn-escribir-vida/notebook.ipynb)

---

## El gen anti-CRISPR diseñado por una IA que supera al control humano

*Nature* · Hayes et al. (2025) entrenan **Evo 1.5**, un modelo de lenguaje genómico, sobre 2,7 millones de genomas procariotas, y le piden generar **anti-CRISPR** y **antitoxinas** condicionadas por contexto genómico. Sintetizan físicamente **86 anti-CRISPR** y **8 antitoxinas T2** y las prueban en *E. coli*: **17%** de las anti-CRISPR muestran actividad medible y **50%** de las antitoxinas rescatan crecimiento. El golpe: **EvoAcr2** —con **0 hits** en BLAST de secuencia y **0 hits** en Foldseek estructural— alcanza una supervivencia relativa de **1,01**, **0,14 puntos por encima** del control natural AcrIIA2 (0,87). En este Lab abrimos los CSVs de Supplementary, distinguimos los **verdaderamente de novo** (EvoAcr1, EvoAcr2) de los **redescubrimientos** (EvoAcr4, EvoAcr5, con 100% y 96% de identidad BLAST a Acrs naturales de *Listeria*) y verificamos la correlación: Spearman **ρ = −0,727** entre identidad estructural y actividad (n=7, p=0,064) — la novedad no penaliza la función. ⚠️ También publican **SynGenome** con **120 mil millones de pares de bases** sintéticas (≈120 millones de genes potenciales — el short del canal usa la cifra de pb sin la unidad explícita; aquí la dejamos clara).

[Ver notebook](../papers/2026-01-17-evo-syngenome-120mil-genes-ia/notebook) · [Leer más](../papers/2026-01-17-evo-syngenome-120mil-genes-ia/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2026-01-17-evo-syngenome-120mil-genes-ia/notebook.ipynb)

---

## ¿Puede una IA entender el mundo sin haberlo vivido?

*Proceedings of the National Academy of Sciences* · Xu et al. (2025) tomaron **66 modelos de lenguaje** — de 70 millones a 47 mil millones de parámetros — y midieron qué tan parecida era su representación interna de conceptos a la humana. Con datos abiertos de Zenodo, reproducimos dos de los tres claims: (1) cuanto más alineado con humanos es un modelo, mejor razona en 8 benchmarks (**Spearman ρ = 0,83, n = 66**), y (2) dentro de Llama-3-70B, la representación converge con más ejemplos *in-context* y la precisión sube en paralelo (**ρ = 0,98, n = 8 demos**). El giro incómodo: el modelo más alineado no es el más grande. **Llama-3 8B (0,74) gana a Mistral 8x7B de 47 mil millones de parámetros (0,72)**. El tercer claim del paper — similitud con actividad cerebral fMRI — no se reproduce aquí (requiere datos adicionales).

[Ver notebook](../papers/2025-10-31-ia-conceptos-humanos-sin-vivir/notebook) · [Leer más](../papers/2025-10-31-ia-conceptos-humanos-sin-vivir/README) · [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ciencia-a-Mordiscos/lab/blob/main/papers/2025-10-31-ia-conceptos-humanos-sin-vivir/notebook.ipynb)
