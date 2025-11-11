# fmri-aud-pipeline
Dynamic Brain State Heritability and Disruption in Alcohol Use Disorder 

# fMRI Preprocessing Pipeline for AUD Twin Study  
**National Brain Research Center (NBRC), Haryana, India | Sep 2025 – Present**

> **Investigating genetic heritability of dynamic brain state disruptions in Alcohol Use Disorder (AUD)** using resting-state fMRI (rs-fMRI) from **120 monozygotic/dizygotic twin pairs**.

---

## Pipeline Overview

End-to-end **neuroimaging data processing pipeline** built with **ConnToolbox**, **TbCaps**, **Python**, and **MATLAB**:

1. **Artifact Correction & Motion Reduction**  
   → Reduced motion artifacts by **64%** using ICA-based denoising  
2. **Independent Component Analysis (ICA)**  
   → Extracted **64 high-fidelity Intrinsic Connectivity Networks (ICNs)**  
3. **Co-Activation Pattern (CAP) Clustering**  
   → K-means clustering to identify recurrent brain states  
   → Derived temporal metrics:  
   - **Fractional Occupancy (FO)**  
   - **Mean Dwell Time (MDT)**  
   - **Appearance Rate (AR)**  
4. **Statistical Validation**  
   → **p < 0.05**: Dynamic brain state metrics show **strong genetic influence** in AUD  
   → Replicated across twin cohorts

---

## Tools & Technologies

| Category         | Tools |
|------------------|-------|
| **fMRI Preprocessing** | ConnToolbox, FSL, AFNI |
| **Dynamic State Analysis** | TbCaps |
| **Behavioral Tasks** | Psychopy |
| **Scripting** | Python (NumPy, Nilearn), MATLAB |

---

## Key Findings (Reproducible)

- Dynamic connectivity metrics exhibit **significant heritability** in AUD  
- **Manuscript in preparation** for *NeuroImage*  
- **Tool demo accepted** at **ISMRM 2026**

---

## Repository Structure

