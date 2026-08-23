# Relectura del corpus completo — criterio de ciclo/edad y heterogeneidad de grupo

**Origen:** observación de la investigadora sobre `criterio_contextual_grupo` — el código venía mezclando bajo una misma etiqueta dos preguntas distintas: "¿en qué ciclo sí/no?" y "¿cómo adapto dentro de un grupo ya dado?". Se formalizan dos códigos inductivos (`codebook_v0_manual.md`, Núcleo 5, 2026-08-07) y se relee el corpus completo (15/15).

**Corrección explícita, no silenciosa:** en el intercambio previo a este, afirmé —basándome únicamente en P1 y P15, las dos únicas participantes de "área especial" que dan clase en ambos ciclos— que *"cuando hay comparación directa dentro de la misma docente, el corte por ciclo aparece siempre en la misma dirección"*. **Esa lectura era prematura.** La relectura formal de las 15 entrevistas la complica de forma productiva: hay una tensión real en el corpus, no un consenso limpio. Se corrige acá con el detalle completo.

---

## 1. `criterio_etario_ciclo` — 7/15 participantes con criterio explícito, dividido en dos posturas

| Participante | Postura | Cita |
|---|---|---|
| P15 | Exclusión | *"Con los más chicos no lo trabajé porque trabajo en primer ciclo"* [08:33] |
| P1 | Exclusión | *"En los grados más chicos no le veo mucha aplicación. Los chicos tienen que aprender lo básico"* |
| P9 | Exclusión relativa | *"Cree que es más apropiada para segundo ciclo que primer ciclo"* [20:26] |
| P6 | Exclusión mixta con vulnerabilidad | *"Con grados chicos en contextos vulnerables cuesta más, es todo más de cero"* [01:04-02:23] — mezcla edad con contexto socioeconómico, no es un criterio etario puro |
| P3 | **Contra-instancia** | *"Confirma que lo aplicaría también en primer ciclo (1° y 2°/3° grado)"* [línea 74] — para una estrategia de estudio en casa con un alumno con dificultades |
| P4 | **Contra-instancia explícita, formulada como principio general** | *"La incluiría también en primer ciclo, con algo simple... se puede sumar tranquilamente a cualquier tipo de planificación... independientemente del grado"* [línea 72] |
| P12 | **Adaptación diferenciada, no exclusión** | Con primer grado: trabajo "desenchufado" primero (dibujar a mano), luego animación de las figuras vía IA. Con grados mayores: curaduría de contenidos más directa (NotebookLM, Canva) [11:17-12:40] |

**Lectura:** 4 participantes (P1, P6, P9, P15) tienden hacia la exclusión o limitación de primer ciclo; **3 participantes (P3, P4, P12) rechazan esa lógica de forma explícita** — no niegan que haya que adaptar la actividad, pero sostienen que el ciclo no debería ser, por sí solo, un criterio de exclusión. P4 es la formulación más nítida de esta postura ("independientemente del grado"), y P12 aporta el ejemplo más elaborado de **cómo** se adapta sin excluir (trabajo desenchufado como puente hacia el uso de IA en primer grado).

**Nota sobre P6:** su instancia no es un criterio etario puro — mezcla "grados chicos" con "contextos vulnerables", dos variables que en su caso covarían pero que son conceptualmente distintas (edad vs. nivel socioeconómico/institucional). No forzar la lectura como si fuera solo sobre edad.

**Implicancia para el Capítulo 4/Discusión:** este es un hallazgo más interesante que un consenso uniforme — hay una **tensión real y explícita en el corpus** sobre si la edad es una barrera legítima o una excusa que oculta falta de estrategias de adaptación. Vale la pena presentarlo como tal (postura A vs. postura B, con sus argumentos respectivos), no colapsarlo en una sola tendencia.

## 2. `criterio_heterogeneidad_competencias_grupo` — 1/15, código genuinamente delgado por ahora

Solo **P14** aporta una instancia clara: *"Hay alumnos que pueden arrastrar muy bien bloques en las plataformas... y hay otros alumnos que no, entonces lograr que todos vayan a la par... lleva tiempo"* — diferencia de manejo técnico **dentro de un mismo grado**, no por ciclo.

No se encontraron instancias adicionales en la relectura de P3, P4, P6, P7, P8, P9, P12 — el código queda, por ahora, subdesarrollado (1/15). No se fuerza. Puede deberse a que el protocolo no indaga específicamente en esta dimensión (heterogeneidad intra-grupo es distinto de heterogeneidad entre grados/ciclos, y el guion no la separa explícitamente), o a que efectivamente es menos saliente en el discurso docente que la variable ciclo/edad. Cualquiera de las dos es un hallazgo válido a nombrar, no un error de codificación.

## 3. Tercera categoría identificada durante la relectura, ya cubierta por códigos existentes — no requiere código nuevo

Al revisar P7 y P8 (ambas listadas originalmente bajo `criterio_contextual_grupo`), sus instancias resultaron ser **adaptación a un estudiante individual específico** con dificultades de aprendizaje/integración — un objeto distinto tanto del ciclo como de la heterogeneidad grupal:
- P7: *"Darle el texto y que me lo adecue con palabras más sencillas"* para un alumno con dificultades de integración, buscando autonomía [09:47]
- P8: actividad adaptada para un alumno específico con dificultades [18:52]

Estas dos instancias ya estaban correctamente dobles-codificadas como `adaptacion_saberes_previos` (Núcleo 2) — no necesitan un código nuevo, pero **se recomienda retirarlas del conteo de `criterio_contextual_grupo`** en el Cap. 4, ya que no son ni ciclo ni heterogeneidad de grupo: son adaptación individual. Esto deja a `criterio_contextual_grupo` como código más limpio, o eventualmente candidato a ser reemplazado en el reporte final por sus tres componentes más específicos (ciclo, heterogeneidad grupal, adaptación individual) en vez de usarse como categoría paraguas.

---

## Síntesis para el Capítulo 4

Lo que aparecía como un único código (`criterio_contextual_grupo`, 10/15) en la matriz de patrones en realidad son **tres fenómenos distintos**, con densidades y lecturas propias:
1. **Ciclo/edad** (7/15, dividido 4 exclusión / 3 contra-instancia) — la variable más saliente y más controvertida del corpus.
2. **Heterogeneidad dentro del grupo** (1/15) — código delgado, a monitorear.
3. **Adaptación a un estudiante individual** (2/15: P7, P8) — ya cubierto por `adaptacion_saberes_previos`, no requiere código propio.

Recomiendo que el Cap. 4 (§4.4 de la matriz de patrones) presente estos tres por separado en vez de bajo el paraguas único de `criterio_contextual_grupo` — es más preciso y más interesante analíticamente, sobre todo por la tensión real que aparece en el punto 1.

---

## Actualización de tablas

- Excel: `Núcleo 5` (definiciones agregadas), `Log códigos inductivos` (2 filas nuevas), `Segmentos codificados` (instancias de ciclo/heterogeneidad agregadas).
- `matriz_patrones_capitulo4.md`, §4.4: actualizado, reemplaza el renglón único de `criterio_contextual_grupo` por el desglose en tres fenómenos.
