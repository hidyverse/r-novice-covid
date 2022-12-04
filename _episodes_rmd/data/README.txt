---------------------------------------------
# University of Arizona Test-Trace-Treat COVID-19 testing results

Preferred citation (DataCite format):

  Merchant, Nirav C; Davis, Jim; Franks, George H; Ly, Chun; Rios, Fernando; Wickizer, Todd; et al. (2021).
  University of Arizona Test-Trace-Treat COVID-19 testing results.
  University of Arizona Research Data Repository.
  Dataset. https://doi.org/10.25422/azu.data.14869740


Corresponding Author:
  Nirav C Merchant, RII, nirav@email.arizona.edu


License:
  CC0


DOI:
  https://doi.org/10.25422/azu.data.14869740



---------------------------------------------
## Summary

The University of Arizona as part of the Test, Trace, Treat (T3) efforts
offers two clinical diagnostic tests (Antigen, RT-PCR) to determine whether an
individual is currently infected with the COVID-19 virus. These tests are
offered on a voluntary basis to all campus community members, symptomatic
community members are encouraged to get directly tested at the Campus Health
facility.

The Antigen test samples are processed at the CLIA facilities of Harris lab
and the RT-PCR samples at the University of Arizona Genomic Core Clinical
Services.  

This data set is an archive of the daily summary of tests conducted by T3 
sites and Campus Health from August 4, 2020 to June 30, 2022 which is 
presented on the testing dashboard (https://covid19.arizona.edu/dashboard).

- v1 of this data release consists of data from August 4, 2020 to December 31, 2020 (Fall semester 2020).
- v2 of this data release consists of data from August 4, 2020 to June 30, 2021.
- v3 of this data release consists of data from August 4, 2020 to June 30, 2022



---------------------------------------------
## Files and Folders

- daily_summary.csv: CSV file containing summary testing data beginning on August 4, 2020. 
The table contains the following columns:
   result_date: Date of the testing
   affil_category: University of Arizona affiliation. Either "Employee", "Off-Campus Students" or "On-Campus Students"
   test_type: COVID-19 testing method. Either "Antigen" or "PCR"
   test_result: Result of test. Either "Negative" or "Positive"
   test_count: Number of tests in the test_result category
   test_source: Where testing was conducting. Either "Campus Health" or "Test All Test Smart"



---------------------------------------------
## Contributor Roles

The roles are defined by the CRediT taxonomy http://credit.niso.org/

  - Nirav Merchant, University of Arizona (Data Science Institute): Conceptualization, Formal Analysis, Funding acquisition, Investigation, Methodology, Project administration, Resources, Software, Supervision, Validation, Visualization, Writing - original draft, Writing - review & editing			
  - Jim Davis, University of Arizona (Data Science Institute): Resources											
  - Hagan Franks, University of Arizona (Data Science Institute): Investigation, Methodology, Resources, Software, Validation					
  - Chun Ly, University of Arizona (University Libraries): Data Curation, Software										
  - Fernando Rios, University of Arizona (University Libraries): Data Curation, Project administration								
  - Todd Wickizer, University of Arizona (Data Science Institute): Methodology, Software, Validation								
  - Gary Windham, University of Arizona (Test All Test Smart): Formal Analysis, Investigation, Methodology, Resources, Software, Validation			
  - Michelle Yung, University of Arizona (Data Science Institute): Software											



---------------------------------------------
## Additional Notes

Links:
  - https://covid19.arizona.edu/dashboard