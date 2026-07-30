# Codebook v0 — para codificación manual

**Proyecto:** Representaciones de docentes de nivel primario sobre IA generativa (UNSAM)
**Versión:** v0 (deductiva, semilla) — fecha de inicio: completar al empezar a usar
**Basado en:** `quality_reports/strategy/ia-generativa-docentes-primaria/pseudo_code.md`, Fase 2

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

### Lista de marcadores v0 del imaginario oficial (provisoria — a refinar)

Extraída de una primera lectura de la Guía 2025 (PaideIA) y el informe Educ.ar 2025. **Importante:** el acceso directo a la Guía 2025 estuvo bloqueado durante la búsqueda bibliográfica (error 403 del proxy hacia el dominio .gob.ar) — esta lista se arma con lo confirmado por fuentes secundarias y debe **revisarse/completarse cuando puedas leer el documento completo vos misma**. Es un instrumento vivo: agregá marcadores nuevos a medida que codificás, con fecha.

- "aprendizaje personalizado"
- "acompañamiento docente" (no reemplazo del docente)
- "uso responsable/ético"
- "necesidad de formación/capacitación"
- "brecha de formación"
- "integración progresiva"
- "eficiencia"

**Regla de auditoría:** cada vez que uses `eco_discurso_institucional`, anotá a qué marcador específico corresponde y de qué documento/línea viene — tiene que poder rastrearse, no alcanza con "esto suena institucional".

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
