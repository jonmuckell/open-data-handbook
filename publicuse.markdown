---
layout: default
previous: guidelines.html
next: ExecutiveOrder95.html
---


Public Use of data.ny.gov
=========

The following section is intended for use by the public when interacting with data.ny.gov.

###Public Input

Data.ny.gov facilitates citizen engagement and participation directly through the website.  The portal provides the capability by which the public can engage with the data provider, and accepts submissions from users through the "Give Feedback" form.  In addition, data.ny.gov provides a mechanism for the public to submit and request online, through the site’s “Suggest a Dataset,” datasets not currently released. 

###Downloading Bulk Data
The Open New York Data platform provides an open, standards-based, RESTful application programming interface  to provide automatic access to the publicly published datasets within the open data catalogue.  The platform will be optimized towards the developer community, technical users, and researchers and enable programmatic reuse.  

###Datasets 
The Open Data Platform supports two classifications of datasets: tabular and geospatial.  A tabular dataset is a flat file that conforms to a predefined schema.  The schema defines the characteristics of a fixed number of columns, including the column name and data type.  A geospatial dataset contains information that can be readily rendered on an underlying map.  Examples of geospatial features include points (buildings), polylines (bus routes), and polygons (school districts), along with attribute information that describes characteristics of each spatial feature.

####Tabular
Datasets can be exported for download in popular human-readable formats, machine-readable standards and streamable file formats.  The Open Data Platform currently supports the following exportable tabular file formats:
* **CSV**
* **JSON**
* **PDF**
* **RDF**
* **RSS**
* **XLS**
* **XLSX**
* **XML**

####Large Files
Public data often consists of historical archives, comprised of potentially millions of records collected over an extended period of time. The Open Data Platform supports the loading, exporting and visualization of large datasets (> 1GB). 

####Geo-Spatial
Geospatial data contains geographic features and attribute data that defines the properties of geographic features.   Attributes are stored in a tabular format with unique key references to the associated geographic features.   Two export methodologies are supported for exporting geographic information:  geospatial and attribute.  Attribute layers can be exported as tabular data export file formats as identified above under Tabular. 
Geospatial data can be downloaded in any of the tabular formats defined above, as well as the following formats: 
* **Shapefile**
* **Keyhole Markup Language (KML/KMZ)**

###Application Program Interface (API)
All data on the platform can be consumed via an Application Program Interface (API) which provides direct access to the raw data for developers.   The platform’s APIs allow the end user to get results back in JSON, XML, RSS, etc.  This separation of data model and encoding allows the support of many different encoding standards, even ones that do not yet exist.  
This enables users to access the data in a host of different file formats that is independent of the original format of the data.

####Access to Datasets
The Open New York Platform supports the existence of an API Strategy that allows the developer community to dynamically query a dataset within the data catalogue. Each hosted dataset within the data catalogue will:

1.	be readily and uniformly accessible.
2.	be available for automated processing by applications and systems
3.	have a standard API Endpoint

The Endpoint points to a RESTful implementation of the underlying dataset that has been accessed.  All communication with the API is done through an HTTPS protocol. The platform provides the following preferred response types which are made available by specifying the format as part of the URI, or by sending the appropriate HTTP “Accepts” header:

* **JSON**
* **XML**
* **CSV**
* **RDF**

####Featured API Catalog
Additionally, the Open New York Platform supports the creation of a featured API Catalog that provides custom endpoints to the developer community to dynamically query the raw dataset based on “specified” dataset elements. Just like published data sets, the featured API Catalog is categorized and tagged using the common domain and metadata schema.

###Terms of Use
The OPEN-NY Terms of Use may be found on the OPEN-NY website at the following link:   https://data.ny.gov/download/77gx-ii52/application/pdf.  The terms are subject to modification as conditions warrant.  When the Terms of Use change, this will be indicated within the Terms themselves with notification of the "Last Modified Date.
