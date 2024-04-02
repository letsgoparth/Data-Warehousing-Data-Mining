<div align="center">
  
  
  <a href="one.md">
    <img src="images/dw.png" alt="Logo" width="100" height="100">
  </a>
  <h3 align="center">Data Warehousing & Data Mining</h3>
    BCA 6th semester notes

</div>

<br>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  UNIT 1
  <li><a href="#introduction-to-data-warehousing">Introduction to Data Warehousing</a></li>
  <ol>
    <li><a href="#overview">Overview</li>
    <li><a href="#database-and-data-warehousing">Database and Data Warehousing</li>
    <li><a href="#need-for-data-warehousing">Need for Data Warehouse</li>
    <!-- <li></a>
      <ul>
        <li><a href="#Inserting-single record">Inserting single record</a></li>
        <li><a href="#Inserting-with-reference-to-fields">Inserting with reference to fields</a></li>
        <li><a href="#inserting-multiple-records">Inserting Multiple Records</a></li>
      </ul>
    </li>
    <li><a href="#copy-table">Copy Table</a></li>
    <li><a href="#roadmap">Update</a></li>
    <li><a href="#contributing">Delete</a></li> -->
    <li><a href="#features">Features</a></li>
    <li><a href="#data-warehouses-and-data-marts">Data Warehouse and Data Marts</a></li>
    <li><a href="#components-of-data-warehousing">Components of Data Warehousing</a></li>
    <li><a href="#three-tier-data-warehouse-architecture">Three Tier Data Warehouse Architecture</a></li>
  </ol>
</details>

<br>

# Unit I

## INTRODUCTION TO DATA WAREHOUSING

### Overview
<ul>
<li>Constructed by integrating data from multiple heterogeneous
sources.
<li>Used for reporting and data analysis.
<li>Data warehousing involves data cleaning, data integration, and data consolidations.
</ul>

### Database and Data Warehousing





| **Parameter**  | **Data Warehouse**                  | **Database**                  |
|----------------|-------------------------------------|-------------------------------|
| **Workloads**  | Analytical                          | Transactional and Operational |
| **Datatype**   | Stores Histrical and Current Data   | Stores Current Data           |
| **Purpose**    | Analysis                            | Record                        |
| **Query Type** | Simple transaction queries          | Complex queries               |
| **Users**      | Data Scientists & Business Analysts | Application Developers        |

### Need for Data Warehousing


<ol>
<li> <strong> Business User </strong>

Business users require a data warehouse to view summarized data from the
past.

<li> <strong> Store Historical Data </strong>

Data Warehouse is required to store historical data.

<li> <strong> Analysis</strong>

Insights are derived from the data extracted from the data warehouse

<li> <strong> Data Consistency & Quality </strong>

Data from different sources is stored, increases uniformity and consistency

<li> <strong> Response Time</strong>

Data warehouse has low latency to facilitate real time analytics

</ol>


### Features
<ol>
<li>Subject Oriented

Data warehouses typically provide a concise and straightforward view around a particular subject
<li>Integrated

Integrates various heterogeneous data sources
<li>Time Variant

Stores Historcal data
<li>Non Volatile

Physically separate data storage in which no data manipulation can occur

</ol>

### Data Warehouses and Data Marts

| **Parameter**  | **Data Warehouse**                  | **Database**                  |
|----------------|-------------------------------------|-------------------------------|
| **Workloads**  | Analytical                          | Transactional and Operational |
| **Datatype**   | Stores Histrical and Current Data   | Stores Updated Data           |
| **Purpose**    | Analysis                            | Record                        |
| **Query Type** | Simple transaction queries          | Complex queries               |
| **Users**      | Data Scientists & Business Analysts | Application Developers        |


### Components of Data Warehousing
<ol>
<li> Source Data Component
    <ul>
        <li>Production Data

Comes from the different operating systems of the enterprise. 
<li>Internal Data

Spreadsheets, reports, customer profilers and department databases

<li>Archived Data

no longer active, long-term storage 

<li>External Data

Third party source

</ul>
<li> Data Staging Component

Preperation of files for storing in the data warehouse

<li> Data Storage

<li> Metadata

Data about the data, data catalogs, data dictionary

<li> Data Marts

<li> Management and Control Component
</ol>

### Three Tier Data Warehouse Architecture
<ol>
<li><strong>Bottom Tier</strong>

Data Warehouse Server
<ul>
<li>Consists of the Data Warehouse server, which is almost always an RDBMS.
<li>Data from operational Databases and External sources are extracted using application program interfaces called a gateway.
<li>OLE-DB (Open-Linking and Embedding for Databases), by Microsoft,

</ul>
<li><strong>Middle Tier</strong>

OLAP server
<ul>
<li>Consists of an <strong>OLAP</strong> server for fast querying of the data
warehouse.
<ol>
<li>Relational OLAP (ROLAP) model

Extended relational DBMS that maps functions on multidimensional data
<li>Multidimensional OLAP (MOLAP) model

particular purpose server
that directly implements multidimensional information and operations.


</ul>
<li><strong>Top Tier</strong>

Front end Tools

Contains front-end tools for displaying results provided by OLAP

</ol>


## Author

### __[Parth Verma](https://github.com/itsparthverma)__

<a href="https://www.linkedin.com/in/itsparthverma"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://letsgoparth.github.io/parthverma.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-255E63?style=for-the-badge&logo=About.me&logoColor=white"></a>
<a href="https://www.kaggle.com/letsgoparth"><img alt="Kaggle" src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white"></a>
<a href="mailto:letsgoparth@gmail.com"><img alt="Mail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>

Parth Verma is a Computer Application student and a Data Analytics enthusiast from Delhi, India. 


<!-- 
Thanks to for icons https://github.com/alexandresanlim/Badges4-README.md-Profile/tree/master -->