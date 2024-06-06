# Information on Repository for Maria Olsen's Spatial Exam Project 2024

## Disciption of project 
This repository includes relevant code and data for the Spatial Exam Project 2024 by Maria Olsen. A report of the project is written that addresses loneliness by leveraging spatial data and technology to facilitate social connections. A proof-of-concept event-match-making app is proposed, aiming to recommend local events and connect individuals with shared interests within the same geographical area. Using an Agent Based Model (ABM) implemented in R, the project simulates app functionality and user engagement. Empirical results show promising outcomes, despite limitations stemming from a small, non-representative survey sample. 

## Repository content
### R markdowns
**simulating_data.Rmd**: code to produce data used in the ABM <br>
**event_match_making_ABM.Rmd**: code tp produce ABM <br>
**analysis_ABM.Rmd**: code to produce analysis of the ABM data <br>

### Data used to produce the data used for ABM
**FOLK1AM.csv** <br>
**gadm42_DK_2.shp** <br>
**Municipality_code_ranges.csv** <br>

### Data produced in the R markdowns 
This data is loaded in here for simplicity as some of the code requires data produced in some of the other code. Now that it is all in one place, you can run any of the code files in direred order to get same output. <br> <br>
**population_df.csv** <br>
**survey_data.csv** <br>
**scaled_data.csv** <br>
**all_events.csv** <br>
**matched_people.csv** <br>

### Other
**MIT License**: The lisense for code in this repository <br>
**survey_Spatial_Exam**: The questions used in the survey 


## Requirnments
To rerun the code it is required to use R and RStudio (works on these desktop versions: R 4.4.0, RStudio 2024.4.1.748). Relevant packages are loaded in the code, but it is required to have the package "pacman" already installed in R in able to load in the relevant packages. To install pacman you can copy the following code in your R environment:
install.packages("pacman")
