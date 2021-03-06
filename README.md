# DS-HealthInsuranceMarketplace

Exploration Ideas
To help get you started, here are some data exploration ideas:

How do plan rates and benefits vary across states?

How do plan benefits relate to plan rates?

How do plan rates vary by age?

How do plans vary across insurance network providers?


Data Description:

This data was originally prepared and released by the Centers for Medicare & Medicaid Services (CMS). Please read the CMS Disclaimer-User Agreement before using this data.

Here, we've processed the data to facilitate analytics. This processed version has three components:

1. Original versions of the data

The original versions of the 2014, 2015, 2016 data are available in the "raw" directory of the download and "../input/raw" on Kaggle Scripts. Search for "dictionaries" on this page to find the data dictionaries describing the individual raw files.

2. Combined CSV files that contain

In the top level directory of the download ("../input" on Kaggle Scripts), there are six CSV files that contain the combined at across all years:

BenefitsCostSharing.csv <br>
BusinessRules.csv <br>
Network.csv <br>
PlanAttributes.csv <br>
Rate.csv <br>
ServiceArea.csv <br>
Additionally, there are two CSV files that facilitate joining data across years:

Crosswalk2015.csv - joining 2014 and 2015 data <br>
Crosswalk2016.csv - joining 2015 and 2016 data<br>

3. SQLite database

The "database.sqlite" file contains tables corresponding to each of the processed CSV files.
