01\_write-installed-packages.R
================
skim68
Mon Jan 28 18:53:26 2019

``` r
## deja vu from earlier!

## create a data frame of your installed packages


## hint: installed.packages() is the function you need

df <- installed.packages()
head(df)
```

    ##            Package      LibPath                                     
    ## abind      "abind"      "C:/Users/sweet/Documents/R/win-library/3.4"
    ## assertthat "assertthat" "C:/Users/sweet/Documents/R/win-library/3.4"
    ## backports  "backports"  "C:/Users/sweet/Documents/R/win-library/3.4"
    ## base64enc  "base64enc"  "C:/Users/sweet/Documents/R/win-library/3.4"
    ## BH         "BH"         "C:/Users/sweet/Documents/R/win-library/3.4"
    ## bindr      "bindr"      "C:/Users/sweet/Documents/R/win-library/3.4"
    ##            Version    Priority Depends        Imports          LinkingTo
    ## abind      "1.4-5"    NA       "R (>= 1.5.0)" "methods, utils" NA       
    ## assertthat "0.2.0"    NA       NA             "tools"          NA       
    ## backports  "1.1.2"    NA       "R (>= 3.0.0)" "utils"          NA       
    ## base64enc  "0.1-3"    NA       "R (>= 2.9.0)" NA               NA       
    ## BH         "1.66.0-1" NA       NA             NA               NA       
    ## bindr      "0.1.1"    NA       NA             NA               NA       
    ##            Suggests   Enhances License              License_is_FOSS
    ## abind      NA         NA       "LGPL (>= 2)"        NA             
    ## assertthat "testthat" NA       "GPL-3"              NA             
    ## backports  NA         NA       "GPL-2"              NA             
    ## base64enc  NA         "png"    "GPL-2 | GPL-3"      NA             
    ## BH         NA         NA       "BSL-1.0"            NA             
    ## bindr      "testthat" NA       "MIT + file LICENSE" NA             
    ##            License_restricts_use OS_type MD5sum NeedsCompilation Built  
    ## abind      NA                    NA      NA     "no"             "3.4.1"
    ## assertthat NA                    NA      NA     "no"             "3.4.4"
    ## backports  NA                    NA      NA     "yes"            "3.4.3"
    ## base64enc  NA                    NA      NA     "yes"            "3.4.1"
    ## BH         NA                    NA      NA     "no"             "3.4.3"
    ## bindr      NA                    NA      NA     "no"             "3.4.4"

``` r
## optional: select just some of the variables, such as
##   * Package
##   * LibPath
##   * Version
##   * Priority
##   * Built

## write this data frame to data/installed-packages.csv
## hint: readr::write_csv() or write.table()
## idea: try using here::here() to create the file path

## YES overwrite the file that is there now (or delete it first)
## that's a old result from me (Jenny)
## it an example of what yours should look like and where it should go
```
