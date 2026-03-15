# Minimal GEAGS Model in BioCRNpyler — Chapter Companion

This repository accompanies the chapter **Gene Expression Across Growth Stages (GEAGS): Modeling Circuit Dynamics in Batch Cultures** in **[BOOK/VOLUME — TBD]**. It provides a small, self-contained notebook demonstrating how to construct and run a minimal dual-scale gene-expression model in **BioCRNpyler**, using a tiny example dataset.

---

## Repository Structure

├─ building_dual_scale_model_bioCRNpyler_tutorial.ipynb   # Step-by-step tutorial <br>
├─ experimental_data.csv                                  # Example dataset used in the notebook <br>
└─ README.md                                              # You are here <br>

NOTE: Open the notebook first; it is self-contained and annotated. <br> <br>

Quick start <br> <br>
1) Create an environment (any one option) <br>

```
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install biocrnpyler=1.1.1 jupyter numpy pandas matplotlib scipy
```
or 

```
conda create -n dualscale python=3.11 -y
conda activate dualscale
pip install biocrnpyler=1.1.1 jupyter numpy pandas matplotlib scipy
```




