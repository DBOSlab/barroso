## CRAN submission for barRoso 1.0.0

### Package Summary

* **Package name:** barRoso  
* **Version:** 1.0.0  
* **Title:** Biodiversity Analysis and Record Reconciliation for Organizing Specimen Observations  
* **Authors:** Domingos Cardoso  
* **Maintainer:** domingoscardoso@jbrj.gov.br  
* **License:** MIT  
* **URL:** https://github.com/DBOSlab/barRoso  
* **BugReports:** https://github.com/DBOSlab/barRoso/issues  

### Submission Notes

* This is the initial submission of the `barRoso` package to CRAN.
* The package provides tools to access, download, and filter plant specimen data from the REFLORA Virtual Herbarium maintained by the Rio de Janeiro Botanical Garden (JBRJ).
* It leverages standard packages (`dplyr`, `stringr`, `finch`, etc.) and supports tidyverse workflows.
* All exported functions are documented with reproducible examples.
* Unit tests using `testthat` cover all key functionalities, with overall test coverage above 85%.

### R CMD check

* `R CMD check` was run on:
  - Local machine (macOS Ventura, R 4.3.2)
  - GitHub Actions (Ubuntu, Windows, macOS)

  Results:  
  ❯ 0 errors ✔  
  ❯ 0 warnings ✔  
  ❯ 0 notes ✔ 
  
### Additional Information

* This package contributes to biodiversity and herbarium data digitization by facilitating access to a key Brazilian resource.
* Development supported by CNPq and FINEP, and institutional support from JBRJ.
