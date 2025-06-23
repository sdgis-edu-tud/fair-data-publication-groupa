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


- Data from course: TU Delft 
- Atlas of Slovak Republic: Slovak environment agency (Slovenska Agentura Zivotneho Prostredia)
- Landsat 8-9 Collection2 Level2:USGS (US Geological Survey)



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

### 3.1.1 Biodiversity

-   "species.shp":
-   "green_areas.shp":

### 3.1.2 Quality of Life

-   "parks.shp":
-   "points_of_interest.shp":
-   "activities.shp":

### 3.1.3 Climate Adaptation

-   "built_up.tif": built-up area along the Teplica
-   "q100_flood_area.shp": flood area of a q100 flood along the Teplica

**Percentage of Green**\
-   osm_greenspace: provided from course coordination team

**Connectivity to Green**\
-   osm_greenspace: provided from course coordination team

**Presence of Species**\
-   Lopatka dúhová Rhodeus amarus (European bitterling): data from Atlas
of Slovak Republic

-   Ohrozené druhy obojživelníkov a plazov (Endangered species of
    amphibians and reptiles): data from Atlas of Slovak Republic

-   Poľovné oblasti (Hunting Areas): data from Atlas of Slovak Republic

-   Muflónia zver Ovis musimon (European mouflon): data from Atlas of
    Slovak Republic

-   Zajac Lepus europaeus (European hare): data from Atlas of Slovak
    Republic

-   Jelenia zver Cervus elaphus (Red deer): data from Atlas of Slovak
    Republic

### 3.1.2 Quality of Life

**Proximity to Parks**

-   "osm_greenspace": provided from course coordination team
-   "osm_buildings": provided from course coordination team

**Proximity to Activities

-   "osm_greenspace": provided from course coordination team
-   "osm_activities": provided from course coordination team

**Concentration of POI**

-   "osm_POI": provided from course coordination team

### 3.1.3 Climate Adaptation

**Permeability**
-   "Landcover": provided from course coordination team

**Impact of Flooding**
-   "q100_flood_area.shp": flood area of a q100 flood along the Teplica

**Land Surface Temperature**
-   "built_up.tif": built-up area along the Teplica

-   "temperature.tif": land surface temperature for a sunny day in may
    2025, clipped, converted and interpolated from the LANDSAT8/9 B10
    band data

### 3.1.4 MCDA

-   "zones_100.shp": aggregation zones, buffered 100m from the Teplica
-   "zones_200.shp": aggregation zones, buffered 200m from the Teplica
-   "zones_500.shp": aggregation zones, buffered 500m from the Teplica
-   "zones_1000.shp": aggregation zones, buffered 1000m from the Teplica
-   "zones_2000.shp": aggregation zones, buffered 2000m from the Teplica
-   "MCDA.shp": normalised data for every 200m interval of the Teplica
    for every criteria of the MCDA + derived MCDA scores


    
### 3.1.5 Typology Construction

-   "clustering.gpkg": k-means clustering result for stream unit


## 3.2 Relationship between files:

The following tables (csv files) employ a foreign key to refer to the
primary key (unique identifier) in one or more other table(s):

"MCDA.shp" & "zones_xxx.shp" - the "MCDA.shp" and the "zones_xxx.shp"
file use the same primary key (ID) to refer to the 200m intervals of the
Teplica stream

## 3.3 File formats and naming conventions

### 3.3.1 File formats

-   .shp - vector data

-   .tif - raster data

-   .gpkg - vector data



### 3.3.2 Naming conventions

-   files named lower case, spaces replaced with dashes (dash-case)
-   in tabular data, variable names snake case

### 3.3.3 Coordinate reference system

-   data uses the EPSG:25833 (ETRS89 / UTM zone 33N) CRS

# 4. DATA-SPECIFIC INFORMATION

-   Missing data code: NA
-   Not Applicable: N/A

## 4.1 Data Category A

### 4.1.1 filename.extension

1.  Number of variables:

2.  Number of cases/rows:

3.  Variable List:

"variable_name" - Full name: - Description: - Type of variable: - Unit
of measurement: - Number of missing values:

4.  Specialised formats or other abbreviations used:

5.  Total file size:

## 4.2 Data Category B

...

## 4.3 Data Category C

...

## 4.4 MCDA

### 4.1.1 MCDA.extension

1.  Number of variables: 13

2.  Number of cases/rows: 54

3.  Variable List:

"variable_name" - Full name: - Description: - Type of variable: - Unit
of measurement: - Number of missing values:

4.  Specialised formats or other abbreviations used:

5.  Total file size:

# 5. SHARING/ACCESS INFORMATION

## 5.1 Licenses/restrictions placed on the data:

...

## 5.2 Links to other resources:

### 5.2.1 Links to publications that cite or use the data:

...

### 5.2.2 Links to other publicly accessible locations of the data:

...

### 5.2.3 Links/relationships to ancillary data sets:

...

### 5.2.4 Links to publicly accessible scripts for analysis of the dataset:

-   [Link title](link%20url)

### 5.2.5 Was data derived from another source?

Yes/No

## 5.3 Recommended citation for this dataset:

...

This README.md file template was generated on 2022-04-19 by Claudiu
Forgaci and Adele Therias according to the 4TU.ResearchData [Guidelines
for creating a README
file](https://data.4tu.nl/info/en/use/publish-cite/upload-your-data-in-our-data-repository)
and the Cornell University template [Guide to writing "readme" style
metadata](https://cornell.app.box.com/v/ReadmeTemplate) and is licensed
under CC BY 4.0
