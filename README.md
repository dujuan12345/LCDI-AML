# LCDI-AML
Analysis code for the LCDI AML study.
# LCDI AML Analysis Code

Analysis code supporting the LCDI AML study (manuscript version v42).

## Download

Download and extract `LCDI_AML_Ordered_Code_v42_20261008_v2.zip`.
The archive contains 117 code files and a README with module order,
input requirements and workspace preparation instructions.

## Analysis workflow

The numbered folders cover gene screening, cohort preparation and LCDI modeling,
survival validation, clinical incremental value, age and expression analyses,
bulk mechanisms, single-cell states, trajectories and transcription factor activity,
virtual perturbation, qPCR, robustness analyses and figure generation.

Start with `01_Gene_screening/01_screen_target_genes.R` for target-gene screening.
It performs differential expression analysis, univariable Cox regression,
coexpression analysis, LASSO selection, candidate prioritization and survival plots.

## Requirements and use

Read the README inside the archive before running any code.
Required datasets and cached analysis objects are not included.
Software dependencies and input/output paths must be configured for the selected module.

The code has undergone static syntax and file-integrity checks.
A complete end-to-end run on another machine has not been validated.
