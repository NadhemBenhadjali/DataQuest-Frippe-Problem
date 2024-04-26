# Marka Brand Clothing Analysis Notebook

This repository contains a Jupyter notebook for analyzing clothing data with various features such as brand, price, formality, type of clothing, fabric thickness, garment length, garment width, and RGB color values. The data was used in a competition hosted on Kaggle and ranked 14th among participants.

## Dataset Description

The dataset consists of the following features:

- **Marka (Brand):** The brand of the clothing item.
- **Naw3 (Price):** The price of the clothing item.
- **Modhkhom (Formality):** Formality level of the clothing item (e.g., formal, casual).
- **9at3a (Type of Clothing):** Type of clothing (e.g., shirt, pants).
- **Khochn (Fabric Thickness):** Thickness of the fabric.
- **Toul (Garment Length):** Length of the garment.
- **3ordh (Garment Width):** Width of the garment.
- **R, G, B (Red, Green, Blue):** Color values of the clothing item.
- **soum (Estimated Price):** The estimated price derived from the data.

## Notebook Contents

The notebook includes the following sections:

1. **Data Exploration:** 
   - Summary statistics of the dataset.
   - Visualizations to understand the distribution of features.

2. **Preprocessing:**
   - Handling missing values.
   - Encoding categorical variables.
   - Feature scaling.

3. **Feature Engineering:**
   - Creating new features or transforming existing ones to improve model performance.

4. **Modeling:**
   - Implementing various machine learning models such as:
     - Regression models to predict price.
     - Classification models for formality level or type of clothing.
     - Clustering algorithms to group similar clothing items.
   - Hyperparameter tuning and model evaluation.

5. **Results Analysis:**
   - Evaluating model performance.
   - Interpreting feature importance.
   - Drawing insights from the results.

6. **Conclusion:**
   - Summary of findings.
   - Future work and potential improvements.

## Kaggle Competition Submission

The notebook was used to develop models for the [DataQuest Frippe Problem competition](https://www.kaggle.com/c/dataquest-frippe-problem) on Kaggle. It achieved a ranking of 14 among all participants.

## Dependencies

- Python 3
- Jupyter Notebook
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, etc.

## Usage

1. Clone the repository:

   ```
   git clone https://github.com/your-username/marka-brand-clothing-analysis.git
   ```

2. Navigate to the project directory:

   ```
   cd marka-brand-clothing-analysis
   ```

3. Open the Jupyter notebook:

   ```
   jupyter notebook marka_brand_clothing_analysis.ipynb
   ```

4. Follow the instructions in the notebook to execute each cell and analyze the data.

**Note:** This README serves as a guide to understand and utilize the notebook for analyzing the Marka Brand Clothing dataset. For detailed insights and code implementation, refer to the Jupyter notebook included in this repository.
