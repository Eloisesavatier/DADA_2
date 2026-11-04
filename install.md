R Notebook
================

# Installation de bioconductor et de dada2

``` r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("dada2", version = "3.23")
```

    ## 'getOption("repos")' replaces Bioconductor standard repositories, see
    ## 'help("repositories", package = "BiocManager")' for details.
    ## Replacement repositories:
    ##     CRAN: https://p3m.dev/cran/__linux__/noble/latest

    ## Bioconductor version 3.23 (BiocManager 1.30.27), R 4.6.1 (2026-06-24)

    ## Warning: package(s) not installed when version(s) same as or greater than current; use
    ##   `force = TRUE` to re-install: 'dada2'

    ## Installation paths not writeable, unable to update packages
    ##   path: /usr/local/lib/R/library
    ##   packages:
    ##     class, cluster, foreign, KernSmooth, lattice, MASS, Matrix, mgcv, nlme,
    ##     nnet, spatial, survival

    ## Old packages: 'arrow', 'curl', 'duckdb', 'gargle', 'gert', 'googledrive',
    ##   'googlesheets4', 'lambda.r', 'openssl', 'RcppArmadillo', 'readxl',
    ##   'roxygen2', 'sp', 'xfun'

``` r
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("DECIPHER")
```

    ## 'getOption("repos")' replaces Bioconductor standard repositories, see
    ## 'help("repositories", package = "BiocManager")' for details.
    ## Replacement repositories:
    ##     CRAN: https://p3m.dev/cran/__linux__/noble/latest

    ## Bioconductor version 3.23 (BiocManager 1.30.27), R 4.6.1 (2026-06-24)

    ## Warning: package(s) not installed when version(s) same as or greater than current; use
    ##   `force = TRUE` to re-install: 'DECIPHER'

    ## Installation paths not writeable, unable to update packages
    ##   path: /usr/local/lib/R/library
    ##   packages:
    ##     class, cluster, foreign, KernSmooth, lattice, MASS, Matrix, mgcv, nlme,
    ##     nnet, spatial, survival

    ## Old packages: 'arrow', 'curl', 'duckdb', 'gargle', 'gert', 'googledrive',
    ##   'googlesheets4', 'lambda.r', 'openssl', 'RcppArmadillo', 'readxl',
    ##   'roxygen2', 'sp', 'xfun'

# Installation de phyloseq

``` r
install.packages("igraph", type = "source")
```

    ## Installing package into '/usr/local/lib/R/site-library'
    ## (as 'lib' is unspecified)

``` r
BiocManager::install("phyloseq", update = FALSE)
```

    ## 'getOption("repos")' replaces Bioconductor standard repositories, see
    ## 'help("repositories", package = "BiocManager")' for details.
    ## Replacement repositories:
    ##     CRAN: https://p3m.dev/cran/__linux__/noble/latest

    ## Bioconductor version 3.23 (BiocManager 1.30.27), R 4.6.1 (2026-06-24)

    ## Warning: package(s) not installed when version(s) same as or greater than current; use
    ##   `force = TRUE` to re-install: 'phyloseq'
