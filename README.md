# AirlineClubFleetTools
An RShiny app for analyzing fleet data from the open source Airline Club game. 

## Online Usage
There is none.

## Offline Usage

R Version Requried: R Version 4.1.0 or higher (https://www.r-project.org)

### Installing Required Packages:

From the command line, open an interactive R session:
```
R
```
Then, run the following command to install the necessary packages:
```
install.packages(c("shiny","shinyjqui","DT","shinycssloaders","shinythemes"))
```
List of Packages:
 - shiny
 - shinyjqui
 - DT
 - shinycssloaders
 - shinythemes

Then, download or clone this repository.

---
### Starting Application:

#### From Command Line:

Open a command line and navigate into the same directory as the app.R file in this repository.

Then, execute the following command to launch the application:
```
R -e "library(shiny);runApp(launch.browser=TRUE)"
```
Subsequently, the application will launch and an interactive GUI will open in your default browser.

#### From R:

Working in the same directory that app.R is save in, execute the following R commands:
```
library(shiny)
runApp(launch.browser = TRUE)
```
