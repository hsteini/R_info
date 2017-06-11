# R_info
Tips and tricks for using R

### Recommended Online Trainings
https://www.coursera.org/specializations/jhu-data-science
https://www.datacamp.com/

### Recommended Tutorials
http://gastonsanchez.com/Handling_and_Processing_Strings_in_R.pdf

### CheatSheets
https://www.rstudio.com/resources/cheatsheets/

### First steps wih RStudio
1) Click on File -> New File -> R Markdown
2) Give it a Title
3) File -> Save As -> give it a name
4) You find the path to your working directory in RStudio -> Preferences -> General -> Default working directory (when not in a project)
5) Change the code in your new R Markdown file like this

```

---
title: "new"
author: "Helmut Steinbichler"
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
6) Now you can select all the code cand click on the Knit button
7) Voila - now you should get a pdf or docx o html file
8) If you lick on the arrow on the left of the Knit button you can decide, what file format you want to generate.

