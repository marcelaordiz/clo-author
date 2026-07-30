# Entrevistas — carpeta local, fuera de git

Esta carpeta es para las transcripciones, audios y notas de campo de las 15 entrevistas. **Está excluida del control de versiones** (ver `.gitignore`, sección "Raw interview transcripts") porque contiene datos de participantes recolectados bajo consentimiento informado — no corresponde que viajen en el historial de un repositorio que puede compartirse o pushearse a GitHub.

Este `README.md` es la única excepción trackeada — existe solo para documentar la convención, no contiene datos.

## Convención sugerida de nombres (con IDs anonimizados, no nombres reales)

```
data/raw/entrevistas/
├── P1_transcripcion.txt
├── P2_transcripcion.txt
├── ...
└── P15_transcripcion.txt
```

Si preferís guardar los archivos con otro nombre (por ejemplo el nombre real de la docente, como venían originalmente), hacelo — igual quedan fuera de git — pero para cualquier análisis que se comparta o discuta (código, memos de codificación, ejemplos), usá siempre el identificador anonimizado (P1, P2, ...), nunca el nombre real, consistente con la convención de anonimización del proyecto (`domain-profile.md`, Field Conventions).

## Qué SÍ va a git

- El protocolo de entrevista (`data/raw/protocolo_entrevista_semiestructurada.md`) — es el instrumento, no dato de participante.
- Los codebooks, memos de codificación, y ejemplos anonimizados con fragmentos citados puntualmente (como `quality_reports/strategy/ia-generativa-docentes-primaria/ejemplo_codificacion_P2.md`) — citas breves con fines de ilustración metodológica, no transcripciones completas.

## Qué NO va a git

- Transcripciones completas.
- Audios/grabaciones.
- Notas de campo con datos identificatorios.
