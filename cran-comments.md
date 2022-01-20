## Test environments
* local OS X install, R 3.5.1
* ubuntu 12.04 (on travis-ci), R 3.5.1
* win-builder (devel and release)

0 errors | 0 warnings | 0 notes

## Version 0.1.0 Checks

Result: NOTE 
    Package suggested but not available for checking: ‘INLA’ 
    
INLA is not held in a common repository so package so cannot be made available for checking.

checking re-building of vignette outputs ... [2s/3s] WARNING
Error in re-building vignettes:
  ...
Installing package into '/home/hornik/tmp/R.check/r-release-gcc/Work/build/Packages'
(as 'lib' is unspecified)

We added the vignette output to inst/doc. We also have switched to a static vignette, but with source code available and shown.

## Version 0.2.0 Update

* We expanded authorship of the package.
* We updated the links for URL and BugReports.
* We reworked our vignette.
* We added the capability to use a yearly model. Previously, only 5-year increments were possible.
* We changed the plotting function aesthetics and adjusted for the new yearly model. 
* We renamed our included data, added another data set, and clarified that the data do not represent any real country.
* We added the capability to do a simpler model that uses only binary outcome.
* We made minor updates to the documentation and examples.
* Add vignette to inst/doc to prevent WARNINGs.
* Switch to static vignette with source code available and shown so that INLA does not need to be installed.

## Version 0.2.1 Update
* We developed a new function for simulating spatial and temporal random effects.
* We fixed a problem with fitINLA() function that may arise when user-customized dataset with missing areas.
* We updated the INLA repository as requested.
* We removed packages that are no longer needed to remove NOTEs from https://cran.rstudio.com/web/checks/check_results_SUMMER.html.

## Version 0.2.2 Update
* Remove deprecated calls to cBind() and rBind().
* Update to vignette.
* Minor edits to documentation.
* Add in new data examples.
* Improve generalizability of some functions.

## Version 0.2.3 Update
* Major improvements in generalizability and documents of some functions.
* We changed how non-existent age bins are handled in the discrete survival model. Previously they were ignored. Now these age bins are combined with previous bins. This affects direct estimates in situations where very few observations exist.
* Improved visualizations.
* Update to vignette.

## Version 0.3.0 Update
* Maintainer change.
* Major updates to the functionalities. See the News file for details.
* The size of two directories lead to devtools::check() notes: data (2.7Mb) and doc (8.7Mb). The data directory contains necessary illustrative examples of complex survey data. The doc directory contains static vignettes that provide more details in using the package. Dynamic vignettes are not possible because the computation of examples takes a long time and requires INLA installation. Since the package also concerns visualizing space-time smoothing models for fine geographic areas, the resulting vignettes are slightly larger in size as well.

## Version 1.0.0 Update
* Major updates to the functionalities. See the News file for details.
* The size of two directories lead to devtools::check() notes: data (2.0Mb) and doc (2.9Mb). The data directory contains necessary illustrative examples of complex survey data and maps. The doc directory contains static vignettes that provide more details in using the package. Dynamic vignettes are not possible because the computation of examples takes a long time and requires INLA installation. Since the package also concerns visualizing space-time smoothing models for fine geographic areas, the resulting vignettes are slightly larger in size as well. We have made the vignettes more concise and significantly reduced the size from the previous versions of the package.


## Version 1.1.0 Update
* Major updates to the functionalities. See the News file for details.
* The size of two directories lead to devtools::check() notes: data (2.0Mb) and doc (2.7Mb). The size of these files have been reduced from last version on CRAN. The data directory contains necessary illustrative examples of complex survey data and maps. The doc directory contains static vignettes that provide more details in using the package. Dynamic vignettes are not possible because the computation of examples takes a long time and requires INLA installation. Since the package also concerns visualizing space-time smoothing models for fine geographic areas, the resulting vignettes are slightly larger in size as well. We have made the vignettes more concise and significantly reduced the size from the previous versions of the package.


## Version 1.2.0 Update
* Major updates to the functionalities. See the News file for details.
* The doc directory contains static vignettes that provide more details in using the package. Dynamic vignettes are not possible because the computation of examples takes a long time and requires INLA installation. Since the package also concerns visualizing space-time smoothing models for fine geographic areas, the resulting vignettes are slightly larger in size as well. We have made the vignettes more concise and significantly reduced the size from the previous versions of the package.

