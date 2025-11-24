# 📄 Activity 14 — Data Wrangling, Visualization, and Reflection
### README File  
Author: **Amogh Krishna Namuduri**  
Date: **11/16/2027**

---

## 📌 Overview

This repository contains all files necessary to render and view the Quarto document:

- **`Activity#14.qmd`** — Main Quarto file for data wrangling, visualization, and reflection  
- **`Activity#14 QMD File.pdf`** — PDF output of the QMD file  
- **`US_Armed_Forces_(6_2025).xlsx`** — Dataset used in the analysis  

The QMD performs three main tasks:

1. **Data Wrangling:**  
   - Loads the *U.S. Armed Forces* dataset  
   - Cleans column names  
   - Performs wide-to-long reshaping using `pivot_longer()`  
   - Creates a clean frequency-style summary table

2. **Visualization:**
   - Table shows the reshaped data in the columns of Pay Grade, Branch, Gender and Count
   - Popularity trends of the baby names *Michael* and *Emily*  
   - Plot of a mathematical function representing box volume

4. **Reflection:**  
   - A written reflection about reproducibility and learning outcomes

---

## 📁 Repository Structure

```
├── Activity#14.qmd                 # Main Quarto file (PDF rendering)
├── Activity#14 QMD File.pdf       # PDF version of the QMD
├── US_Armed_Forces_(6_2025).xlsx # Dataset used in the QMD
├── README.md                      # Documentation file (this file)
```

---

## ♻️ Reproducibility Requirements

### ✔ All required files are included
This repo contains:

- The QMD file  
- The PDF version of the QMD  
- The Excel dataset  

No external or missing dependencies are required.

---

### ✔ Relative File Paths Used
The QMD uses:

```r
read_excel("US_Armed_Forces_(6_2025).xlsx", skip = 1)
```

This code runs on any machine as long as the dataset is in the same folder as the `.qmd` file.

---

### ✔ Documentation of External Resources
The QMD includes a comment explaining where the dataset can be accessed publicly:

```r
# This file can be accessed on
# "https://docs.google.com/spreadsheets/d/1cn4i0-ymB1ZytWXCwsJiq6fZ9PhGLUvbMBHlzqG4bwo/edit?usp=sharing"
```

This is how to access the file if it is not locally available.

---

## 📦 Required R Packages

The following packages are used in the analysis:

- **tidyverse**
- **janitor**
- **readxl**
- **ggplot2**
- **babynames**

Install them with:

```r
install.packages(c("tidyverse", "janitor", "readxl", "ggplot2", "babynames"))
```

---

## ▶️ How to Render the QMD

To generate the PDF from the QMD:

1. Install **Quarto**  
   https://quarto.org/docs/get-started/

2. Ensure you have a working LaTeX installation (TinyTeX recommended):

```r
tinytex::install_tinytex()
```

3. Render the document:

```bash
quarto render activity14.qmd
```

This will produce:  
**`Activity#14 QMD File.pdf`**

> The PDF version is already included in the repo for convenience.

---

## 🧪 Notes on Reproducibility

This project adheres to the principles of reproducible analysis:

- Uses **relative paths**
- All required files are **in the repo**
- Code is broken into **clear, documented chunks**
- External resources are **properly noted**
- No hidden data or local-only resources are required

---

## 📬 Contact

If you have questions about the analysis or file structure, please contact:

**Amogh Krishna Namuduri**
- amogh@psu.edu
- amoghnamuduri@gmail.com
