# Checkpoints

## M1 — Project Foundation

**Status:** Completed  
**Defect:** No  
**Milestone:** 1

### Work completed
- Created the Beamer presentation project in Overleaf.
- Established the presentation title, author, and institution.
- Added the background, problem statement, aim and objectives, and research questions.
- Added the study design and variable definitions.
- Defined the four observation periods.
- Created and embedded the synthetic library space utilisation dataset.
- Established 72 observations covering 6 days, 4 periods, and 3 study zones.
- Connected `main.tex` to `data.tex`.
- Compiled the project successfully in Overleaf.
- Downloaded the Overleaf project source and preserved the M1 source files in `milestone_1_base/`.

### Validation completed
- 72 observations confirmed.
- Six observation days and four periods confirmed.
- Three study zones confirmed.
- Zone capacities confirmed as Quiet = 40, General = 60, Group = 30.
- Occupied seats did not exceed zone capacity.
- Study duration values were within the 45–110 minute construction range.
- Satisfaction scores were within the 1–5 scale.
- Student entries were nonnegative whole numbers.
- The actual observed ranges were recorded as:
  - Occupied seats: 12–56
  - Average study duration: 45–108 minutes
  - Student entries: 8–56
  - Satisfaction score: 2.2–4.0

### Source
The M1 project was authored and compiled in Overleaf. The preserved source is stored in `milestone_1_base/`.

### Commands/checks used
- `grep` was used to confirm the 72 observations and day-period combinations.
- `awk` was used to validate capacities, study duration, satisfaction scores, student entries, and occupancy calculations.
- The overall mean occupancy rate calculated from the 72 observations was 71.59%.
- Mean occupancy by zone, period, and day was also calculated for later analysis.


## M2 — Literature and Data

**Status:** Completed  
**Defect:** No  
**Milestone:** 2

### Work completed
- Added a literature review focused on academic library space use and student study environments.
- Added a conceptual background connecting library space, study behaviour, utilisation, and student experience.
- Added five academic references to `project_source/references.bib`.
- Connected the bibliography to `main.tex` using `biblatex` and Biber.
- Added in-text citations to the literature and conceptual background slides.
- Added a dataset overview slide.
- Added a variables and data structure slide.
- Preserved the 72-observation synthetic dataset in `data.tex`.
- Compiled the updated Beamer presentation successfully in TeXStudio.

### M2 validation
- Bibliography processed successfully with Biber.
- In-text citations compiled successfully.
- Dataset remains fully embedded in the project.
- No planted defect was introduced.
- No decoy was introduced.

### Source
The M2 working source is stored in `project_source/`.



## M3 — Methodology and Analysis

**Status:** Completed
**Defect:** No
**Milestone:** 3

### Work completed
- Added the research design and methodology section.
- Added the statistical analysis approach and occupancy rate formula.
- Added overall descriptive statistics derived from the embedded 72-observation dataset.
- Added comparative analysis of study zones and observation periods.
- Added Pearson correlation results for the quantitative variables.
- Added `project_source/analysis.tex` as the internal analysis source containing the verified numerical results.
- Preserved the fully synthetic dataset in `project_source/data.tex`.
- Compiled the updated Beamer presentation successfully in TeXstudio.

### M3 validation
- The presentation compiled successfully after the M3 additions.
- Numerical results are based on the embedded 72-observation dataset.
- Correlation results are reported as associations, not causal effects.
- No planted defect was introduced.
- No decoy was introduced.

### Source
The M3 working source is stored in `project_source/`.
