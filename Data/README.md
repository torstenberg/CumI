# Assessment data for the CumI R script
This directory should contain the data which the R script CumI-assessment.Rmd is using for the assessment. Since this is an enourmous amount of data (some GB), they have not been uploaded to Github.

Please download the Data folder from the [HELCOM EN BENTHIC workspace](https://portal.helcom.fi/workspaces/EN-BENTHIC-191/Shared%20Documents/CumI/CumI-R).

There is one folder for each version of the CumI script:

- version 1.1 = Data-696defe8db
- version 2.0 = Data-2022

Put the downloaded Data directory alongside the R script (i.e. into the same directory) in order to use it. For the R script to be able to find the folder, you should check the script around line 35. There you can point the script to the correct data folder (and name it as you like).