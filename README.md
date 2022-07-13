# SNOWMED-CT-Configuration

## What is SNOWMED CT?

Please check out the following website for an excellent introduction to SNOWMED CT: https://www.snomed.org/snomed-ct/five-step-briefing. It is an ontology and not a corpus. A cursory search of Github projects does not reveal any projects related to SNOWMED, though there may be others out there.

## Purpose

  The purpose of this document is to describe how to obtain the data dictionary SNOWMED CT and put it into a form that it more easily understandable and usable. This dictionary will be used for other applications, such as obtaining free text from wikipedia, pubmed, et al. This guide specifically downloads the United States Edition, and is designed for people less familiar with programming. In this project, we will:
  - Manually download SNOWMED CT
  - Manually download Python and set up our project off of Github
  - Use python to transform SNOWMED CT
  - Use python and SQLLite to push it into a SQL server

## Requirements and Restrictions

### Extracting the ontology
This introduction assumes the user has credentials required to download SNOWMED CT. Additional terms of service can be found here: 
https://uts.nlm.nih.gov/uts/assets/LicenseAgreement.pdf?_gl=1*1s42cqv*_ga*OTc4ODE2ODk0LjE2NTc1NDM3OTI.*_ga_P1FPTH9PL4*MTY1NzU0Mzc5Mi4xLjEuMTY1NzU0NjMzMy4w

My understanding is as follows: the licensee is allowed to develop institution specific applications as long as those applications:
  - Are for within-institution use only.
  - Do not involve re-distributing the vocabulary itself or translations of it.
  - Include proper citations of SNOWMED CT.
  - Adhere to additional restrictions within certain subsections of SNOWMED CT.
    - Eg. certain parts of SNOWMED CT are from copywritten sources. Those rules from those sources need to be followed. Additional section specific restrictions apply.

### Transforming SNOWMED CT
For this program we will be using Python. We have explicitly avoided using 

### Loading SNOWMED CT
For this program we will be using SQLLite and 

## Obtaining SNOWMED CT

### Registering an account

Obtain an account via google, microsoft, your research organization, or gov.id, linked to from the following page:


