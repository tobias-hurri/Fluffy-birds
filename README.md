# Fluffy-birds
[IMAGINARY] Fluffiness and temperature levels on captured birds. 

This R scripts goal is to analyzes the birds fluffiness in 
relation to the environmental temperature in the area the birds 
where captured, generating a visual graph to show a potential 
correlation. 

This datasett is just an imaginary datasett created randomly in Excel
with guidelines from GPT-UiO (an AI chat program created by the 
University of Oslo). All results have no real value, and should 
not be used as a actual scientific study. This whole repository 
project is just a test for using R-coding and sharing data on 
github - all for the sake of learning how to do reproducible science.


If the packages in the R-script dont work, 
try installing them first using this code: 

```r
install.packages("tidyverse")
install.packages("readxl")
install.packages("dplyr")
``` 

If loading the script, 
it says it does not find a "path" to 
at the code 

```r
Fluffy_data <- read_excel("Data/F_data.xlsx") 
``` 

it may be beacuse of a Global option setting in your R studio program.
In that chase: go to "Tools" -> "Global Options" -> "R Markdown" 
-> find "Evaluate Chunks in Dictonary" -> and chose option "Project".
Apply/Ok this, and this may fix the path. 


The R version used when creating the graph was R 4.5.1. The packages
used in the coding where tidyverse, readxl and dplyr. 
The coding happend between 2/10/25 - 6/10/25. 
The PC used for the coding was a Windows 11 Home laptop, 24H2 version.

If you have questions about my data/study/results, please send 
a mail or contact me through: "FuffyBirdMan217@hotmail.com"
