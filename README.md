# 📊 Full Factorial ANOVA Analysis for Gelatin Extraction

## 🔬 Overview

This repository contains a Python-based statistical analysis for evaluating the effects of multiple factors on gelatin extraction using a **full factorial experimental design (2 × 3 × 3 × 2)**.

The analysis focuses on understanding how different processing conditions influence key physicochemical properties of gelatin.

---

## 🧪 Experimental Design

* **Design Type:** Full Factorial Design

* **Factors:**

  * Acid Type (2 levels): Acetic Acid, Hydrochloric Acid (HCl)
  * Temperature (3 levels): 60°C, 70°C, 80°C
  * Time (3 levels): 4, 6, 8 hours
  * Breed (2 levels): Crossbred, Indigenous

* **Total Treatment Combinations:** 36

---

## 📈 Response Variables

The following quality parameters are analyzed:

* Yield (%)
* Moisture (%)
* Ash (%)
* Protein (%)
* Lipid (%)

---

## ⚙️ Features of the Analysis

This script performs:

### ✅ Descriptive Statistics

* Mean and standard deviation for each factor level

### ✅ ANOVA Analysis

* One-way ANOVA (main effects)
* Two-way interactions
* Three-way interactions
* **Full 4-way ANOVA (Type III Sum of Squares using statsmodels)**

### ✅ Post-hoc Testing

* Tukey HSD test for pairwise comparisons

### ✅ Summary Tables

* Marginal means
* Final ANOVA table (ready for manuscript use)

---

## 🧰 Requirements

Install the required Python packages:

```bash
pip install pandas numpy scipy statsmodels
```

---

## ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Navigate to the project directory:

```bash
cd your-repo-name
```

3. Run the script:

```bash
python your_script_name.py
```

---

## 📂 Data Structure

The dataset is embedded within the script as a structured list:

```
Acid, Temperature, Time, Breed, Yield, Moisture, Ash, Protein, Lipid
```

Each row represents one treatment combination.

---

## 📊 Output

The script generates:

* Console-based statistical summaries
* ANOVA tables (F-values, p-values, significance levels)
* Tukey HSD comparison results
* Publication-ready summary outputs

---

## 📌 Key Notes

* The **4-way ANOVA (statsmodels)** provides the most statistically accurate results.
* One-way ANOVA sections are used for simplified interpretation of effects.
* Significance levels:

  * *** p < 0.001
  * ** p < 0.01
  * * p < 0.05
  * ns = not significant

---

## 📖 Application

This analysis is useful for:

* Food science research
* Gelatin extraction optimization
* Experimental design and statistical modeling
* Academic publications

---

## ⚠️ Disclaimer

* Ensure correct installation of dependencies before running the script.
* Modify the dataset section to use your own experimental data if needed.

---

## 👨‍🔬 Author

Iqbal Hossain
Researcher | Food Science & Data Analysis

---

## 📜 License

This project is open-source and available for academic and research use.

---

## ⭐ Acknowledgment

If you find this repository helpful, consider giving it a ⭐ on GitHub!
