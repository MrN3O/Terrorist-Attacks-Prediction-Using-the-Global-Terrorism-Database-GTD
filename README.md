[...existing code...]
# Terrorist Attacks Prediction Using the Global Terrorism Database (GTD)

## Overview

This repository contains the implementation and data supporting the study "Prediction of Terrorist Attacks throughout the Globe Using the Global Terrorism Database: A Comparative Analysis of Machine Learning Prediction Algorithms" by Happy Manoj Yadav.

The code and data here were prepared to reproduce and extend the analyses in the paper (data preprocessing, feature engineering, model training and evaluation, and visualization).

## 🧾 Paper Notice

This repository contains the supporting code, data, and experimental setup for the following publication:

- 📖 Title: Prediction of Terrorist Attacks over the Globe Using the Global Terrorism Database: A Comparative Analysis of Machine Learning Prediction Algorithms
- 📚 In: Artificial Intelligence and Knowledge Processing: Improved Decision-Making and Prediction
- ✍️ Authors: Happy Manoj Yadav
- 🏢 Publisher: Taylor & Francis Group
- 🔗 Official Publication: Available via Taylor & Francis (see publisher page below)

Note:
The final published version (camera-ready chapter) is © Taylor & Francis Group and cannot be redistributed here or elsewhere. Please refer to the official publisher link for access to the complete text.

This repository only includes original research materials (code, derived datasets, preprocessing scripts, and non-copyrighted content) used to support the study. If you require the final published chapter, figures from the publisher, or the camera-ready manuscript, please visit the official published paper website:

Publisher page: https://www.taylorfrancis.com/chapters/edit/10.1201/9781003328414-26/prediction-terrorist-attacks-throughout-globe-using-global-terrorism-database-happy-manoj-yadav

Please cite the published chapter and the Global Terrorism Database (GTD) when you use material from this repository (see the Citation sections below).

## Essential References (please cite when used)

- Paper (preferred citation and link):

  Yadav, Happy Manoj. "Prediction of Terrorist Attacks throughout the Globe Using the Global Terrorism Database: A Comparative Analysis of Machine Learning Prediction Algorithms." In *Advances in Data Science and Analytics*, CRC Press, 2023, pp. 267–278.

  DOI / Chapter: https://doi.org/10.1201/9781003328414-26

  Publisher page: https://www.taylorfrancis.com/chapters/edit/10.1201/9781003328414-26/prediction-terrorist-attacks-throughout-globe-using-global-terrorism-database-happy-manoj-yadav

- Dataset (Global Terrorism Database, GTD):

  The datasets used in this repository are derived from the Global Terrorism Database (GTD) maintained by the National Consortium for the Study of Terrorism and Responses to Terrorism (START) at the University of Maryland. Please consult START's site for licensing, citation, and access terms.

  GTD home: https://www.start.umd.edu/gtd/

  Data access and terms: https://www.start.umd.edu/gtd/

Important: If you reuse this repository, please cite both the paper above and the GTD dataset per START's citation instructions. The GTD data are not public domain; users must follow START's terms and acknowledge the data source in publications.

## Project structure (short)

- `01 GTD Dataset/` — preprocessed CSVs used for modeling (see filenames).
- `02 Orange_Models/` — Orange workflows (.ows) used for exploratory modeling.
- `03 Jupyter_Lab_Python_Code/` — notebooks for preprocessing, analysis, and model training.
- `04 Images/` — figures and visual outputs used in the paper.
- `05 GTD_Overleaf_Code/` — LaTeX source and figures for the paper.
- `06 Conference Proceeding/` — conference materials (PDFs).

## Quick start (recommended)

1. Clone the repo:

```powershell
git clone https://github.com/MrN3O/Terrorist-Attacks-Prediction-Using-the-Global-Terrorism-Database-GTD.git
cd "Terrorist-Attacks-Prediction-Using-the-Global-Terrorism-Database-GTD"
```

2. Prepare environment (recommended using virtualenv or conda):

```powershell
python -m venv .venv; .\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install pandas numpy scikit-learn matplotlib seaborn jupyterlab
```

3. Open the preprocessing notebook and run cells to regenerate the preprocessed CSVs (if you wish to reproduce preprocessing):

 - `03 Jupyter_Lab_Python_Code/Analysis_&_Prediction_Code_PreProcessing_Code.ipynb`

4. Run the main analysis notebook to train and evaluate models:

 - `03 Jupyter_Lab_Python_Code/Analysis_&_Prediction_Code.ipynb`

Notes:

- Some notebooks assume the preprocessed CSVs in `01 GTD Dataset/`. If you re-run preprocessing, confirm paths in the notebooks.
- The .ows Orange workflows can be opened in Orange (https://orange.biolab.si/).

## Reproducibility & large files

- This repository includes dataset CSVs and image files. If repository size becomes large, consider using Git LFS for large CSVs or binary files. If you fork or mirror this repo, be mindful of the GTD terms of use before redistributing raw GTD extracts.

## Licensing & ethical use

- The code in this repository is provided under the MIT license unless otherwise indicated (please add a `LICENSE` file if you need a formal license). The GTD dataset is provided by START — follow their terms.
- Use the data responsibly. Analyses relate to real-world violent events; avoid releasing sensitive or personally-identifiable information.

## Educational use & copyright

- This repository shares supporting materials (code, derived datasets, preprocessing scripts, notebooks, and images) for educational and reproducibility purposes only. It does not contain the final camera-ready chapter or any publisher-owned copyrighted material from Taylor & Francis.
- The final published chapter is © Taylor & Francis Group. For the authoritative (final) version of the chapter, full text, or any publisher-owned figures or tables, please consult the official publisher page: https://www.taylorfrancis.com/chapters/edit/10.1201/9781003328414-26/prediction-terrorist-attacks-throughout-globe-using-global-terrorism-database-happy-manoj-yadav
- If Taylor & Francis or any rights-holder contacts you regarding copyright claims about the published chapter, or requests takedown of publisher-owned content, please note that the published chapter is held under publisher copyright. For inquiries or takedown requests related to materials hosted in this repository (code, derived data, or other non-publisher content), please contact the repository owner via GitHub issues or their GitHub profile (https://github.com/MrN3O). If you are the copyright holder or a publisher representative and believe that this repository hosts infringing material, open an issue or email the repository owner so we can promptly address the concern.

- If you are the author or a representative of Taylor & Francis and want specific language added or require formal notices, please contact the repository owner and we will work to accommodate the request.

## How to cite

If you use code or data from this repository in publications or reports, please include both citations:

1. The paper (Yadav, Happy Manoj) — DOI link above.
2. Global Terrorism Database (START, University of Maryland) — cite per https://www.start.umd.edu/gtd/

Example citation text:

"We used the Global Terrorism Database (START, University of Maryland) and replicated the experiments from Yadav (2023), 'Prediction of Terrorist Attacks throughout the Globe Using the Global Terrorism Database' (DOI: 10.1201/9781003328414-26)."

## Contributing

Contributions and corrections are welcome. Please open an issue for discussion and submit pull requests for proposed changes. When contributing, ensure notebooks remain runnable and provide any environment details or dependency updates.

## Contact

For questions about reproducing the results, please open an issue on GitHub or contact the repository owner.

---

If you'd like, I can also:

- add a `CITATION.cff` or `CITATION.md` with the exact BibTeX entries for the paper and GTD, or
- create a `requirements.txt` to pin dependencies.

Let me know which you'd prefer.

## Full paper citation (for reference)

Yadav, Happy Manoj. "Prediction of Terrorist Attacks over the Globe Using the Global Terrorism Database: A Comparative Analysis of Machine Learning Prediction Algorithms." In Artificial Intelligence and Knowledge Processing: Improved Decision-Making and Prediction. Taylor & Francis Group, 2022.

BibTeX (suggested):

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
