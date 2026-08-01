# Codebook v0 — para codificación manual

**Proyecto:** Representaciones de docentes de nivel primario sobre IA generativa (UNSAM)
**Versión:** v0 (deductiva, semilla) — fecha de inicio: completar al empezar a usar
**Basado en:** `quality_reports/strategy/ia-generativa-docentes-primaria/pseudo_code.md`, Fase 2

**Changelog:**
- 2026-07-31: reemplazada la lista de marcadores del imaginario oficial (v0 → v1, fuentes primarias). Agregados 3 códigos deductivos a Núcleo 4 (`imaginario_inevitabilidad_tecnologica`, `imaginario_desigualdad_estructural`, `imaginario_rol_docente_futuro`) y creado el **Núcleo 5 — Concepciones sobre diseño didáctico y uso pedagógico de la IAG** (4 códigos), propuestos por la investigadora a partir del procesamiento exploratorio de las primeras entrevistas. Esto pasa el marco teórico de 4 a 5 núcleos — pendiente de reflejar formalmente en `domain-profile.md` y en la memo de estrategia (en curso).
- 2026-08-01: **verificada** la cita de Castañeda et al. (2025) — Castañeda, L., Postigo-Fuentes, A. Y. & Arroyo-Sagasta, A. (2025). "Beyond Tools, Toward Power Structures: A Critical Review of AI in Primary Education." *Revista Española de Educación Comparada*, 48 (extra), 73-95. DOI: 10.5944/reec.48.2025.45126. PDF en `master_supporting_docs/supporting_papers/Castaneda_et_al_2025_beyond_tools_power_structures.pdf`. Ya agregada a `Bibliography_base.bib`. Todas las marcas `% UNVERIFIED` de este documento quedan resueltas.

**Cómo usar este documento:** por cada entrevista, leé completa primero (familiarización + memo reflexivo), después codificá segmento por segmento. Cada segmento puede llevar más de un código. Anotá siempre: (a) de qué bloque del protocolo viene, (b) si el código es deductivo (de esta lista) o inductivo (nuevo, que vos agregás), con fecha.

---

## Núcleo 1 — Representaciones sociales clásicas (Moscovici/Jodelet)

| Código | Definición | Incluir cuando... | Ejemplo de frase tipo |
|---|---|---|---|
| `objetivacion_imagen_concreta` | El concepto abstracto "IA generativa" se transforma en una imagen/metáfora concreta | La docente usa una imagen, comparación o metáfora para explicar qué es la IAG | "Es como tener un asistente que..." / "Es una especie de..." |
| `anclaje_tecnologia_previa` | La IAG se integra a un marco de referencia de tecnologías ya conocidas | Compara la IAG con otra tecnología que ya usaba (buscador, procesador de texto, etc.) | "Es como Google pero que te arma el texto" |
| `anclaje_figura_humana` | La IAG se ancla comparándola con un rol/figura humana | Compara la IAG con una persona (colega, asistente, alumno, etc.) | "Es como tener un colega que sabe mucho pero no conoce mi aula" |

**Regla de codificación (representación vs. opinión individual):** para que un elemento cuente como parte de una representación *social* (no solo opinión personal), buscá lenguaje de anclaje social generalizador ("se dice", "en general los docentes...", "todos pensamos"). Un comentario idiosincrático de una sola persona sin ese anclaje se anota igual, pero se marca como `opinion_individual` en vez de representación.

---

## Núcleo 2 — Aprendizaje significativo (Ausubel)

| Código | Definición | Incluir cuando... | Ejemplo de frase tipo |
|---|---|---|---|
| `potencia_integracion_sustantiva` | La docente concibe que la IAG puede ayudar a integrar conocimiento nuevo con saberes previos del estudiante | Menciona que la IAG facilita conectar contenido nuevo con lo que el alumno ya sabe | "Podría ayudar a que el chico relacione esto con lo que ya vio" |
| `limita_integracion_sustantiva` | La docente concibe que la IAG dificulta o reemplaza esa integración | Menciona que la IAG da respuestas genéricas, no ajustadas al alumno real | "Te tira algo genérico que no tiene que ver con mis chicos" |
| `adaptacion_saberes_previos` | Menciona explícitamente la posibilidad/imposibilidad de que la IAG se adapte a conocimientos previos concretos de sus estudiantes | Habla de personalización, diagnóstico de nivel, ajuste al grupo real | "No sé si sabe con qué grupo estoy trabajando" |

---

## Núcleo 3 — Alfabetización digital docente (Lankshear & Knobel)

| Código | Definición | Incluir cuando... | Ejemplo de frase tipo |
|---|---|---|---|
| `competencia_tecnica_declarada` | La docente describe su propio manejo técnico de tecnologías digitales | Habla de qué tan cómoda/o se siente usando herramientas digitales | "Uso el celular para todo pero la compu me cuesta más" |
| `competencia_critica_reflexiva` | La docente reflexiona críticamente sobre el uso de tecnología (no solo manejo técnico) | Habla de cuándo conviene o no usar tecnología, de sus límites/riesgos | "No es que haya que usarla siempre, hay que pensar cuándo sirve" |
| `relacion_no_lineal_competencia_representacion` | Casos donde alta competencia técnica NO implica actitud favorable, o baja competencia NO implica rechazo | La entrevista muestra que el vínculo competencia→representación no es directo | Docente muy hábil técnicamente pero desconfiada, o poco hábil pero entusiasta |

**Regla explícita:** no asumir causalidad directa "a mayor competencia técnica, representación más favorable" — codificar tal como aparece, incluidos los casos que contradicen esa relación (son especialmente valiosos).

---

## Núcleo 4 — Imaginarios sociotécnicos (dimensión analítica activa)

| Código | Definición | Incluir cuando... |
|---|---|---|
| `eco_discurso_institucional` | El segmento repite/parafrasea lenguaje de la Guía 2025 (PaideIA) o de discursos oficiales/de capacitación | Aparece alguno de los marcadores de la lista v0 (abajo) u otro lenguaje claramente institucional |
| `voz_experiencial_propia` | El segmento expresa sentido construido desde la propia experiencia, no un eco institucional | La docente habla desde un episodio concreto, propio, no desde una consigna oficial |
| `eco_imaginario_mercantil_mediatico` (inductivo — agregar solo si aparece) | Eco de discurso comercial/mediático sobre IA (marketing de empresas tech, discurso periodístico genérico) | Aparecen frases tipo "dicen que va a cambiar todo", referencias a lo que "se ve en las noticias" |
| `imaginario_inevitabilidad_tecnologica` (agregado 2026-07-31) | La docente representa la incorporación de IA en educación como un proceso inevitable, natural o irreversible, independientemente de su valoración positiva o negativa | Usa expresiones que presentan la IA como algo que "va a llegar sí o sí", "no hay vuelta atrás", "es el futuro", sin cuestionar quién decide esa incorporación ni en qué condiciones |
| `imaginario_desigualdad_estructural` (agregado 2026-07-31) | La docente anticipa o describe que la incorporación de IA va a reproducir o ampliar desigualdades existentes entre escuelas, sectores sociales o docentes con distinto acceso a recursos | Habla de brecha entre escuelas públicas/privadas, entre docentes con/sin formación, como condición que la IA no resuelve o profundiza |
| `imaginario_rol_docente_futuro` (agregado 2026-07-31) | La docente construye una imagen de lo que será o debería ser el rol docente en un escenario de mayor presencia de IA, más allá de la descripción del presente | Proyecta hacia adelante cómo cambiará la enseñanza, qué hará o dejará de hacer el docente, qué capacidades serán necesarias u obsoletas |

**Ejemplos de frase tipo y notas de uso de los 3 códigos nuevos:**

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

## Núcleo 5 — Concepciones sobre diseño didáctico y uso pedagógico de la IAG (agregado 2026-07-31)

**Por qué es un núcleo separado y no una extensión del Núcleo 2:** Ausubel (Núcleo 2) refiere al aprendizaje del *estudiante* — si la IAG ayuda o no a integrar conocimiento nuevo con saberes previos. Este núcleo refiere a las *decisiones del/de la docente* sobre planificación y diseño de propuestas — un objeto distinto. Mantenerlos separados es más limpio analíticamente y más fiel al marco: conecta directamente con el cuarto eje real del guion de entrevista ("usos proyectados en el diseño de propuestas didácticas") y con la teoría de diseño didáctico ya presente en el marco teórico (Palamidessi & Gvirtz, 1998), que hasta ahora no tenía códigos deductivos propios.

| Código | Definición | Incluir cuando... | Ejemplo de frase tipo |
|---|---|---|---|
| `criterio_sentido_pedagogico` | La docente establece que el uso de IAG en una propuesta debe tener un propósito pedagógico claro, no incorporarse por la tecnología en sí misma | Menciona que usa o usaría la IA solo si "suma", si tiene un "para qué", si está al servicio del contenido/aprendizaje y no al revés | "No la uso porque sí, tiene que tener un sentido" / "Primero pienso qué quiero que aprendan y después veo si la IA puede ayudar" |
| `criterio_contextual_grupo` | La docente toma decisiones sobre el uso de IAG en función de las características concretas de su grupo de alumnos: edad, nivel, necesidades particulares, contexto socioeconómico | Menciona al grupo real como variable que determina si usa o no la IAG, qué actividad diseña, o cómo adapta lo que la IA produce | "Con este grupo no lo usaría porque todavía no leen" / "Para los que tienen dificultades sí, les adapto el texto" |
| `uso_iai_apoyo_administrativo` | La docente describe usos de IAG para tareas que no son estrictamente de diseño didáctico: boletines, informes, comunicaciones, planificaciones formales, búsqueda de recursos | Habla de usar la IA para producir documentos institucionales, ahorrar tiempo en tareas de gestión, o generar materiales de uso propio sin intervención directa de los alumnos | "La uso para hacer los comentarios del boletín" / "Me ayuda a armar la planificación más rápido" |
| `tension_autoria_impronta` | La docente expresa tensión entre usar la IAG para diseñar propuestas y mantener su propia voz, criterio o singularidad como docente | Menciona que no quiere que la IA "reemplace" su forma de hacer las cosas, que le importa que las propuestas "tengan su impronta", o que siente que usar la IA es ceder algo propio | "Me gusta que mis planificaciones sean mías" / "Le doy una idea y ella lo arma, pero después lo tengo que hacer mío" |

**Notas de uso y referencias teóricas:**

- **`criterio_sentido_pedagogico`** — código con mayor frecuencia esperada según el procesamiento exploratorio hasta ahora. Prestar atención a si el criterio pedagógico es autónomo o es a su vez un eco del discurso institucional (puede coexistir con `eco_discurso_institucional`, especialmente con el marcador "pertinencia pedagógica" del Marco de gobernanza CABA). Ref. teórica: Palamidessi & Gvirtz (1998) — el diseño como prefiguración contextualizada; Cabello (2006) — las representaciones como condicionantes de los usos efectivos.
- **`criterio_contextual_grupo`** — distinguir de `adaptacion_saberes_previos` (Núcleo 2): ese código refiere a la capacidad de la IA de adaptarse al alumno individual; este captura la **decisión docente** sobre el grupo, no la capacidad de la herramienta. Ref. teórica: Palamidessi & Gvirtz (1998) — diseño situado; Ausubel (1963) — saberes previos como punto de partida (aplicado acá a la decisión docente, no al aprendizaje del alumno).
- **`uso_iai_apoyo_administrativo`** — distinto de `criterio_sentido_pedagogico` porque no implica necesariamente reflexión sobre el aprendizaje. Puede coexistir con `eco_discurso_institucional` cuando el marcador es "reducir la carga administrativa" (ver Marcadores imaginario, Marco gobernanza CABA). Registrar si la docente distingue o no entre estos usos y los usos pedagógicos con alumnos. Ref. teórica: Castañeda, Postigo-Fuentes & Arroyo-Sagasta (2025, REEC 48, extra) — **verificada**, dimensión instrumental; Cabello (2006).
- **`tension_autoria_impronta`** — código de alta carga identitaria. Prestar atención a si la tensión se resuelve a favor de la IA, a favor de la docente, o queda sin resolución. Puede coexistir con `competencia_critica_reflexiva` (Núcleo 3). Ref. teórica: Moscovici (1986) — la representación como construcción identitaria; Castañeda, Postigo-Fuentes & Arroyo-Sagasta (2025, REEC 48, extra) — **verificada**, dimensión epistemológica e ideológica.

---

## Etiquetas transversales (obligatorias en cada segmento codificado)

- **`bloque_protocolo`**: número de bloque del protocolo de entrevista de donde viene el segmento (1 a 7) — necesario porque la entrevista es semiestructurada y no todos los bloques se administraron a todas las docentes. Sin este dato no se puede interpretar bien la frecuencia de ningún código.
- **`procedencia`**: `deductivo` (viene de esta lista v0) o `inductivo` (código nuevo que agregaste vos), con fecha de creación.

---

## Ancla privilegiada — Bloque 3, Pregunta 1

Cuando la entrevista incluya la pregunta "¿Qué sabés sobre la IAG? Si tuvieras que explicarle a alguien qué es, ¿cómo se lo explicarías?", tratá la primera metáfora/imagen espontánea que use la docente como dato de mayor peso para `objetivacion_imagen_concreta` — es el momento más parecido a una evocación libre que tiene este protocolo. Llevá una tabla aparte:

| Participante | ¿Se administró Bloque 3, P1? | Primera metáfora/imagen espontánea |
|---|---|---|
| P1 | | |
| P2 | | |
| ... | | |

---

## Planilla de seguimiento de saturación

Completar después de codificar cada entrevista (en el orden en que las vayas codificando, no necesariamente el orden en que las hiciste):

| # entrevista codificada | Participante | Códigos nuevos que aparecieron | Total códigos nuevos |
|---|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| ... | | | |

Cuando las últimas 2-3 entrevistas codificadas no agreguen propiedades/relaciones nuevas a ninguna categoría axial (no solo códigos sueltos), hay saturación teórica — anotalo explícitamente cuando llegues a ese punto.

---

## Recordatorio de reflexividad (por cada entrevista)

Antes de codificar cada entrevista, escribí un memo breve que incluya: (a) tu vínculo previo con esta docente/institución si lo hay, (b) qué esperabas encontrar en esta entrevista puntual, (c) si algo de tu propio trabajo de 2024 (Caldeiro, Odetti y Ordiz) está condicionando lo que estás notando o pasando por alto.

---

## Notas de uso — no forzar

Si al codificar las primeras 3-4 entrevistas ves que algún núcleo no aparece o aparece muy poco desarrollado, **no lo fuerces ni lo rellenes** — anotalo como "núcleo subdesarrollado en el corpus" y seguí. Puede ser un hallazgo real (ese eje no resuena en el discurso docente) o una señal de que hay que ajustar el codebook. Las dos cosas son información válida, no un error tuyo.
