HealthMapping
=============

Mapping open health data
------------------------

This is a repository for mapping public health data in the UK using open source software

**Data sources**
- data/etrust.csv
  + a list of NHS Trusts and sites incl. addresses
  + from: http://systems.hscic.gov.uk/data/ods/datadownloads/othernhs/index_html
- data/acci-emer-atte-end-2012-2013-pla.xls
  + NHS A&E attendance data for 2012/2013
  + from: http://data.gov.uk/data/resource_cache/20/204b1b55-1d0a-42eb-8b4b-bd42be229b5b/aandeattendance1213
- data/Hospital.csv
  + details (e.g. contact details/addresses) of Hospitals in the UK, incl. private hospitals
  + this file already contains latitude and longitude codes for the hospital sites!
  + from: http://media.nhschoices.nhs.uk/data/foi/Hospital.csv
- data/KH03-2014-Q2.csv
  + NHS England Bed Availability and Occupancy
  + Original file is: Beds-Open-Overnight-Web_File-Q2-2014-15-Final.xlsx
  + from: http://www.england.nhs.uk/statistics/statistical-work-areas/bed-availability-and-occupancy/bed-data-overnight/
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

2014-11-21
- Uploaded new data: 2014 Q2 Bed Availability and Occupancy Data – Overnight, from http://www.england.nhs.uk/statistics/statistical-work-areas/bed-availability-and-occupancy/bed-data-overnight/