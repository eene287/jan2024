Pre-processing in Nov. 2024, EE \
I am analyzing the Daily Traffic Volume at the FTS stations in the US on a temporal scale from Jan.1st 2019
 to Dec. 31st 2020 \
 The transportation data are downloaded from the Bureau of Transportation Statistics
 (https://www.fhwa.dot.gov/policyinformation/tables/tmasdata/) in its original database format as it was collected through the FHWA Travel Monitoring Analysis System (TMAS). \
 The TMG (2001) specified fixed width volume data format is listed below. \
 In this format, each data field has its unique column with fixed width. The hourly count data for each of the 24
 hours in a day takes 24 columns. \
 The tool asks for a zipped volume file (downloaded from the FHWA Office of Highway Policy Information website
 (https://www.fhwa.dot.gov/policyinformation/tables/tmasdata/
 (https://www.fhwa.dot.gov/policyinformation/tables/tmasdata/)). \ 
 The tool then converts it to different formats with a daily record or hourly record forms. \
 Field Columns Length Description
 1 Record Type
 2-3 2 FIPS State Code
 4-5 2 Functional Classification
 6-11 6 Station Identification
 12 1 Direction of Travel
 13 1 Lane of Travel
 14-15 2 Year of Data
 16-17 2 Month of Data
 18-19 2 Day of Data
 20 1 Day of Week
 21-25 5 Traffic Volume Counted, 00:01 - 01:00
 26-30 5 Traffic Volume Counted, 01:01 - 02:00
 31-35 5 Traffic Volume Counted, 02:01 - 03:00
 36-40 5 Traffic Volume Counted, 03:01 - 04:00
 41-45 5 Traffic Volume Counted, 04:01 - 05:00
 46-50 5 Traffic Volume Counted, 05:01 - 06:00
 51-55 5 Traffic Volume Counted, 06:01 - 07:00
 56-60 5 Traffic Volume Counted, 07:01 - 08:00
 61-65 5 Traffic Volume Counted, 08:01 - 09:00
 66-70 5 Traffic Volume Counted, 09:01 - 10:00
 71-75 5 Traffic Volume Counted, 10:01 - 11:00
 76-80 5 Traffic Volume Counted, 11:01 - 12:00
 81-85 5 Traffic Volume Counted, 12:01 - 13:00
 86-90 5 Traffic Volume Counted, 13:01 - 14:00
 91-95 5 Traffic Volume Counted, 14:01 - 15:00
 96-100 5 Traffic Volume Counted, 15:01 - 16:00
 101-105 5 Traffic Volume Counted, 16:01 - 17:00
 106-110 5 Traffic Volume Counted, 17:01 - 18:00
 111-115 5 Traffic Volume Counted, 18:01 - 19:00
 116-120 5 Traffic Volume Counted, 19:01 - 20:00
 121-125 5 Traffic Volume Counted, 20:01 - 21:00
 126-130 5 Traffic Volume Counted, 21:01 - 22:00
 131-135 5 Traffic Volume Counted, 22:01 - 23:00
 136-140 5 Traffic Volume Counted, 23:01 - 24:00
 141 1 Restrictions
