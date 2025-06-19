# Logic Field Theory (LFT)

**Author:** JD Longmire  
**Project Status:** Active | Version: Stage 17 Complete  
**Paper:** *Logic Field Theory: Temporal Collapse Dynamics from Logical Strain*  
**Repository Type:** Research Framework & Simulation Suite  
**License:** MIT

---

## 🧠 Overview

Logic Field Theory (LFT) is a foundational framework that modifies quantum mechanics by introducing **logical strain** as the governing constraint on physical realization. It preserves the formalism of QM but replaces amplitude-based collapse assumptions with strain-dependent realizability. LFT predicts:

- **Temporal decay in measurement success**  
- **Null outcomes from logical overstrain**  
- **Platform-dependent realization behavior**

These predictions are falsifiable with current quantum computing platforms.

---

## 📄 Included Artifacts

### 🔬 Manuscript
[📄 Logic Field Theory: Temporal Collapse Dynamics from Logical Strain (PDF)](https://github.com/jdlongmire/Logic_Field_Theory_Gen13/blob/main/Logic_Field_Theory_Gen13.pdf) — Full academic paper outlining theory, derivation, predictions, and experiment plan.

### 🧪 Jupyter Notebooks (Simulations)
- `LFTG13_Stage5_Collapse_Simulation_Complete.ipynb`
- `LFTG13_Stage10_Refined_Collapse_Probability.ipynb`
- `LFTG13_Stage11_Collapse_Simulation.ipynb`
- `LFTG13_Stage13_Composite_Collapse.ipynb`
- `LFTG13_Stage14_W_State_Simulation.ipynb`
- `LFTG13_Stage15_Logical_Strain.ipynb`
- `G13S16LFT_Stage_16_Collapse_Probabilities.ipynb`
- `G13S17Stage17_Dynamic_Strain_LFT.ipynb`
- `LFT_G13_GHZ_Collapse_Simulation.ipynb`

### 📊 JSON Schema Artifacts
- `LFTG13_stage15_principled_values.json` — Empirical v_I, v_N, v_E values  
- `LFTG13_Math_Formalization_Stage_13.json` — Formal strain/collapse definitions  
- `lftG13_postulates_5_6_schema.json` — Collapse probability and threshold rules  
- `LFT_Full_Theory_Export_Stage16.json` — Postulates 1–6 and simulation summary

---

## 🧪 How to Run the Simulations

1. Install Python 3.9+ with the following packages:
    ```bash
    pip install numpy matplotlib networkx
    ```
2. Open any notebook in Jupyter Lab or VS Code.
3. Run all cells to generate predictions and compare LFT vs. QM behavior.

---

## 🔍 Reproducibility

All notebooks are designed to reproduce the figures and tables referenced in the paper. Parameter blocks allow easy tuning of:
- Logical strain coefficients (λ, μ)
- Temporal growth rate (γ)
- Collapse threshold (ε)
- Logical inverse temperature (β)

---

## 📈 Experimental Outlook

LFT’s predictions can be tested on IBM Q, Rigetti, or IonQ platforms using 3-qubit GHZ and W-states with temporal delay circuits.  
Simulated collapse time range: **50–100 µs**  
Target signature: **Exponential decay + null measurement events**

---

## 📬 Contact

For questions, contributions, or collaboration:
**JD Longmire**  
[bitbucket_username or email]

---

*Logic is not emergent. It is the constraint.*
