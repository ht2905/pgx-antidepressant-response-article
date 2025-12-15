# 🧬 *CYP2D6* and *CYP2C19* Polymorphisms as Predictors of Antidepressant Response

**Precision Pharmacogenomics for Major Depressive Disorder (MDD)**

This repository contains the **Quarto** project and supporting files for an academic review paper submitted for the **Genetics (BT313IU)** course. The manuscript is formatted using the **Elsevier Quarto template** to ensure journal-style structure, citations, and figure handling.

> **PDF Preview:** A rendered PDF version of the final paper is included for quick reference without requiring local rendering.

---

## 🎯 Project Overview

This paper examines how genetic variation in the cytochrome P450 enzymes **CYP2D6** and **CYP2C19** influences antidepressant response, metabolism, treatment resistance, and clinical decision-making. Emphasis is placed on **pharmacogenomic (PGx) applications** for improving therapeutic outcomes in **Major Depressive Disorder (MDD)**.

**Key Details**

* **Topic:** Pharmacogenomics of *CYP2D6* and *CYP2C19* in Antidepressant Therapy
* **Course:** Genetics (BT313IU)
* **Authors:**
  Tran Quoc Hoang, Nguyen Hoang Thanh Ngan, Pham Gia Han,
  Pham Ngo Phuong Thao, Nguyen Hoang Tuong Vy, Nguyen Le Ngoc Vy
* **Instructor:** MSc. Hang T. Tong
* **Institution:** International University – VNU-HCM
* **Document Type:** Literature Review & PGx Analysis

### **Abstract Highlights**

* Variability in antidepressant efficacy linked to genetic polymorphisms
* Functional interpretation of metabolic phenotypes (UM, RM, NM, IM, PM)
* CPIC and DPWG guideline-driven drug selection and dose adjustment
* PGx applications in Treatment-Resistant Depression (TRD)
* Challenges: cost, training, multi-gene interpretation
* Future directions: EHR integration, automated CDS, polygenic risk scores

---

## 💻 Technical Environment

The manuscript is created using **Quarto** with **R (RStudio)** for reproducible rendering. The **Elsevier PDF template** ensures publication-style formatting.

### 📄 Main Files

* **Manuscript Source:** `pgx_antidepressants.qmd`
* **Figures:** `photos/` folder
* **LaTeX Header:** `preamble.tex`
* **Bibliography:** `bibliography.bib`

### 🖥 Recommended System Setup

* **OS:** Windows 11 / WSL2 Ubuntu 22.04
* **R Version:** ≥ 4.2
* **Key R Packages:** `knitr`, `rmarkdown`, `tinytex`, `yaml`, `ragg`

---

## ⚠️ Disclaimer

This README intentionally omits an explicit list of system-level packages and platform-specific build commands. Collaborators are expected to manage any required system dependencies appropriate to their environment. The project is reproducible at the R/Quarto level via `renv` and the steps below; however, rendering advanced outputs (e.g., PDF) can require additional system libraries or LaTeX, which are not documented here.

---

## 🛠 Installation Instructions

### 1️⃣ Restore R Project Environment

Inside R or RStudio:

```r
install.packages("renv")
renv::restore()
```

This automatically installs all packages used to build the manuscript, including LaTeX support via **tinytex**.

---

### 2️⃣ Install Quarto & Elsevier Template

1. **Install Quarto:**
   [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/)

   Verify installation:

   ```bash
   quarto check install
   ```

2. **Install Elsevier Journal Template:**

   ```bash
   quarto add quarto-journals/elsevier
   ```

---

### 3️⃣ Render the Manuscript

From the project root, run:

```bash
quarto render pgx_antidepressant_response_article.qmd
```

The output PDF will be placed in the same directory, automatically formatted with appropriate figures, references, and tables.

---

## 📚 Key Sections

1. **Introduction:**
   Precision medicine, PGx foundations, and the clinical challenge of MDD.

2. **Materials & Methods:**
   Literature search strategy and evidence synthesis.

3. **Discussion:**

   * **3.1 Genetics in Etiology & Diagnosis** — SNPs, CYP enzyme polymorphisms, phenotype classification
   * **3.2 Applications in Therapy** — Drug selection, dose adjustment, guidelines (CPIC/DPWG), TRD management
   * **3.3 Clinical Challenges & Future Directions** — Cost, training, multi-gene complexity, PRS, EHR integration

4. **Conclusion:**
   PGx testing as a validated, practical tool for personalized antidepressant therapy.

---

## 👥 Author Contributions

* **Tran Quoc Hoang:** Conceptualization, methodology, project administration, Quarto compilation, literature synthesis, Section 3.2 writing, revision
* **Nguyen Hoang Thanh Ngan:** Section 3.1 research & writing, manuscript editing
* **Pham Gia Han:** Sections 1 & 2 research & writing, methodology, editing
* **Pham Ngo Phuong Thao:** Section 3.3 writing, challenges/future directions research, editing
* **Nguyen Hoang Tuong Vy:** Data curation, visualization, slide preparation, editing
* **Nguyen Le Ngoc Vy:** Data curation, visualization, slide preparation, editing

---

## ⚖️ Declaration of Competing Interest

The authors declare **no competing interests**.

---

## 📂 Data & Code Availability

All source files for the manuscript, including figures, LaTeX header, and bibliography, are available at:

**[https://github.com/ht2905/pgx-antidepressant-response-article](https://github.com/ht2905/pgx-antidepressant-response-article)**

A rendered PDF is included in the repository for convenience.