# 🧪 Prenatal Chemical Exposure Analysis
## Non-Targeted Small Molecule Analysis

A research project investigating prenatal chemical exposures and their 
associations with pregnancy health outcomes using non-targeted 
mass spectrometry-based metabolomics.

---

## 📋 Project Overview

This project applies non-targeted analysis workflows to identify and 
characterise small molecules detected in prenatal samples. The analysis 
pipeline covers feature detection, spectral database matching, 
calibration curve development, and demographic association analysis 
to understand how chemical exposures during pregnancy relate to 
maternal and fetal health outcomes.

---

## 📁 Notebooks

| Notebook | Description |
|---|---|
| `EIC_for_targetedmsms.ipynb` | Extracted ion chromatogram (EIC) generation for targeted MS/MS confirmation of candidate compounds |
| `Spectrum_database_extract_msmsspectrum_QAcompounds.ipynb` | Extracts MS/MS spectra from the spectral database for QA compounds used in method validation |
| `QACs_calibration_curve_development.ipynb` | Develops and evaluates calibration curves for quantitative assessment of QA compounds |
| `features_demographic_analysis_revision.ipynb` | Revised association analysis between detected chemical features and participant demographic variables |
| `demographic_analysis_second_batch_forQAcompounds.ipynb` | Demographic association analysis for the second sample batch, focused on QA compounds |

---

## 🔬 Analysis Pipeline
Raw MS Data
│
▼
EIC Generation & MS/MS Confirmation
(EIC_for_targetedmsms)
│
▼
Spectral Database Extraction
(Spectrum_database_extract_msmsspectrum_QAcompounds)
│
▼
Feature-to-Spectrum Matching
(Spectrum_database_matching_for_all_matched_features)
│
▼
Calibration Curve Development
(QACs_calibration_curve_development)
│
▼
Demographic & Health Association Analysis
(features_demographic_analysis_revision)
(demographic_analysis_second_batch_forQAcompounds)

---

## 🛠️ Requirements

**Python 3.8 or later**

dependencies:
Core libraries used across notebooks:
| Library | Purpose |
|---|---|
| `pandas` | Data manipulation and analysis |
| `numpy` | Numerical computing |
| `matplotlib` | Plotting and visualisation |
| `scipy` | Statistical analysis |
| `sklearn` | Machine learning and preprocessing |
| `matchms` | Mass spectrometry spectral matching |
| `jupyter` | Running the notebooks |

---

## 👩‍🔬 Author

**YANG JUNJIE**
Program on Reproductive Health and the Environment, University of California San Francisco
yangjunjie0531@gmail.com

---

## 📄 Citation

If you use this code in your research, please cite:.

---

## 📬 Contact

For questions about the analysis pipeline or data access, 
please open a GitHub Issue or contact yangjunjie0531@gmail.com.