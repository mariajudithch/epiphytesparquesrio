# Epiphytes Parques del Río 🌿

Dataset and analysis associated with the study:

**"Survival of vascular epiphytes established in urban environments: A case study in Medellín, Colombia"**  
Carmona-Higuita, M.J. & Benavides, A.M.  
*Actualidades Biológicas* (in press)

---

## 📌 Overview

This repository contains the dataset and (optionally) analysis workflows used to evaluate the **long-term survival of vascular epiphytes** established in urban trees in Medellín, Colombia.

The study monitored **310 individuals from 8 epiphyte taxa** across **50 host trees** in three urban parks within the *Parques del Río* ecological corridor over a **7-year period (2016–2023)**.

The primary goal is to provide **open, reproducible data** supporting research on:

- Urban biodiversity  
- Ex situ conservation  
- Epiphyte ecology  
- Green infrastructure design  

---

## 📊 Data description

The dataset includes:

- Species identity (epiphytes)
- Host tree characteristics
- Establishment variables:
  - Height (m)
  - Position on tree (trunk, branch, bifurcation)
  - Bark type (smooth / rough)
- Monitoring data across multiple time points:
  - Survival status
  - Growth indicators (leaves, roots)
  - Clonality
  - Phenology (flowering, fruiting)
  - Phytosanitary condition
- Cause of loss (when applicable):
  - Natural mortality
  - Anthropogenic removal
  - Disappearance (unknown cause)

---

## 📈 Methods summary

The study applied:

- Kaplan–Meier survival analysis  
- Cox proportional hazards models  
- Non-parametric tests (Kruskal–Wallis)  
- Correlation analyses (Spearman)

Analyses were conducted in **R** using packages such as:

- `survival`
- `survminer`
- `tidyverse`
- `coxme`
- `sandwich`

---

## 🌆 Study system

- **Location:** Medellín, Colombia  
- **Ecosystem:** Urban green infrastructure  
- **Sites:**
  - Parque Lineal El Refugio  
  - Parque Conquistadores  
  - Parque El Triángulo – Quebrada La Picacha  

Epiphytes were established between **2–8 m height** on urban trees as part of a biodiversity enrichment strategy.

---

## 🔑 Key findings (brief)

- Overall survival after 7 years: **32%**
- Strong differences among species
- **Establishment height increased survival**
- Host tree species was not a strong predictor
- Microhabitat and management conditions were critical

---

## 📂 Repository structure
├── data/ # Raw and/or cleaned datasets
├── scripts/ # R scripts for analysis (optional)
├── outputs/ # Figures, tables (optional)
└── README.md

---

---

## 📖 Citation

If you use this dataset, please cite:

> Carmona-Higuita, M.J. & Benavides, A.M. (in press).  
> Survival of vascular epiphytes established in urban environments:  
> A case study in Medellín, Colombia. *Actualidades Biológicas*.

---

## 📜 License

Specify your license here (recommended: MIT, CC-BY 4.0, or CC0 for data).

---

## 🤝 Acknowledgements

Field establishment and monitoring were conducted with the support of:

- Jardín Botánico de Medellín  
- Secretaría de Infraestructura Física de Medellín  
- Field and monitoring teams (2016–2023)

---

## 📬 Contact

**Maria Judith Carmona-Higuita**  
University of Marburg / Jardín Botánico de Medellín  
📧 judith.carmona@udea.edu.co; maria.carmonahiguita@biologie.uni-marburg.de

---
