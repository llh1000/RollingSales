Rolling Sales Project
"Rolling Sales.Rproj"

Purpose: analyze Rolling Sales data for Brooklyn to examine relationship between total square feet and sales price for 1, 2, and 3 family homes.

Session Info
R version 3.3.2 (2016-10-31)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows >= 8 x64 (build 9200)

locale:
[1] LC_COLLATE=English_United States.1252  LC_CTYPE=English_United States.1252  [3] LC_MONETARY=English_United States.1252 LC_NUMERIC=C                       
[5] LC_TIME=English_United States.1252    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base   other attached packages:
[1] plyr_1.8.4

loaded via a namespace (and not attached):
 [1] backports_1.0.5 magrittr_1.5    rprojroot_1.2   htmltools_0.3.5 tools_3.3.2  [6] yaml_2.1.14     Rcpp_0.12.9     stringi_1.1.2   rmarkdown_1.3   knitr_1.15.1   
[11] stringr_1.1.0   digest_0.6.11   evaluate_0.10 

Project directory contains

- DATA
  Downloaded datafile from path:
  http://www1.nyc.gov/assets/finance/downloads/pdf/rolling_sales/rollingsales_brooklyn.xls
  imported in .csv file format
  saved as "rollingsales_brooklyn.csv" in data directory

- SOURCE
  cleaned datafile using protocol in R file
  R_rollingsales_brooklyn.R in source directory
  
- PAPER
  presentation of results showing relationship between total square feet and sales price
  R Markdown file knitted to produce
  rolling.html
                