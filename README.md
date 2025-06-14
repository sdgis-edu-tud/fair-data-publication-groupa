# Dataset title

## Table of Contents

- [1. GENERAL INFORMATION](#1-general-information)
- [2. METHODOLOGICAL INFORMATION](#2-methodological-information)
  - [2.1 Research questions, methods and envisioned uses](#21-research-questions-methods-and-envisioned-uses)
  - [2.2 Methods for processing the data](#22-methods-for-processing-the-data)
  - [2.3 Instrument- or software-specific information](#23-instrument--or-software-specific-information)
- [3. FILE OVERVIEW](#3-file-overview)
  - [3.1 File List](#31-file-list)
  - [3.2 Relationship between files](#32-relationship-between-files)
  - [3.3 File formats and naming conventions](#33-file-formats-and-naming-conventions)
- [4. DATA-SPECIFIC INFORMATION](#4-data-specific-information)
  - [4.1 Data Category A](#41-data-category-a)
  - [4.2 Data Category B](#42-data-category-b)
  - [4.3 Data Category C](#43-data-category-c)
  - [4.4 Data Category D](#44-data-category-d)
- [5. SHARING/ACCESS INFORMATION](#5-sharingaccess-information)
  - [5.1 Licenses/restrictions placed on the data](#51-licensesrestrictions-placed-on-the-data)
  - [5.2 Links to other resources](#52-links-to-other-resources)
  - [5.3 Recommended citation for this dataset](#57-recommended-citation-for-this-dataset)


# 1. GENERAL INFORMATION

## 1.1 Title of Dataset
Human-nature connectedness of the Teplica stream of Senica

## 1.2 Dataset description
This dataset contains qualitative and/or quantitative data on ... Context for the research project... Additional details about the project can be accessed [here](https://...).

## 1.3 Author Information
A. Principal Investigator  
- Name: Vincent Vanderheeren
- Institution: TU Delft
- Address: 
- Email: v.j.a.vanderheeren@student.tudelft.nl

B. Associate or Co-investigator
- Name: 
- Institution: 
- Address: 
- Email:

C. Associated study personnel 
- ...
- ...

## 1.4 Dates of data collection
- Survey 1: 2025-05-20

## 1.5 Geographic location of data collection
Teplica River, Senica, Slovakia

## 1.6 Keywords
Urban stream restoration, Quality of life, Biodiversity, Climate adaptation, river, liveability, biophylia, human-nature connectedness

## 1.7 Language
English

## 1.8 Information about funding sources that supported the collection of the data
TU Delft I guess

# 2. METHODOLOGICAL INFORMATION
## 2.1 Research questions, methods and envisioned uses
Insert brief overarching summary of methods...

### 2.1.1 Research question 1: ...?
- Instrument 1 (quan/qual)
- Instrument 2 (quan/qual)

### 2.1.2 Research question 2: ...?
- Instrument 1 (quan/qual)
- Instrument 2 (quan/qual)

### 2.1.3 Envisioned uses of the dataset
- ...
- ...

## 2.2 Methods for processing the data
- ...
- ...

## 2.3 Instrument- or software-specific information
- Software version X.X was used for ...

# 3. FILE OVERVIEW
Are there multiple versions of the dataset? Yes/No

## 3.1 File List

### 3.1.1 Biodiversity
- "species.shp":
- "green_areas.shp": 

### 3.1.2 Quality of Life
- "parks.shp": 
- "points_of_interest.shp":
- "activities.shp":

### 3.1.3 Climate Adaptation
- "built_up.tif": built-up area along the Teplica
- "q100_flood_area.shp": flood area of a q100 flood along the Teplica
- "temperature.tif": land surface temperature for a sunny day in may 2025, clipped, converted and interpolated from the LANDSAT8/9 B10 band data

### 3.1.4 MCDA
- "zones_100.shp": aggregation zones, buffered 100m from the Teplica
- "zones_200.shp": aggregation zones, buffered 200m from the Teplica
- "zones_500.shp": aggregation zones, buffered 500m from the Teplica
- "zones_1000.shp": aggregation zones, buffered 1000m from the Teplica
- "zones_2000.shp": aggregation zones, buffered 2000m from the Teplica
- "MCDA.shp": normalised data for every 200m interval of the Teplica for every criteria of the MCDA + derived MCDA scores

## 3.2 Relationship between files:
The following tables (csv files) employ a foreign key to refer to the primary key (unique identifier) in one or more other table(s):

"MCDA.shp" & "zones_xxx.shp"
- the "MCDA.shp" and the "zones_xxx.shp" file use the same primary key (ID) to refer to the 200m intervals of the Teplica stream

## 3.3 File formats and naming conventions
### 3.3.1 File formats
- .shp - vector data
- .tif - raster data

### 3.3.2 Naming conventions
- files named lower case, spaces replaced with dashes (dash-case)
- in tabular data, variable names snake case

### 3.3.3 Coordinate reference system
- data uses the EPSG:25833 (ETRS89 / UTM zone 33N) CRS

# 4. DATA-SPECIFIC INFORMATION

- Missing data code: NA
- Not Applicable: N/A

## 4.1 Data Category A

### 4.1.1 filename.extension
1. Number of variables: 

2. Number of cases/rows: 

3. Variable List:

"variable_name"
- Full name: 
- Description: 
- Type of variable: 
- Unit of measurement:
- Number of missing values: 

4. Specialised formats or other abbreviations used: 

5. Total file size: 

## 4.2 Data Category B
...

## 4.3 Data Category C
...

## 4.4 MCDA
### 4.1.1 MCDA.extension
1. Number of variables: 13

2. Number of cases/rows: 54

3. Variable List:

"variable_name"
- Full name: 
- Description: 
- Type of variable: 
- Unit of measurement:
- Number of missing values: 

4. Specialised formats or other abbreviations used: 

5. Total file size: 

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
- [Link title](link url)

### 5.2.5 Was data derived from another source?
Yes/No

## 5.3 Recommended citation for this dataset:
...

This README.md file template was generated on 2022-04-19 by Claudiu Forgaci and Adele Therias according to the 4TU.ResearchData [Guidelines for creating a README file](https://data.4tu.nl/info/en/use/publish-cite/upload-your-data-in-our-data-repository) and the Cornell University template [Guide to writing "readme" style metadata](https://cornell.app.box.com/v/ReadmeTemplate) and is licensed under CC BY 4.0
