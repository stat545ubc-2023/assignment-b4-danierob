#### Author: Daniel Robinson
## Assignment B4: Option A – Strings and functional programming in R 

Weclome to the final STAT 545 Assignment. I elected for option A for my final project.

### Exercise 1: Text Analysis (Dissecting Frankestein)
In the first exercise, we take a closer look at the freuquency of the most common words in Mary Shelley's Frankenstein to get a better idea of the important themes and focus of the book. 
For this analysis, we utilize the tidyverse, the map() functions from the purrr package, some regular expressions, and common stopwords from the stopwords package to filter out articles and common stopwords and mine the text for the critical thematic words.

**DATA SOURCE** .txt file for Frankenstein was sourced from [Project Gutenberg](https://dev.gutenberg.org/ebooks/84) and inspiration for code and methods came largely from [tidytextmining.com](https://www.tidytextmining.com/tidytext).

### Exercise 3: 
For exercise 3, I looked at data from my own research to run multiple linear models across the different levels of a group. 
In my thesis data, I am interested in the relationship between 8 groups of my response variable and one explanatory variable. Data was collected periodically throughout the dry season, and each obs_period group represents data collected later in the dry season. Rather than run each relationship as a separate model, I will use the "map" family of functions in the purrr package to apply a linear model to multiple columns simultaneously.

# Files Descrpition  
__README.md__ provides a brief descrption of the author, intent, and files in this repository.  

__B4.Rmd__ is an R markdown file where all code and descriptions were recorded.

__B4.md__ is the final deliverable file, created from the B4.Rmd file.

__Frankenstein.txt__ is a text file of Mary Shelley's Frankstein sourced from Project Gutenberg.

__data__ is a folder with the "field_data" file from my own research, which serve as the source for the models in Exercise 3.

# How to run the code:  
* Open RStudio  
* Click "File" in the upper lefthand corner  
* Click "New Project"  
* Click "Version Control"  
* Click "Git"  
* Paste the Repository URL for the code you would like to run into the "Repository URL" box  
* Click "Create Project"  
* Under the "Files" tab you can select whichever file of code you would like to run    
* You can now run our code in RStudio!  

# How to run Rmarkdown (.Rmd) file:
* Open RStudio
* Follow above steps and select a ".Rmd" file
* Click "Knit" to generate a ".md" file
