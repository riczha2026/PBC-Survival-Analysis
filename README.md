# Primary Biliary Cholangitis (PBC) Survival Analysis

## 📌 Introduction

In today’s era of growing awareness around body positivity and personal health, understanding chronic and genetic illnesses has become increasingly important. One such illness is **Primary Biliary Cholangitis (PBC)** — a chronic, progressive autoimmune liver disease. Globally, PBC affects an estimated **1.76 to 14.60 individuals per 100,000 people**[^1], with significantly higher prevalence in the United States:
- **33.5 to 57.8 per 100,000 women**[^1]
- **7.7 to 15.4 per 100,000 men**[^1]

PBC is marked by inflammation and gradual destruction of bile ducts, which are essential for transporting bile from the liver. Without treatment, the disease can progress to **liver failure and ultimately death**. Due to its progressive nature and higher incidence in certain populations, gaining a deeper understanding of PBC progression is crucial for improving treatment outcomes and patient care.

## ❓ Research Question

This project leverages the **Mayo Clinic’s Primary Biliary Cholangitis dataset**, available in the `survival` package in R. The dataset includes clinical information from **418 patients** across **20 variables**, allowing for a robust statistical analysis of PBC progression.

### Core Research Question:

> **How effective is D-penicillamine in slowing the progression of primary biliary cholangitis (PBC), and what role do other clinical factors (e.g., cholesterol levels, histologic stage, etc.) play in influencing survival time in PBC patients?**

## 🎯 Objectives

- Evaluate the survival benefit of **D-penicillamine** in PBC patients.
- Identify significant **confounding variables** (e.g., bilirubin, albumin, histologic stage).
- Build **survival models** (e.g., Kaplan-Meier, Cox Proportional Hazards) to quantify impact of treatment and patient characteristics.
- Recommend **treatment insights** and areas for further clinical investigation.

## 📂 Dataset

- **Source**: Mayo Clinic
- **Availability**: `survival` package in R (`pbc` dataset)
- **Observations**: 418 patients
- **Variables**: 20 clinical and demographic variables including:
  - Age, Sex, Bilirubin, Albumin, Copper, Aspartate Aminotransferase, Prothrombin Time
  - Treatment group (D-penicillamine vs placebo)

## 🧪 Methodology

- Data exploration and preprocessing in **R**
- **Kaplan-Meier curves** to estimate survival probabilities
- **Cox proportional hazards models** to assess treatment effects and identify significant predictors
- Validation and diagnostics to ensure model robustness

## 📈 Expected Impact

This study aims to contribute to:
- A more nuanced understanding of how **treatment and biological factors** influence survival in PBC patients.
- Identification of **key prognostic markers** to guide clinicians in tailoring care.
- Improved patient **risk stratification and treatment planning**.

---

**Authors**: Richard Zhang, Randy Van Waes, Vincent Agrella  
**Course**: PSTAT 175 – Spring 2025  
**Institution**: UC Santa Barbara



[^1]:Trivella, J., John, B. V., & Levy, C. (2023). Primary biliary cholangitis: Epidemiology, prognosis, and treatment. Hepatology communications, 7(6), e0179. https://doi.org/10.1097/HC9.0000000000000179


