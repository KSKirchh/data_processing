# Plotting gene concentrations through qPCR data

The visualization and analysis of data play a central role in modern scientific research. In the context of the master's thesis "Reduction of resistance genes through wastewater treatment," a Jupyter Notebook was utilized for the analysis and visualization of data on gene concentrations quantified through qPCR from wastewater samples. In addition to considering absolute gene concentrations, the study also took into account relative concentrations, determined by normalization using 16S rRNA.The primary focus of this research was on the reduction of resistance genes in different wastewater treatment plants using various purification processes. Observing resistance genes in wastewater is significant as it allows for tracking the spread of these genes and initiating elimination measures. Preventing the spread as much as possible is crucial, as it poses a risk to both health and the environment.

January 2024, Kira S. Kirchhoff (B.Sc.)

***

## Content

* [Folder structure](#folderstructure)
* [Usage of this notebook](#usage-of-this-notebook)
* [References](#references)
* [License](#license)

***

#### Folder structure

data:
* 1. raw: Raw data used for processing.

> **Note**: Was not used for this repository because the original data was not published and a random data set was created to run the Jupyter notebook.

graphics: 
* 1. graphics used for the Jupyter notebook and README.

src:
* 1. src = Source: Is the source of the actual work (code).
* 2. src/ARG.ipynb: Jupyter notebook for the entire code.

README.md:
* 1. contains basic information about the repository and its handling.

requirements.txt:
* 1. contains a list of all libraries and their versions for future work on the PC or in connection with Binder and similar consorts.

.gitignore:
* 1. contains a list of data/folders that should NOT be uploaded when pushing to the remote repo.

***

### Usage of this notebook

Launch this notebook on Binder in your browser by clicking the button:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KSKirchh/data_processing/HEAD?labpath=%2Fsrc%2FARG.ipynb)

or scan the QR-Code to run this Notebook over Binder on your smartphone:

![Binder-QR](https://raw.githubusercontent.com/KSKirchh/data_processing/master/grafics/kira_master.png)

***

### References

Harris, C.R., Millman, K.J., van der Walt, S.J., Gommers, R., Virtanen, P., Cournapeau, D., Wieser, E., Taylor, J., Berg, S., Smith, N.J., Kern, R., Picus, M., Hoyer, S., van Kerkwijk, M.H., Brett, M., Haldane, A., del Río, J.F., Wiebe, M., Peterson, P., Gérard-Marchant, P., Sheppard, K., Reddy, T., Weckesser, W., Abbasi, H., Gohlke, C., Oliphant, T.E., 2020. Array programming with NumPy. Nature 585, 357–362. https://doi.org/10.1038/s41586-020-2649-2

Hunter, J.D., 2007. Matplotlib: A 2D Graphics Environment. Computing in Science & Engineering 9, 90–95. https://doi.org/10.1109/MCSE.2007.55

McKinney, W., 2010. Data Structures for Statistical Computing in Python. Presented at the Python in Science Conference, Austin, Texas, pp. 56–61. https://doi.org/10.25080/Majora-92bf1922-00a

Waskom, M.L., 2021. seaborn: statistical data visualization. Journal of Open Source Software 6, 3021. https://doi.org/10.21105/joss.03021


***

### License

**CC BY-NC-SA 4.0 Licence**

With this licence, you may use, modify and share the work as long as you credit the original author. However, you may 
not use it for commercial purposes, i.e. you may not make money from it. And if you make changes and share the new work, 
it must be shared under the same conditions.
