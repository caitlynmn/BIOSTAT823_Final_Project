# BIOSTAT823 Final Project
By Caitlyn Nguyen

Intensive Care Units (ICUs) are areas within hospitals that provide crucial treatment for critically-ill patients. In this study, we tested three different neural network model architectures to improve prediction for in-hospital mortality of ICU patients. Demographic and routinely collected physiological data from 2001 to 2012 was sourced from the Multiparameter Intelligent Monitoring in Intensive Care III (MIMIC-III) Clinical Database. There were a total of n = 1,178 individuals. The best model architecture had an AUROC of 0.776 and an AUPRC of 0.600. This model shows the possibility of incorporating both baseline demographic data and medical laboratory for in-hospital mortality prediction. This provides insights on how we can develop clinical decision support tools to aid clinicians in making data-driven decisions when caring for patients.

# Requirements and installation
System requirements:
* Ubuntu 16.04 or higher (64-bit)
* macOS 10.12.6 (Sierra) or higher (64-bit) (no GPU support)
* Windows Native - Windows 7 or higher (64-bit)
* Windows WSL2 - Windows 10 19044 or higher (64-bit)

The following should be installed following these installation instructions:
* Python 3.7-3.10 ([https://packaging.python.org/en/latest/tutorials/installing-packages/](https://packaging.python.org/en/latest/tutorials/installing-packages/))
* pip version 19.0 or higher for Linux (requires manylinux2010 support) and Windows. pip version 20.3 or higher for macOS ([https://pip.pypa.io/en/stable/installation/](https://pip.pypa.io/en/stable/installation/))
* Jupyter Notebook ([https://jupyter.org/install](https://jupyter.org/install))
* Matplotlib ([https://matplotlib.org/stable/users/installing/index.html](https://matplotlib.org/stable/users/installing/index.html))
* pandas ([https://pandas.pydata.org/docs/getting_started/install.html])(https://pandas.pydata.org/docs/getting_started/install.html))
* tensorflow ([https://www.tensorflow.org/install/pip](https://www.tensorflow.org/install/pip))
* scikit-learn ([https://scikit-learn.org/stable/install.html](https://scikit-learn.org/stable/install.html)

# Contents
* `data01.csv` contains the dataset acquired from ([https://www.kaggle.com/datasets/saurabhshahane/in-hospital-mortality-prediction](https://www.kaggle.com/datasets/saurabhshahane/in-hospital-mortality-prediction))
* `Final_Project_Models.ipynb` is the Jupyter Notebook script for data cleaning, model development, and model evaluation
* `Final_Project_Models.pdf` is the printed document of the Jupyter Notebook output
* `Final_Project_Report.tex` is the final report written in LaTex format
* `Final_Project_Report.pdf` is the final report in `.pdf` format, outputted from the LaTex file
* `bibliograpy.bib` contains the bibliography used in writing the report, and is called upon in the `Final_Project_Report.tex` file
* The `images` folder contains screenshot images of the plots outputted from the Jupyter Notebook file
