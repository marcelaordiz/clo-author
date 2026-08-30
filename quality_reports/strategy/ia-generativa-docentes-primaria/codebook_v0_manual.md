# Codebook v0 — para codificación manual

**Proyecto:** Representaciones de docentes de nivel primario sobre IA generativa (UNSAM)
**Versión:** v0 (deductiva, semilla) — fecha de inicio: completar al empezar a usar
**Basado en:** `quality_reports/strategy/ia-generativa-docentes-primaria/pseudo_code.md`, Fase 2

**Changelog:**
- **2026-08-08 — reorganización terminológica (decisión de la directora de tesis):** los códigos deductivos dejan de organizarse en 5 "núcleos" agrupados por autor/teoría y pasan a organizarse en **5 dimensiones**, derivadas directamente del objetivo general y los 5 objetivos específicos del plan de tesis — no del marco teórico en primer lugar. La teoría se conserva como **fundamento teórico secundario** dentro de cada dimensión (no desaparece, deja de ser el criterio organizador principal). Los imaginarios sociotécnicos **quedan como dimensión transversal**, tal como ya estaban descriptos en el Cap. 3 §3.5 — no se convierten en una sexta dimensión paralela. Mapeo completo: antiguo Núcleo 3 (alfabetización digital) → Dimensión 1 (OE1); antiguo Núcleo 1 (representaciones sociales clásicas) → Dimensión 2 (OE2); Dimensión 3 (OE3, preocupaciones/expectativas) es nueva como categoría explícita, pero **no tiene familia deductiva propia** — situación que ya existía antes del cambio (ningún núcleo la cubría) y se mantiene honesta, no se fuerza; antiguo Núcleo 2 (Ausubel) → Dimensión 4 (OE4); antiguo Núcleo 5 (diseño didáctico) → Dimensión 5 (OE5); antiguo Núcleo 4 (imaginarios) → dimensión transversal, sin numeración paralela a las 5. **Este cambio es solo de organización/etiqueta — ningún código, definición, criterio de inclusión ni cita de ejemplo se modificó.** Los documentos históricos de codificación (`codificacion_P*.md`) usan la terminología "núcleo" vigente al momento de su redacción y **no se reescriben** — esta tabla es la referencia de equivalencia:

  | Terminología histórica (`codificacion_P*.md`, hasta 2026-08-07) | Terminología vigente (desde 2026-08-08) |
  |---|---|
  | Núcleo 1 — Representaciones sociales clásicas | Dimensión 2 (OE2 — conocimientos previos) |
  | Núcleo 2 — Aprendizaje significativo | Dimensión 4 (OE4 — concepción del potencial pedagógico) |
  | Núcleo 3 — Alfabetización digital docente | Dimensión 1 (OE1 — competencias digitales) |
  | Núcleo 4 — Imaginarios sociotécnicos | Dimensión transversal (sin número) |
  | Núcleo 5 — Diseño didáctico | Dimensión 5 (OE5 — usos proyectados) |
  | (sin núcleo propio) | Dimensión 3 (OE3 — preocupaciones/expectativas) |

- 2026-08-07: agregados 2 códigos inductivos a la dimensión de diseño didáctico (hoy Dimensión 5) — `criterio_etario_ciclo` y `criterio_heterogeneidad_competencias_grupo` — a partir de una observación de la investigadora sobre el criterio de ciclo/edad dentro de `criterio_contextual_grupo`. Relectura formal del corpus completo aplicada, con corrección explícita de una lectura previa apresurada (ver nota abajo y `relectura_ciclo_heterogeneidad.md`).
- 2026-08-07: agregados 2 códigos inductivos a la dimensión de aprendizaje significativo (hoy Dimensión 4) — `ejemplo_centrado_producto_proceso` y su contraparte `aprendizaje_explicitado_en_ejemplo` — a partir de una observación de la investigadora sobre los ejemplos de uso ya codificados. Relectura formal del corpus completo (15/15) aplicada. Ver detalle en `relectura_producto_proceso_aprendizaje.md`.
- 2026-08-05: candidato inductivo `etica_regulacion_autonomia_infantil` (propuesto tras P15, n=1) **no promovido** — la investigadora decidió absorberlo en `eco_discurso_institucional` (dimensión transversal de imaginarios), con nota explícita conservada en la definición del código. Ver `codificacion_P15.md` §4/§6 para el detalle.
- 2026-07-31: reemplazada la lista de marcadores del imaginario oficial (v0 → v1, fuentes primarias). Agregados 3 códigos deductivos a la dimensión de imaginarios (`imaginario_inevitabilidad_tecnologica`, `imaginario_desigualdad_estructural`, `imaginario_rol_docente_futuro`) y creada la familia de códigos de **diseño didáctico y uso pedagógico de la IAG** (hoy Dimensión 5, 4 códigos), propuestos por la investigadora a partir del procesamiento exploratorio de las primeras entrevistas.
- 2026-08-01: **verificada** la cita de Castañeda et al. (2025) — Castañeda, L., Postigo-Fuentes, A. Y. & Arroyo-Sagasta, A. (2025). "Beyond Tools, Toward Power Structures: A Critical Review of AI in Primary Education." *Revista Española de Educación Comparada*, 48 (extra), 73-95. DOI: 10.5944/reec.48.2025.45126. PDF en `master_supporting_docs/supporting_papers/Castaneda_et_al_2025_beyond_tools_power_structures.pdf`. Ya agregada a `Bibliography_base.bib`. Todas las marcas `% UNVERIFIED` de este documento quedan resueltas.

**Cómo usar este documento:** por cada entrevista, leé completa primero (familiarización + memo reflexivo), después codificá segmento por segmento. Cada segmento puede llevar más de un código. Anotá siempre: (a) de qué bloque del protocolo viene, (b) si el código es deductivo (de esta lista) o inductivo (nuevo, que vos agregás), con fecha.

---

## Dimensión 1 — Competencias digitales (Objetivo específico 1)

**Objetivo específico que la origina:** *"Identificar las competencias digitales de los docentes de escuelas primarias de CABA en relación con el uso de herramientas tecnológicas para el diseño de propuestas didácticas orientadas al aprendizaje significativo."*
**Fundamento teórico secundario:** alfabetización digital docente — Lankshear & Knobel (2008); Dussel (2012). Complementado con marcos específicos de competencia digital docente (más operacionalizables que Lankshear & Knobel, que es un marco general): DigCompEdu (Redecker, 2017, 6 áreas) y su adaptación regional (OEI, 2023). Ver `paper/sections/capitulo3_diseno_metodologico.md` §3.2.2.
**Bloque del protocolo más relevante:** Bloque 2 (competencias digitales/TIC); Bloque 1 (perfil).

| Código | Definición | Incluir cuando... | Ejemplo de frase tipo |
|---|---|---|---|
| `competencia_tecnica_declarada` | La docente describe su propio manejo técnico de tecnologías digitales | Habla de qué tan cómoda/o se siente usando herramientas digitales | "Uso el celular para todo pero la compu me cuesta más" |
| `competencia_critica_reflexiva` | La docente reflexiona críticamente sobre el uso de tecnología (no solo manejo técnico) | Habla de cuándo conviene o no usar tecnología, de sus límites/riesgos | "No es que haya que usarla siempre, hay que pensar cuándo sirve" |
| `relacion_no_lineal_competencia_representacion` | Casos donde alta competencia técnica NO implica actitud favorable, o baja competencia NO implica rechazo | La entrevista muestra que el vínculo competencia→representación no es directo | Docente muy hábil técnicamente pero desconfiada, o poco hábil pero entusiasta |

**Regla explícita:** no asumir causalidad directa "a mayor competencia técnica, representación más favorable" — codificar tal como aparece, incluidos los casos que contradicen esa relación (son especialmente valiosos).

**Nota conceptual (2026-08-09):** el OE1 pide "competencias digitales" (noción instrumental), pero el fundamento teórico elegido es alfabetización digital docente (Lankshear & Knobel) — más amplio, incluye una dimensión crítica que la sola noción de competencia no captura. `competencia_tecnica_declarada` cubre la dimensión operacional (más cercana a "competencia" en sentido estricto); `competencia_critica_reflexiva` cubre la dimensión crítica (el aporte propio de Lankshear & Knobel). Justificación completa en `paper/sections/capitulo3_diseno_metodologico.md` §3.2.2.

---

## Dimensión 2 — Conocimientos previos sobre IA generativa (Objetivo específico 2)

**Objetivo específico que la origina:** *"Analizar los conocimientos previos que poseen los docentes sobre algoritmos generativos e inteligencia artificial, y su relación con sus representaciones sobre el potencial de estas herramientas para promover aprendizajes significativos."*
**Fundamento teórico secundario:** representaciones sociales clásicas — Jodelet (1986, capítulo "La representación social: fenómenos, concepto y teoría", en el volumen *Psicología Social II* dirigido por Moscovici; 1991, 2011). Procesos de objetivación y anclaje. **Corrección (2026-08-09):** este capítulo, fuente directa de objetivación/anclaje, es de Jodelet — antes citado por error como "Moscovici (1986)" en varios documentos del proyecto; Moscovici dirige el volumen pero no escribió este capítulo.
**Bloque del protocolo más relevante:** Bloque 3 (conocimientos previos), especialmente el ancla de objetivación en Bloque 3-Pregunta 1 (ver más abajo).

| Código | Definición | Incluir cuando... | Ejemplo de frase tipo |
|---|---|---|---|
| `objetivacion_imagen_concreta` | El concepto abstracto "IA generativa" se transforma en una imagen/metáfora concreta | La docente usa una imagen, comparación o metáfora para explicar qué es la IAG | "Es como tener un asistente que..." / "Es una especie de..." |
| `anclaje_tecnologia_previa` | La IAG se integra a un marco de referencia de tecnologías ya conocidas | Compara la IAG con otra tecnología que ya usaba (buscador, procesador de texto, etc.) | "Es como Google pero que te arma el texto" |
| `anclaje_figura_humana` | La IAG se ancla comparándola con un rol/figura humana | Compara la IAG con una persona (colega, asistente, alumno, etc.) | "Es como tener un colega que sabe mucho pero no conoce mi aula" |

**Regla de codificación (representación vs. opinión individual):** para que un elemento cuente como parte de una representación *social* (no solo opinión personal), buscá lenguaje de anclaje social generalizador ("se dice", "en general los docentes...", "todos pensamos"). Un comentario idiosincrático de una sola persona sin ese anclaje se anota igual, pero se marca como `opinion_individual` en vez de representación.

---

## Dimensión 3 — Preocupaciones y expectativas (Objetivo específico 3)

**Objetivo específico que la origina:** *"Describir las preocupaciones y expectativas que manifiestan los docentes respecto al uso de algoritmos generativos para diseñar propuestas didácticas que favorezcan el aprendizaje significativo."*
**Bloque del protocolo más relevante:** Bloque 4 (preocupaciones/expectativas).

**Esta dimensión no tiene familia de códigos deductivos propia** — situación que ya existía antes de la reorganización terminológica (ningún núcleo la cubría) y se mantiene honesta, sin forzar códigos nuevos solo para llenar la categoría. Se alimenta de:
- Códigos inductivos: `preocupacion_recursos_materiales_infraestructura`, `eco_de_par_colega`.
- Códigos de otras dimensiones que aportan contenido de preocupación cuando aparece en Bloque 4: `limita_integracion_sustantiva` (Dimensión 4), `eco_imaginario_mercantil_mediatico`, `imaginario_desigualdad_estructural`, `imaginario_rol_docente_futuro` (dimensión transversal de imaginarios).

---

## Dimensión 4 — Concepción del potencial pedagógico / aprendizaje significativo (Objetivo específico 4)

**Objetivo específico que la origina:** *"Explorar cómo los docentes conciben la relación entre el uso de algoritmos generativos y la promoción de aprendizajes significativos en sus propuestas didácticas."*
**Fundamento teórico secundario:** aprendizaje significativo — Ausubel (1963).
**Bloque del protocolo más relevante:** Bloque 5 (IAG y aprendizaje significativo).

| Código | Definición | Incluir cuando... | Ejemplo de frase tipo |
|---|---|---|---|
| `potencia_integracion_sustantiva` | La docente concibe que la IAG puede ayudar a integrar conocimiento nuevo con saberes previos del estudiante | Menciona que la IAG facilita conectar contenido nuevo con lo que el alumno ya sabe | "Podría ayudar a que el chico relacione esto con lo que ya vio" |
| `limita_integracion_sustantiva` | La docente concibe que la IAG dificulta o reemplaza esa integración | Menciona que la IAG da respuestas genéricas, no ajustadas al alumno real | "Te tira algo genérico que no tiene que ver con mis chicos" |
| `adaptacion_saberes_previos` | Menciona explícitamente la posibilidad/imposibilidad de que la IAG se adapte a conocimientos previos concretos de sus estudiantes | Habla de personalización, diagnóstico de nivel, ajuste al grupo real | "No sé si sabe con qué grupo estoy trabajando" |
| `ejemplo_centrado_producto_proceso` (inductivo, agregado 2026-08-07) | Al describir un ejemplo concreto de uso de IAG en una propuesta didáctica, la docente articula qué se produjo (el producto) o cómo se usó la herramienta (el proceso), pero no qué comprendieron, integraron o lograron los estudiantes como resultado | Hay un ejemplo concreto y narrado (no una opinión general) y el relato se agota en el producto/proceso, sin mención de un resultado de aprendizaje observado o evidenciado | "Hicimos las figuras... y luego los imprimimos en las impresoras 3D" (P15) |
| `aprendizaje_explicitado_en_ejemplo` (inductivo, agregado 2026-08-07 — contraparte del anterior, código espejo) | La docente sí articula, dentro de un ejemplo concreto, qué comprendió, integró o logró el estudiante como resultado del uso de IAG | Buscar activamente, no solo esperar a que aparezca (regla de forcing/emergencia) | (buscado activamente en la relectura del corpus completo — ver hallazgo abajo) |

**Nota de relectura del corpus completo (2026-08-07):** ambos códigos de producto/proceso surgieron de una observación de la investigadora sobre los ejemplos de uso ya codificados — un caso de código inductivo emergiendo de la comparación constante entre casos, no de la teoría original. Resultado de la relectura formal: `ejemplo_centrado_producto_proceso` aparece en 5/15 participantes con ejemplo concreto narrado (P1, P3 -- 2 instancias --, P7, P8, P15 -- 2 instancias); `aprendizaje_explicitado_en_ejemplo` **no aparece en ninguna de las 15 entrevistas (0/15)**, buscado activamente. Detalle completo, incluida una tercera categoría hallada durante la búsqueda (evidencia de *ausencia* de aprendizaje, no solo de su no-articulación — P12), en `relectura_producto_proceso_aprendizaje.md`.

---

## Dimensión 5 — Usos proyectados en el diseño de propuestas didácticas (Objetivo específico 5)

**Objetivo específico que la origina:** *"Caracterizar los tipos de usos que los docentes consideran posibles y deseables para los algoritmos generativos en el diseño de propuestas didácticas que potencien el aprendizaje significativo de sus estudiantes."*
**Fundamento teórico secundario:** diseño didáctico — Palamidessi & Gvirtz (1998); Cabello (2006); Castañeda, Postigo-Fuentes & Arroyo-Sagasta (2025).
**Bloque del protocolo más relevante:** Bloque 6 (usos proyectados en propuestas didácticas).

**Por qué esta dimensión no se confunde con la Dimensión 4:** la Dimensión 4 (Ausubel) refiere al aprendizaje del *estudiante* — si la IAG ayuda o no a integrar conocimiento nuevo con saberes previos. Esta dimensión refiere a las *decisiones del/de la docente* sobre planificación y diseño de propuestas — un objeto distinto. Mantenerlas separadas es más limpio analíticamente y más fiel al plan de tesis: conecta directamente con el cuarto eje real del guion de entrevista ("usos proyectados en el diseño de propuestas didácticas").

| Código | Definición | Incluir cuando... | Ejemplo de frase tipo |
|---|---|---|---|
| `criterio_sentido_pedagogico` | La docente establece que el uso de IAG en una propuesta debe tener un propósito pedagógico claro, no incorporarse por la tecnología en sí misma | Menciona que usa o usaría la IA solo si "suma", si tiene un "para qué", si está al servicio del contenido/aprendizaje y no al revés | "No la uso porque sí, tiene que tener un sentido" / "Primero pienso qué quiero que aprendan y después veo si la IA puede ayudar" |
| `criterio_contextual_grupo` | La docente toma decisiones sobre el uso de IAG en función de las características concretas de su grupo de alumnos: nivel, necesidades particulares, contexto socioeconómico | Menciona al grupo real como variable que determina si usa o no la IAG, qué actividad diseña, o cómo adapta lo que la IA produce | "Para los que tienen dificultades sí, les adapto el texto" |
| `uso_iai_apoyo_administrativo` | La docente describe usos de IAG para tareas que no son estrictamente de diseño didáctico: boletines, informes, comunicaciones, planificaciones formales, búsqueda de recursos | Habla de usar la IA para producir documentos institucionales, ahorrar tiempo en tareas de gestión, o generar materiales de uso propio sin intervención directa de los alumnos | "La uso para hacer los comentarios del boletín" / "Me ayuda a armar la planificación más rápido" |
| `tension_autoria_impronta` | La docente expresa tensión entre usar la IAG para diseñar propuestas y mantener su propia voz, criterio o singularidad como docente | Menciona que no quiere que la IA "reemplace" su forma de hacer las cosas, que le importa que las propuestas "tengan su impronta", o que siente que usar la IA es ceder algo propio | "Me gusta que mis planificaciones sean mías" / "Le doy una idea y ella lo arma, pero después lo tengo que hacer mío" |
| `criterio_etario_ciclo` (inductivo, agregado 2026-08-07) | La docente toma decisiones sobre el uso de IAG en función del ciclo/edad de sus estudiantes (primer ciclo, 1°-3°, vs. segundo ciclo, 4°-7°) — incluye tanto instancias donde el ciclo limita o excluye el uso, como instancias donde se rechaza explícitamente el ciclo como criterio de exclusión y se opta por adaptar la actividad en vez de descartarla | Menciona explícitamente el ciclo o la edad como razón para usar, no usar, o adaptar el uso de IAG | "Con los más chicos no lo trabajé porque trabajo en primer ciclo" (exclusión) / "Se puede sumar tranquilamente... independientemente del grado" (contra-instancia) |
| `criterio_heterogeneidad_competencias_grupo` (inductivo, agregado 2026-08-07) | La docente considera la heterogeneidad de competencias digitales entre estudiantes dentro de un mismo grupo/grado (no por ciclo) al planificar el uso de IAG | Habla de diferencias de manejo técnico entre compañeros del mismo grado como variable de planificación, distinto de una diferencia por edad/ciclo | "Hay alumnos que pueden arrastrar muy bien bloques... y hay otros que no, entonces lograr que todos vayan a la par lleva tiempo" |

**Nota de relectura del corpus completo (2026-08-07) — corrige una lectura previa demasiado apresurada:** una primera observación (basada solo en P1 y P15, las dos únicas docentes de "área especial" que dan clase en ambos ciclos) sugería un patrón limpio y uniforme de exclusión de primer ciclo. **La relectura formal del corpus completo lo complica de forma productiva, no lo confirma sin más:** de 7 participantes con un criterio etario/de ciclo explícito, 4 tienden a la exclusión o limitación (P1, P6, P9, P15) pero **3 rechazan explícitamente esa lógica** (P3, P4, P12) — P4 en particular lo verbaliza como principio general ("independientemente del grado"), y P12 muestra un patrón de adaptación diferenciada por ciclo (actividad "desenchufada" primero en primer grado, uso más directo en grados mayores), no de exclusión. El corpus tiene una tensión real entre ambas posturas, no un consenso — detalle completo en `relectura_ciclo_heterogeneidad.md`.

**Notas de uso y referencias teóricas:**

- **`criterio_sentido_pedagogico`** — código con mayor frecuencia esperada según el procesamiento exploratorio hasta ahora. Prestar atención a si el criterio pedagógico es autónomo o es a su vez un eco del discurso institucional (puede coexistir con `eco_discurso_institucional`, especialmente con el marcador "pertinencia pedagógica" del Marco de gobernanza CABA). Ref. teórica: Palamidessi & Gvirtz (1998) — el diseño como prefiguración contextualizada; Cabello (2006) — las representaciones como condicionantes de los usos efectivos.
- **`criterio_contextual_grupo`** — distinguir de `adaptacion_saberes_previos` (Dimensión 4): ese código refiere a la capacidad de la IA de adaptarse al alumno individual; este captura la **decisión docente** sobre el grupo, no la capacidad de la herramienta. Distinguir también de `criterio_etario_ciclo` y `criterio_heterogeneidad_competencias_grupo` (ambos, más específicos, desagregan lo que este código captura de forma más general — ver relectura). Ref. teórica: Palamidessi & Gvirtz (1998) — diseño situado; Ausubel (1963) — saberes previos como punto de partida (aplicado acá a la decisión docente, no al aprendizaje del alumno).
- **`uso_iai_apoyo_administrativo`** — distinto de `criterio_sentido_pedagogico` porque no implica necesariamente reflexión sobre el aprendizaje. Puede coexistir con `eco_discurso_institucional` cuando el marcador es "reducir la carga administrativa" (ver Marcadores imaginario, Marco gobernanza CABA). Registrar si la docente distingue o no entre estos usos y los usos pedagógicos con alumnos. Ref. teórica: Castañeda, Postigo-Fuentes & Arroyo-Sagasta (2025, REEC 48, extra) — **verificada**, dimensión instrumental; Cabello (2006).
- **`tension_autoria_impronta`** — código de alta carga identitaria. Prestar atención a si la tensión se resuelve a favor de la IA, a favor de la docente, o queda sin resolución. Puede coexistir con `competencia_critica_reflexiva` (Dimensión 1). Ref. teórica: Jodelet (1986) — la representación como construcción identitaria; Castañeda, Postigo-Fuentes & Arroyo-Sagasta (2025, REEC 48, extra) — **verificada**, dimensión epistemológica e ideológica.

---

## Imaginarios sociotécnicos — dimensión transversal (dimensión analítica activa)

**No es una sexta dimensión paralela a las cinco anteriores** — cruza las cinco, rastreada dentro del propio discurso docente, no solo como telón de fondo teórico (ver Cap. 3, §3.5).
**Fundamento teórico secundario:** Jasanoff & Kim (2015); Saura, Lima & Arguelho (2024); Zhai et al. (2021).

| Código | Definición | Incluir cuando... |
|---|---|---|
| `eco_discurso_institucional` | El segmento repite/parafrasea lenguaje de la Guía 2025 (PaideIA) o de discursos oficiales/de capacitación | Aparece alguno de los marcadores de la lista v0 (abajo) u otro lenguaje claramente institucional. **Nota (2026-08-05, decisión de la investigadora sobre P15):** incluye también preocupaciones por ética/regulación centradas específicamente en la autonomía infantil como condición previa al uso de cualquier tecnología (propuesto como candidato inductivo separado, `etica_regulacion_autonomia_infantil`, tras P15 — la investigadora decidió absorberlo acá en vez de crear un código nuevo, dado que es un matiz del mismo eco regulatorio/ético institucional, no un objeto distinto). Si este matiz reaparece con volumen en próximas entrevistas, reevaluar si merece código propio. |
| `voz_experiencial_propia` | El segmento expresa sentido construido desde la propia experiencia, no un eco institucional | La docente habla desde un episodio concreto, propio, no desde una consigna oficial |
| `eco_imaginario_mercantil_mediatico` (inductivo — agregar solo si aparece) | Eco de discurso comercial/mediático sobre IA (marketing de empresas tech, discurso periodístico genérico) | Aparecen frases tipo "dicen que va a cambiar todo", referencias a lo que "se ve en las noticias" |
| `imaginario_inevitabilidad_tecnologica` (agregado 2026-07-31) | La docente representa la incorporación de IA en educación como un proceso inevitable, natural o irreversible, independientemente de su valoración positiva o negativa | Usa expresiones que presentan la IA como algo que "va a llegar sí o sí", "no hay vuelta atrás", "es el futuro", sin cuestionar quién decide esa incorporación ni en qué condiciones |
| `imaginario_desigualdad_estructural` (agregado 2026-07-31) | La docente anticipa o describe que la incorporación de IA va a reproducir o ampliar desigualdades existentes entre escuelas, sectores sociales o docentes con distinto acceso a recursos | Habla de brecha entre escuelas públicas/privadas, entre docentes con/sin formación, como condición que la IA no resuelve o profundiza |
| `imaginario_rol_docente_futuro` (agregado 2026-07-31) | La docente construye una imagen de lo que será o debería ser el rol docente en un escenario de mayor presencia de IA, más allá de la descripción del presente | Proyecta hacia adelante cómo cambiará la enseñanza, qué hará o dejará de hacer el docente, qué capacidades serán necesarias u obsoletas |

**Ejemplos de frase tipo y notas de uso de los 3 códigos de contenido:**

- **`imaginario_inevitabilidad_tecnologica`** — *"Queramos o no, la IA va a estar en las aulas" / "Es algo que va a pasar de todas formas"*. Distinguir de `voz_experiencial_propia`: la inevitabilidad puede expresarse desde la experiencia propia, pero el código captura la **estructura del argumento** (algo dado, no decidido), no su tono. Anotar si la docente acepta, resiste o naturaliza esa inevitabilidad. Ref. teórica: Jasanoff & Kim (2015) — imaginarios como visiones de futuros estabilizados institucionalmente; Saura et al. (2024) — imaginarios globales que presentan la IA como solución neutral y necesaria.
- **`imaginario_desigualdad_estructural`** — *"Las escuelas que ya tienen todo van a poder usarla, las que no tienen nada van a quedar más atrás" / "Esto va a ser para los que pueden pagarlo"*. Distinguir del código inductivo `preocupacion_recursos_materiales_infraestructura` (de P2): ese código captura la preocupación concreta por falta de equipamiento en el propio contexto; este captura una visión **estructural y comparativa** sobre distribución desigual entre contextos. Pueden coexistir en el mismo segmento — no forzar la elección de uno solo. Ref. teórica: Saura et al. (2024) — imaginarios mercantilistas; Castañeda, Postigo-Fuentes & Arroyo-Sagasta (2025, REEC 48, extra) — **verificada**, dimensión comercial y política de su marco de 7 dimensiones.
- **`imaginario_rol_docente_futuro`** — *"El docente va a tener que ser más un guía que alguien que transmite contenido" / "Si no te formás, te van a dejar afuera"*. Prestar atención a si la visión proyectada reproduce el imaginario de automatización docente (Zhai et al., 2021) o propone una transformación del rol con agencia propia — anotar en Notas cuál de los dos patrones prevalece. Ref. teórica: Jasanoff & Kim (2015); Saura et al. (2024); Zhai et al. (2021) sobre inevitabilidad de la automatización.

### Lista de marcadores v1 del imaginario oficial (fuentes primarias, tres niveles)

**Revisión 2026-07-31:** reemplaza la lista v0 (armada con fuentes secundarias, ya que el acceso directo estuvo bloqueado). La investigadora compartió el texto completo de los 4 documentos oficiales — ahora la lista sale de lectura directa, organizada por nivel (global/nacional/jurisdiccional), tal como distingue Saura, Lima & Arguelho (2024). Sigue siendo un instrumento vivo: agregá marcadores nuevos a medida que codificás, con fecha.

**Fuentes primarias** (guardadas en `master_supporting_docs/supporting_papers/`):
- **UNESCO (global):** Holmes, W., Hui, Z., Miao, F. & Ronghuai, H. (2021). *Inteligencia artificial y educación: Guía para las personas a cargo de formular políticas*. `UNESCO_Holmes_2021_IA_educacion.pdf`
- **Nación (Argentina):** Ministerio de Capital Humano, Secretaría de Educación (2025). *Guía para la Integración de las Inteligencias Artificiales en Educación* (Programa PaideIA). `Guia_Nacion_Integracion_IA_Educacion_2025.pdf`
- **CABA (jurisdiccional — tu propio sitio de investigación):** Ministerio de Educación GCBA (v2.0). *IA en la escuela: Guía para un uso crítico*. `Guia_CABA_uso_critico_v2.pdf` — y su documento complementario *Marco de gobernanza y uso responsable de la inteligencia artificial*. `Marco_gobernanza_CABA_IA.pdf`

| Marcador | Nivel | Fuente | Cita/paráfrasis |
|---|---|---|---|
| "uso responsable, ético y efectivo" / "uso crítico, ético y creativo" | Nación / CABA | Guía Nación p.5; Guía CABA p.4 (objetivo) | Formulación casi idéntica en ambos niveles — buen candidato de alta frecuencia esperada |
| "acompañar" / "acompañamiento docente" (no reemplazo) | Nación / CABA (gobernanza) | Guía Nación §"Impacto en el rol docente"; Marco gobernanza CABA, principio 1 "Humanocentrismo y agencia pedagógica" | "la IA nunca reemplaza... complementa la labor docente sin sustituir el contacto humano" |
| "potenciar lo humano, no reemplazarlo con IA" | CABA | Guía CABA p.6, principio "Humanismo digital" | Formulación explícita como principio orientador |
| "el docente tiene que aprender, tiene que actualizarse" / "formación continua" | Nación / CABA (gobernanza) | Guía Nación §"Estrategias para capacitar..."; Marco gobernanza CABA, "Nivel de los docentes" | Ya identificado en la entrevista de P2 |
| "reducir la carga administrativa" (para "tareas de mayor valor pedagógico: planificación, evaluación formativa, retroalimentación") | CABA (gobernanza) | Marco gobernanza CABA, "Nivel de los docentes", objetivos específicos | Marcador nuevo, muy específico — buen candidato para segmentos donde la docente habla de ahorrar tiempo en corrección/evaluación |
| "eficiencia" / "agilizar la corrección" / "ahorro de tiempo" | Nación / CABA | Guía Nación §"Evaluación y retroalimentación"; Guía CABA p.5 | Ya usado en P2 ("evaluaciones más rápidas") |
| "personalización" / "educación personalizada" / "adaptar contenidos al ritmo de cada estudiante" | Los 3 niveles | Presente casi textual en los 3 documentos | Marcador transversal, altísima frecuencia esperada en el discurso oficial |
| "sesgos" / "sesgo algorítmico" / "alucinaciones" (respuestas incorrectas que parecen coherentes) | Nación / CABA | Guía Nación p.8; Guía CABA glosario | Vocabulario técnico específico — si una docente lo usa tal cual, es un eco fuerte, no genuino desde la experiencia |
| "brecha(s)" — acceso, formación, infraestructura, digital | Los 3 niveles | Guía Nación p.8 ("brechas en el acceso"); Marco gobernanza CABA, "Equidad e inclusión digital" | Distinguir de la `preocupacion_recursos_materiales_infraestructura` inductiva de P2 — puede solaparse, evaluar caso por caso |
| "pensamiento crítico" / "las 4C" (creatividad, pensamiento crítico, comunicación, colaboración) | CABA | Guía CABA p.5 | Vocabulario específico de la Guía CABA — marcador de alta especificidad |
| "protección de datos" / "consentimiento informado" / "privacidad" | Los 3 niveles | Presente en los 3, con cita a Ley 25.326 en Nación y CABA | Poco probable que aparezca espontáneamente en el discurso docente sobre representaciones, pero vigilar |
| "aliada estratégica" / "IA como aliada" | CABA (gobernanza) | Marco gobernanza CABA, Presentación | Metáfora oficial específica — si una docente usa "aliada" para describir la IA, marcador fuerte |
| "estrategias desafiantes y auténticas que promuevan aprendizajes que no puedan ser automatizados" / "palabra propia" (Ravela y Cardoner) | CABA (gobernanza) / Nación | Marco gobernanza CABA, "Nivel de los docentes"; Guía Nación p.18-19 | Vocabulario de evaluación auténtica — vigilar si aparece en el eje de aprendizaje significativo |
| "criterio docente" / "supervisión docente" / "el docente valida y decide" | Los 3 niveles | Marco gobernanza CABA, principio 5; Guía Nación (Matemática, "rol del docente como mediador") | Formulación de resguardo del rol, distinta de "no reemplaza" — vigilar matices |

**Regla de auditoría:** cada vez que uses `eco_discurso_institucional`, anotá a qué marcador específico corresponde, de qué documento y en qué nivel (global/nacional/CABA) — tiene que poder rastrearse, no alcanza con "esto suena institucional". Si un mismo fragmento resuena con marcadores de más de un nivel (por ejemplo, "personalización" aparece en los 3), anotá todos los niveles posibles — no fuerces la elección de uno solo.

**Nota metodológica:** ahora que tenés los 3 niveles con texto real, podés empezar a distinguir si una docente ecoa el discurso **nacional**, el **jurisdiccional** (CABA — el más relevante dado que tu muestra es de CABA), o el **global/UNESCO** — esto puede ser un hallazgo interesante en sí mismo (¿el discurso que más circula entre las docentes porteñas es el de su propia jurisdicción, o llega mediado por el nivel nacional?).

---

## Etiquetas transversales (obligatorias en cada segmento codificado)

- **`bloque_protocolo`**: número de bloque del protocolo de entrevista de donde viene el segmento (1 a 7) — necesario porque la entrevista es semiestructurada y no todos los bloques se administraron a todas las docentes. Sin este dato no se puede interpretar bien la frecuencia de ningún código.
- **`procedencia`**: `deductivo` (viene de esta lista v0) o `inductivo` (código nuevo que agregaste vos), con fecha de creación.

---

## Ancla privilegiada — Bloque 3, Pregunta 1

Cuando la entrevista incluya la pregunta "¿Qué sabés sobre la IAG? Si tuvieras que explicarle a alguien qué es, ¿cómo se lo explicarías?", tratá la primera metáfora/imagen espontánea que use la docente como dato de mayor peso para `objetivacion_imagen_concreta` (Dimensión 2) — es el momento más parecido a una evocación libre que tiene este protocolo. Tabla completa por participante en `paper/supplementary/anexo_d_descripcion_densa_participantes.md` y en la hoja "Ancla objetivación" del Excel.

---

## Planilla de seguimiento de saturación

Ver hoja "Saturación" del Excel y la síntesis final en `codificacion_P1_P14_cierre_corpus.md` §5 y `paper/sections/capitulo3_diseno_metodologico.md` §3.7 — saturación teórica propuesta como alcanzada con el corpus completo (15/15), pendiente de confirmación final de la investigadora.

---

## Recordatorio de reflexividad (por cada entrevista)

Antes de codificar cada entrevista, escribí un memo breve que incluya: (a) tu vínculo previo con esta docente/institución si lo hay, (b) qué esperabas encontrar en esta entrevista puntual, (c) si algo de tu propio trabajo de 2024 (Caldeiro, Odetti y Ordiz) está condicionando lo que estás notando o pasando por alto.

---

## Notas de uso — no forzar

Si al codificar ves que alguna dimensión no aparece o aparece muy poco desarrollada, **no la fuerces ni la rellenes** — anotalo como "dimensión subdesarrollada en el corpus" y seguí. Puede ser un hallazgo real (ese eje no resuena en el discurso docente) o una señal de que hay que ajustar el codebook. Las dos cosas son información válida, no un error tuyo.
