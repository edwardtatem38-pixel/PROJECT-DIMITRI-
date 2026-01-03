# 🧪 PROJECT DIMITRI: Chemical Informatics LLM

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardtatem38-pixel/PROJECT-DIMITRI-/blob/main/chemistry_llm_DIMITRI.ipynb)

## 🔬 Overview
Dimitri is a specialized "Hybrid Intelligence" dashboard. It combines the linguistic power of **Llama-3 8B** with the mathematical precision of the **RDKit Chemical Engine**. 

## 🛡️ PubChem-Certified Mode
This version includes a verification layer that cross-references all AI-generated reports with official NIH/PubChem data.
* **Accuracy:** Uses Molecular Weight fuzzy-matching (±0.1 g/mol) to prevent hallucinations.
* **Standardization:** Automatically canonicalizes SMILES strings for database consistency.
* **Hardware:** Optimized for stable execution on Virtual CPU/GPU environments.

## 🛠️ Setup
```bash
pip install -r requirements.txt
