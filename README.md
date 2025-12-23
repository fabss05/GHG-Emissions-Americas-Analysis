# GHG Emissions Analysis in the Americas (1990-2025)

![R](https://img.shields.io/badge/R-v4.3%2B-blue?logo=r&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Field](https://img.shields.io/badge/Field-Bioengineering-orange)

### Description
R pipeline for analyzing **1990–2025 GHG emissions** in the Americas using **EDGAR v8.0** data. 

The code evaluates the impact of the Paris Agreement (2015) by implementing data orchestration, K-means clustering for regional heterogeneity, and multivariate OLS regressions. Features include non-parametric testing, sectoral analysis, and 2030 inertial projections with 95% confidence intervals.

---

### 🚀 Key Features
* **Data Orchestration:** Automated processing of EDGAR v8.0 via `tidyverse`.
* **Statistical Rigor:** Shapiro-Wilk & Wilcoxon Rank Sum tests with Bonferroni adjustments.
* **Unsupervised Learning:** K-means clustering to classify regional trends.
* **Multivariate Modeling:** OLS regressions (GDP & Population control) to estimate policy effects.
* **Predictive Insights:** Inertial modeling to 2030 (95% CI).
* **Scientific Visualization:** Publication-quality graphics using `ggplot2`.

---

### 🛠️ Technical Requirements
* **Language:** R (v4.3+)
* **Key Packages:** `tidyverse`, `rstatix`, `broom`, `ggpubr`, `ggrepel`, `patchwork`

### 📂 Repository Structure
* `analysis_emissions_americas.R`: Main analytical pipeline.
* `/data`: Processed datasets derived from EDGAR.
* `/plots`: High-resolution figures (.png / 300 DPI).

---

### 📝 How to Use
1. Clone the repository:
   ```bash
   git clone [https://github.com/tu-usuario/GHG-Emissions-Americas-Analysis.git](https://github.com/tu-usuario/GHG-Emissions-Americas-Analysis.git)
2. Install dependencies in R:
   ```bash
   install.packages(c("tidyverse", "rstatix", "broom", "ggpubr", "ggrepel", "patchwork"))
3. Run the main script analysis_emissions_americas.R.

---

### 👨‍🔬 Author
* **Fabrizio Y. Flores-Huamán** | *Bioengineering Student* [![ORCID](https://img.shields.io/badge/ORCID-0009--0009--7530--6040-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0009-7530-6040) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fabrizio-yasuo-flores-huaman)

* **Nicolás Kcomt de la Torre** | *Bioengineering Student* [![ORCID](https://img.shields.io/badge/ORCID-0009--0001--8966--5345-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0001-8966-5345) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolas-sergio-kcomt-de-la-torre-a70a8a380)

* **Claudia Pérez Gronerth** | *Bioengineering Student* [![ORCID](https://img.shields.io/badge/ORCID-0009--0009--5038--0471-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0009-5038-0471) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/claudiasofiaperezgronerth)

* **Andrea Luksic Sirvas** | *Bioengineering Student* [![ORCID](https://img.shields.io/badge/ORCID-Profile-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrea-daniela-luksic-sirvas)

---

*Developed for academic research and reproducible science.*
