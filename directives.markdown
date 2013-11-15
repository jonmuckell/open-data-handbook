---
layout: default
previous: index.html
next: guidelines.html
---

Directives for Participating Agencies
=========
The following directives are based upon Executive Order 95.

###Open Data Website
New York State Office of Information Technology Services will create an Open Data Website for the purposes of collecting and dissemination Publishable State data. 

###Data Coordinator
Each covered State entity will designate a Data Coordinator. The Data Coordinator shall:

* have authority equivalent to that of a Deputy Commissioner or the head of a division or department within their agency;
* have knowledge of data and resources in use by their agency; and 
* be responsible for their agency’s compliance with the Executive Order, this handbook, and future directives which may be needed to support the open data program.

The Data Coordinator serves as the liaison between the ITS data.ny.gov team and the agency.  As such, the Data Coordinator is best positioned to convey to their agency any specific needs of the Open Data platform (such as formatting the data or defining a structure that is optimal for publication). Insofar as agencies vary in terms of size, functions, and complexity, larger agencies may also identify individuals within specific divisions, bureaus, and/or units (as data champions) to assist the agency data coordinator. 

###Data Working Group (“DWG”)
ITS will form a Data Working Group (“DWG”).  The DWG will assist the CDO in carrying out his or her duties under this Order. The DWG is made up of representatives from ITS and the Information Security division of ITS, the New York State Office of General Services, the Division of Budget, a local government expert from the Department of State and eight to twelve Data Coordinators, who represent an appropriate cross-section of covered State entities.  

###Open Data Handbook
ITS, in consultation with the DWG, is required to issue guidance in this Open Data Handbook to covered State entities about implementing the Executive Order.  Within 90 days after the date of the Executive Order, ITS shall issue a provisional Open Data Handbook. Within 240 days, ITS shall issue a final Open Data Handbook.  The Open Data Handbook may be amended by ITS from time to time. 

###Publication of Data 
Each covered State entity shall create a catalogue of their Publishable State data, and propose a schedule to ITS and the CDO for making its Publishable State data publicly available.  Such schedules shall be made publicly available and provide for updating the data catalogue as appropriate.  Each covered State entity shall prioritize data publication in accordance with guidelines set forth in the Open Data Handbook.

###Participation by Localities and Other State Entities
Localities are invited, and are encouraged, to submit data to the Open Data Website for publication in accordance with guidelines set forth in this Open Data Handbook.
New York State agencies and authorities other than covered State entities shall be permitted, and are encouraged, to submit data to the Open Data Website for publication in accordance with guidelines set forth in the Open Data Handbook.

###Publishing Approvals
Participating agencies are required to engage in an internal review process and obtain approvals for the datasets which the agency wishes to commit to the Open Data Website.  Agencies are responsible for driving towards increasing data content quality and accuracy, and are responsible for ensuring compliance with all security, privacy, confidentiality laws, rules, and regulations, as well as any Intellectual Property Rights requirements and status under the NYS Freedom of Information Law (including whether data may lawfully be withheld under FOIL's limited exceptions).

For any particular dataset, at a minimum, agencies must receive explicit approval and sign-off from the individuals listed below.  Standardized approval forms provided by ITS must be completed and signed prior to dataset publication.   Agencies may determine additional internal approvals and signatures are required, and should include such additional persons in their review and sign off process (e.g. Public Information Officer) 

The Data Coordinator is responsible for obtaining the following approvals from within their agency:
* **Data Owner:**  This is typically the head of an agency department, a bureau director, or person situated similarly within the agency and likely to have been directly involved with the collection of the data.  The Data Owner will have the greatest familiarity with and knowledge of the dataset and the data it contains, and the purpose for the collection of the data.  The Data Owner should know the accuracy and currency of the data, and be best able to describe and fill in the metadata elements describing the data.  Approval by the Data Owner also validates that the agency has obtained permission and knowledge from the department which is most responsible for the specific data.  (This may also be referred to as Program owner, or Data Steward)
* **Legal counsel (e.g. in-house or an outside attorney where applicable):**  Legal counsel will likely be in the best position to determine whether the dataset has internally been reviewed sufficiently to ensure compliance with privacy and security requirements, intellectual property rights, and FOIL responsibilities.  It is recommended that the legal counsel consult with the agency's chief privacy official, chief security officer, FOIL officer, and records access officer.  
* **Point of Contact: (i.e., the agency's Data Coordinator):**  The Point of Contact is the liaison between data.ny.gov and the agency.   This person is best positioned to convey to the Data Owner any specific needs of the data.ny.gov platform maintainers for the data to be formatted or defined in an optimal manner for publication.  (For example, an individual dataset may need to be cleansed to remove extraneous, non-machine-readable elements).  This person also serves as an additional internal control ensuring the dataset has been properly evaluated before being provided to data.ny.gov.
* **Chief Executive or designee:**  Approval by the head of the agency ensures full knowledge within the agency and that the agency is providing a dataset to data.ny.gov under full authority to do so.  It also serves as the ultimate internal control to exercise authority within the agency to ensure proper evaluations of the datasets have been completed.

###Standardization
The way data consumers interact and use the Open Data Platform is greatly influenced by the way the data is published. The Open Data Platform requires the agencies to present the data in a machine-readable format to enable software tools, applications & systems to process it.  Instead of preprocessing the data, data consumers can directly access the raw data and customize the data for their own consumption needs.
 
Standardizing the data publishing model on the platform in a machine-readable format enables automation leading to the development of new, friendly analysis tools. The same data can be reused for another business use case without extra processing.

As part of the standardization process, the Open New York Data platform has identified the following minimum requirements:

###Metadata
The platform will support a common and fully described core metadata scheme for each hosted dataset and Application Program Interface (API) within the data catalogue. The metadata scheme would allow data publishers to classify selected contextual fields or elements within their dataset as well as adhere to common Meta attributes identified platform-wide empowering the data consumers to build automated discovery mechanisms at a granular-level.  Using a common metadata taxonomy will allow Open New York to convey and increase discoverability of high-value datasets

data.ny.gov adheres to core components of the Dublin Core standard for metadata (http://www.dublincore.org/documents/dces/).   The ability to search and find information is enhanced by the adherence to metadata standards required with each dataset.  In addition, metadata is linked to subject categories which provides for more precise searching and document management.  Adoption of the Dublin Core, together with standards for Open Data, maximizes adaptability and interoperability. 
  
The Dublin Core Metadata Initiative (DCMI) is incorporated as a non-profit organization hosted at the National Library Board of Singapore.  Its lists of elements, glossary, and FAQs were last revised in 2005, but an effort to update its User Guide is being developed at the wiki page http://wiki.dublincore.org/index.php/User_Guide.  data.ny.gov uses the current set of elements, which are required to accompany each dataset (Refer to Appendix B: Metadata Elements for additional details).

#####Descriptive Information
data.ny.gov serves as a platform to present machine-readable data, so that end-users may process, access, discover, extract and combine data elements to discover new insights, observations, and utility regarding the data.  In furtherance of New York State’s commitment to high quality, data.ny.gov requires agencies to submit metadata and supplemental documentation with each dataset (e.g., data dictionaries, overview documents, etc.).   This ensures data are fully described to maximize the public’s understanding and interpretation of the data and facilitates interoperability. 

#####Domain Categories
The platform supports a common domain model that allows data publishers to identify, transform and anchor datasets in a particular domain. Using a common scheme based on categories and tags, Open New York standardizes the available domains within the platform, thus helping data consumers to retrieve datasets readily and uniformly using either the standard core metadata or extending the search using domain-specific metadata.  Refer to Appendix B for examples of categories. 

#####Catalog Sharing
data.ny.gov currently federates with a number of data catalogues. The ability to federate in a bi-directional way creates a nimble and agile data ecosystem facilitating interoperability.  As technology advances, and publication of data worldwide continues to grow exponentially, there is a wealth of metadata being assembled.  The ability to query embedded metadata across catalogues can generate invaluable insights and, as such, data.ny.gov will explore common, open formats (such as DCAT).

#####Data Sets
In order to facilitate automatic processing of the data, make it easily accessible and available in machine-readable formats, standardized open data file formats for data publishers and data consumers must be made available so that they can be uploaded, retrieved, indexed and searched.

#####Open Specifications 
Published data sets must be compatible with open specifications, where they exist, and support the requirements of the agency and its data and adaptability to facilitate interoperability.  For example, additional open formats may be included, over time, such as (KML/KMZ) and GeoJSON. 

#####Content Formats
Datasets published to the Open New York platform are machine-readable and have a clear separation of metadata from the original source data.  Data Consumers will be able to automate the process of discovery, accessibility and ingestion by using the uniform open data formats supported by the platform.

####Tabular Data
The current Open Data Platform supports the following formats: 

* **CSV & TSV:** Comma/Tab Separated Values

####Geographic Data
Geospatial data is usually organized as a collection of features that define a layer.   Layers can be overlaid on top of one another, allowing visualization spatial relations, spatial queries, and analysis. The Open Data Platform supports two data formats for geospatial information.  The appropriate format is dependent on the specific characteristics of the underlying geographic data.

* **Points:** All Tabular File Formats or Shapefile
* **Lines:**  Shapefile
* **Polygons:** Shapefile

Point data can be stored in either tabular or shapefile format.  Tabular formatting of points requires either columns for latitude and longitude, or complete address information (house number, street, village/town/city, state, and zip code) that can be geocoded.  In contrast, lines and polygons define complex geometric structures that are not easily defined as column attributes.  Therefore, shapefile format is a preferred format for these complex geographic structures.  

Each shapefile (at a minimum) should contain the following files:

* **.shp:** Defines the geometry (shapes)
* **.dpf:** Defines the attribute table 
* **.prj:** Projection, ensures the feature locations are accurately rendered on the map
* **.shx:** Shape indexing file, for efficient processing

Note: Shapefiles which use projections other than WGS-1984/Web Mercatur will require conversion which may result in a minimal loss of accuracy. In some cases this conversion can be handled by the Open Data Platform; in other cases it must be done by the participating agency.

Other supported geospatial formats may include Keyhole Markup Language (KML/KMZ).

###Geocoding

The Open Data New York Platform supports geocoding services which convert human-readable address information into mappable coordinates (Latitude/Longitude).  

###Updates to Published Data Sets
Data sets on data.ny.gov must be kept up-to-date. Specific guidance regarding updates will be addressed in technical and working documents previously referenced.  Four mechanisms are supported for refreshing a dataset. 

* **Replace:** All existing records are removed and new records are inserted.
* **Append:** New dataset records are inserted
* **Update:** Existing records are modified 
* **Delete:** Existing records are removed

The frequency of updates is included in the metadata each provides with each dataset (see metadata posting frequency).
