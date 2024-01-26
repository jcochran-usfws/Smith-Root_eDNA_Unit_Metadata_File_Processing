# Smith-Root eDNA Unit Metadata File Processing Tool
 
### General 
Repository for files and scripts related to a simple tool that takes Smith-Root eDNA unit metadata files and compiles them into a more database ingestable format.

### Installation

In order to run this tool, you will need the following:

1. **R version >4.0** Available through FWS Apps-to-Go.
1. **Dependent R Packages** The 'Package Install and Import' chunk at the beggining of the .Rmd will install, if necessary, any missing packages and then imports them.

 ### Description
This repository contains an Rproject complete with an .Rmd script, folders, and example data for processing metadata files downloaded from Smith-Root eDNA filtration units. Users can drop raw metadata files in thier folder structure into the *Raw Files* folder and then run the script. Multiple raw metadata files can be processed at once. It is important that the file name is the eDNA units serial number as that is used as a join field for the USFWS eDNA Projects Database. This script results in two output CSV files. The first file is a compilation of the summary statistics from each filter ID. The second file compiles the raw metadata along with their GPS location into a CSV for easy import and use in spatial mapping applications such as ArcGIS Pro. Both output files can be found in the *Processing Output* folder once the script has been run. Both folders contain example data that can be used to test the tool upon downloading.
 
 Any questions regarding this repository or the code within, please contact:
 
Jacob Cochran, Fish Biologist, Lower Great Lakes FWCO
<br /> jacob_cochran@fws.gov

Jason Coombs, Geneticist, Northeast Fishery Center
<br /> jason_coombs@fws.gov
 
### USFWS Disclaimer
This United States Fish & Wildlife Service (USFWS) code is provided on an “as is” basis and the user assumes responsibility for its use. USFWS has relinquished control of the information and no longer has responsibility to protect the integrity , confidentiality, or availability of the information. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recomendation or favoring by USFWS. The USFWS seal and logo shall not be used in any manner to imply endorsement of any commercial product or activity by USFWS or the United States Government.
