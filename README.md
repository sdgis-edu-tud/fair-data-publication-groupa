---
editor_options: 
  markdown: 
    wrap: 72
---

# Dataset title

## Table of Contents

-   [1. GENERAL INFORMATION](#1-general-information)
-   [2. METHODOLOGICAL INFORMATION](#2-methodological-information)
    -   [2.1 Research questions, methods and envisioned
        uses](#21-research-questions-methods-and-envisioned-uses)
    -   [2.2 Methods for processing the
        data](#22-methods-for-processing-the-data)
    -   [2.3 Instrument- or software-specific
        information](#23-instrument--or-software-specific-information)
-   [3. FILE OVERVIEW](#3-file-overview)
    -   [3.1 File List](#31-file-list)
    -   [3.2 Relationship between files](#32-relationship-between-files)
    -   [3.3 File formats and naming
        conventions](#33-file-formats-and-naming-conventions)
-   [4. DATA-SPECIFIC INFORMATION](#4-data-specific-information)
    -   [4.1 Data Category A](#41-data-category-a)
    -   [4.2 Data Category B](#42-data-category-b)
    -   [4.3 Data Category C](#43-data-category-c)
    -   [4.4 Data Category D](#44-data-category-d)
-   [5. SHARING/ACCESS INFORMATION](#5-sharingaccess-information)
    -   [5.1 Licenses/restrictions placed on the
        data](#51-licensesrestrictions-placed-on-the-data)
    -   [5.2 Links to other resources](#52-links-to-other-resources)
    -   [5.3 Recommended citation for this
        dataset](#57-recommended-citation-for-this-dataset)

# 1. GENERAL INFORMATION

## 1.1 Title of Dataset

Human-nature connectedness of the Teplica stream of Senica

## 1.2 Dataset description

This dataset contains qualitative and/or quantitative data on ...
Context for the research project... Additional details about the project
can be accessed [here](https://...).

## 1.3 Author Information

A. Principal Investigator\
- Name: Vincent Vanderheeren - Institution: TU Delft - Address: - Email:
[v.j.a.vanderheeren\@student.tudelft.nl](mailto:v.j.a.vanderheeren@student.tudelft.nl){.email}

B. Associate or Co-investigator - Name: Youjin Lee - Institution: TU
Delft - Address: - Email:
[y.lee-20\@student.tudelft.nl](mailto:y.lee-20@student.tudelft.nl){.email}

-   Name: Shreya Rajmane

-   Institution: TU Delft

-   Address:

-   Email:
    [s.h.rajmand\@student.tudelft.nl](mailto:s.h.rajmand@student.tudelft.nl){.email}

-   Name: Vasileios Letsios

-   Institution: TU Delft

-   Address:

-   Email:
    [v.letsios\@student.tudelft.nl](mailto:v.letsios@student.tudelft.nl){.email}
C. Tutors
-   Name: Claudiu Forgaci

-   Institution: TU Delft

-   Email:
    [C.Forgaci@tudelft.nl](mailto:C.Forgaci@tudelft.nl){.email}
    
-   Name: Daniele Cannatella

-   Institution: TU Delft

-   Email:
    [D.Cannatella@tudelft.nl](mailto:D.Cannatella@tudelft.nl){.email}
    
-   Name: Yehan Wu

-   Institution: TU Delft

-   Email:
    Y.Wu-13@tudelft.nl](mailto:Y.Wu-13@tudelft.nl){.email}

## 1.4 Dates of data collection

-   Data from course: 2025-05-02
-   Atlas of Slovak Republic (Atlas krajiny Slovenskej republiky):
    2025-05-20
-   Landsat 8-9 Collection2 Level2: 2025-06-05

## 1.5 Geographic location of data collection

Teplica River, Senica, Slovakia

## 1.6 Keywords

Urban stream restoration, Quality of life, Biodiversity, Climate
adaptation, river, liveability, biophylia, human-nature connectedness

## 1.7 Language

English

## 1.8 Information about funding sources that supported the collection of the data

-   Data from course: TU Delft
-   Atlas of Slovak Republic: Slovak environment agency (Slovenska
    Agentura Zivotneho Prostredia)
-   Landsat 8-9 Collection2 Level2:USGS (US Geological Survey)

# 2. METHODOLOGICAL INFORMATION

## 2.1 Research questions, methods and envisioned uses

The research examines the potential for Urban stream restoration of the
Teplica stream in the city of Senica through enchanced human nature
connectedness using the ‘biophilia’ hypothesis. Currently the Teplica is
struggling with several problems, like poor flood handling, poor
morphological and ecological quality, low flow during dry periods, an
upstream dam and poorly utilized public space (Škrinár, 2025). 

The report proposes a way to determine which parts of the Teplica stream
have the most potential for human-nature connectedness. 

Methods: The research used methods of Multi-Criteria Decision
analysis(MCDA) and Typology Construction to analyse the potential of the
stream. This is done using 3 main criteria – Biodiversity, Quality of
Lfe and Climate adaptation. Each criterion contains 3 sub-criteria which
are analyzed against a spatial unit of 200m segments along the stream.
These segments have a buffer ranging from 0m to 2km parallel to the
length of the stream.  

These analyses give an indication of the human-nature connectedness
around the stream. Based on this we can give an indication of where
change is needed the most to improve this relationship. 

Check

### 2.1.1 Research question 1: How does biodiversity affect human-nature connectedness?

-   osm_greenspace (quan)
-   Slovak atlas (quan)

### 2.1.2 Research question 2: How is quality of life affected by human-nature connectedness?

-   osm_greenspace (quan)
-   osm_buildings (quan)
-   osm_activities (quan)
-   osm_POI (quan)

### 2.1.3 Research question 3: How does micro-climate affect human-nature connectedness?

-   Senica Landcover (quan)
-   Floodplains (quan)
-   Landsat 8-9 Level 2 (quan)

### 2.1.4 Envisioned uses of the dataset

-   Analyse presence, connectivity and potential of blue and green
    spaces in the city
-   Indicate the strongest and weakest areas of human-nature
    connectedness
-   Identify areas for intervention for urban stream restoration

## 2.2 Methods for processing the data

-   Percentage
-   Count
-   Summary
-   Attraction reach
-   Angular integration

## 2.3 Instrument- or software-specific information

-   QGIS version 3.34.10 was used for creating and processing spatial
    data
-   Rstudio 12.1 was used for typology construction

# 3. FILE OVERVIEW

Are there multiple versions of the dataset? Yes/No

## 3.1 File List

### 3.1.1 MCDA

-   "units.shp": units, divided by 200m length from stream Teplica
-   "buffer_100.shp": aggregation zones, buffered 100m from the Teplica
-   "buffer_200.shp": aggregation zones, buffered 200m from the Teplica
-   "buffer_500.shp": aggregation zones, buffered 500m from the Teplica
-   "buffer_1000.shp": aggregation zones, buffered 1000m from the Teplica
-   "buffer_2000.shp": aggregation zones, buffered 2000m from the Teplica
-   "MCDA.gpkg": normalised data for every 200m interval of the Teplica
    for every criteria of the MCDA + derived MCDA scores

### 3.1.2 Typology Construction

-   "MCDA+Clustering.gpkg": k-means clustering result for stream unit

## 3.2 Relationship between files:

files related to MCDA and Typology Construction ("units.shp", "buffer_xxx.shp", "MCDA.gpkg", "MCDA+Clustering.gpkg")
use the same primary key (ID) to refer to the 200m intervals of the
Teplica stream

## 3.3 File formats and naming conventions

### 3.3.1 File formats

-   .shp - vector data

-   .gpkg - vector data

-   .tif - raster data


### 3.3.2 Naming conventions

-   files named lower case, spaces replaced with underscores (kebab case)
-   in tabular data, variable names pascal case

### 3.3.3 Coordinate reference system

-   data uses the EPSG:25833 (ETRS89 / UTM zone 33N) CRS

# 4. DATA-SPECIFIC INFORMATION

-   Missing data code: NA
-   Not Applicable: N/A

## 4.1 MCDA

### 4.1.1 Units and buffers

1.  Number of variables: 1

2.  Number of cases/rows: 54

3.  Variable List:

"ID"
-   Full name: ID
-   Description: primary key that distinguishes each unit
-   Type of variable:
-   Unit of measurement:
-   Number of missing values: 0

4.  Specialised formats or other abbreviations used:

5.  Total file size:

### 4.1.2 MCDA

1.  Number of variables: 14

2.  Number of cases/rows: 54

3.  Variable List:

"ID"
-   Full name: ID
-   Description: primary key that distinguishes each unit
-   Type of variable: Decimal
-   Unit of measurement:
-   Number of missing values: 0

"Percentage"
-   Full name: Percentage of Green
-   Description: first criterion of biodiversity - normalized number derived from percentage of green in each buffered unit (200m)
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Connectivity"
-   Full name: Connectivity to Green
-   Description: second criterion of biodiversity - normalized number derived from shortest distance between stream unit to closest greenspace
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Species"
-   Full name: Presence of Species
-   Description: third criterion of biodiversity - normalized number derived from overlaps of different habitat layer
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Parks"
-   Full name: Proximity to Parks
-   Description: first criterion of quality of life - normalized number derived from aggregated proximity from houses to parks in 1000m buffered zone
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Activities"
-   Full name: Proximity to Activities
-   Description: second criterion of quality of life - normalized number derived from aggregated proximity from houses to activities in 1000m buffered zone
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"POI"
-   Full name: Concentration of POI
-   Description: third criterion of quality of life - normalized number derived from aggregated proximity from stream unit to points of interests in 200m buffered zone
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Permeability"
-   Full name: Permeability
-   Description: first criterion of climate adaptation - normalized number derived from counted number of permeable pixels from land cover raster data
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Impact of Flooding"
-   Full name: Impact of Flooding 
-   Description: second criterion of climate adaptation - normalized number derived from counted number of buildings withing flood zones 500m maximum from stream unit. (reversed: higher number means low flood risk)
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Temperature"
-   Full name: Land Surface Temperature
-   Description: second criterion of climate adaptation - normalized number derived from land surface temperature data (reversed: higher number means low land surface temperature)
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Biodiversity"
-   Full name: Biodiversity
-   Description: aggregated value of biodiversity criteria with different weights
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"QualityOfLife"
-   Full name: Quality of Life
-   Description: aggregated value of quality of life criteria with different weights
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"ClimateAdaptation"
-   Full name: Climate Adaptation
-   Description: aggregated value of climate adaptation criteria with different weights
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

4.  Specialised formats or other abbreviations used:

5.  Total file size: 128KB

### 4.2.1 MCDA+Clustering 

1.  Number of variables: 15

2.  Number of cases/rows: 54

3.  Variable List:

"ID"
-   Full name: ID
-   Description: primary key that distinguishes each unit
-   Type of variable: Decimal
-   Unit of measurement:
-   Number of missing values: 0

"Percentage"
-   Full name: Percentage of Green
-   Description: first criterion of biodiversity - normalized number derived from percentage of green in each buffered unit (200m)
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Connectivity"
-   Full name: Connectivity to Green
-   Description: second criterion of biodiversity - normalized number derived from shortest distance between stream unit to closest greenspace
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Species"
-   Full name: Presence of Species
-   Description: third criterion of biodiversity - normalized number derived from overlaps of different habitat layer
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Parks"
-   Full name: Proximity to Parks
-   Description: first criterion of quality of life - normalized number derived from aggregated proximity from houses to parks in 1000m buffered zone
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Activities"
-   Full name: Proximity to Activities
-   Description: second criterion of quality of life - normalized number derived from aggregated proximity from houses to activities in 1000m buffered zone
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"POI"
-   Full name: Concentration of POI
-   Description: third criterion of quality of life - normalized number derived from aggregated proximity from stream unit to points of interests in 200m buffered zone
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Permeability"
-   Full name: Permeability
-   Description: first criterion of climate adaptation - normalized number derived from counted number of permeable pixels from land cover raster data
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Impact of Flooding"
-   Full name: Impact of Flooding 
-   Description: second criterion of climate adaptation - normalized number derived from counted number of buildings withing flood zones 500m maximum from stream unit. (reversed: higher number means low flood risk)
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Temperature"
-   Full name: Land Surface Temperature
-   Description: second criterion of climate adaptation - normalized number derived from land surface temperature data (reversed: higher number means low land surface temperature)
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Biodiversity"
-   Full name: Biodiversity
-   Description: aggregated value of biodiversity criteria with different weights
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"QualityOfLife"
-   Full name: Quality of Life
-   Description: aggregated value of quality of life criteria with different weights
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"ClimateAdaptation"
-   Full name: Climate Adaptation
-   Description: aggregated value of climate adaptation criteria with different weights
-   Type of variable: Decimal
-   Unit of measurement:-
-   Number of missing values: 0

"Clustering"
-   Full name: Clustering Results
-   Description: results of k-means clustering for each unit
-   Type of variable: String
-   Unit of measurement:-
-   Number of missing values: 0

4.  Specialised formats or other abbreviations used:

5.  Total file size: 116KB


# 5. SHARING/ACCESS INFORMATION

## 5.1 Licenses/restrictions placed on the data:

...

## 5.2 Links to other resources:

### 5.2.1 Links to publications that cite or use the data:

...

### 5.2.2 Links to other publicly accessible locations of the data:

-   [Atlas of Slovak Republic](https://data.sazp.sk/atlas-krajiny-slovenskej-republiky/ogc-open-web-services-w3s)
-   [LandsAt 8-9 Collection 2 Level 2](https://www.usgs.gov/landsat-missions/landsat-collection-2-level-2-science-products)
-   [mpt.svk geoserver Floodplain](https://mpt.svp.sk/gisserver/rest/services/mpo_mpr/zaplavova_ciara_q0100/MapServer)

### 5.2.3 Links/relationships to ancillary data sets:

...

### 5.2.4 Links to publicly accessible scripts for analysis of the dataset:

-   [Link title](link%20url)

### 5.2.5 Was data derived from another source?

Yes

## 5.3 Recommended citation for this dataset:

...

This README.md file template was generated on 2022-04-19 by Claudiu
Forgaci and Adele Therias according to the 4TU.ResearchData [Guidelines
for creating a README
file](https://data.4tu.nl/info/en/use/publish-cite/upload-your-data-in-our-data-repository)
and the Cornell University template [Guide to writing "readme" style
metadata](https://cornell.app.box.com/v/ReadmeTemplate) and is licensed
under CC BY 4.0
