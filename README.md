# Short-Course (4-month) Tuberculosis Treatment Completion in Sub-Saharan Africa

## Overview
A world-class, multi-persona reviewed meta-analysis estimating the pooled completion proportion of short-course TB regimens in SSA.

## Methodological Upgrades
Following a Multi-Persona Review (Statistical Methodologist, Clinical Domain Expert, Editorial Reviewer), this repository was upgraded to "world class" standards:
- **Statistical rigor**: Shifted to **Logit Transformed Proportions (PLO)** using `metafor::escalc`.
- **Small-k corrections**: Implemented the **Knapp-Hartung adjustment** (`test="knha"`).
- **Sensitivity analysis**: Included a leave-one-out sensitivity analysis.
- **Visualizations**: Added a funnel plot for publication bias and improved the forest plot layout.
- **Clinical terminology**: Updated E156 text to use non-stigmatizing language.

## Quick Start
Run the analysis in R:
```bash
cd code
Rscript meta_analysis.R
```