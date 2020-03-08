# Web Scraping with R

Python is the go-to among data journalists for web-scraping, and for good reaons. But it's not the only tool. Web scraping can be easy in R. Plus you get to enjoy other advantages of R such as data visualization.

This is a session for NICAR 2020 and teachs how to use R library Rvest to scrape data from the web. [Rvest](https://github.com/tidyverse/rvest) is a library inspired by Beautiful Soup written by Hadley Wickham. It's easy to learn and use. 

## What we're covering
During the sessioin, we will walk through how to scrape a table of OSHA inspections, including additional tables hidden behind hyperlinks, extract information based on style of the text. 

After this session you will walk away with knowledge about:
+ what a webpage is 
+ how to inspect the source code
+ a few most useful Rvest functions
  + read_html()
  + html_nodes()
  + html_table()
  + html_attr()
  + html_text()

I will also offer some tips on how to deal with errors.

A rendered HTML file of the tutorial can be found [here](https://rpubs.com/Jasmineyehan/582039).

As homework, I ask you to try scraping some comment letters for a proposed federal rule.

This session will be the best for someone with some knowledge of R, including subsetting a dataframe, piping (%>%) and how to create a basic function. Knowledge with HTML/CSS is helpful but not required.

## To get a copy

If you don't have access to IRE-provided laptops, you can download the files to your computer with the "usethis" package:

`install.packages("usethis")`

After the library is installed, you can load the course session by running this command in the console:

`usethis::use_course("https://github.com/yhy6f/nicar20_scraping_r/archive/master.zip")`

A local version of the repo should be saved to your desktop.

Packages you'll need to install for this session:

`Rvest`, `Dplyr`

## Q&A

+ Where do I learn more about Rvest?
  + Rvest has a detailed document table on CRAN: https://cran.r-project.org/web/packages/rvest/rvest.pdf
+ Can you scrape dynamic websites with R?
  + Apparently there is an Rselenium package: https://ropensci.org/tutorials/rselenium_tutorial/, which I wasn't aware of until the session, so thanks for the question, and to Christina who helped me answer it.

If you have any further questions, feel free to reach out. I'm on Twitter @JasmineHanYe or Yhan AT Bloomberglaw dot com.
