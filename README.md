# Web Scraping with R

Python is the go-to among data journalists for web-scraping, and for good reaons. But it's not the only tool. Web scraping can be easy in R too. Plus you get to enjoy other advantages of R such as data visualization.

This is a session for NICAR 2020 and teachs how to use R library Rvest to scrape data from the web. 

## Main goals
During the sessioin, we will walk through how to scrape a table of OSHA inspections, including additional tables hidden behind hyperlinks, extract information based on style of the text. In the process I will introduce what webpage is and how to find CSS selector by inspecting the source code. I will also offer some tips on how to deal with errors. 

As homework, I ask you to try scraping some comment letters for a proposed federal rule.

This session will be the best for someone with some knowledge of R, including data types, subsetting a dataframe, piping (%>%) and how to create a basic function. Knowledge with HTML/CSS is helpful but not necessary.

## To get a copy

If you don't have access to IRE-provided laptops, you can download the files to your computer with the "usethis" package:

`install.packages("usethis")`

After the library is installed, you can load the course session by running this command in the console:

`usethis::use_course("https://github.com/yhy6f/nicar20_scraping_r/archive/master.zip")`

A local version of the repo should be saved to your desktop.

Packages you'll need to install for this session:

`Rvest`, `Dplyr`
