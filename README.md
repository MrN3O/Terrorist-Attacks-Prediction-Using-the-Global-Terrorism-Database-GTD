# Terrorist Attacks Prediction Using the Global Terrorism Database (GTD)

## Overview

This repository contains the implementation and data for the research paper titled **"Prediction of Terrorist Attacks throughout the Globe Using the Global Terrorism Database: A Comparative Analysis of Machine Learning Prediction Algorithms"** by Happy Manoj Yadav.

The study leverages the Global Terrorism Database (GTD) to develop predictive models for terrorist attacks worldwide, comparing various machine learning algorithms for accuracy and effectiveness.

**Paper Link:** [Prediction of Terrorist Attacks throughout the Globe Using the Global Terrorism Database](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003328414-26/prediction-terrorist-attacks-throughout-globe-using-global-terrorism-database-happy-manoj-yadav)

## Project Structure

### 01 GTD Dataset/
Contains preprocessed datasets derived from the Global Terrorism Database:
- `00 GTD_DF_FOR_ATTACK_OR_NOT_1.csv`: Initial dataset for attack prediction.
- `01 GTD_DF_FOR_ATTACK_OR_NOT_AND_MORE.csv`: Extended dataset with additional features.
- `02 GTD_DF_FOR_ATTACK_OR_NOT.csv`: Refined dataset for binary classification.
- `03 Final_GTD_After_All_Preprocessing_Steps.csv`: Final preprocessed dataset ready for modeling.

### 02 Orange_Models/
Orange data mining workflows for building and evaluating machine learning models:
- `00_Attack_or_not.ows`: Initial workflow for attack prediction.
- `00_GTD_DF_FOR_ATTACK_OR_NOT_1.csv` & `00_GTD_DF_FOR_ATTACK_OR_NOT_AND_MORE.csv`: Supporting data files.
- `01_Attack_or_Not_Final.ows`: Finalized workflow for attack classification.
- `02_Final_Predications.ows`: Workflow for generating predictions.
- `03_Models.ows`: Comparative analysis of different models.

### 03 Jupyter_Lab_Python_Code/
Jupyter notebooks containing Python code for data analysis, preprocessing, and prediction:
- `Analysis_&_Prediction_Code_ Analysis_Code.ipynb`: Analysis and prediction code.
- `Analysis_&_Prediction_Code_PreProcessing_Code.ipynb`: Data preprocessing steps.
- `Analysis_&_Prediction_Code.ipynb`: Main analysis notebook.
- `Combine_05-12-2021.ipynb`: Notebook combining results from 05-12-2021.
- `Final_GTD_After_All_Preprocessing_Steps.csv` & `GTD_DF_FOR_ATTACK_OR_NOT.csv`: Supporting data files.

### 04 Images/
Visualizations and images related to the analysis:
- `B&W/`: Black and white images.
- `COLOR/`: Color images.

### 05 GTD_Overleaf_Code/
LaTeX source code for the research paper:
- `conference_101719.tex`: Main LaTeX file for the conference paper.

### 06 Conference Proceeding/
Additional materials related to the conference proceeding.

## Methodology

The project involves:
1. **Data Preprocessing:** Cleaning and preparing the GTD data for modeling.
2. **Feature Engineering:** Selecting and transforming relevant features for prediction.
3. **Model Development:** Implementing and comparing machine learning algorithms (e.g., logistic regression, random forests, SVM, neural networks).
4. **Evaluation:** Assessing model performance using metrics like accuracy, precision, recall, and F1-score.
5. **Visualization:** Creating plots and charts to illustrate findings.

## Requirements

To run the code in this repository, you need:
- **Python 3.x**
- **Jupyter Notebook** or **JupyterLab**
- **Orange Data Mining** (for .ows workflows)
- Required Python libraries (install via `pip`):
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - (Check individual notebooks for additional dependencies)

Install Python packages using:
```
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. **Clone the Repository:**
   ```
   git clone https://github.com/MrN3O/Terrorist-Attacks-Prediction-Using-the-Global-Terrorism-Database-GTD.git
   cd Terrorist-Attacks-Prediction-Using-the-Global-Terrorism-Database-GTD
   ```

2. **Data Preprocessing:**
   - Open `03 Jupyter_Lab_Python_Code/Analysis_&_Prediction_Code_PreProcessing_Code.ipynb` in Jupyter.
   - Run the cells to preprocess the data.

3. **Analysis and Prediction:**
   - Use `03 Jupyter_Lab_Python_Code/Analysis_&_Prediction_Code.ipynb` for main analysis.
   - Execute the notebooks to train models and generate predictions.

4. **Orange Workflows:**
   - Install Orange from [orange.biolab.si](https://orange.biolab.si/).
   - Open the .ows files in `02 Orange_Models/` to visualize and run the workflows.

5. **Visualizations:**
   - Refer to images in `04 Images/` for pre-generated plots.

## Results

The comparative analysis evaluates multiple ML algorithms for predicting terrorist attacks. Key findings include performance metrics, feature importance, and global patterns in terrorism data. Refer to the paper for detailed results.

## Citation

If you use this code or data in your research, please cite the original paper:

```
Yadav, Happy Manoj. "Prediction of Terrorist Attacks throughout the Globe Using the Global Terrorism Database: A Comparative Analysis of Machine Learning Prediction Algorithms." In *Advances in Data Science and Analytics*, edited by M. N. Doja, N. Kumar, V. B. Singh, and D. Singh, CRC Press, 2023, pp. 267-278.
```

**DOI:** [10.1201/9781003328414-26](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003328414-26/prediction-terrorist-attacks-throughout-globe-using-global-terrorism-database-happy-manoj-yadav)

## Contributing

Contributions are welcome. Please open an issue or submit a pull request for improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. (Add a LICENSE file if needed.)

## Contact

For questions or collaborations, contact the author: Happy Manoj Yadav.