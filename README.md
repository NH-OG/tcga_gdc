# TCGA Clinical Parsing
Goal of this project is to extract key clinical information from the GDCs json dump.
Intial goals:
* Diagnoses, stage, diagnostic markers, biomarkers
* Survival time events
* Treatments given/durations

All directories exist in notehub environment, in the rahul-work notebook name. The specific project is called tcga_gdc.

You can find input json at `source-data/20180823_release_12.0.clean.json`.

Main parsing notebook - GDC Parsing.ipynb

Survival tests - Doxorubicin.ipynb, Test KM Plots.ipynb, TNBC Survival.ipynb
Drug annotations - Drug Parsing Nant API + Pubchem.ipynb
