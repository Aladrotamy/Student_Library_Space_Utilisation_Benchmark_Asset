# Asset Metadata

## Asset
Student Library Space Utilisation Benchmark Asset

## Owner
Rotimi Alade

## Domain
Overleaf / LaTeX

## Project
Analysing University Library Space Utilisation and Student Study Patterns

## Format
Beamer academic defense presentation

## Data
Fully synthetic and self-contained.

The project contains 72 observations covering six days, four observation
periods, and three library study zones.

## Planted defects
One deliberate Beamer/LaTeX defect is planted in the current project state.

The defect changes the closing command of the Conclusion frame from
`\end{frame}` to `\end{fram}`, causing Beamer compilation to fail.

The correct version is preserved in the preceding M4 results checkpoint,
the M5 final snapshot, and the golden output.

## Decoys
The project contains an unused supplementary file:

`project_source/archived_library_notes.tex`

The file contains plausible archived notes about library space features
such as seating layout, lighting, charging points, and noise levels. It is
not referenced by `main.tex` and is not part of the current analysis.

## Room to vary
Future benchmark tasks may vary the presentation content, analysis,
formatting, chart presentation, references, or Beamer structure while
retaining the embedded dataset and core research context.

## Final asset status
The correct project version was completed and compiled successfully before
the deliberate defect was planted.

The benchmark package includes milestone snapshots, the planted-defect
state, requirements, documentation, and a verified 22-page golden output.
