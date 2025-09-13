# 🌌 Phase-Field Fracture Demo (AT1/AT2) – FEniCS

This repository provides a simple demonstration of the **phase-field fracture model** (AT1 and AT2 formulations) implemented in the **open-source FEA library [FEniCS](https://fenicsproject.org/)**.  

The implementation is **general**, avoids the history energy formulation, and uses the **SNES nonlinear solver** to enforce **irreversibility constraints**.  
It is designed as a reference and learning tool for researchers interested in phase-field modeling of fracture using FEniCS.

---

## 📂 Repository Contents
- **`PFH.ipynb`** – Jupyter Notebook containing the Python/FEniCS implementation of the AT1/AT2 phase-field fracture model.  
- **`mesh.xml`** – Example mesh input file used in the notebook.  

---

## ▶️ Usage
1. Install [FEniCS](https://fenicsproject.org/download/) (via Docker, Conda, or Ubuntu PPA).  
2. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook PFH.ipynb
