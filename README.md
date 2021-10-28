# Boston311
Analysis of the requests from Boston 311

Some cities in the U.S. have 311 services, a phone number that people call for non-emergencies requests, such as lost animals, loud noise, parking issues, etc. The city of Boston has a vast set of datasets from various types, including their 311 requests.

## Dataset

The used dataset is available [here](https://data.boston.gov/dataset/311-service-requests).

There are available data from 2011 to the present. It is updated daily.

The data used is:
* **open date**: the date the request was opened (date)
* **closed date**: the date the request was closed, NaN if the request is still open (date)
* **target date**: the date the request should be closed, NaN if the request is too fresh (date)
* **on time**: on time, if the request is still on time or was closed on time, or overdue if the request is open past the target date or was closed after it (string)
* **case status**: if the case is open or closed (string)
* **subject**: the department responsible for the request (string)
* **reason**: the reason for the request (string)
* **type**: the type of the request. Along with subject and reason is a part of case classification hierarchy: subject>reason>type (string)
* **latitude, longitude**: the coordinates of the request (float)

## Goals:

Analise the requests to answer the following questions:

* Which government departments are taking most of the complaints/requests?
* Which government departments are responding and resolving the complaints in the given time?

# Contents:

1. [Data loading and wrapping](https://github.com/Denisebps/Boston311/blob/main/Boston311_cleaning.ipynb)
2. [Departments analysis] (https://github.com/Denisebps/Boston311/blob/main/Boston311_departments_analysis.ipynb)
3. Datafolio presented in DS4A - Women's Summit
4. Dashboard 

