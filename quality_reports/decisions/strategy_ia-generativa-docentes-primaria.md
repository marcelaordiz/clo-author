# Strategy Decision Record: ia-generativa-docentes-primaria

**Date:** 2026-07-28
**Decision type:** analytic-strategy (qualitative — repurposed from identification-strategy per domain-profile.md)

---

## Decision

Se adopta la **Teoría de las Representaciones Sociales, enfoque estructural (Moscovici/Jodelet/Abric) adaptado a datos de entrevista semi-estructurada** — con identificación de candidatos al núcleo central y elementos periféricos mediante criterios cualitativos de centralidad (frecuencia, fuerza connotativa, función organizadora, estabilidad entre dominios de práctica) — usando **análisis temático (Braun & Clarke, 2006) como técnica de codificación subordinada**, y **análisis lexicométrico (IRAMUTEQ) como triangulación complementaria, no como método primario**. El aula y las tareas docentes propias se tratan como **dos campos de práctica de un mismo objeto representacional**, no como dos representaciones independientes.

---

## Alternatives Considered

### Alternative 1: Análisis temático puro (Braun & Clarke), sin pretensión estructural SRT
- **Description:** Codificar las 14 entrevistas con análisis temático estándar, reportando temas/percepciones docentes sobre IA generativa sin intentar clasificar núcleo central vs. periférico.
- **Why rejected:** Abandona precisamente el elemento que diferencia esta tesis de la literatura internacional dominante de nivel primario (Calleja & Camilleri 2025; Han et al. 2024; Yu, Lee & Kim 2025), que ya usa marcos descriptivos/de aceptación sin estructura núcleo/periférico. Adoptar análisis temático puro colapsaría la tesis en la categoría de estudios ya existentes que el frontier_map identifica como el status quo, no como el vacío. Se retiene como capa técnica subordinada (fase de codificación), no como estrategia analítica primaria.
- **What would make this viable as primary:** Si el objetivo de la tesis se redefiniera explícitamente como "percepciones docentes" sin anclaje SRT — no es el caso aquí, dado el marco teórico ya elegido en el domain-profile y el lit review.

### Alternative 2: Núcleo central por método clásico (Vergès, asociación libre de palabras + evocación jerarquizada), como en Carvalho & Corrallo (2024)
- **Description:** Aplicar el método cuantitativo-estructural clásico de identificación de núcleo central (rango × frecuencia de evocaciones libres, cuestionario de caracterización).
- **Why rejected:** Los datos ya fueron recolectados mediante entrevista semi-estructurada según una guía de preguntas ya utilizada — no existe instrumento de asociación libre/evocación jerarquizada, y no es razonable ni ético volver a citar a los 14 docentes para administrar un instrumento adicional en el marco de esta tesis. El método clásico no puede aplicarse retroactivamente sobre datos de entrevista abierta sin introducir un salto metodológico no justificado.
- **What would make this viable:** Solo sería viable en un diseño prospectivo (no es el caso: los datos ya están recolectados) que incluyera desde el inicio un instrumento de asociación libre de palabras + cuestionario de caracterización, complementario a la entrevista.

### Alternative 3: Análisis de discurso como método primario (narrativas herramienta/amenaza/colega)
- **Description:** Centrar el análisis en cómo los/las docentes narrativizan la IA generativa (amenaza, herramienta, colega/par), sin intentar una clasificación estructural núcleo/periférico.
- **Why rejected:** Captura bien la dimensión valorativa/narrativa (componente afectivo de la representación, per Jodelet 2011), pero por sí solo no permite sostener la afirmación central de posicionamiento de la tesis ("reconstrucción de núcleo central y elementos periféricos"). Se retiene como lente complementaria dentro del esquema de codificación (código `narrativa_*`, §2.1 del strategy memo), no como estrategia primaria.
- **What would make this viable as primary:** Si la pregunta de investigación se redefiniera hacia "cómo narrativizan los docentes la IA generativa" en lugar de "cuál es la estructura de su representación social" — cambiaría el posicionamiento frente a la literatura y perdería el anclaje SRT explícito que el domain-profile y el lit review ya establecieron.

### Alternative 4: Teoría fundamentada (grounded theory) pura, sin marco SRT a priori
- **Description:** Codificación inductiva completa desde cero (Glaser/Strauss o Charmaz), dejando que la teoría emerja de los datos sin codebook deductivo previo basado en SRT.
- **Why rejected:** Forfeit el andamiaje deductivo (núcleo/periférico, componentes cognitivo/afectivo/normativo) que constituye precisamente el vacío de literatura identificado (frontier_map.md: "ningún estudio combina SRT estructural + primaria + IA generativa + cobertura dual + Argentina"). Un diseño grounded-theory puro produciría una teoría de representaciones/percepciones docentes ad hoc, no necesariamente comparable ni dialogante con el anclaje teórico SRT que el domain-profile ya fija como marco del proyecto. También aumenta el riesgo de "reinventar" categorías que la literatura SRT ya ofrece (núcleo, periferia, componentes), sin ganancia clara.
- **What would make this viable:** Si el objetivo del proyecto se redefiniera explícitamente como generación de teoría sustantiva nueva sobre representaciones docentes de IA, en lugar de aplicación/extensión de la SRT estructural existente — no es el encuadre actual del proyecto.

### Alternative 5: IRAMUTEQ / análisis lexicométrico como método primario
- **Description:** Tratar el corpus de 14 entrevistas transcriptas como un corpus lexicométrico primario, aplicando Classification Hiérarchique Descendante (CHD), análisis de similitud y nube de palabras como la evidencia estructural central (como hace Carvalho & Corrallo 2024, aunque sobre datos de asociación libre, no de entrevista).
- **Why rejected:** N=14 transcripciones de entrevista es un corpus pequeño para clases CHD estables (la literatura lexicométrica recomienda corpus considerablemente mayores, o al menos textos de asociación libre más cortos y numerosos, no 14 entrevistas largas y heterogéneas). Usarlo como método primario expondría la tesis a la objeción metodológica más fuerte posible ("tamaño de corpus insuficiente para el método declarado").
- **What would make this viable:** Un corpus considerablemente mayor (más entrevistas, o un instrumento de asociación libre de palabras administrado a una muestra más amplia) — no es el caso de este diseño retrospectivo con N=14.

---

## Rationale

El enfoque elegido (SRT estructural adaptada + análisis temático subordinado + triangulación lexicométrica) es el único que preserva simultáneamente (i) el anclaje teórico que sostiene la afirmación de contribución de la tesis frente al vacío de literatura identificado, (ii) la honestidad metodológica frente a los datos realmente disponibles (entrevista semi-estructurada, sin instrumento de evocación jerarquizada, N=14), y (iii) la posibilidad de entregar evidencia doble (cualitativa + lexicométrica parcial) que preempte la objeción de referato más previsible ("¿esto es realmente estructural o es solo temático con otro nombre?").

---

## Key Assumptions

| Assumption | Statement | Credibility | If violated |
|-----------|-----------|-------------|-------------|
| A1 — Adecuación de criterios cualitativos de centralidad | Frecuencia + fuerza connotativa + función organizadora + estabilidad entre dominios identifican candidatos a núcleo central de manera defendible sin instrumento de evocación jerarquizada | Basado en los criterios cualitativos que Abric (2001) mismo describe junto al método cuantitativo; usado (implícitamente) por antecedentes sin instrumento estructurado (Ramos Ramón & Frías López 2019) | Si un/a referí exige el método de Vergès como único válido, la respuesta pre-planeada (§6, objeción 5 del memo) es declarar la adaptación explícitamente y usar lenguaje hedged ("candidatos al núcleo") en todo el manuscrito |
| A2 — Los 14 casos permiten saturación de códigos | La curva de temas nuevos por entrevista se aplana antes de la entrevista 14 | Anclado en literatura general de saturación cualitativa (Guest et al. 2006; Hennink & Kaiser 2022) — **ASSUMED, no verificado contra la bibliografía propia de este proyecto** | Si no se aplana, reportar honestamente que no se alcanzó saturación completa y acotar las conclusiones en consecuencia (no forzar un cierre estructural prematuro) |
| A3 — El núcleo puede compararse válidamente entre dominios (aula/tareas) sin instrumento separado por dominio | Codificar segmentos de una misma entrevista con distinto domain-tag es suficiente para detectar estabilidad/fragmentación del núcleo entre campos de práctica | Consistente con la teoría de "champs de représentation" de Abric/Flament | Si la fragmentación entre dominios resulta indistinguible de ruido de codificación, reportar como limitación y no forzar una conclusión de "núcleo estable" o "fragmentado" sin evidencia suficiente |
| A4 — La transcripción completa de las 14 entrevistas es alcanzable antes de la fase de codificación formal | El tiempo de tesis permite completar las transcripciones pendientes | Depende de recursos/tiempo de la investigadora — no verificado en este memo | Si no es alcanzable, se activa el protocolo documentado de notas de campo estructuradas (memo, §5.2) y se reporta la sensibilidad del análisis a esa decisión (Robustness Plan #7) |

---

## What Would Invalidate This Strategy

- La curva de saturación no muestra ningún aplanamiento hacia la entrevista 14 (sugiere que N=14 es insuficiente incluso para saturación de códigos, no solo de sentido).
- Al aplicar los criterios de centralidad (§2.3 del memo), ningún elemento cumple simultáneamente los cuatro criterios en al menos 8/14 entrevistas — es decir, no emerge ningún candidato robusto a núcleo central, y el hallazgo sustantivo termina siendo "representación fragmentada/sin núcleo consensuado" (nota: esto NO invalida la estrategia por sí solo — es un hallazgo legítimo y reportable — pero sí invalidaría la afirmación de posicionamiento de "reconstrucción de núcleo central" si se sostiene sin matices).
- La comparación IRAMUTEQ vs. codificación manual arroja resultados completamente contradictorios sin explicación plausible (sugeriría un problema de codificación, no solo una limitación de corpus pequeño).

Si alguno de estos ocurre, el fallback es: reportar honestamente el hallazgo (representación sin núcleo consensuado, o estructura frágil/inestable) como resultado sustantivo de la tesis, en lugar de forzar una narrativa de núcleo central robusto no sostenida por la evidencia — esto es consistente con el estándar de credibilidad (§3 del memo) y evita el riesgo de referato más serio (sobre-reclamo estructural, §6 objeción 5).

---

## Risks and Mitigations

| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|-----------|
| Sobre-reclamo de "estructura núcleo/periférico" sin instrumento de evocación jerarquizada (mayor riesgo del diseño) | Medium-High | High — ataca directamente la afirmación de contribución de la tesis | Lenguaje hedged consistente ("candidatos al núcleo"), disclosure explícito en métodos, triangulación IRAMUTEQ, ver §6 objeción 5 y §7 del memo |
| Transcripción incompleta al momento de iniciar la codificación | Medium | Medium-High — introduce confusión entre profundidad de dato y diferencia representacional real | Recomendación de completar transcripción antes de codificar; protocolo documentado de fallback si no es posible (§5.2 del memo) |
| Sesgo de deseabilidad social subestima rechazo/desconocimiento docente | Medium | Medium | Priorizar episodios concretos sobre declaraciones generales; declarar limitación explícitamente (§5.3 del memo) |
| Investigadora única sin doble codificación completa | High (asumido, tesis de maestría) | Medium | Doble codificación parcial (3–4 entrevistas) + peer debriefing documentado con director/a de tesis (§3, Dependability/Confirmability) |
| Confusión entre discurso institucional/oficial y representación genuina | Medium | Medium-High — podría hacer que la "representación docente" reportada sea en realidad discurso oficial repetido | Código `eco_discurso_institucional` explícito; comparación de núcleo con/sin esos segmentos (§5.5, Robustness #4) |
