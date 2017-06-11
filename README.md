# R_info
Tips and tricks for using R

### Recommended Online Trainings
Coursera
https://www.coursera.org/specializations/jhu-data-science

DataCamp
https://www.datacamp.com/

### Recommended Tutorials
http://gastonsanchez.com/Handling_and_Processing_Strings_in_R.pdf

### CheatSheets
https://www.rstudio.com/resources/cheatsheets/

### Packages for the first steps
(It's very easy to install new packages -> Tools -> Install Packages -> write the name of the package you want to install)
* dplyr - for merging data and much more - here you find the CheatSheet https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf
* tidyr - for data wrangling
* rmarkdown for using markdown 
* sqldf - Perform SQL Selects on R Data Frames
* lubridate - Make Dealing with Dates a Little Easier

### First steps wih RStudio
1) Click on File -> New File -> R Markdown
2) Give it a title
3) File -> Save As -> give it a name
4) You find the path to your working directory in RStudio -> Preferences -> General -> Default working directory (when not in a project)
5) Change the code in your new R Markdown file like this

```

---
title: "new"
author: "First Name Last Name"
date: "11 6 2017"
output:
  word_document: default
  pdf_document: default
  html_document: default
---

### Documentation for the calculations
Assign x the values 3 and 5 and print x afterwards

```{r}
x <- 3 + 5
x

```

6) Attention! Below the x are three ``` 
7) In a Rmarkdown file the code is always between \``` {r}  code code code  \```
8) The documentation you write with RMarkdown - look at the CheatSheets for the simple syntax.
9) Now you can select all the code and click on the Knit button
10) Voila - now you should get a pdf or docx or html file
11) If you click on the arrow on the left side of the Knit button you can decide, what file format you want to generate.
12) If you have any further questions feel free to contact me.

