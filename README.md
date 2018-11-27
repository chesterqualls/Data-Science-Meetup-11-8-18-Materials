# Data-Science-Meetup-11-8-18-Materials
Data set and R code for the 11/8/18 Data Science meetup presentation

"ECLSK.dat": subset of 6K children from the Early Childhood Longitudinal Study - Kindergarten cohort 1998-1999. The full data set and information on the variables is publicly available at https://nces.ed.gov/ecls/kindergarten.asp.

"Example ECLSK.R": R code to fit trees, cross-validated trees, and random forests on the ECLSK.dat data set.

>This is a fork of an original repo from **Gabriela Stegmann** https://github.com/gabistegmann/Data-Science-Meetup-11-8-18-Materials
I made this so I could move the R code into a **Jupyter Notebook/R Kernel** and play with the code to learn more about it.
* Not sure why but when running this Jupyter NB the plots began to have an error "Error in png(tf, width, height, "in", pointsize, bg, res, antialias = antialias): unable to start png() device". I tried to look into this but don't yet have a fix.  The original file still works in RStudio and displays all plots. I hadn't looked at this file for a few weeks and when I came back to it I was changing = to <- the standard R assignment notification (If not mistaken). But plots still have a problem when I changed back to =. 

