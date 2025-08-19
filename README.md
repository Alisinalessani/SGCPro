# SGCPro-Spectral-Analyze

**Rule-Boosted Spectral Galaxy Classifier (SGC-Pro)** for **SDSS** spectra.  
Classifies spectra into **AGN galaxies**, **star-forming galaxies**, **stars (G/K types)**, or **nebulae** using astrophysical rules and line-ratio diagnostics — **no ML**.

---

## Features
- Auto-retrieval of SDSS spectra with valid subclasses  
- Continuum removal & Savitzky–Golay smoothing  
- Redshift estimation via line matching  
- Emission/absorption line measurement  
- Rule-based classification (BPT-like diagnostics)  
- SGC code generation from emission-peak spacings  
- Evaluation: confusion matrix, precision, recall, F1  

---

## Installation
```bash
git clone https://github.com/Alisinalessani/SGCPro.git
cd SGCPro
pip install -r requirements.txt
