My [drat](http://dirk.eddelbuettel.com/code/drat.html) repository for hosting non-CRAN/BioConductor packages that my own packages rely on. The GitHub repo for this R package repository is [here](https://github.com/daynefiler/drat).

## Current Packages
- **[lisi](https://github.com/immunogenomics/LISI)**
    - *v1.0: [05b79bb](https://github.com/immunogenomics/LISI/tree/05b79bbd6aa155c2e84d28f665c83d1666277404)*
- **[kBET](https://github.com/theislab/kBET)**
    - *v0.99.6: [4c9dafa](https://github.com/theislab/kBET/tree/4c9dafab2e4183422ad76bfcb65ca50eac1277e4)*
- **[harmony](https://github.com/immunogenomics/harmony)**
    - *v1.0: [272fa11](https://github.com/immunogenomics/harmony/tree/272fa115bc77d594223fe8e55f1c9fbe7d31dee4)*
- **[dlfUtils](https://github.com/daynefiler/dlfUtils)**
    - *v0.2.0 [af810ff](https://github.com/daynefiler/dlfUtils/releases/tag/0.2.0)*
    - *v0.6.0 [e0359eb](https://github.com/daynefiler/dlfUtils/releases/tag/v0.6)*
    - *v0.8.0 [fcbeb7f](https://github.com/daynefiler/dlfUtils/releases/tag/v0.8)*

## Notes for maintenance

To add a package, use `drat::insertPackage("pathTo.tar.gz", repodir = "~/Github/drat/")`.
`drat:insertPackage` should update `src/conrib/PACKAGES`, `src/contrib/PACKAGES.gz`, `src/contrib/PACKAGES.rds` and add the source package file to `src/contrib`. 
After adding the new package, update this README and commit/push the changes.

