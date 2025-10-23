
Load the necessary packages and read in the data.csv file into R (use an
R chunk)

``` r
# loading common packages, not sure if they'll be used
library(tidyverse)
```

    ## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
    ## ✔ dplyr     1.1.4     ✔ readr     2.1.5
    ## ✔ forcats   1.0.1     ✔ stringr   1.5.1
    ## ✔ ggplot2   4.0.0     ✔ tibble    3.3.0
    ## ✔ lubridate 1.9.4     ✔ tidyr     1.3.1
    ## ✔ purrr     1.1.0     
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()
    ## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors

``` r
library(ggplot2)

# see if R can read the file
read.csv("data/data.csv")
```

    ##       info durationV     f0   int
    ## 1   capo_1      0.15 254.19 80.82
    ## 2   capo_2      0.15 212.27 71.26
    ## 3  pinto_1      0.09 264.30 78.40
    ## 4  pinto_2      0.09 214.41 73.88
    ## 5   pujo_1      0.18 275.79 79.56
    ## 6   pujo_2      0.14 222.42 77.16
    ## 7  quemo_1      0.17 262.11 86.04
    ## 8  quemo_2      0.15 214.60 79.27
    ## 9  testo_1      0.15 260.22 84.00
    ## 10 testo_2      0.11 219.52 79.50

``` r
# asign data to an object
data <- read.csv("data/data.csv")

# view data
view(data)
```

Manipulate the dataframe as necessary so that you can calculate average
duration, f0 and intensity as a function of lexical stress (extra points
if you can create a plot)

``` r
# calculate average duration as a function of lexical stress

# calculate average f0 as a function of lexical stress

# calculate average intensity as a function of lexical stress
```
