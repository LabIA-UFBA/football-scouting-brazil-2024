# Unified Scouting Repository --- Brazilian Championship 2024

## 🗺️ Overview

This repository consolidates **all code, data, notebooks, dashboards,
and supplementary results** from a project related to
football scouting in the **2024 Brazilian Championship**.

It includes: - The full **interactive Streamlit scouting dashboard** for
identifying high‑performance, low‑cost players ("good and cheap"); - The
**original statistical analysis notebook**, datasets, and machine
learning experiments; - The **supplementary results** used in the
academic paper *"Artificial Intelligence in Football Scouting:
Systematic Literature Review and Application with Unsupervised Machine
Learning"*.

More details about the content, structure, and usage are found in the
folders of this repository.

------------------------------------------------------------------------

## 🗂️ Repository structure

The organization of this repository is:

> -   **dashboard/** : Streamlit application for interactive scouting\
> -   **notebooks/** : original exploratory, statistical analysis,
>     preprocessing, feature engineering, and modeling
>     (`.ipynb`)\
> -   **supplementary_results/** : supplementary tables, figures, and extended outputs
>     used in the paper\

------------------------------------------------------------------------

## ⚽ Scouting Dataset & Methodology

### Summary of Included Components

-   **Player performance metrics** collected from FBref\
-   **Market value data** collected from Transfermarkt\
-   **Custom feature engineering** for each position (FW, MF, DF, GK)\
-   **Unsupervised learning methods**:
    -   DBSCAN\
    -   Isolation Forest\
    -   Local Outlier Factor\
    -   One‑Class SVM\
-   **Performance and cost‑benefit scoring system**\
-   **Identification of positive outliers** ("good and cheap" players)

These resources enable analysts, researchers, and clubs to explore: -
Statistical patterns\
- Clustering behavior\
- Market inefficiencies\
- Player scouting recommendations

------------------------------------------------------------------------

## 📝 Citation

If this repository contributes to your research or analysis, please cite
the associated academic work:

``` latex
@dataset{ScoutingBrazil2024,
  author       = {Guilherme Fontes and Ricardo Rios},
  title        = {Unified Scouting Repository --- Brazilian Championship 2024},
  year         = {2025},
  publisher    = {Federal University of Bahia (UFBA)},
}
```

------------------------------------------------------------------------

## 📃 License

This project is licensed under the **MIT License**.
