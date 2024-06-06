# Information on Repository for Maria Olsen's Spatial Exam Project 2024

## Disciption of project 
This repository includes relevant code and data for the Spatial Exam Project 2024 by Maria Olsen. A report of the project is written that addresses loneliness by leveraging spatial data and technology to facilitate social connections. A proof-of-concept event-match-making app is proposed, aiming to recommend local events and connect individuals with shared interests within the same geographical area. Using an Agent Based Model (ABM) implemented in R, the project simulates app functionality and user engagement. Empirical results show promising outcomes, despite limitations stemming from a small, non-representative survey sample. 

## Repository content
### R markdowns
**simulating_data.Rmd**: code to produce data used in the ABM
**event_match_making_ABM.Rmd**: code tp produce ABM
**analysis_ABM.Rmd**: code to produce analysis of the ABM data

### Data used to produce the data used for ABM
**FOLK1AM.csv**
**gadm42_DK_2.shp**
**Municipality_code_ranges.csv**

### Data produced in the R markdowns 
This data is loaded in here for simplicity as some of the code requires data produced in some of the other code. Now that it is all in one place, you can run any of the code files in direred order to get same output.
**population_df.csv**
**survey_data.csv**
**scaled_data.csv**
**all_events.csv**
**matched_people.csv**

### Other
**MIT License**: The lisense for code in this repository
**Survey Questions**: The questions used in the survey 


## Requirnments
To rerun the code it is required to use R and RStudio (works on these desktop versions: R 4.4.0, RStudio 2024.4.1.748). Relevant packages are loaded in the code, but it is required to have the package "pacman" already installed in R in able to load in the relevant packages. To install pacman you can copy the following code in your R environment:
install.packages("pacman")
