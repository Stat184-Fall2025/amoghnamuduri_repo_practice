# Activity 14: Project and Repo Plan Document

**Author:** Amogh Krishna Namuduri  
**Date:** 11/16/2027

---

## 1. Project Plan

### Goal(s)
- Perform comprehensive **data wrangling** on the U.S. Armed Forces dataset.
- Create meaningful **visualizations** to understand trends (e.g., baby names popularity, volume function plot).
- Develop a **reflective report** documenting the learning process and reproducibility steps.
- Produce a fully **reproducible analysis** that can be executed by others.

### Needs
- The **Armed Forces dataset** (`US_Armed_Forces_(6_2025).xlsx`).
- Access to **Quarto** for rendering `.qmd` files to PDF.
- R packages: `tidyverse`, `janitor`, `readxl`, `ggplot2`, `babynames`.
- Understanding of **data wrangling functions** (`pivot_longer`, `clean_names`) and **visualization techniques** (line plots, mathematical functions).

### Steps
1. **Load the dataset** and inspect the structure and headers.
2. **Clean column names** using `janitor::clean_names()` and manually rename where necessary.
3. **Reshape data** from wide to long format using `pivot_longer()`.
4. **Filter and convert data** to ensure numeric values only, removing NA values.
5. **Create a frequency-style table** for Pay Grade × Branch × Gender.
6. **Visualize trends** for Michael and Emily using `babynames` dataset.
7. **Plot mathematical function** for box volume.
8. **Write reflection** summarizing learning and reproducibility considerations.
9. **Test the QMD file** to ensure it runs on a fresh system with all relative paths working.

---

## 2. Repository Setup and Maintenance Plan

### Goal(s)
- Create a well-organized repository for Activity 14.
- Ensure all files required to run the QMD and generate outputs are included.
- Maintain clarity and accessibility for anyone viewing or using the repo.

### Needs
- Folder structure with clearly named files:
  - `activity14.qmd`
  - `US_Armed_Forces_(6_2025).xlsx`
  - `Activity#14 QMD File.pdf`
  - `README.md`
  - `Plan Document` (this file)
- Consistent **relative file paths** for all resources.
- Version control to track changes in scripts and analysis.

### Steps
1. **Create repo structure** with main folder and subfolders (if necessary).
2. **Add all required files** to the repository.
3. **Ensure relative paths** are used in the QMD file for dataset access.
4. **Document the project** with a README and plan document.
5. **Check reproducibility** by cloning the repo on a fresh system and rendering the QMD.
6. **Commit changes** regularly with descriptive messages.
7. **Maintain the repo** by updating files, reflecting on improvements, and ensuring compatibility with newer versions of R packages.

---

**End**

