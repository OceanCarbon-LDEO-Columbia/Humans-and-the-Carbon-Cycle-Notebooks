# Humans-and-the-Carbon-Cycle-Notebooks
Python notebooks for the Columbia course "Humans and the Carbon Cycle", Fall 2024

## To download repo
- Click the green "code" button above, and press "download zip".
- Drag and drop the .zip file to your Jupyterhub. Place in in your home directory.
- In Jupyterhub, make a new notebook.
- In it, paste the following and then run the cell:\
\
    import zipfile as zf\
    files = zf.ZipFile("/home/jovyan/Humans-and-the-Carbon-Cycle-Notebooks-main.zip", 'r')\
    files.extractall()\
    files.close()

- Return to the GUI on the left to navigate into the folder Humans-and-the-Carbon-Cycle-Notebooks-main, and open the desired notebook
  
## Folders
- "in_development" is notebooks for future homework assignments. **(students, no need to look at this)**
- "misc" is data pre-processing **(students, no need to look at this)**
- "data" is data loaded into Python notebooks.

## **Data sources**

**Notebook 1: plot_explore_GCB.ipynb**
- Data from the Global Carbon Budget: **Global_Carbon_Budget_2023v1.0.xlsx** at **_https://essd.copernicus.org/articles/15/5301/2023/_**, spreadsheet page: **HistoricalBudget**
- Data source for CO2 mole fraction (ppm) measured monthly at Mauna Loa since 1958: **https://gml.noaa.gov/webdata/ccgg/trends/co2/co2_mm_mlo.csv**

**Notebook 2: PS2_carbon_chemistry_student.ipynb**
- Run seawater carbon calculations

**Notebook 3: future-carbon-sinks-HCC2024.ipynb**
- Betas and alpha: The Sixth Assessment Report of the United Nations Intergovernmental Panel on Climate Change (IPCC AR6), Chapter 5 at **https://www.ipcc.ch/report/ar6/wg1/downloads/report/IPCC_AR6_WGI_Chapter05.pdf**
- Driver data have been downloaded for you (in data) Shared Socioeconomic Pathways (SSP) Temperature and Atmospheric CO2 Data: **https://live.magicc.org/scenarios**_ (requires making an account. Click on a scenario, then click the download button.)

- Calculate the future land and ocean sinks based on these factors and the future SSP scenarios
