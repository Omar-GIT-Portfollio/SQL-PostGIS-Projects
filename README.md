# Omar SQL & PostGIS Portfolio

This repository contains SQL and PostGIS projects demonstrating spatial
database design, data loading, indexing, and spatial analysis.  
The projects focus on building and querying spatial databases using
PostgreSQL with the PostGIS extension.

This work reflects coursework and hands-on practice with relational
databases and GIS-focused SQL workflows.

---

## Featured Projects

### PostGIS Data Loading & Spatial Indexing
**File:** `postgis_data_loading_and_indexing.sql`

- Loads raw coordinate data into staging tables
- Assigns and transforms spatial reference systems (SRID)
- Creates geometry columns and spatial constraints
- Builds GiST spatial indexes for efficient querying

This project demonstrates a full workflow from raw data to an indexed,
analysis-ready spatial database.

---

### PostGIS Database Design & Proximity Analysis
**File:** `postgis_restaurants_highways_proximity.sql`

- Designs a relational spatial schema with lookup tables
- Uses spatial joins and distance-based queries
- Applies `ST_DWithin` and buffering for proximity analysis
- Analyzes restaurant locations relative to major highways

This project highlights real-world spatial analysis using PostGIS.

---

### PostGIS Geometry Formats & Casting
**File:** `postgis_geometry_formats_and_casting.sql`

- Converts geometries to GeoJSON, KML, SVG, and GML
- Explores WKB and binary geometry representations
- Demonstrates geometry type casting and constraints
- Examines geometry vs. geography behavior

This project focuses on advanced PostGIS geometry handling and data formats.

---

## Supporting Materials

- **ER Diagram** (`ER Diagram.png`)  
  Visual representation of database schema and table relationships

- **SQL Queries.pdf**  
  Practice with core SQL querying, joins, filtering, and aggregation

- **Getting Data From a Database.pdf**  
  Fundamentals of retrieving and working with data from relational databases

---

## Tools & Technologies

- PostgreSQL
- PostGIS
- SQL
- Spatial indexing (GiST)
- Coordinate reference systems (SRID)

---

## Notes

- SQL scripts are written to be run in a PostGIS-enabled PostgreSQL database
- File paths and data sources may need adjustment for local execution
- Emphasis is on spatial database logic and query design rather than UI

---

## About Me

GIS major with a Computer Science & Engineering minor at The Ohio State University.  
Interested in GIS analytics, spatial databases, and geospatial data engineering.

For Python-based spatial analysis and algorithms, see my **Python Projects**
repository.
