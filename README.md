 # Student Library Space Utilisation Benchmark Asset

## Overview

This is an OSWorld V2 Domain Asset for the Overleaf/LaTeX domain.

The asset contains a Beamer academic defense presentation titled:

**Analysing University Library Space Utilisation and Student Study Patterns**

The project uses a fully synthetic, self-contained dataset to analyse patterns in university library study-space utilisation.

## Research Project

The presentation is authored in Overleaf using LaTeX Beamer.

The project examines:

- Occupancy rates
- Study zone utilisation
- Time-period utilisation
- Day-level utilisation
- Average study duration
- Student entries
- Student satisfaction
- Relationships among selected variables

The analysis uses descriptive, comparative, and correlation methods rather than multiple linear regression.

## Dataset

The dataset contains 72 observations.

Each observation represents:

**one study zone × one observation period × one day**

The observation period covers a hypothetical Monday-to-Saturday week.

### Study zones

- Quiet Study Zone: 40 seats
- General Study Zone: 60 seats
- Group Study Zone: 30 seats

### Observation periods

- P1: 8:00–10:00 AM
- P2: 10:00 AM–12:00 PM
- P3: 2:00–4:00 PM
- P4: 4:00–6:00 PM

The raw observations are embedded in `project_source/data.tex`.

## Data Traceability

The embedded raw dataset is the source of truth for the analysis.

Derived statistics, tables, and charts are calculated from the embedded observations rather than manually invented or entered as unrelated values.

The occupancy rate is derived as:

Occupancy Rate = (Occupied Seats / Capacity) × 100

## Literature and References

The presentation contains an academic literature review and in-text citations supported by five references stored in `project_source/references.bib`.

## Benchmark Structure

```text
Student_Library_Space_Utilisation_Benchmark_Asset/
├── requirements.pdf
├── README.md
├── CHECKPOINTS.md
├── ASSET.md
├── assets/
├── project_source/
├── milestone_1_base/
├── milestone_2_literature/
├── milestone_3_methodology/
├── milestone_4_results/
├── milestone_5_final/
└── golden_output/