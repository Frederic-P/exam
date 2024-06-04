# exam
Exam Data Science Year1 - Examday1
Downloadable from: [GitHub](https://github.com/Frederic-P/exam)

## Overview of key files/folders:

```
root
|__data
|   - {load your CSV files here.}
|__notebooks
|       - examen_deel1.ipynb
|__utils
    -plotstyle.py
-.gitignore
-.environment.yaml
-.readme.md

```

## Data: 
The GitHub Repo does not contain data. The full dataset should be loaded into the correct folders before running the notebooks. The data should be CSV files with the names following the following convention ```2019-1-3.csv```
Each CSV file should have the following structure: 
```
    gemeente,naam,geslacht,verwachte datum
    Sint-Niklaas (Sint-Niklaas),Wout,Mannelijk,01/26/2019
    Manhay,Henri,Mannelijk,01/06/2019
    Merchtem,Gitte,Vrouwelijk,01/28/2019
    Pelt,Laura,Vrouwelijk,01/04/2019
    Bredene,Leen,Vrouwelijk,01/16/2019
    Moeskroen,Killian,Mannelijk,01/02/2019
    Hoogstraten,Lea,Vrouwelijk,01/06/2019
```

### Data loading instructions: 
Put your data in the data folder, data must match the constraints given above. Your CSV files go directly in the data-folder, there's no need for subfolders. 


## Installation: 
1) Download the GitHub repository, or clone it as you would with every other GitHub project.
2) Install and activate the virtual environment (environment.yaml). For this you'll need to have [Anaconda](https://docs.anaconda.com/free/navigator/index.html) installed.
- Open an Anaconda PowerShell prompt and use `cd` to navigate to the directory where you cloned this repository to. The commands below assume you are in the root-directory of the codebase. To install the environment use: `conda env create -f environment.yaml` Wait for the installation process to complete. You'll know if the process is complete when the Anaconda PowerShell shows you the commands to activate and deactivate the newly installed environemnt.
3) Deploy the data files you have in the folders as described in the **Data** section.
- once installed type: `conda activate env_examen` to activate this environment; you need to use this Kernel for all modules to work. 
- once activated open the notebook using the `jupyter notebook` command and open the notebooks you are interested in in the browserwindow that pops up. 
4) Run the notebook
5) Play with all the cells