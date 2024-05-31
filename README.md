# PorphyryAuML 🌍🔬

## Introduction
Welcome to the PorphyryAuML project! This repository is dedicated to exploring the mechanism of gold (Au) enrichment in porphyry systems within the Central Asian Orogenic Belt using machine learning. We apply models like XGBoost and Random Forest to analyze whole-rock geochemical data, aiming to classify porphyry deposit types and highlight key geochemical indicators.

## Key Features 🌟
- **Principal Component Analysis (PCA):** Reduce dimensionality to discover the most significant variables.
- **Machine Learning Models:** Utilize XGBoost and Random Forest for robust classification.
- **Feature Importance Analysis:** Identify crucial geochemical markers for Au presence and quantity.
- **Visualization:** Detailed plots to illustrate model outcomes and geochemical patterns.

## Getting Started 🚀
To get started with this project, follow these steps:
1. Clone the repository:
   ```
   git clone https://github.com/vectorzhao/PorphyryAuML.git
   ```
2. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the analysis notebook:
   ```
   jupyter notebook
   ```

## Data 📊

### DATA.xlsx
The `DATA.xlsx` file contains crucial geochemical data used in our analysis, organized across three sheets:

- **group1**: Represents the Cu-Au (Copper-Gold) porphyry deposits. This sheet contains all relevant geochemical markers and measurements specific to this group.
- **group2**: Corresponds to Cu(-Au±Mo) (Copper with minor Gold and possibly Molybdenum) porphyry deposits. It includes a detailed set of data focusing on the variations and characteristics of these mixed element deposits.
- **group3**: Contains data related to Cu-Mo (Copper-Molybdenum) porphyry deposits, focusing on the distinct geochemical profiles that typify these deposits.

Each sheet is named to reflect the group it represents and is vital for our machine learning analysis to classify and predict porphyry deposit types based on their geochemical properties.

## License 📜
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


Enjoy exploring and contributing to PorphyryAuML! 🌟
