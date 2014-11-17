HealthMapping
=============

Mapping open health data
------------------------

This is a repository for mapping public health data in the UK using open source software

**Data sources**
- data/etrust.csv
  + a list of NHS Trusts and sites incl. addresses
- data/acci-emer-atte-end-2012-2013-pla.xls
  + NHS A&E attendance data for 2012/2013
- data/Hospital.csv
  + details (e.g. contact details/addresses) of Hospitals in the UK, incl. private hospitals
  + this file already contains latitude and longitude codes for the hospital sites!

Log
===

2014-11-15
- file created
- initial data of A&E attendances in 2012-2013 uploaded from http://data.gov.uk/data/resource_cache/20/204b1b55-1d0a-42eb-8b4b-bd42be229b5b/aandeattendance1213

2014-11-16
- upload of etrust.csv data file: a list of NHS trusts and sites incl. addresses from http://data.gov.uk/dataset/england-nhs-connecting-for-health-organisation-data-service-data-files-of-nhsorganisations
- started geocoding script to elucidate the coordinates of all NHS trust sites
- upload of Hospital.csv data file: a list of all hospitals from the NHS Choices website. From: http://media.nhschoices.nhs.uk/data/foi/Hospital.csv

2014-11-17
- Made a map from Hospital.csv file via a GeoJSON file using MakeGeoJSON.Rmd