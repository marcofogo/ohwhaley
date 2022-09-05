
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ohwhaley

Whale-come! This R package was inspired by
[cowsay](https://github.com/sckott/cowsay) and
[praise](https://github.com/rladies/praise). I hope this package made
you smile today!

## First things first

`ohwhaley` is a toy project and is still under development. You can
install the latest version from [GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("fontikar/ohwhaley")
#> Downloading GitHub repo fontikar/ohwhaley@HEAD
#> Installing 1 packages: magrittr
#> Installing package into 'C:/Users/marco/OneDrive/Documents/R/win-library/4.1'
#> (as 'lib' is unspecified)
#> Warning: cannot remove prior installation of package 'magrittr'
#> Warning in file.copy(savedcopy, lib, recursive = TRUE):
#> problem copying C:\Users\marco\OneDrive\Documents\R\win-
#> library\4.1\00LOCK\magrittr\libs\x64\magrittr.dll
#> to C:\Users\marco\OneDrive\Documents\R\win-
#> library\4.1\magrittr\libs\x64\magrittr.dll: Permission denied
#> Warning: restored 'magrittr'
#> Installing package into 'C:/Users/marco/OneDrive/Documents/R/win-library/4.1'
#> (as 'lib' is unspecified)
```

## Take it for a spin

`ohwhaley` contains one function only. `say()` will echo a randomly
chosen whale-themed phrase for your enjoyment.

``` r
library(ohwhaley)
 
say() 
#> 
#>             ------ 
#>            Whale, whale, whale...look who's here! 
#>             ------ 
#>                \   
#>                 \  
#>                  \
#>      .-'
#> '--./ /     _.---.
#> '-,  (__..-`       \
#>    \          .     |
#>     `,.__.   ,__.--/
#>      '._/_.'___.-`
```

Alternatively, you can supply your own phrase

``` r
say("I'm beached as bro!!!")
#> 
#>             ------ 
#>            I'm beached as bro!!! 
#>             ------ 
#>                \   
#>                 \  
#>                  \
#>      .-'
#> '--./ /     _.---.
#> '-,  (__..-`       \
#>    \          .     |
#>     `,.__.   ,__.--/
#>      '._/_.'___.-`
```
