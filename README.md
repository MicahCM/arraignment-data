# Welcome! 

This is the replication repository for my (Micah Clark Moody's) work comparing arraignment outcomes across legal and political eras.

To use this code, clone this repository or download each file to your local device.

Re-name the file paths in replication code. Make sure you have all the packages installed for the libraries listed in the replication code. This code was written with R version 4.5.1 (2025-06-13).

After downloading each file, installing packages, and re-naming paths you should be able to run the code! 

This code is written so that all results presented in the paper are generated. They will be generated in the order that they appear in the paper.

Claims in the paper - for example median is x or brant test is y - are included in the code but if they are not presented as results they will also not print when this code is run. Those numbers are saved as objects. Everything is with the relevant hypothesis. To check a specific number, look for the object in that hypothesis code chunk.

# Data 

There are two datasets presented in this paper: reform-oriented data and detention data.

Reform-oriented data is available here: (Cook County "Initiation Data")[https://datacatalog.cookcountyil.gov/Legal-Judicial/Initiation/7mck-ehwz/about_data]

* I recommend downloading as a csv file for easiest use of the replication code.
* *Reform-oriented data is not saved in this repository because it is bigger than my storage limit. If there are access issues, please feel free to rech out to me at clarkmoody@u.northwestern.edu and I'll share a copy!*

Detention data is available here: (Detention Data)[https://github.com/MicahCM/arraignment-data/blob/main/detention_data.xlsx]

# Replication Code

Download the code in the (replication-code.Rmd)[], rename data paths at the top of the file, and run! #TODO flag paths easily