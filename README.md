# Youth annual statistics 2022

Repository containing scripts to create dashboards containing maps for the annual publication.  

To clone this repo:
1. Open a terminal window
2. Go to the path where you want to have the repo. Remember that if your path contains spaces it is necesarry to wrap the path in quotation marks:

> cd "path_name"  
> git clone "https://github.com/YJB-Statistics-Analysis/maps_annual_stats_2020_2021.git"

# Package Installation   

To install the packages used in this project run the file renv/activate.R


The dashboards are also available on the [YJB Rpubs website](https://rpubs.com/yjb_statistics). 

# To re-create/update the dashboards

Dashboards are created using the Rmd files in scripts: ```children.Rmd```, ```offences.Rmd``` and ```outcomes.Rmd```. Running these files will create a copy of the dashboards in the scripts folder.
To create a copy in the ```output.html``` folder, run the file ```main.R```.

To update the maps replace files in data folder and change paths (with the new file name) when reading the files in ```children.Rmd```, ```offences.Rmd``` and ```outcomes.Rmd```.
Make sure the same titles in the Excel files are mantained: 'YOT', 'Region', 'PCC', Children/Offences/Outcomes, Population, Rate.  
To publish on R pubs click Publish > New and fill in the required information (name of the dashboard, description, and link).


The dashboard are hosted on the Rpubs website:
- Outcomes: https://rpubs.com/yjb_statistics/outcomes_2020_2021
- Children: https://rpubs.com/yjb_statistics/children_2020_2021
- Offences: https://rpubs.com/yjb_statistics/offences_2020_2021
>>>>>>> 53d617f (Documentation revised)
