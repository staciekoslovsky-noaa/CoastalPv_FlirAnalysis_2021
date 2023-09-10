# Coastal Harbor Seal Processing for FLIR Analyses

The code in this repository was used in an evaluation of FLIR for detecting harbor seals in the Aleutian Islands. The manuscript associated with this work can be found here: https://repository.library.noaa.gov/view/noaa/41940.

The data management processing code is as follows:
* **FLIR_Counts.txt** - code for generating the count dataset used for the FLIR analysis; this code is run in PGAdmin
* **FLIR_FLIR2SLR_Summary.Rmd** - code for generating a report to compare FLIR counts to SLR counts from the study area
* **FLIR_ProcessImages.R** - code for processing FLIR images to get date/time and other information from the text on the screen