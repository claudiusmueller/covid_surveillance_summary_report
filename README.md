# Covid Surveillance Summary Report (LDT Lab)

Summary report creation for the COVID-19 PCR testing effort at the George Mason University Clinical Proteomics Laboratory.

## Introduction

<img align="right" src="readme_images/GMU_PLogo_4CP_small.png">

This R-markdown script summarizes the COVID-19 testing data as performed at the CAP/CLIA accredited Clinical Proteomics Laboratory (CAP Number: 7223012; CLIA License: 49D2002076) at George Mason University.

## Technologies

[![R](https://img.shields.io/badge/R-4.05-blue)](https://cran.r-project.org/)

## Installation

1. Clone github project.

2. Add a copy of old ICA schedules (date prior to database setup) into an "old_ICA_schedules" subdirectory. This data cannot be shared via github due to HIPAA regulations.

3. Open the script file in RStudio (or other editor).

4. Update the following lines of code:
   * line 3: set the author of the report
   * line 60: set the path/filename to the most up-to-date Covid Database (make sure to use "\\" for any "\" when on a Windows operating system)

5. Knit the markdown file to create a pdf report (click "knit" in RStudio).
