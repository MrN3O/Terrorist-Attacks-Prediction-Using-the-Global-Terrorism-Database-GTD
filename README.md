# Terrorist Attacks Prediction Using the Global Terrorism Database (GTD)

## Overview

This repository contains the implementation and data supporting the research paper **"Prediction of Terrorist Attacks over the Globe Using the Global Terrorism Database: A Comparative Analysis of Machine Learning Prediction Algorithms"** by Happy Manoj Yadav, published in *Artificial Intelligence and Knowledge Processing: Improved Decision-Making and Prediction* (Taylor & Francis Group, 2022).

The materials are provided for **academic and educational purposes**, including data preprocessing, feature engineering, model training, evaluation, and visualization.

## 📄 Publication & Copyright Notice

**Published Paper:**
- **Title:** Prediction of Terrorist Attacks over the Globe Using the Global Terrorism Database: A Comparative Analysis of Machine Learning Prediction Algorithms
- **Book:** Artificial Intelligence and Knowledge Processing: Improved Decision-Making and Prediction
- **Publisher:** Taylor & Francis Group (2022)
- **DOI:** [10.1201/9781003328414-26](https://doi.org/10.1201/9781003328414-26)
- **Publisher Link:** [Taylor & Francis](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003328414-26/prediction-terrorist-attacks-throughout-globe-using-global-terrorism-database-happy-manoj-yadav)

**Copyright Notice:**
The final published chapter is © Taylor & Francis Group and cannot be redistributed. This repository contains only supporting research materials (code, derived datasets, preprocessing scripts, notebooks, and images) for educational and reproducibility purposes. For the authoritative published chapter, please visit the publisher link above.

For copyright inquiries or takedown requests, please contact the repository owner via [GitHub Issues](https://github.com/MrN3O/Terrorist-Attacks-Prediction-Using-the-Global-Terrorism-Database-GTD/issues).

## 📚 Dataset Citation

The datasets in this repository are derived from the **Global Terrorism Database (GTD)** maintained by START (National Consortium for the Study of Terrorism and Responses to Terrorism) at the University of Maryland.

- **GTD Website:** https://www.start.umd.edu/gtd/
- **Terms of Use:** Follow START's licensing and citation requirements when using GTD data

**Important:** The GTD data are not public domain. Users must cite both the paper and the GTD dataset in publications.

## 📁 Repository Structure

```
├── 01 GTD Dataset/              # Preprocessed CSV datasets for modeling
├── 02 Orange_Models/            # Orange data mining workflows (.ows files)
├── 03 Jupyter_Lab_Python_Code/  # Jupyter notebooks for analysis and modeling
├── 04 Images/                   # Figures and visualizations from the paper
├── 05 Conference Proceeding/    # Conference materials (PDFs)
├── CITATION.cff                 # Citation metadata
├── CITATION.md                  # BibTeX citation information
├── requirements.txt             # Python dependencies
└── README.md                    # This file
```

## 🚀 Quick Start

### Prerequisites
- Python 3.7+
- Jupyter Notebook/JupyterLab
- Orange Data Mining (optional, for .ows workflows)

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/MrN3O/Terrorist-Attacks-Prediction-Using-the-Global-Terrorism-Database-GTD.git
cd Terrorist-Attacks-Prediction-Using-the-Global-Terrorism-Database-GTD
```

2. **Set up Python environment:**
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install --upgrade pip
pip install -r requirements.txt
```

Or install dependencies manually:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyterlab
```

3. **Launch Jupyter:**
```bash
jupyter lab
```

### Running the Analysis

1. **Preprocessing:** Open and run `03 Jupyter_Lab_Python_Code/Analysis_&_Prediction_Code_PreProcessing_Code.ipynb` to preprocess the GTD data.

2. **Main Analysis:** Run `03 Jupyter_Lab_Python_Code/Analysis_&_Prediction_Code.ipynb` to train models and generate predictions.

3. **Orange Workflows:** Install [Orange](https://orange.biolab.si/) and open the `.ows` files in `02 Orange_Models/` for visual modeling workflows.

## 📖 How to Cite

If you use this code or data in your research, please cite both the paper and the GTD dataset:

**Paper Citation:**
```bibtex
@incollection{yadav2022prediction,
  author = {Yadav, Happy Manoj},
  title = {Prediction of Terrorist Attacks over the Globe Using the Global Terrorism Database: A Comparative Analysis of Machine Learning Prediction Algorithms},
  booktitle = {Artificial Intelligence and Knowledge Processing: Improved Decision-Making and Prediction},
  publisher = {Taylor & Francis Group},
  year = {2022},
  doi = {10.1201/9781003328414-26},
  url = {https://www.taylorfrancis.com/chapters/edit/10.1201/9781003328414-26/prediction-terrorist-attacks-throughout-globe-using-global-terrorism-database-happy-manoj-yadav}
}
```

**GTD Dataset Citation:**
```bibtex
@misc{start_gtd,
  author = {{National Consortium for the Study of Terrorism and Responses to Terrorism (START)}},
  title = {Global Terrorism Database (GTD)},
  howpublished = {\url{https://www.start.umd.edu/gtd/}},
  note = {Accessed: 2025-11-09}
}
```

## 📝 License & Ethical Use

- The code in this repository is available for educational and research purposes.
- The GTD dataset is subject to START's terms of use.
- Use the data responsibly. Analyses relate to real-world violent events; avoid releasing sensitive or personally-identifiable information.
- The published chapter is © Taylor & Francis Group and subject to publisher copyright.

## 🤝 Contributing

Contributions and corrections are welcome! Please:
1. Open an issue for discussion
2. Submit pull requests with clear descriptions
3. Ensure notebooks remain runnable
4. Document any dependency changes

## 📧 Contact

For questions about reproducing the results or issues with the repository:
- Open a [GitHub Issue](https://github.com/MrN3O/Terrorist-Attacks-Prediction-Using-the-Global-Terrorism-Database-GTD/issues)
- Contact the repository owner via GitHub

---

**Note:** This repository provides supporting materials for academic research. For the official published chapter, please refer to the Taylor & Francis publisher link above.
