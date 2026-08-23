# Awesome Geospatial with stars

Long list of geospatial analysis tools. Geospatial analysis, or just spatial analysis, is an approach to applying statistical analysis and other analytic techniques to data which has a geographical or spatial aspect.

![427672\_2794027726746\_176065793\_n](https://user-images.githubusercontent.com/7756611/48104109-2f465b80-e219-11e8-81bb-f6066e6a1be8.jpg)

* [Awesome Geospatial   ](#awesome-geospatial---)
  * [Database](#database)
  * [Image Classification & DIP Software](#image-classification--dip-software)
  * [Geographic Information System](#geographic-information-system)
  * [Web Map Development](#web-map-development)
  * [Web Map Server](#web-map-server)
  * [Radar](#radar)
  * [Lidar](#lidar)
  * [3D Application](#3d-application)
  * [Geographic Data Mining](#geographic-data-mining)
  * [GNSS/INS Post Processing](#gnssins-post-processing)
  * [Atmospheric Correction](#atmospheric-correction)
  * [Agent-based Modeling](#agent-based-modeling)
  * [Landscape Metrics](#landscape-metrics)
  * [Landscape Modelling](#landscape-modelling)
  * [Spatial Optimization](#spatial-optimization)
  * [Libraries](#libraries)
  * [PaaS - Platform as a Service](#paas---platform-as-a-service)
  * [SaaS - Software as a Service](#saas---software-as-a-service)
  * [DaaS - Data as a Service](#daas---data-as-a-service)
  * [Google Earth Engine](#google-earth-engine)
  * [Deep Learning](#deep-learning)
  * [MCP Servers](#mcp-servers)
  * [C](#c)
  * [C++](#c-1)
  * [C Sharp](#c-sharp)
  * [Clojure](#clojure)
  * [Crystal](#crystal)
  * [CSS](#css)
  * [Dart](#dart)
  * [Delphi](#delphi)
  * [Elixir](#elixir)
  * [Fortran](#fortran)
  * [Go](#go)
  * [Groovy](#groovy)
  * [Haskell](#haskell)
  * [IDL](#idl)
  * [Java](#java)
  * [JavaScript](#javascript)
  * [Julia](#julia)
  * [Kotlin](#kotlin)
  * [Lisp](#lisp)
  * [Lua](#lua)
  * [MATLAB](#matlab)
  * [Nim](#nim)
  * [Perl](#perl)
  * [Python](#python)
  * [PHP](#php)
  * [R](#r)
  * [Ruby](#ruby)
  * [Rust](#rust)
  * [Scala](#scala)
  * [Swift](#swift)
  * [Mobile Development](#mobile-development)
  * [Geospatial Big Data](#geospatial-big-data)
  * [Visualization](#visualization)
  * [Tools](#tools)
  * [Cheat sheets](#cheat-sheets)
  * [Data Sources](#data-sources)
  * [Resources](#resources)
    * [Icons](#icons)
    * [Color Advice](#color-advice)
  * [Free and Open Source Books](#free-and-open-source-books)
  * [Conferences](#conferences)
  * [Podcasts](#podcasts)
  * [References and other awesome lists](#references-and-other-awesome-lists)

***

## Database

* [Tile38](https://github.com/tidwall/tile38) ⭐ 9,716 | 🐛 163 | 🌐 Go | 📅 2026-08-07 - Tile38 is a geospatial database, spatial index, and realtime geofence.
* [OrientDB](https://github.com/orientechnologies/orientdb) ⭐ 4,980 | 🐛 356 | 🌐 Java | 📅 2026-08-19 - OrientDB is an Open Source Multi-Model NoSQL DBMS with the support of Native Graphs, Documents Full-Text, Reactivity, Geo-Spatial and Object Oriented concepts.
* [TileDB](https://github.com/TileDB-Inc/TileDB) ⭐ 2,072 | 🐛 116 | 🌐 C++ | 📅 2026-07-01 - TileDB is a powerful engine for storing and accessing dense and sparse multi-dimensional arrays, which can help you model any complex data efficiently.
* [Neo4j Spatial](https://github.com/neo4j-contrib/spatial) ⭐ 826 | 🐛 80 | 🌐 Java | 📅 2026-02-28 - Library of spatial utilities for Neo4j.
* [MobilityDB](https://github.com/ULB-CoDE-WIT/MobilityDB) ⭐ 623 | 🐛 10 | 🌐 C | 📅 2026-08-23 - An extension to the Postgres database which adds support for temporal and spatio-temporal objects
* [GeoCouch](https://github.com/couchbase/geocouch) ⭐ 516 | 🐛 3 | 🌐 Erlang | 📅 2021-11-10 - GeoCouch is a spatial extension for Couchbase and Apache CouchDB.
* [PointCloud](https://github.com/pgpointcloud/pointcloud) ⭐ 426 | 🐛 48 | 🌐 PLpgSQL | 📅 2026-08-08 - A PostgreSQL extension for storing point cloud (LIDAR) data.
* [PostGIS Vector Tile Utils](https://github.com/mapbox/postgis-vt-util) ⭐ 282 | 🐛 4 | 🌐 PLpgSQL | 📅 2026-06-29 - A set of PostgreSQL functions that are useful when creating vector tile sources.
* [H2GIS](https://github.com/orbisgis/h2gis) ⭐ 221 | 🐛 33 | 🌐 PLpgSQL | 📅 2026-06-24 - A spatial extension of the H2 database.
* [GeoDesk](https://github.com/clarisma/geodesk) ⭐ 192 | 🐛 43 | 🌐 Java | 📅 2026-07-17 - Fast and storage-efficient spatial database engine for OpenStreetMap data
* [duckdb-raster](https://github.com/ahuarte47/duckdb-raster) ⭐ 53 | 🐛 0 | 🌐 C | 📅 2026-08-21 - DuckDB Extension for reading and writing raster files using SQL.
* [Hastings](https://github.com/cloudant-labs/hastings) ⭐ 29 | 🐛 3 | 🌐 Erlang | 📅 2026-08-06 - GeoSpatial Search for CouchDB 2
* [yogrt](https://github.com/Anagraph/yogrt) ⭐ 19 | 🐛 3 | 🌐 Python | 📅 2022-11-16 - A simple templating tool for importing GIS data to PostGIS
* [Atlas4D](https://github.com/crisbez/atlas4d-base) ⭐ 15 | 🐛 9 | 🌐 HTML | 📅 2026-05-15 - Open-source 4D spatiotemporal platform with PostGIS, TimescaleDB, pgvector, and H3 hexagonal indexing.
* [3D CityDB](http://www.3dcitydb.org/) - A free 3D geo database to store, represent, and manage virtual 3D city models on top of a standard spatial relational database. The database model contains semantically rich, hierarchically structured, multi-scale urban objects facilitating complex GIS modeling and analysis tasks, far beyond visualization.
* [Cloudant](https://cloudant.com/) - IBM noSQL database that supports spatial data (GeoJSON).
* [DB2 Spatial Extender](http://www-03.ibm.com/software/products/en/db2spaext) - Spatial Extender allows you to store, manage, and analyze spatial data in DB2.
* [Geopackage](https://www.geopackage.org/) - SQLite spatial extension. More powerful than its older brother Spatialite.
* [Informix Spatial](https://www.ibm.com/docs/en/informix-servers/14.10?topic=guide-getting-started-spatial-data) - Informix spatial extension.
* [Microsoft SQL Server](https://docs.microsoft.com/en-us/sql/relational-databases/spatial/spatial-data-sql-server) - Microsoft SQL/SQL Azure spatial features. All the spatial functionality is also available as a .NET library (can be downloaded using nuget)
* [MongoDB](https://www.mongodb.com/) - Also supports GeoJSON and spatial indexes.
* [MySql Spatial](https://dev.mysql.com/doc/refman/8.0/en/spatial-analysis-functions.html) - MySql spatial extension.
* [Oracle Spatial](http://www.oracle.com/us/products/database/options/spatial/overview/index.html) - Oracle database spatial extension.
* [PgRouting](https://pgrouting.org/) - pgRouting extends the PostGIS / PostgreSQL geospatial database to provide geospatial routing functionality.
* [PostGEESE](https://duckdb.org/2023/04/28/spatial.html) - A spatial extension for DuckDB.
* [PostGIS](http://postgis.net/) - PostgreSql spatial extension.
* [Rasdaman](http://www.rasdaman.org/) - Array database that allows storing and querying massive multi-dimensional arrays, such as sensor, image, simulation, and statistics data appearing in domains like earth, space, and life science.
* [SciDB](http://www.paradigm4.com/) - Array database designed for multidimensional data management and analytics common to scientific, geospatial, financial, and industrial applications.
* [Spatialite](http://www.gaia-gis.it/gaia-sins/) - SQLite spatial extension.
* [Teradata Geospatial Feature](https://docs.teradata.com/r/Teradata-VantageTM-Geospatial-Data-Types/March-2019/Geospatial-Data/Geospatial-Information) - Teradata spatial extension for DW and BI.

## Image Classification & DIP Software

* [gdal2tilesp](https://github.com/pramsey/gdal2tilesp) ⭐ 81 | 🐛 6 | 🌐 Python | 📅 2021-11-09 - This enhancement to the gdal2tiles.py script includes additional features.
* [ArcMap Raster Edit Suite](https://github.com/haoliangyu/ares) ⚠️ Archived - An ArcMap Addin that enables manual editing of single pixels on raster layer.
* [Interimage](https://github.com/nuest/interimage-container) ⭐ 0 | 🐛 1 | 📅 2016-06-07 - Open Source GEOBIA software.
* [ContextCapture](https://www.bentley.com/software/contextcapture/) - ContextCapture enables you to automatically generate multi-resolution 3D models at any scale and precision.
* [Correlator3D](https://www.simactive.com/correlator3d-mapping-software-features) - High-end photogrammetry suite.
* [Dinamica EGO](http://csr.ufmg.br/dinamica/) - Dinamica EGO consists of a sophisticated platform for environmental modeling.
* [e-Foto](http://www.efoto.eng.uerj.br/en) - Free and open source digital photogrammetric workstation.
* [eCognition](https://geospatial.trimble.com/products-and-solutions/ecognition) - GEOBIA software.
* [ENVI](https://www.nv5geospatialsoftware.com/Products/ENVI) - Geospatial image processing and classification software.
* [ERDAS](http://www.hexagongeospatial.com/products/producer-suite/erdas-imagine) - Geospatial image processing and classification software.
* [Global Mapper](http://www.bluemarblegeo.com/products/global-mapper.php) - Geospatial and remote sensing data analysis.
* [Guidos Toolbox](http://forest.jrc.ec.europa.eu/download/software/guidos/) - Some GDAL functionalities and includes MSPA (Morphological Spatial Pattern Analysis) for connectivity maps.
* [IDL](https://www.nv5geospatialsoftware.com/Products/IDL) - IDL is a programming language used for data analysis and image processing programming.
* [INPHO](https://geospatial.trimble.com/products-and-solutions/trimble-inpho) - INPHO is a Digital Photogrammetry Software.
* [Matlab](http://www.mathworks.com/products/matlab/) - Multi-paradigm numerical computing environment and fourth-generation programming language.
* [Metashape](https://www.agisoft.com/) - Agisoft Metashape is a stand-alone software product that performs photogrammetric processing of digital images.
* [MultiSpec](https://engineering.purdue.edu/~biehl/MultiSpec/index.html) - A Freeware Multispectral Image Data Analysis System.
* [OSSIM](http://trac.osgeo.org/ossim/) - Suite of geospatial libraries and applications used to process imagery, maps, terrain, and vector data.
* [PCI Geomatica](http://www.pcigeomatics.com/software/geomatica/professional) - Remote sensing software package for image processing
* [RealityCapture](https://www.realitycapture-training.com/) - Photogrammetry software.
* [SNAP](https://step.esa.int/main/download/snap-download/) - SNAP is an open source common architecture for ESA Toolboxes ideal for the exploitation of Earth Observation data.
* [Spring](http://www.dpi.inpe.br/spring/) - GIS and remote sensing image processing system with an object-oriented data model.
* [TerrSet](https://clarklabs.org/terrset/) - TerrSet (formerly IDRISI) is an integrated geographic information system (GIS) and remote sensing software
* [The Sentinel Toolbox](https://step.esa.int/main/toolboxes/) - The Sentinel Toolboxes consists of a collection of processing tools, data product readers and writers and a display and analysis application to process Sentinel data.
* [TIMESAT](http://web.nateko.lu.se/timesat/timesat.asp?cat=0) - TIMESAT is a software package for analysing time-series of satellite sensor data.
* [WebODM](https://www.opendronemap.org/webodm/) - Generate maps, point clouds, DEMs and 3D models from aerial images.

## Geographic Information System

* [Mapbox Studio](https://github.com/mapbox/mapbox-studio-classic) ⚠️ Archived - Desktop application for vector tile driven map design.
* [TerraMA2](https://github.com/TerraMA2/terrama2) ⭐ 34 | 🐛 5 | 🌐 C++ | 📅 2021-09-02 - A free and open source computational platform for early warning systems.
* [ArcGIS Pro](https://pro.arcgis.com/en/pro-app/) - Fully 64-bit version of ArcGIS with new GUI and 2D/3D integration.
* [ArcGIS](https://www.arcgis.com/features/) - GIS for working with maps and geographic information.
* [AutoCAD Map 3D](http://www.autodesk.com.br/products/autocad-map-3d/overview) - GIS AutoCAD integration.
* [FME Desktop](https://www.safe.com/fme/fme-desktop/) - FME is an integrated collection of Spatial ETL tools for data transformation and data translation.
* [GC2](http://www.mapcentia.com/en/product/) - GC2 is an enterprise platform GIS (open source)
* [GeoDa](http://geodacenter.github.io/) - Spatial data analysis software.
* [Geomedia](https://hexagon.com/products/geomedia) - Commercial GIS.
* [GRASS GIS](https://grass.osgeo.org/) - GRASS (Geographic Resources Analysis Support System) is a free and open source GIS.
* [gvSIG](http://www.gvsig.com/en) - Free and open source GIS.
* [ILWIS](http://52north.org/communities/ilwis/ilwis-open) - Integrated Land and Water Information System (ILWIS) is a remote sensing and GIS software.
* [LuciadFusion](http://www.luciad.com/solutions/luciadfusion) - An all-in-one server solution for your data publication workflow and geospatial data management
* [Manifold System](http://www.manifold.net/) - Commercial GIS.
* [MapInfo](https://www.geograph.com.br/mapinfo) - Commercial GIS.
* [MapWindow GIS](http://www.mapwindow.org/) - Free and open source desktop geographic information system.
* [MicroImages TNTgis](https://www.microimages.com/) - Commercial GIS.
* [OpenJUMP](http://openjump.org/) - Open source Java GIS.
* [QGIS](http://www.qgis.org/en/site/) - Cross-platform free and open-source desktop geographic information system.
* [SAGA](http://www.saga-gis.org/en/index.html) - SAGA is the abbreviation for System for Automated Geoscientific Analyses.
* [Smallworld](https://www.gegridsolutions.com/geospatial/catalog/smallworld_core.htm) - Commercial GIS.
* [Terraview](http://www.obt.inpe.br/OBT/assuntos/projetos/terralib-terraview) - GIS application built using the TerraLib  GIS library.
* [uDig](http://udig.refractions.net/) - A GIS Framework for Eclipse (Java) and also a GIS software.

## Web Map Development

* [MapLibre GL](https://github.com/maplibre/maplibre-gl-js) ⭐ 11,411 | 🐛 387 | 🌐 TypeScript | 📅 2026-08-23 - Is a community led fork derived from Mapbox GL JS prior to their switch to a non-OSS license.
* [MapTalks.js](https://github.com/maptalks/maptalks.js) ⭐ 4,533 | 🐛 118 | 🌐 HTML | 📅 2026-08-18 - An open-source JavaScript library for integrated 2D/3D maps.
* [L7](https://github.com/antvis/L7) ⭐ 4,056 | 🐛 214 | 🌐 TypeScript | 📅 2026-07-30 - Large-scale WebGL-powered Geospatial Data Visualization By Ant Financial
* [datamaps](https://github.com/markmarkoh/datamaps) ⭐ 3,799 | 🐛 229 | 🌐 JavaScript | 📅 2026-02-10 - Customizable map visualizations in one file.
* [react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) ⭐ 3,308 | 🐛 190 | 🌐 JavaScript | 📅 2024-08-08 - An SVG mapping component library for React, built on top of d3-geo.
* [globe.gl](https://github.com/vasturiano/globe.gl) ⭐ 3,146 | 🐛 131 | 🌐 HTML | 📅 2026-08-22 - This library is a convenience wrapper around the three-globe plugin, using ThreeJS/WebGL for 3D rendering.
* [Mapzen Tangram](https://github.com/tangrams/tangram) ⭐ 2,334 | 🐛 66 | 🌐 JavaScript | 📅 2026-02-08 - JavaScript library for rendering 2D & 3D maps live in a web browser with WebGL, supports MVT, GeoJSON, TopoJSON.
* [geojson-vt](https://github.com/mapbox/geojson-vt) ⭐ 2,041 | 🐛 15 | 🌐 JavaScript | 📅 2026-07-02 - A highly efficient JavaScript library for slicing GeoJSON data into vector tiles on the fly.
* [TerriaJS](https://github.com/TerriaJS/terriajs) ⭐ 1,357 | 🐛 891 | 🌐 TypeScript | 📅 2026-08-21 - A library for building rich, web-based geospatial data explorers.
* [d3-geo-projection](https://github.com/d3/d3-geo-projection) ⭐ 1,152 | 🐛 27 | 🌐 JavaScript | 📅 2023-07-12 - Extended geographic projections for d3-geo.
* [titiler](https://github.com/developmentseed/titiler) ⭐ 1,148 | 🐛 26 | 🌐 Python | 📅 2026-08-22 - A dynamic Web Map tile server.
* [d3-geo](https://github.com/d3/d3-geo) ⭐ 1,098 | 🐛 34 | 🌐 JavaScript | 📅 2024-06-28 - A library for creating maps based on D3.js.
* [Map Forecast API](https://github.com/windycom/API) ⭐ 909 | 🐛 1 | 🌐 JavaScript | 📅 2022-06-27 - Simple-to-use library based on Leaflet 1.4.x. It allows you to show wind maps.
* [Wrld.js](https://github.com/wrld3d/wrld.js/) ⭐ 435 | 🐛 27 | 🌐 JavaScript | 📅 2023-07-18 - Animated 3D city maps based on Leaflet.
* [ArcGIS REST JS](https://github.com/Esri/arcgis-rest-js) ⭐ 390 | 🐛 60 | 🌐 TypeScript | 📅 2026-08-19 - Compact, modular JavaScript wrappers for the ArcGIS REST API that run in Node.js and modern browsers.
* [CMV - The Configurable Map Viewer](https://github.com/cmv/cmv-app) ⭐ 331 | 🐛 60 | 🌐 JavaScript | 📅 2026-02-13 - CMV is a community-supported open source mapping framework. CMV works with the Esri JavaScript API, ArcGIS Server, ArcGIS Online and more.
* [Bertin.js](https://github.com/neocarto/bertin) ⭐ 316 | 🐛 9 | 🌐 JavaScript | 📅 2023-10-23 - A JavaScript library for visualizing geospatial data and make thematic maps for the web.
* [Leaflet.MapboxVectorTile](https://github.com/SpatialServer/Leaflet.MapboxVectorTile) ⭐ 302 | 🐛 43 | 🌐 JavaScript | 📅 2021-10-24 - A Leaflet Plugin that renders Mapbox Vector Tiles on HTML5 Canvas.
* [d3-geo-voronoi](https://github.com/Fil/d3-geo-voronoi) ⭐ 276 | 🐛 9 | 🌐 JavaScript | 📅 2026-03-26 - Voronoi diagrams and Delaunay triangulation for the sphere.
* [gridviz](https://github.com/eurostat/gridviz) ⭐ 243 | 🐛 20 | 🌐 JavaScript | 📅 2026-05-08 - A package for visualizing gridded data.
* [v-mapbox](https://github.com/geospoc/v-mapbox) ⭐ 187 | 🐛 44 | 🌐 Vue | 📅 2024-08-12 - Vue.js wrapper for `mapbox-gl-js`.
* [Flare Cluster Layer](https://github.com/nickcam/FlareClusterLayer) ⭐ 136 | 🐛 6 | 🌐 JavaScript | 📅 2022-06-22 - ArcGIS javascript custom graphics layer. Creates clusters and creates flares for clusters.
* [Google Maps API Polyline String Decoder](https://github.com/mgd722/decode-google-maps-polyline) ⭐ 61 | 🐛 0 | 🌐 Python | 📅 2019-12-24 - Function that will convert encoded polyline strings (as returned by the Google Maps API) into a list of lat/lon pairs.
* [react-azure-maps](https://github.com/WiredSolutions/react-azure-maps) ⭐ 58 | 🐛 28 | 🌐 TypeScript | 📅 2025-12-06 - React Wrapper for azure-maps-control.
* [ArcGIS JS App Generator](https://github.com/odoe/generator-arcgis-js-app) ⭐ 42 | 🐛 3 | 🌐 JavaScript | 📅 2017-10-23 - This is a yeoman generator for ArcGIS API for JavaScript applications.
* [Pumperly](https://github.com/GeiserX/pumperly) ⭐ 31 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-22 - Open-source fuel and EV route planner that finds the cheapest stations along your route using PostGIS spatial queries, MapLibre GL JS, Valhalla routing, and Photon geocoding. Covers 36 European countries with real-time pricing.
* [vue-azure-maps](https://github.com/rickyruiz/vue-azure-maps) ⭐ 23 | 🐛 28 | 🌐 Vue | 📅 2022-12-10 - Integrate Azure Maps in your Vue application.
* [azure-maps-animations](https://github.com/Azure-Samples/azure-maps-animations) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-09 - A rich library of animations for use with the Azure Maps Web SDK.
* [azure-maps-geolocation-control](https://github.com/Azure-Samples/azure-maps-geolocation-control) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-10 - An Azure Maps Web SDK module that provides a control that uses the browser's geolocation API to locate the user on the map.
* [azure-maps-gridded-data-source](https://github.com/Azure-Samples/azure-maps-gridded-data-source) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2024-10-23 - A module for the Azure Maps Web SDK that provides a data source that clusters data points into cells of a grid area.
* [azure-maps-services-ui](https://github.com/Azure-Samples/azure-maps-services-ui) ⚠️ Archived - A set of web UI controls that wrap the Azure Maps REST services.
* [angular-azure-maps](https://github.com/Acaisoft/angular-azure-maps) ⭐ 3 | 🐛 35 | 🌐 TypeScript | 📅 2023-12-13 - Angular 6 Azure Maps is a wrapped MS Azure Map on Angular.
* [azure-maps-fullscreen-control](https://github.com/Azure-Samples/azure-maps-fullscreen-control) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2024-08-26 - An Azure Maps Web SDK module that provides a control to display the map in fullscreen mode.
* [azure-maps-swipe-map](https://github.com/Azure-Samples/azure-maps-swipe-map) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2024-08-21 - A module for the Azure Maps Web SDK that allows swiping between two overlapping maps, ideal for comparing two overlapping data sets.
* [MapLineDraw](https://github.com/patrsc/MapLineDraw) ⭐ 2 | 🐛 0 | 🌐 Vue | 📅 2025-11-19 - An open source web application for drawing smooth curves (splines) on a map, suitable for sketching or measuring railway lines or roads.
* [azure-maps-sync-maps](https://github.com/Azure-Samples/azure-maps-sync-maps) ⚠️ Archived - An Azure Maps Web SDK module that synchronizes the cameras of two or more maps.
* [Honua SDK JS](https://github.com/honua-io/honua-sdk-js) ⭐ 1 | 🐛 92 | 🌐 TypeScript | 📅 2026-08-23 - TypeScript geospatial client for ArcGIS/Esri GeoServices, OGC API, WFS, WMS/WMTS, STAC, OData, and GeoParquet with a MapLibre runtime and an ArcGIS migration codemod. [Example](https://honua-io.github.io/honua-sdk-js/guides/quickstart.html)
* [azure-maps-selection-control](https://github.com/Azure-Samples/azure-maps-selection-control) ⚠️ Archived - An Azure Maps Web SDK module that provides controls for selecting data in a data source using drawing tools or by requesting a route range polygon.
* [BuoyBoy](https://www.buoyboy.info/) - Web app for visualizing real-time NOAA and CDIP buoy data, including wave height and swell period.
* [CesiumJS](https://cesium.com/platform/cesiumjs/) - An open-source JavaScript library for world-class 3D globes and maps.
* [deck.gl](https://deck.gl) - A WebGL-powered framework for visual exploratory data analysis of large datasets.
* [GeoNode](http://geonode.org/) - A web-based application and platform for developing geospatial information systems (GIS) and for deploying spatial data infrastructures (SDI).
* [HERE maps API](https://developer.here.com/develop/javascript-api) - Build web applications with feature-rich and customizable HERE maps.
* [jVectorMap](https://jvectormap.com/) - jVectorMap is a vector-based, cross-browser and cross-platform component for interactive geography-related data visualization on the web. It provides numerious features like smooth zooming and panning, fully-customizable styling, markers, labels and tooltips.
* [Leaflet](http://leafletjs.com/) - Open-Source JavaScript Library for Mobile-Friendly Interactive Maps.
* [LuciadRIA](http://www.luciad.com/solutions/luciadria) - A JavaScript library for 3D globes and maps, with support for military symbology and desktop-like performance
* [Mapbox GL JS](https://www.mapbox.com/mapbox-gl-js/api/) - Mapbox GL JS is a JavaScript library that uses WebGL to render interactive maps from vector tiles and Mapbox styles.
* [Ol-ext](https://viglino.github.io/ol-ext/) - Cool extensions for OpenLayers (ol) - animated clusters, CSS popup, Font Awesome symbol renderer, charts for statistical map (pie/bar), layer switcher, wikipedia layer, animations, canvas filters.
* [OpenGlobus](https://www.openglobus.org/) - A javascript library designed to display interactive 3d maps and planets with map tiles, imagery and vector data, markers and 3d objects. It uses the WebGL technology, open source and completely free.
* [OpenLayers](http://openlayers.org/) - High-performance, feature-packed library for creating interactive maps on the web.
* [Oskari](https://oskari.org/) - Framework for easily building multipurpose web mapping applications utilizing distributed Spatial Data Infrastructures like INSPIRE.
* [Pharos AI](https://conflicts.app) - Open-source real-time intelligence dashboard for geopolitical conflict tracking with interactive geospatial visualization.
* [VectorAtlas](https://vectoratlas.menelabs.com/) - Free, 80KB SVG world map with one path per country, id-keyed by ISO 3166-1 alpha-2 code, ready for choropleths.

## Web Map Server

* [Terracotta](https://github.com/DHI-GRAS/terracotta) ⭐ 755 | 🐛 37 | 🌐 Python | 📅 2026-01-14 - A light-weight, versatile XYZ tile server. MIT-licensed, pure Python, serving Cloud-Optimized GeoTIFF (COG).
* [Nanocubes](https://github.com/laurolins/nanocube) ⭐ 732 | 🐛 42 | 🌐 C | 📅 2023-05-04 - An in-memory data structure for spatiotemporal data cubes.
* [PGRestAPI](https://github.com/spatialdev/PGRestAPI) ⭐ 433 | 🐛 88 | 🌐 JavaScript | 📅 2018-04-28 - Node.js REST API for PostGres Spatial Entities. AKA: SpatialServer.
* [THREDDS](https://github.com/Unidata/thredds) ⚠️ Archived - The THREDDS Data Server (TDS) is a web server that provides metadata and data access for scientific data sets, using OPeNDAP, OGC WCS, HTTP, and other data access protocols.
* [GeoLens](https://github.com/geolens-io/geolens) ⭐ 202 | 🐛 19 | 🌐 Python | 📅 2026-08-23 - Self-hosted geospatial catalog and map builder on PostGIS; upload data, get vector tiles, style and share maps. Implements OGC API - Features/Records, STAC and DCAT.
* [GeoTrellis Server](https://github.com/geotrellis/geotrellis-server) ⭐ 80 | 🐛 31 | 🌐 Scala | 📅 2026-02-09 - Tools for building raster processing and display services. It supports WMS, WCS, WMTS and can use individual rasters, STAC Catalogs (through the STAC API service) and GeoTrellis Layers as input raster sources.
* [utilery](https://github.com/tilery/utilery) ⭐ 44 | 🐛 6 | 🌐 Python | 📅 2017-11-01 - Micro vector tile manufacturing from PostGIS.
* [Planisfy](https://github.com/giseity/planisfy) ⭐ 1 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-10 - Open-source geospatial API platform for MapLibre styles, vector tiles, routing, geocoding, API keys, usage tracking, jobs, and map operations.
* [52North WPS](http://52north.org/communities/geoprocessing/wps/index.html) - The 52°North Web Processing Service (WPS) enables the deployment of geo-processes on the web in a standardized way. It features a pluggable architecture for processes and data encodings. The implementation is based on the current OpenGIS specification: 05-007r7. Its focus was the creation of an extensible framework to provide algorithms for generalization on the web.
* [Baremaps](https://baremaps.apache.org/) - An open source pipeline for producing Mapbox vector tiles from OpenStreetMap with Postgis and Java.
* [Deegree](http://www.deegree.org/) - Open source software for spatial data infrastructures and the geospatial web. Deegree offers components for geospatial data management, including data access, visualization, discovery and security. Open standards are at the heart of Deegree. It supports WMS, WFS for Catalogue Service, WCS, WPS, WMTS.
* [Geoserver](http://geoserver.org/) - WMS written in Java and relies on GeoTools. Allows users to share and edit geospatial data.
* [MapGuide](https://mapguide.osgeo.org/) - Runs on Linux or Windows, supports Apache and IIS web servers, and has APIs (PHP, .NET, Java, and JavaScript) for application development.
* [MapProxy](http://mapproxy.org/) - An open source tile server proxy for geospatial data (WMS-C, TMS, WMTS, KML SuperOverlays). It caches, accelerates and transforms data from existing map services and serves any desktop or web GIS client.
* [Mapserver](http://mapserver.org/) - WMS written in C.
* [MapTiler Server](https://www.maptiler.com/server/) - Map server for self-hosting. Publish interactive maps to get map services from your own server or laptop.
* [Zoo Project WPS](http://www.zoo-project.org/) - A WPS (Web Processing Service) implementation written in C, Python and JavaScript. It is an open source platform which implements the WPS 1.0.0 and WPS 2.0.0 standards edited by the Open Geospatial Consortium (OGC). It provides a developer-friendly framework for creating and chaining WPS compliant Web Services.

## Radar

* [PySAR](https://github.com/insarlab/PySAR) ⭐ 827 | 🐛 69 | 🌐 Python | 📅 2026-08-18 - InSAR time series analysis in Python.
* [pyroSAR](https://github.com/johntruckenbrodt/pyroSAR) ⭐ 612 | 🐛 47 | 🌐 Python | 📅 2026-08-20 - A Python Framework for Large-Scale SAR Satellite Data Processing.
* [LiCSBAS](https://github.com/yumorishita/LiCSBAS) ⭐ 283 | 🐛 4 | 🌐 Python | 📅 2024-11-29 - LiCSBAS is an open-source package in Python and bash to carry out InSAR time series analysis using LiCSAR products.
* [PyRate](https://github.com/GeoscienceAustralia/PyRate) ⚠️ Archived - A Python tool for estimating velocity and time-series from Interferometric Synthetic Aperture Radar (InSAR) data.
* [NANSAT](https://github.com/nansencenter/nansat) ⭐ 188 | 🐛 100 | 🌐 Python | 📅 2026-07-02 - Nansat is a scientist friendly Python toolbox for processing 2D satellite earth observation data.
* [InSARHub](https://github.com/jldz9/InSARHub) ⭐ 159 | 🐛 2 | 🌐 Python | 📅 2026-08-13 - A modular Python framework for end to end InSAR and time-series processing with GUI support.
* [GAMMA](https://www.gamma-rs.ch/software) - Allows processing of SAR, interferometric SAR (InSAR) and differential interferometric SAR (DInSAR).
* [GMT5SAR](https://topex.ucsd.edu/gmtsar/) - InSAR processing system based on GMT.
* [PolSARpro](https://earth.esa.int/web/polsarpro) - Open source radar image data processing software.
* [SARbian](https://eo-college.org/sarbian/) - Free and open SAR operating system (based on Debian Linux).
* [Sarmap](https://www.sarmap.ch/index.php/software/sarscape/) - Synthetic Aperture Radar processing software.
* [SARPROZ](https://www.sarproz.com/) - Implements a wide range of Synthetic Aperture Radar (SAR), Interferometric SAR (InSAR) and Multi-Temporal InSAR processing techniques.
* [Sentinel Toolboxes](https://step.esa.int/main/toolboxes/) - Free open source toolboxes for the scientific exploitation of the Sentinel missions.

## Lidar

* [potree](https://github.com/potree/potree/) ⭐ 5,584 | 🐛 822 | 🌐 JavaScript | 📅 2026-01-08 - Potree is a free open-source WebGL based point cloud renderer for large point clouds. PotreeConverter provides all files to view your point cloud with only a basic webserver running.
* [lidR](https://github.com/Jean-Romain/lidR) ⭐ 704 | 🐛 16 | 🌐 R | 📅 2026-08-14 - R package for airborne LiDAR data manipulation and visualisation for forestry application.
* [plas.io](https://github.com/verma/plasio) ⭐ 537 | 🐛 36 | 🌐 JavaScript | 📅 2020-03-26 - WebGL point cloud rendering.
* [Entwine](https://github.com/connormanning/entwine) ⭐ 527 | 🐛 3 | 🌐 C++ | 📅 2026-06-02 - Point cloud indexing for massive datasets.
* [displaz](https://github.com/c42f/displaz) ⭐ 248 | 🐛 59 | 🌐 C++ | 📅 2026-07-08 - A hackable lidar viewer.
* [rGEDI](https://github.com/carlos-alberto-silva/rGEDI) ⭐ 184 | 🐛 1 | 🌐 R | 📅 2026-03-27 - An R Package for NASA's Global Ecosystem Dynamics Investigation (GEDI) Data Visualization and Processing.
* [greyhound](https://github.com/hobu/greyhound) ⭐ 131 | 🐛 14 | 🌐 JavaScript | 📅 2018-07-11 - A point cloud streaming framework for dynamic web services and native applications.
* [Treetop](https://github.com/carlos-alberto-silva/weblidar-treetop) ⭐ 126 | 🐛 6 | 🌐 R | 📅 2025-05-14 - A Shiny-based Application for Extracting Forest Information from LiDAR data.
* [pyGEDI](https://github.com/EduinHSERNA/pyGEDI) ⭐ 109 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2022-07-17 - pyGEDI provides a high performance, lower cognitive load, and cleaner and more transparent code for data extraction, analysis, processing, and visualization of GEDI's products.
* [lidario](https://github.com/jblindsay/lidario) ⭐ 31 | 🐛 2 | 🌐 Go | 📅 2021-05-04 - A small Go library for reading and writing LiDAR (LAS) files.
* [lidar](https://github.com/jblindsay/lidar) ⭐ 6 | 🐛 0 | 🌐 Crystal | 📅 2017-02-26 - A Crystal language library for reading and writing LiDAR data in LAS format.
* [CloudCompare](https://www.danielgm.net/cc/) - 3D point cloud processing software.
* [DielmoOpenLidar](http://www.dielmo.com/eng/ficha-tecnologia-software.php?prod=21) - Open source software based in gvSIG for the management of LiDAR data.
* [FullAnalyze](https://code.google.com/archive/p/fullanalyze/) - Handling, visualizing and processing lidar data (3D point clouds and waveforms).
* [Fusion](http://forsys.cfr.washington.edu/fusion/fusionlatest.html) - CLI/GUI Lidar software.
* [Global Mapper Lidar Module](https://www.bluemarblegeo.com/products/global-mapper-lidar.php) - Lidar module for Global Mapper.
* [Laspy](http://laspy.readthedocs.io/en/latest/) - Laspy is a python library for reading, modifying, and creating .LAS LIDAR files.
* [LAStools](https://rapidlasso.de) - A collection of highly-efficient, scriptable tools with multi-core batching that process LAS, compressed LAZ, Terrasolid BIN, .shp, and ASCII.
* [LASzip](https://laszip.org/) - Quickly turns bulky LAS files into compact LAZ files without information loss.
* [libLAS](https://liblas.org/) - libLAS is a C/C++ library for reading and writing the very common LAS LiDAR format.
* [MCC-LIDAR](https://sourceforge.net/projects/mcclidar/) - Multiscale Curvature Classification for LIDAR Data.
* [PDAL](https://pdal.io/) - PDAL is a C++ BSD library for translating and manipulating point cloud data.
* [PyLAS](https://pypi.python.org/pypi/PyLAS) - A python library for reading and writing LAS files.
* [Quick Terrain Modeler](http://appliedimagery.com/) - Proprietary LiDAR exploitation software by Applied Imagery.
* [The Point Cloud Library - PCL](https://pointclouds.org/) - Standalone, large scale, open project for 2D/3D image and point cloud processing.
* [TopoDOT](https://new.certainty3d.com/) - Proprietary software for extracting topography, 3D models, GIS Assets, and more from point cloud data.

## 3D Application

* [3dfier](https://github.com/tudelft3d/3dfier) ⭐ 630 | 🐛 30 | 🌐 C++ | 📅 2026-05-06 - The open-source tool for creation of 3D models.
* [3dcitybuilder](https://github.com/arthurRuf/3dcitybuilder) ⭐ 57 | 🐛 6 | 🌐 Python | 📅 2021-07-06 - QGIS Plugin that generates 3D Models of Urban Areas.
* [ArcGIS Earth](http://www.esri.com/software/arcgis-earth) - Display data, sketch placemarks, measure distances and areas, and add annotations at any part of the world
* [CityEngine](http://www.esri.com/software/cityengine/) - Transform 2D GIS Data into Smart 3D City Models
* [Google Earth](http://earth.google.com/) - Bringing a earth view for global mapping
* [Open3D](http://www.open3d.org/) - Open-source library that supports rapid development of software that deals with 3D data. The Open3D frontend exposes a set of carefully selected data structures and algorithms in both C++ and Python.
* [Planetary Atlas](https://planetatlas.org) - Browser-based 3D globes of 14 worlds built from open NASA, USGS, ESA and JAXA imagery, with the IAU nomenclature and surface mission landing sites
* [Skyline](http://www.skylineglobe.com/SkylineGlobe/corporate/Default.aspx?) - A glimpse into Skyline's cutting-edge 3D geospatial visualization products, and their potential to transform the way your organization makes decisions, shares information and manages its assets
* [World Wind](http://worldwind.arc.nasa.gov/java/) -  Providing features for displaying with geographic data

## Geographic Data Mining

* [GeoDMA](https://sourceforge.net/projects/geodma/) - GeoDMA is a plugin for TerraView software, used for geographical data mining.
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Weka is a collection of machine learning algorithms for data mining tasks written in Java.

## GNSS/INS Post Processing

* [Applanix POSPAC MMS](https://www.applanix.com/products/pospac-mms.htm) - POSPac MMS leverages Global Navigation Satellite Systems (GNSS) and inertial navigation systems (INS) data to generate a source of truth for post-mission trajectories and mapping.
* [Leica Infinity Surveying Software](https://leica-geosystems.com/en-us/products/gnss-systems/software/leica-infinity) - Easily manage and process data from multiple sites and survey teams and from all of your different survey instruments – digital levels, total stations, UAVs, GNSS sensors, and now even scanners.
* [Novatel Waypoint](https://novatel.com/products/waypoint-post-processing-software) - Waypoint software leverages Global Navigation Satellite Systems (GNSS) and inertial navigation systems (INS) data to generate a source of truth for post-mission trajectories and mapping.
* [RTKLIB](https://github.com/tomojitakasu/RTKLIB) ⭐ 3,112 | 🐛 455 | 🌐 C | 📅 2024-05-28 - RTKLIB is an open source program package for standard and precise positioning
  with GNSS (global navigation satellite system).
* [Trimble Business Center](https://geospatial.trimble.com/en/products/software/trimble-business-center) - Trimble® Business Center (TBC) software enables surveyors to transform field data from GNSS receivers, total stations, laser scanners, mobile mapping systems, drones and more into high-quality, actionable information and client deliverables.

## Atmospheric Correction

* [gee-atmcorr-S2](https://github.com/samsammurphy/gee-atmcorr-S2) ⭐ 161 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2020-10-16 - Atmospheric correction of Sentinel 2 imagery in Google Earth Engine using Py6S.
* [6S\_emulator](https://github.com/samsammurphy/6S_emulator) ⭐ 86 | 🐛 2 | 🌐 HTML | 📅 2020-08-07 - The 6S emulator is an open-source atmospheric correction tool. It is based on the 6S radiative transfer model but it runs 100x faster with minimal additional error (i.e. < 0.5 %).
* [SIAC](https://github.com/MarcYin/SIAC) ⭐ 72 | 🐛 3 | 🌐 C | 📅 2026-08-01 - A sensor invariant Atmospheric Correction (SIAC).
* [SIAC\_GEE](https://github.com/MarcYin/SIAC_GEE) ⭐ 64 | 🐛 3 | 🌐 JavaScript | 📅 2020-10-23 - SIAC GEE version.
* [ARCSI](https://github.com/remotesensinginfo/arcsi) ⭐ 46 | 🐛 5 | 🌐 Python | 📅 2024-07-28 - The Atmospheric and Radiometric Correction of Satellite Imagery (ARCSI) software provides a command line tool for the generation of Analysis Ready Data (ARD) optical data including atmospheric correction, cloud masking, topographic correction etc.
* [radiometric\_normalization](https://github.com/planetlabs/radiometric_normalization) ⭐ 37 | 🐛 2 | 🌐 Python | 📅 2023-08-08 - Implementation of radiometric normalization workflows.
* [ACOLITE\_MR](https://github.com/acolite/acolite_mr) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2021-04-21 - Atmospheric correction for aquatic applications of metre-scale satellites.
* [6S](http://6s.ltdri.org/) - Second Simulation of the Satellite Signal in the Solar Spectrum (6S) open source algorithm.
* [ATCOR](http://www.atcor.de/) - ERDAS Imagine module.
* [i.atcorr](https://grass.osgeo.org/grass70/manuals/i.atcorr.html) - GRASS GIS module that performs atmospheric correction using the 6S algorithm.
* [Py6S](https://py6s.readthedocs.io/en/latest/) - Py6S is a interface to the Second Simulation of the Satellite Signal in the Solar Spectrum (6S) atmospheric Radiative Transfer Model through the Python programming language.
* [sen2cor](http://step.esa.int/main/third-party-plugins-2/sen2cor/) - is a processor for Sentinel-2 Level 2A product generation and formatting; it performs the atmospheric-, terrain and cirrus correction of Top-Of- Atmosphere Level 1C input data.

## Agent-based Modeling

* [Mesa](https://github.com/projectmesa/mesa) ⭐ 3,801 | 🐛 101 | 🌐 Python | 📅 2026-08-23 - Mesa is an Apache2 licensed agent-based modeling (or ABM) framework in Python.
* [nlrx](https://github.com/ropensci/nlrx) ⭐ 80 | 🐛 21 | 🌐 R | 📅 2026-08-21 - Provides tools to setup and execute NetLogo simulations from R.
* [DMASON](https://github.com/isislab-unisa/dmason) ⭐ 19 | 🐛 7 | 🌐 Java | 📅 2022-05-16 - DMASON is a parallel version of the MASON library for writing and running simulations of Agent based simulation models.
* [MASON](https://cs.gmu.edu/~eclab/projects/mason/) - MASON is a fast discrete-event multiagent simulation library core in Java, designed to be the foundation for large custom-purpose Java simulations, and also to provide more than enough functionality for many lightweight simulation needs. MASON contains both a model library and an optional suite of visualization tools in 2D and 3D.
* [NetLogo](https://ccl.northwestern.edu/netlogo/) - NetLogo is a multi-agent programmable modeling environment.
* [Repast](https://repast.github.io/) - The Repast Suite is a family of advanced, free, and open source agent-based modeling and simulation platforms.
* [SpaDES](https://spades.predictiveecology.org/) - Metapackage for implementing a variety of event-based models, with a focus on spatially explicit models. These include raster-based, event-based, and agent-based models.

## Landscape Metrics

* [landscapemetrics](https://github.com/r-spatialecology/landscapemetrics) ⭐ 262 | 🐛 12 | 🌐 R | 📅 2026-03-17 - landscapemetrics is an R package for calculating landscape metrics for categorical landscape patterns in a tidy workflow.
* [PyLandStats](https://github.com/martibosch/pylandstats) ⭐ 111 | 🐛 6 | 🌐 Python | 📅 2026-08-17 - An open-source Pythonic library to compute landscape metrics.
* [NLMR](https://github.com/ropensci/NLMR) ⭐ 68 | 🐛 11 | 🌐 R | 📅 2026-08-09 - R package to simulate neutral landscape models.
* [Makurhini](https://github.com/connectscape/Makurhini) ⭐ 57 | 🐛 14 | 🌐 HTML | 📅 2026-06-22 - R package for calculating fragmentation and landscape connectivity indices used in conservation planning.
* [LS\_METRICS](https://github.com/LEEClab/LS_METRICS) ⭐ 26 | 🐛 6 | 🌐 Python | 📅 2025-10-11 - A tool for calculating landscape connectivity and other ecologically scaled landscape metrics
* [Fragstats](https://fragstats.org/) - Spatial Pattern Analysis Program for Categorical Maps.
* [nlmpy](https://pypi.org/project/nlmpy/) - A Python package to create neutral landscape models.

## Landscape Modelling

* [GLOBIOM](https://iiasa.ac.at/web/home/research/GLOBIOM/GLOBIOM.html) - Global Biosphere Management Model (GLOBIOM) is used to analyze the competition for land use between agriculture, forestry, and bioenergy, which are the main land-based production sectors.
* [InVEST](https://naturalcapitalproject.stanford.edu/software/invest) - InVEST (Integrated Valuation of Ecosystem Services and Tradeoffs) is a suite of models used to map and value the goods and services from nature that sustain and fulfill human life.

## Spatial Optimization

* [prioritizr](https://github.com/prioritizr/prioritizr) ⭐ 137 | 🐛 14 | 🌐 R | 📅 2026-06-17 - R package that uses integer linear programming (ILP) techniques to provide a flexible interface for building and solving conservation planning problems.
* [prioriactions](https://github.com/prioriactions/prioriactions) ⭐ 11 | 🐛 1 | 🌐 R | 📅 2025-11-18 - The prioriactions R package uses a mixed integer mathematical programming (MIP) approach for building and solving multi-action conservation planning problems, where the goal is to find an optimal combination of management actions that abate threats, in an efficient way while accounting for connectivity.
* [MARXAN](https://marxansolutions.org/) - Marxan is a freely available conservation planning software. It provides decision support to a range of conservation planning problems, including the design of new reserve systems, reporting on the performance of existing reserve systems, and developing multiple-use zoning plans for natural resource management.
* [Zonation](http://conservationcorridor.org/corridor-toolbox/programs-and-tools/zonation/) - Zonation produces a hierarchical prioritization of the landscape based on the occurrence levels of biodiversity features in sites (cells) by iteratively removing the least valuable remaining cell while accounting for connectivity and generalized complementarity.

## Libraries

* [H3](https://github.com/uber/h3) ⭐ 6,484 | 🐛 167 | 🌐 C | 📅 2026-08-20 - Hexagonal hierarchical geospatial indexing system, written in C with bindings/ports in Python, JavaScript, Java, R, Rust, Go, Swift, and C#.
* [MDAL](https://github.com/lutraconsulting/MDAL) ⭐ 188 | 🐛 81 | 🌐 Roff | 📅 2026-07-31 - Mesh Data Abstraction Library.
* [GDAL](http://www.gdal.org/) - Geospatial Data Abstraction Library (GDAL) is a translator library for raster and vector geospatial data formats.
* [GEOS](https://trac.osgeo.org/geos/) - Geometry Engine - Open Source, a C++ port of the Java Topology Suite (JTS) that provides spatial predicates and functions, serving as the core engine for libraries like Shapely (Python), sf (R), and spatial databases like PostGIS.
* [GeographicLib](http://geographiclib.sourceforge.net/) - For solving geodesic problems. Implemented in C, C++, Java, Javascript, Fortran, Python and Matlab.
* [Geolib](http://www.geolib.co.uk/) - GeoLib is a fast, efficient, computational geometry library available in C++, C# and Java.
* [Mapnik](http://mapnik.org/) - C++/Python/Node.js library for map rendering.
* [PDAL](https://pdal.io/) - Point Data Abstraction Library (PDAL) is a C++ library and command-line utility for translating and manipulating point cloud data formats, similar to GDAL for raster/vector data.
* [PROJ](https://proj.org/) - Cartographic Projections library for transforming coordinates between different reference systems, with bindings/ports in almost every language (C, C++, Python, R, Java, JavaScript, Rust, Go).
* [S2 Geometry](https://s2geometry.io/) - Computational geometry and spatial indexing on the sphere, written in C++ with ports/bindings in Go, Java, Python, Rust, and R.
* [Terralib](http://www.terralib.org/) - TerraLib is a GIS classes and functions open source library.

## PaaS - Platform as a Service

* [ArcGIS Platform](https://www.esri.com/en-us/arcgis/products/arcgis-platform/overview) - Esri's PaaS with multiple location services and developer APIs.
* [Google Maps API](https://developers.google.com/maps/) - Google's PaaS (Platform as a Service) for Geocoding or analysis/processing services.
* [Mapbox GL JS](https://www.mapbox.com/mapbox-gl-js/api/) - MapBox WebGL Javascript API.
* [Mapbox.js](https://www.mapbox.com/mapbox.js/api/v2.4.0/) - MapBox Javascript API.
* [Microsoft Bing API](https://www.microsoft.com/en-us/maps) - Microsoft Bing Maps API.
* [OpenStreetMap API](http://wiki.openstreetmap.org/wiki/API_v0.6) - OpenStreetMap API.

## SaaS - Software as a Service

* [OpenSky API](https://github.com/openskynetwork/opensky-api) ⭐ 464 | 🐛 14 | 🌐 Python | 📅 2026-07-20 - Retrieve live airspace information.
* [movebank-api](https://github.com/movebank/movebank-api-doc) ⭐ 191 | 🐛 14 | 🌐 Python | 📅 2026-01-02 - Platform for animal tracking data.
* [Phantom Tide](https://github.com/tg12/phantomtide) ⭐ 122 | 🐛 4 | 📅 2026-08-18 - Real-time geospatial intelligence platform for maritime and airspace monitoring, combining vessel tracking, ADS-B flight activity, official notices, environmental context, and satellite detections in a single live map workflow.
* [Address API](https://gisco-services.ec.europa.eu/addressapi/docs/) - Pan-European address data with geocoding and reverse-geocoding.
* [API Geo](https://geo.api.gouv.fr/) - Official French geographical data API.
* [ArcGIS Online](https://www.arcgis.com/home/) - ArcGIS Online GIS platform for mapping and spatial analysis.
* [ARLAS](https://www.arlas.io/) - ARLAS Exploration is an Open Source software for exploring and analysing Geo BigData.
* [AssessorSearch](https://assessorsearch.com/) - U.S. property-record and parcel lookup service with assessor data, owner details, tax records, deeds, permits, and county-source links.
* [BC Property Check](https://bcpropertycheck.ca/) - Free parcel intelligence for British Columbia, Canada - zoning, density (Bill 44 SSMUH), riparian setbacks, ALR, BC Hydro corridors, all from open government data.
* [bng2latlong](https://www.getthedata.com/bng2latlong) - Converts British National Grid to latitude and longitude.
* [BreezoMeter](https://docs.breezometer.com/api-documentation/introduction/) - Air Quality, Weather, Pollen, and Environmental data.
* [Carto](https://carto.com/) - Cloud computing platform that provides GIS and web mapping tools for display in a web browser.
* [CenaDzialki.pl](https://cenadzialki.pl/) - Polish land-parcel analysis and valuation: price medians from notarial transactions (RCN), zoning plans (MPZP), utilities, flood/mining risk layers and a 3D house-fit check.
* [Country State City API](https://countrystatecity.in/) - Database of city, state, and country data.
* [CSV2GEO](https://csv2geo.com) - Batch geocoder using excel/csv file, text or API as an input and get latitude, longitude and an interactive map as output.
* [DataV Atlas](https://datav.aliyun.com/portal/school/atlas/area_generator) - Cloud AI platform for online real-time analysis and visualization of geo bigdata. Powered by Alibaba Cloud with Qwen.
* [Dekart](https://dekart.xyz) - Open-source alternative to CARTO. SQL to interactive map platform that connects BigQuery, Snowflake, and PostGIS. Self-host or cloud.
* [Draw on a Map](https://drawonamap.com/) - Browser-based map annotation and route-planning tool for drawing routes, markers, arrows, and radius circles on OpenStreetMap and sharing them by URL.
* [Działkopedia](https://dzialkopedia.pl) - Polish land-parcel due-diligence tool: cadastral boundaries (GUGiK), orthophoto, transaction prices (RCN) and municipal zoning plans on an OpenStreetMap-based map.
* [Fulcrum](http://www.fulcrumapp.com/) - A mobile data collection platform that allows you to build, deploy, & collect field data with your own customizable data collection apps.
* [Geobox](https://en.geobox.ir/) - Geobox is a suite of products that together cover all stages of building an online GIS.
* [Geocode.xyz](https://geocode.xyz/) - Reverse geocoding, forward geocoding, and geoparsing API.
* [Geodocs](https://geodocs.io/) - GIS-powered project management platform for construction and infrastructure projects with support for KML, KMZ, Shapefile, and GeoJSON uploads, PostGIS database, MVT vector tiles, dynamic forms, and Mapbox GL JS visualization.
* [GIS Cloud](https://www.giscloud.com/) - Real-time mapping platform for the entire workflow of your organization.
* [GISCO data distribution API](https://gisco-services.ec.europa.eu/distribution/v2/) - European Commission data source for administrative regions and boundaries.
* [GraphHopper Route Optimization API](https://www.graphhopper.com/route-optimization/) - Solves various vehicle routing problems.
* [Grundradar](https://grundradar.de/) - Free German land-parcel due-diligence tool: cadastral context, official land values, planning constraints and environmental risks from public data.
* [Honeycomb Maps](https://honeycombmaps.com) - Browser-based enterprise map dashboard software, with real-time filtering and metric calculation.
* [InstaMaps](https://get-instamaps.com) - Location formulas for Google Sheets: geocoding, routing (100-stop Google Maps links), territories and live shareable maps from spreadsheet data
* [Knowground](https://www.knowground.com) - Free, no-signup lookup of per-address US civic and environmental data - FEMA flood zone, ground elevation, NCES public schools, EPA hazard facilities, FCC broadband, and Census/ACS - each value attributed to its federal source and dated.
* [LatLng](https://www.latlng.work/) - OSM-based geocoding, reverse geocoding, places, static maps, and tile APIs.
* [LYRASENSE](https://lyrasense.com) - Agentic AI platform for satellite data analysis with a notebook environment and Google Earth Engine integration.
* [MapAtlas](https://mapatlas.eu/) - A mapping REST API providing geocoding, directions, route optimization, matrix, isochrone, MVT vector tiles, map matching, and GeoEnrich services using OpenStreetMap and proprietary data.
* [Mapbase](https://mapbase.dev/) - Location registry API that turns coordinates into official locations, custom zones, hierarchy, geometry, and SEO-ready location context. Includes autocomplete, resolve, postcodes, LAU regions, and a TypeScript SDK.
* [Mapbox](https://www.mapbox.com/) - Platform for web map design and manipulation.
* [MapTiler Cloud](https://www.maptiler.com/cloud/) - Maps API for web & mobile developers. Customize maps, upload or create own geodata and publish online.
* [Mercator](https://mercator.blue/) - Gridded earth data (weather, ocean, air quality, elevation) as value-encoded Web Mercator tiles, with an open-source MapLibre SDK for colormapped rasters, wind and current streamlines, arrows and contours.
* [Mergin Maps](https://merginmaps.com/) - A mobile data collection open-source platform for field data surveys based on QGIS. Available as service or self-hosted.
* [MyCarTracks](https://mycartracks.com) - Mainly app-based GPS vehicle tracking and automatic mileage tracking with route history, geofencing, mileage reports, and fleet visibility.
* [NetLoc8](https://netloc8.com) - IP geolocation API with city-level precision and SDKs for Next.js, React, and Go. Free tier included.
* [NMEA Checksum Calculator](https://beomanro.com/tools/net/nmea-checksum/) - Browser-based NMEA 0183 and AIS sentence checksum validator and calculator with batch processing and XOR step visualization.
* [NextGIS](http://nextgis.com/) - A cloud geospatial service that allows you to create web GIS right in the browser.
* [OnCoord](https://www.oncoord.com) - Geocoding, reverse geocoding, location intelligence, and geospatial APIs for Latin America. Includes population, terrain, nightlight activity, and POI services.
* [Open Notify](http://open-notify.org/Open-Notify-API/) - ISS location and number of people in space.
* [Open Postcode Geo API](https://www.getthedata.com/open-postcode-geo-api) - British postcodes with geospatial data.
* [Open-Meteo](https://open-meteo.com/) - Global weather forecast API.
* [OpenCage Geocoding API](https://geocoder.opencagedata.com/) - An API aggregating multiple open geo datasources (OpenStreetMap and others).
* [OpenMapTiles](https://openmaptiles.com/) - Vector tiles and map services as service, self-hosted or off-line.
* [OSM2CDR](https://osm2cdr.com/) - Web service that exports OpenStreetMap data for a drawn area or admin boundary into 62+ vector, CAD, GIS and 3D formats (CDR, DWG, DXF, SVG, Shapefile, GeoJSON, STL, PMTiles), keeping map layers editable.
* [OSRMRoute](https://osrmroute.com) - Hosted routing, distance matrix, isochrones, map-matching and geocoding REST API built on OpenStreetMap/OSRM.
* [PixelGust](https://pixelgust.com/) - A web-based geospatial analysis platform providing 30m terrain data, climate risk assessment, NDVI time series, and environmental reports for any location. Free tier and API available.
* [PostalCodes](https://postalcodes.info/api) - Global postal code search, country exports, and address validation data.
* [RainViewer](https://www.rainviewer.com/api.html) - Free weather radar and satellite data API.
* [REST countries](https://restcountries.com/) - Get country information via a RESTful API.
* [SafeStreets](https://safestreets.streetsandcommons.com) - Free address-level walkability and pedestrian-safety analysis, scoring any neighborhood on a 15-minute-city framework using OpenStreetMap and public data.
* [Sunrise and sunset](https://sunrise-sunset.org) - Provides sunset and sunrise times for locations.
* [TomTom](https://developer.tomtom.com/api-explorer-index/documentation/product-information/introduction) - Geocoding, routing, traffic, and more.
* [USGS earthquake data](https://earthquake.usgs.gov/fdsnws/event/1/) - Search earthquake data by various parameters.
* [what3words](https://developer.what3words.com/public-api) - Converts 3-word addresses to coordinates.
* [World Monitor](https://www.worldmonitor.app) - Real-time global intelligence platform aggregating live military flight tracking (ADS-B), AIS vessel monitoring, GPS jamming heatmaps, conflict event overlays, satellite data, and geopolitical risk scores on an interactive 3D globe.
* [Zornade](https://app.zornade.com) - Italian cadastral parcel intelligence platform aggregating 15+ public data sources (ISPRA hydrogeological risk, OMI real estate prices, ISTAT demographics) into a per-parcel profile covering 85M Italian cadastral parcels, with a free REST API.

## DaaS - Data as a Service

* [Apple Maps](https://mapsconnect.apple.com/) - Apple map service.
* [AtlasPI](https://atlaspi.it) - Historical geography as a service for AI agents: 1000+ polities with real GeoJSON borders, events, trade routes, succession chains and cited sources, 4500 BCE-2024. Free, no key, Apache-2.0.
* [Crime Brasil](https://crimebrasil.com.br) - Open-data platform consolidating and geocoding Brazilian crime data. \~3M incidents geocoded to neighborhood level in Rio Grande do Sul, municipality-level for MG and RJ. Free REST API, CC BY 4.0.
* [GeoRank](https://georank.place) - Monthly sunshine, temperature, rainfall and outdoor-comfort hours for 478 world cities with coordinates. Single JSON file, no key, CC BY 4.0, archived at [Zenodo](https://doi.org/10.5281/zenodo.21976372).
* [Google Maps](https://www.google.com.br/maps) - Google map service.
* [Mantle Place](https://mantle.place) - Draw an area on a globe to get elevation, features, and imagery, delivered as multiple file types you own. Free up to 2 km².
* [Microsoft Bing Maps](http://www.bing.com/mapspreview) - Microsoft map service.
* [OpenStreetMap](http://www.openstreetmap.org/) - OpenStreeMap map service.
* [OpenWaterAtlas](https://openwateratlas.com/en/datasets/) - Integrated open dataset joining 2,928 dive/kite/surf/freedive sites with per-spot climate aggregates (Open-Meteo + ERA5), 112,548 OBIS + GBIF marine species observations, and the 34,876-route OpenFlights direct-route airline graph. CSV + Parquet, CC-BY 4.0, DOI 10.5281/zenodo.20668393.
* [Pera Portal](https://portal.geopera.com) - Satellite imagery platform with a free tier: unlimited Sentinel-2 browsing with 45+ spectral indices computed in-browser. Commercial archive search and tasking across 100+ satellites (30 cm to 2 m), per-km² price shown before ordering, public STAC 1.0.0 API.
* [Postali](https://postali.app/api) - Free postal codes (zip codes) REST API for Mexico, Colombia, and Spain. \~200k entries from official sources (SEPOMEX, GeoNames). No API key, no signup, no monthly quota.
* [Seamap](https://openwaters.io/charts/seamap) - Nautical chart web-map tiles rendered weekly from OpenStreetMap seamark data: buoys and beacons with IALA colours and topmarks, lights with sector arcs and characteristics, rocks, wrecks, traffic separation schemes, and depth shading from Seascape. Vector tiles and a MapLibre GL style, CC BY 4.0.
* [Seascape](https://openwaters.io/charts/seascape) - Global bathymetry web-map tiles built from 23 global and regional open sources: Terrarium raster DEM and vector depth contours, spot soundings, and drying areas for MapLibre/Mapbox GL, CC BY 4.0.
* [Warnely](https://warnely.com/) - Composite travel-safety scores for 180 countries (FCDO + US State + Global Peace Index + WGI + live incident wire). Free REST API, OpenAPI 3.1 spec, CC BY 4.0. Returns per-country lat/lng centroids alongside score and tier.
* [Zip-Codes](https://www.zip-codes.com/api/) - REST API for US ZIP and Canadian postal code lookup, address validation, radius search, demographics, and boundaries.

## Google Earth Engine

* [geemap](https://github.com/giswqs/geemap) ⭐ 4,017 | 🐛 53 | 🌐 Python | 📅 2026-08-22 - A Python package for interactive mapping with Google Earth Engine, ipyleaflet, and ipywidgets.
* [rgee](https://github.com/r-spatial/rgee) ⭐ 776 | 🐛 63 | 🌐 R | 📅 2026-08-17 - Google Earth Engine for R.
* [eemont](https://github.com/davemlz/eemont) ⭐ 451 | 🐛 9 | 🌐 Python | 📅 2026-08-05 - A python package that extends Google Earth Engine.
* [gee\_s1\_ard](https://github.com/adugnag/gee_s1_ard) ⭐ 298 | 🐛 1 | 🌐 Python | 📅 2024-12-17 - Creates an analysis ready sentinel-1 SAR image collection in Google Earth Engine by applying additional border noise correction, speckle filtering and radiometric terrain normalization.
* [wxee](https://github.com/aazuspan/wxee) ⭐ 214 | 🐛 1 | 🌐 Python | 📅 2025-08-23 - A Python interface between Earth Engine and xarray for processing weather and climate data.
* [spectral](https://github.com/awesome-spectral-indices/spectral) ⭐ 206 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-11 - Awesome Spectral Indices for the Google Earth Engine JavaScript API (Code Editor).
* [GEET](https://github.com/sacridini/GEET) ⭐ 175 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-17 - Google Earth Engine Toolbox - Library to write small EE apps or big/complex apps with a lot less code.
* [gee-atmcorr-S2](https://github.com/samsammurphy/gee-atmcorr-S2) ⭐ 161 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2020-10-16 - Atmospheric correction of Sentinel 2 imagery in Google Earth Engine using Py6S.
* [OpenEarthEngineLibrary](https://github.com/open-geocomputing/OpenEarthEngineLibrary) ⭐ 150 | 🐛 2 | 🌐 JavaScript | 📅 2026-06-28 - Collection of code goodies for Google Earth Engine(GEE).
* [geeup](https://github.com/samapriya/geeup) ⭐ 140 | 🐛 0 | 🌐 Python | 📅 2025-12-31 - Simple CLI for Earth Engine Uploads.
* [sankee](https://github.com/aazuspan/sankee) ⭐ 106 | 🐛 2 | 🌐 Python | 📅 2025-06-25 - Visualize classified time series data with interactive Sankey plots in Google Earth Engine.
* [ee-fastapi](https://github.com/csaybar/ee-fastapi) ⭐ 88 | 🐛 1 | 🌐 Python | 📅 2021-04-25 - Flood Detection with Google Earth Engine.
* [ee-rgb-timeseries](https://github.com/jdbcode/ee-rgb-timeseries) ⭐ 71 | 🐛 5 | 🌐 JavaScript | 📅 2026-02-11 - Earth Engine JS module to color time series chart points as stretched 3-band RGB.
* [BAP-GEE](https://github.com/saveriofrancini/bap) ⭐ 64 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-23 - Best Available Pixel calculation using Google Earth Engine.
* [landsat-extract-gee](https://github.com/loicdtx/landsat-extract-gee) ⭐ 62 | 🐛 3 | 🌐 Python | 📅 2019-09-11 - Get Landsat surface reflectance time-series from google earth engine.
* [earthEngineGrabR](https://github.com/JesJehle/earthEngineGrabR) ⭐ 55 | 🐛 8 | 🌐 R | 📅 2020-06-24 - The earthEngineGrabR is an interface between R and the Google Earth Engine, which simplifies the acquisition of remote sensing data.
* [EarthEngine.jl](https://github.com/KMarkert/EarthEngine.jl) ⭐ 50 | 🐛 4 | 🌐 Julia | 📅 2023-09-02 - Google Earth Engine in Julia.
* [OEEex](https://github.com/open-geocomputing/OEEex) ⭐ 43 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-21 - A chrome extension to enhance Google Earth Engine code editor.
* [exploreRGEE](https://github.com/joshualerickson/exploreRGEE) ⭐ 23 | 🐛 1 | 🌐 R | 📅 2022-05-01 - Google Earth Engine (GEE) in the Rstudio IDE.
* [msslib](https://github.com/gee-community/msslib) ⭐ 18 | 🐛 1 | 🌐 JavaScript | 📅 2021-06-16 - An Earth Engine JavaScript library for working with Landsat MSS image data.
* [geeo](https://github.com/leonsnill/geeo) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2026-06-09 - GEEO is a processing pipeline and collection of algorithms for obtaining Analysis-Ready-Data (ARD) from Landsat and Sentinel-2 using the Google Earth Engine Python API.
* [ee-goes](https://github.com/jdbcode/ee-goes) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2021-09-23 - An Earth Engine JavaScript library for visualizing GOES-R time series.
* [AREA2](https://area2.readthedocs.io/en/latest/overview.html) - AREA 2 (“area squared” or “area two”), short for Area Estimation & Accuracy Assessment, is a Google Earth Engine application that provides comprehensive support for sampling and estimation in a design-based inference framework.
* [restee](https://kmarkert.github.io/restee/) - Aims to make plugging Earth Engine (EE) computations into downstream Python processing easier.

## Deep Learning

* [mmsegmentation](https://github.com/open-mmlab/mmsegmentation) ⭐ 9,924 | 🐛 869 | 🌐 Python | 📅 2024-08-13 - MMSegmentation is an open source semantic segmentation toolbox based on PyTorch. It is a part of the OpenMMLab project.
* [TorchGeo](https://github.com/microsoft/torchgeo) ⭐ 4,156 | 🐛 198 | 🌐 Python | 📅 2026-08-23 - TorchGeo is a PyTorch domain library, similar to torchvision, that provides datasets, transforms, samplers, and pre-trained models specific to geospatial data.
* [segment-geospatial](https://github.com/opengeos/segment-geospatial) ⭐ 4,117 | 🐛 6 | 🌐 Python | 📅 2026-08-22 - Meta AI' Segment Anything Model (SAM) for Geospatial Data
* [SNIPER](https://github.com/mahyarnajibi/SNIPER) ⭐ 2,690 | 🐛 115 | 🌐 Python | 📅 2021-08-22 - SNIPER is an efficient multi-scale object detection algorithm.
* [Raster Vision](https://github.com/azavea/raster-vision) ⭐ 2,240 | 🐛 45 | 🌐 Python | 📅 2026-06-04 - An open source framework for deep learning on satellite and aerial imagery.
* [eo-learn](https://github.com/sentinel-hub/eo-learn) ⭐ 1,246 | 🐛 7 | 🌐 Python | 📅 2026-01-15 - Earth observation processing framework for machine learning in Python.
* [PixelLib](https://github.com/ayoolaolafenwa/PixelLib) ⭐ 1,072 | 🐛 99 | 🌐 Python | 📅 2023-10-06 - Pixellib is a library for performing segmentation of images. It suports both Semantic Segmentation as Instance Segmentation.
* [DeepForest](https://github.com/weecology/DeepForest) ⭐ 767 | 🐛 107 | 🌐 Python | 📅 2026-08-18 - Python Package for Tree Crown Detection in Airborne RGB imagery.
* [LightNet](https://github.com/ansleliu/LightNet) ⭐ 725 | 🐛 14 | 🌐 Python | 📅 2020-02-23 - LightNet: Light-weight Networks for Semantic Image Segmentation (Cityscapes and Mapillary Vistas Dataset)
* [Deep Learning ArcGIS](https://github.com/Esri/deep-learning-frameworks) ⭐ 644 | 🐛 9 | 📅 2026-07-21 - Deep Learning Libraries Installers for ArcGIS.
* [TernausNetV2](https://github.com/ternaus/TernausNetV2) ⭐ 543 | 🐛 14 | 🌐 Jupyter Notebook | 📅 2020-05-23 - TernausNetV2: Fully Convolutional Network for Instance Segmentation.
* [Label Maker](https://github.com/developmentseed/label-maker) ⭐ 471 | 🐛 39 | 🌐 Python | 📅 2023-10-03 - Data Preparation for Satellite Machine Learning.
* [libtorch-yolov3](https://github.com/walktree/libtorch-yolov3) ⭐ 453 | 🐛 38 | 🌐 C++ | 📅 2020-10-16 - A Libtorch implementation of the YOLO v3 object detection algorithm.
* [Solaris](https://github.com/cosmiq/solaris) ⭐ 441 | 🐛 94 | 🌐 Python | 📅 2025-10-21 - CosmiQ Works Geospatial Machine Learning Analysis Toolkit.
* [TorchSat](https://github.com/sshuair/torchsat) ⭐ 397 | 🐛 6 | 🌐 Python | 📅 2020-08-30 - TorchSat is an open-source PyTorch framework for satellite imagery analysis.
* [tsl](https://github.com/TorchSpatiotemporal/tsl) ⭐ 386 | 🐛 22 | 🌐 Python | 📅 2026-07-27 - PyTorch library for processing spatiotemporal data.
* [Hyperspectral](https://github.com/KGPML/Hyperspectral) ⭐ 307 | 🐛 16 | 🌐 Jupyter Notebook | 📅 2019-01-14 - Deep Learning for Land-cover Classification in Hyperspectral Images.
* [YOLT](https://github.com/avanetten/yolt) ⭐ 279 | 🐛 15 | 🌐 C | 📅 2019-12-09 - You Only Look Twice: Rapid Multi-Scale Object Detection In Satellite Imagery.
* [Presto](https://github.com/nasaharvest/presto) ⭐ 278 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2026-06-10 - Lightweight, Pre-trained Transformers for Remote Sensing Timeseries.
* [ShelfNet](https://github.com/juntang-zhuang/ShelfNet) ⭐ 252 | 🐛 5 | 🌐 Python | 📅 2021-02-27 - Implementation of a CNN model for real-time semantic segmentation.
* [WaterNet](https://github.com/treigerm/WaterNet) ⚠️ Archived - A convolutional neural network that identifies water in satellite images.
* [AIDE](https://github.com/microsoft/aerial_wildlife_detection) ⭐ 244 | 🐛 29 | 🌐 Python | 📅 2026-06-10 - Annotation Interface for Data-driven Ecology: Tools for detecting wildlife in aerial images using active learning
* [SIMRDWN](https://github.com/avanetten/simrdwn) ⭐ 223 | 🐛 28 | 🌐 C | 📅 2020-05-08 - The Satellite Imagery Multiscale Rapid Detection with Windowed Networks (SIMRDWN) codebase combines some of the leading object detection algorithms into a unified framework designed to detect objects both large and small in overhead imagery.
* [sentinel-tree-cover](https://github.com/wri/sentinel-tree-cover) ⭐ 180 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2025-12-08 - Image segmentations of trees outside forest.
* [Temporal Convolutional Neural Network](https://github.com/charlotte-pel/temporalCNN) ⭐ 174 | 🐛 1 | 🌐 Python | 📅 2020-05-07 - Temporal Convolutional Neural Network for the Classification of Satellite Image Time Series.
* [platypus](https://github.com/maju116/platypus) ⭐ 135 | 🐛 31 | 🌐 R | 📅 2021-12-06 - R package for object detection and image segmentation.
* [AirNet](https://github.com/mathildor/TF-SegNet) ⭐ 101 | 🐛 5 | 🌐 Python | 📅 2018-10-08 - SegNet-like network implemented in TensorFlow to use for segmenting aerial images.
* [srcnn](https://github.com/WarrenGreen/srcnn) ⭐ 88 | 🐛 3 | 🌐 Python | 📅 2020-07-07 - Super Resolution for Satellite Imagery.
* [Pixel Decoder](https://github.com/Geoyi/pixel-decoder) ⭐ 82 | 🐛 4 | 🌐 Python | 📅 2023-03-24 - A machine learning python package to run deep learning with satellite imagery.
* [aviary](https://github.com/geospaitial-lab/aviary) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2026-08-17 - Pythonic Framework for AI Inference on Geospatial Data.
* [SamGIS](https://github.com/trincadev/samgis-be) ⚠️ Archived – Image Segmentation machine learning based (Segment Anything by Meta - Facebook) applied to GIS and geo data also with GPU requirements. A Segment Anything HuggingFace demo [here](https://huggingface.co/spaces/aletrn/samgis) and an HuggingFace [demo](https://huggingface.co/spaces/aletrn/samgis-lisa-on-cuda) with natural language-based image segmentation capabilities via [LISA](https://github.com/dvlab-research/LISA) ⭐ 2,672 | 🐛 115 | 🌐 Python | 📅 2025-02-16.

## MCP Servers

* [emem](https://github.com/Vortx-AI/emem) ⭐ 53 | 🐛 0 | 🌐 Rust | 📅 2026-08-23 - Earth memory MCP server that gives AI agents signed geospatial facts and cite-able receipts for place-based questions.
* [bhoonidhi-mcp](https://github.com/geovicco-dev/bhoonidhi-mcp) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - Model Context Protocol server for ISRO's Bhoonidhi Earth-observation portal, over the bhoonidhi-downloader SDK. Lets an AI agent search the archive in natural language, resolve place names and satellite tokens, report each scene's availability, and (with a login) save queries, download open-access scenes, and stage scenes to the cart.
* [NetLoc8 MCP](https://github.com/netloc8/netloc8-mcp) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2026-06-24 - Model Context Protocol server giving AI assistants geolocation tools to lookup country, city, region, timezone, coordinates, and ASN.
* [CARTO for Agents](https://docs.carto.com/carto-for-agents?utm_source=awesome-geospatial\&utm_medium=listing\&utm_campaign=mcp-marketplace-listings) - Official remote MCP server for CARTO, the Agentic GIS platform. Query governed warehouse data, run spatial analysis, create or edit maps and workflows, and render interactive maps in the conversation; every tool call runs inside your own data warehouse (BigQuery, Snowflake, Databricks, Redshift, or PostgreSQL).
* [League of Spin](https://leagueofspin.com/api/mcp) - Remote MCP server for finding 27,000+ outdoor ping-pong tables worldwide, built on OpenStreetMap data, with spot details and live playing conditions.
* [Microsoft Planetary Computer Pro MCP Tools](https://marketplace.visualstudio.com/items?itemName=ms-planetarycomputer.mpc-pro-mcp-tools) - A Model Context Protocol (MCP) server that enables GitHub Copilot to interact with Microsoft Planetary Computer Pro.

## C

* [libvips](https://github.com/libvips/libvips) ⭐ 11,589 | 🐛 83 | 🌐 C | 📅 2026-08-21 - A fast image processing library with low memory needs.
* [H3](https://github.com/uber/h3) ⭐ 6,484 | 🐛 167 | 🌐 C | 📅 2026-08-20 - Hexagonal hierarchical geospatial indexing system.
* [libpostal](https://github.com/openvenues/libpostal) ⭐ 4,877 | 🐛 299 | 🌐 C | 📅 2026-05-13 - A C library for parsing/normalizing street addresses around the world. Powered by statistical NLP and open geo data.
* [YOLT](https://github.com/CosmiQ/yolt) ⭐ 674 | 🐛 0 | 🌐 C | 📅 2018-10-25 - You Only Look Twice: Rapid Multi-Scale Object Detection In Satellite Imagery.
* [Datamaps](https://github.com/ericfischer/datamaps) ⭐ 350 | 🐛 4 | 🌐 C | 📅 2014-08-19 - This is a tool for indexing large lists of geographic points or lines and dynamically generating map tiles from the index for display.
* [FORCE](https://github.com/davidfrantz/force) ⭐ 198 | 🐛 21 | 🌐 C | 📅 2026-08-18 - Framework for Operational Radiometric Correction for Environmental monitoring.
* [udunits2](https://github.com/Unidata/UDUNITS-2) ⭐ 70 | 🐛 51 | 🌐 C | 📅 2026-08-19 - API and utility for arithmetic manipulation of units of physical quantities.
* [Shapefile C Library](http://shapelib.maptools.org/) - Provides the ability to write simple C programs for reading, writing and updating (to a limited extent) .shp and .dbf files.

## C++

* [Halide](https://github.com/halide/Halide) ⭐ 6,587 | 🐛 769 | 🌐 C++ | 📅 2026-08-23 - Halide is a programming language designed to make it easier to write high-performance image processing code on modern machines.
* [OpenDroneMap](https://github.com/OpenDroneMap/OpenDroneMap) ⭐ 6,389 | 🐛 112 | 🌐 Python | 📅 2026-08-21 - OpenDroneMap is a tool to postprocess drone, balloon, kite, and street view data to geographic data including orthophotos, point clouds, & textured mesh.
* [valhalla](https://github.com/valhalla/valhalla) ⭐ 6,107 | 🐛 936 | 🌐 C++ | 📅 2026-08-22 - Open Source Routing Engine for OpenStreetMap.
* [Mapbox GL Native](https://github.com/mapbox/mapbox-gl-native) ⚠️ Archived - Render Mapbox styles in mobile, desktop, and node applications using C++ and OpenGL.
* [tippecanoe](https://github.com/mapbox/tippecanoe) ⭐ 3,110 | 🐛 217 | 🌐 C++ | 📅 2026-06-29 - Build vector tilesets from large collections of GeoJSON features.
* [S2 Geometry](https://github.com/google/s2geometry) ⭐ 2,712 | 🐛 76 | 🌐 C++ | 📅 2026-08-18 - Computational geometry and spatial indexing on the sphere.
* [VROOM](https://github.com/VROOM-Project/vroom) ⭐ 1,838 | 🐛 50 | 🌐 C++ | 📅 2026-05-11 - VROOM is an open-source optimization engine written in C++17 that aim at providing good solutions to various real-life vehicle routing problems (VRP) within a small computing time.
* [osgearth](https://github.com/gwaldron/osgearth) ⭐ 1,797 | 🐛 57 | 🌐 C | 📅 2026-08-20 - A free open source C++ geospatial toolkit.
* [Mapzen Tangram-ES](https://github.com/tangrams/tangram-es) ⭐ 873 | 🐛 177 | 🌐 C++ | 📅 2024-01-08 - C++ library for rendering 2D and 3D maps using OpenGL ES 2 with custom styling and interactions
* [networkit](https://github.com/networkit/networkit) ⭐ 871 | 🐛 42 | 🌐 C++ | 📅 2026-08-17 - NetworKit is a growing open-source toolkit for large-scale network analysis.
* [libspatialindex](https://github.com/libspatialindex/libspatialindex) ⭐ 795 | 🐛 28 | 🌐 C++ | 📅 2026-07-07 - C++ implementation of R\*-tree, an MVR-tree and a TPR-tree with C API.
* [hmm](https://github.com/fogleman/hmm) ⭐ 616 | 🐛 13 | 🌐 C | 📅 2023-12-19 - Heightmap meshing utility
* [TIN Terrain](https://github.com/heremaps/tin-terrain) ⚠️ Archived - A command-line tool for converting heightmaps in GeoTIFF format into tiled optimized meshes.
* [Mapnik Vector Tile](https://github.com/mapbox/mapnik-vector-tile) ⚠️ Archived - Mapnik C++ implemention of Mapbox Vector Tile specification.
* [entwine](https://github.com/connormanning/entwine) ⭐ 527 | 🐛 3 | 🌐 C++ | 📅 2026-06-02 - Entwine is a data organization library for massive point clouds, designed to conquer datasets of hundreds of billions of points as well as desktop-scale point clouds.
* [OpenOrienteering Mapper](https://github.com/OpenOrienteering/mapper) ⭐ 494 | 🐛 553 | 🌐 C++ | 📅 2026-07-21 - OpenOrienteering Mapper is a software for creating maps for the orienteering sport.
* [cpd](https://github.com/gadomski/cpd) ⭐ 441 | 🐛 17 | 🌐 C++ | 📅 2026-06-22 - Coherent Point Drift (CPD) is a point-set registration algorithm.
* [RoutingKit](https://github.com/RoutingKit/RoutingKit) ⭐ 438 | 🐛 43 | 🌐 C++ | 📅 2026-04-13 - RoutingKit is a C++ library that provides advanced route planning functionality.
* [gSLICr](https://github.com/carlren/gSLICr) ⭐ 349 | 🐛 14 | 🌐 C++ | 📅 2024-01-03 - Real-time super-pixel segmentation.
* [RichDEM](https://github.com/r-barnes/richdem) ⭐ 323 | 🐛 64 | 🌐 C++ | 📅 2024-06-24 - High-performance Terrain and Hydrology Analysis.
* [Selene](https://github.com/kmhofmann/selene) ⭐ 314 | 🐛 1 | 🌐 C++ | 📅 2022-08-04 - A C++14 image representation, processing and I/O library.
* [TauDEM](https://github.com/dtarb/TauDEM) ⭐ 274 | 🐛 94 | 🌐 C++ | 📅 2026-07-24 - Terrain Analysis Using Digital Elevation Models (TauDEM) software for hydrologic terrain analysis and channel network extraction.
* [OSMExpress](https://github.com/protomaps/OSMExpress) ⭐ 271 | 🐛 12 | 🌐 C++ | 📅 2025-12-04 - Fast database file format for OpenStreetMap.
* [LASzip](https://github.com/LASzip/LASzip) ⭐ 233 | 🐛 26 | 🌐 C++ | 📅 2026-08-21 - Quickly turns bulky LAS files into compact LAZ files without information loss.
* [depthmapX](https://github.com/varoudis/depthmapX) ⭐ 194 | 🐛 10 | 🌐 C++ | 📅 2026-08-09 - Multi-platform Spatial Network Analysis Software.
* [otbtf](https://github.com/remicres/otbtf) ⭐ 167 | 🐛 22 | 🌐 C++ | 📅 2025-05-20 - Deep learning with otb.
* [gdalcubes](https://github.com/appelmar/gdalcubes) ⭐ 131 | 🐛 36 | 🌐 C++ | 📅 2026-05-29 - gdalcubes is a library to represent collections of Earth Observation (EO) images as on demand data cubes (or multidimensional arrays).
* [prepair](https://github.com/tudelft3d/prepair) ⭐ 114 | 🐛 12 | 🌐 C++ | 📅 2026-08-14 - Automatic repair of single polygons (according to the OGC Simple Features / ISO19107 rules) using a constrained triangulation.
* [geojson-vt-cpp](https://github.com/mapbox/geojson-vt-cpp) ⚠️ Archived - Port to C++ of JS GeoJSON-VT for slicing GeoJSON into vector tiles on the fly.
* [laz-perf](https://github.com/hobu/laz-perf) ⭐ 103 | 🐛 9 | 🌐 C++ | 📅 2026-03-25 - Alternative LAZ implementation for C++ and JavaScript.
* [pprepair](https://github.com/tudelft3d/pprepair) ⭐ 63 | 🐛 17 | 🌐 C++ | 📅 2026-04-29 - Validation and Automatic Repair of Planar Partitions.
* [copc-lib](https://github.com/RockRobotic/copc-lib) ⭐ 62 | 🐛 10 | 🌐 C++ | 📅 2026-05-25 - copc-lib provides an easy-to-use interface for reading and creating Cloud Optimized Point Clouds.
* [geo-utils-cpp](https://github.com/gistrec/geo-utils-cpp) ⭐ 60 | 🐛 2 | 🌐 C++ | 📅 2026-08-21 - Header-only C++17 library for spherical (lat/lng) geometry: distance, bearing, area, point-in-polygon.
* [Pronto Raster](https://github.com/ahhz/raster) ⭐ 51 | 🐛 0 | 🌐 C++ | 📅 2025-06-12 - C++ library for geographical raster data analysis.
* [Supercluster](https://github.com/mapbox/supercluster.hpp) ⚠️ Archived - A C++14 port of supercluster, a fast 2D point clustering library for use in interactive maps.
* [dreich\_algorithm](https://github.com/csdms-contrib/dreich_algorithm) ⭐ 2 | 🐛 1 | 🌐 C++ | 📅 2015-02-25 - Algorithm for extracting channel networks from high resolution topographic data.
* [hydroflow](https://github.com/sistemalabgis/hydroflow) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2019-02-01 - Compute drainage orders in drainage basins using Strahler and Shreve methods.
* [Boost Geometry](http://www.boost.org/doc/libs/1_61_0/libs/geometry/doc/html/index.html) - Part of collection of the Boost C++ Libraries, defines concepts, primitives and algorithms for solving geometry problems.
* [GDAL](http://www.gdal.org/) - Geospatial Data Abstraction Library (GDAL) is a computer library that serve as a translator library for raster and vector geospatial data formats.
* [GEOS](https://trac.osgeo.org/geos/) - GEOS (Geometry Engine - Open Source) is a C++ port of the Java Topology Suite (JTS).
* [ITK](https://itk.org/) - ITK is an open-source, cross-platform system that provides developers with an extensive suite of software tools for image analysis.
* [libGeoTiff](https://trac.osgeo.org/geotiff/) - Manipulate TIFF based interchange format for georeferenced raster imagery.
* [Mapbox Maps SDK for Qt](https://www.mapbox.com/qt/) - Qt Automotive Map Suite.
* [Mapnik](http://mapnik.org/) - C++ library for map rendering.
* [Orfeo ToolBox](https://www.orfeo-toolbox.org/) - Orfeo TooLBox (OTB) is an open-source C++ library for remote sensing images processing, distributed under the Apache v2.0 licence.
* [OSRM (Open Source Routing Machine)](http://project-osrm.org/) - High performance routing engine written in C++, designed to run on OpenStreetMap data. Services available: Nearest, Route, Table, Match, Trip, Tile.
* [RSGISLib](http://rsgislib.org/) - The Remote Sensing and GIS software library (RSGISLib) is a collection of tools for processing remote sensing and GIS datasets. The tools are accessed using Python bindings or an XML interface.
* [SFCGAL](https://www.sfcgal.org/) - a C++ wrapper library around [CGAL](https://www.cgal.org/) with the aim of supporting ISO 19107:2013 and OGC Simple Features Access 1.2 for 3D operations.
* [Spatial](https://sourceforge.net/projects/spatial/) - Spatial is a generic header-only C++ library providing multi-dimensional in-memory containers, iterators and functionals.
* [Terralib](http://www.dpi.inpe.br/terralib5/wiki/doku.php?id=start) - TerraLib is a GIS classes and functions open source library.
* [Vector Tiles Producer](https://github.com/vross/vector-tiles-producer) - Command line tool in C++ to creates vector tiles for a given area at chosen zoom levels using a Mapnik XML.

## C Sharp

* [NTS Net Topology Suite](https://github.com/NetTopologySuite/NetTopologySuite) ⭐ 1,713 | 🐛 82 | 🌐 C# | 📅 2026-08-19 - A .NET GIS solution that is fast and reliable for the .NET platform.
* [DotSpatial](https://github.com/DotSpatial/DotSpatial) ⭐ 922 | 🐛 255 | 🌐 C# | 📅 2025-10-22 - DotSpatial is a geographic information system library written for .NET 4.
* [SharpMap](https://github.com/SharpMap/SharpMap) ⭐ 861 | 🐛 48 | 🌐 C# | 📅 2025-01-06 - SharpMap is an easy-to-use mapping library for use in web and desktop applications.
* [GeoJSON.Net](https://github.com/GeoJSON-Net/GeoJSON.Net) ⭐ 462 | 🐛 20 | 🌐 C# | 📅 2024-08-12 - .Net library for GeoJSON types & corresponding Json.Net (de)serializers.
* [BruTile](https://github.com/BruTile/BruTile) ⭐ 374 | 🐛 14 | 🌐 C# | 📅 2026-05-18 - BruTile is a .NET library to access tile services like those of OpenStreetMap, MapBox or GeodanMaps.
* [DEM Net Elevation API](https://github.com/dem-net/DEM.Net) ⭐ 354 | 🐛 18 | 🌐 C# | 📅 2026-04-18 - 3D terrain generation library, provides access to global DEM datasets (OpenTopography, Nasa ASTER) and tiled imagery services. GlTF and STL export formats supported. [Live demo](https://elevationapi.com)
* [Bing-Maps-Fleet-Tracker](https://github.com/Microsoft/Bing-Maps-Fleet-Tracker) ⚠️ Archived - The Bing Maps Fleet Tracker is a tracking solution for small to medium sized teams. Easily track vehicles and mobile devices.
* [MaxRev.Gdal.Core](https://github.com/MaxRev-Dev/gdal.netcore) ⭐ 210 | 🐛 2 | 🌐 C# | 📅 2026-08-22 - Bindings for GDAL and OGR (both win-x64 and linux-x64).
* [Geo](https://github.com/sibartlett/Geo) ⭐ 192 | 🐛 8 | 🌐 C# | 📅 2026-08-22 - A geospatial library for .NET
* [Bing Maps REST Toolkit](https://github.com/Microsoft/BingMapsRESTToolkit) ⚠️ Archived - This is a portable class library which makes it easy to access the Bing Maps REST services from .NET.
* [SharpKml](https://github.com/samcragg/sharpkml) ⭐ 167 | 🐛 7 | 🌐 C# | 📅 2024-04-18 - Is able to read/write both KML files and KMZ files.
* [Sanchez](https://github.com/nullpainter/sanchez) ⭐ 144 | 🐛 7 | 🌐 C# | 📅 2025-06-29 - False-colour geostationary satellite image compositor.
* [Earth-Lens](https://github.com/Microsoft/Earth-Lens) ⚠️ Archived - Earth Lens, a Microsoft Garage project is an iOS iPad application that helps people and organizations quickly identify and classify objects in aerial imagery through the power of machine learning.
* [Bing Maps Spatial Data Services Toolkit](https://github.com/Microsoft/BingMapsSDSToolkit) ⚠️ Archived - This toolkit makes it easy to use the Bing Maps Spatial Data Services (SDS) in .NET.
* [AzureMapsRestServices](https://github.com/perfahlen/AzureMapsRestServices) ⭐ 26 | 🐛 18 | 🌐 C# | 📅 2022-02-24 - .Net Standard 2.0 library to access AzureMaps Services.
* [GeoJSON4EntityFramework](https://github.com/alatas/GeoJSON4EntityFramework) ⭐ 20 | 🐛 4 | 🌐 Visual Basic | 📅 2017-04-12 - Create GeoJSON from Entity Framework Spatial Data or WKT.
* [ArcBruTile](https://github.com/ArcBruTile/ArcBruTile) ⭐ 6 | 🐛 0 | 📅 2022-01-18 - ArcBruTile displays a collection of maps in ArcGIS Pro 2.0 and ArcMap 10.0 - 10.6.
* [Bing Maps WPF SDK ](https://msdn.microsoft.com/en-us/library/hh750210.aspx) - The Bing Maps WPF API.
* [GDAL/OGR CSharp](https://trac.osgeo.org/gdal/wiki/GdalOgrInCsharp) - C# bindings for GDAL and OGR.
* [Mapbox Maps SDK for Unity](https://www.mapbox.com/unity-sdk/) - The Maps SDK for Unity is a collection of tools for building Unity applications from real map data.
* [osmsharp](http://www.osmsharp.com/) - OsmSharp is a C# library to work with OpenStreetMap (OSM) data.
* [Windows UWP map control](https://msdn.microsoft.com/en-us/library/windows/apps/xaml/dn642089.aspx) - The Bing Maps control built into the Windows UWP platform.

## Clojure

* [geo](https://github.com/Factual/geo) ⭐ 319 | 🐛 8 | 🌐 Clojure | 📅 2024-04-09 - Clojure library for working with geohashes, polygons, and other world geometry.

## Crystal

* [geo](https://github.com/geocrystal/geo) ⭐ 22 | 🐛 1 | 🌐 Crystal | 📅 2026-07-07 - Geospatial primitives and algorithms for Crystal.
* [lidar](https://github.com/jblindsay/lidar) ⭐ 6 | 🐛 0 | 🌐 Crystal | 📅 2017-02-26 - A Crystal language library for reading and writing LiDAR data in LAS format.

## CSS

* [CartoCSS](https://www.mapbox.com/tilemill/docs/manual/carto/) - TileMills language.
* [MapCSS](http://wiki.openstreetmap.org/wiki/MapCSS) - MapCSS is a CSS-like language for map stylesheets.

## Dart

* [turf\_dart](https://github.com/dartclub/turf_dart) ⭐ 83 | 🐛 32 | 🌐 Dart | 📅 2026-07-10 - A turf.js-like geospatial analysis library working with GeoJSON, written in pure Dart.

## Delphi

* [DSpatial](http://dspatial.sourceforge.net/) - DSpatial is an Open Source software development project to provide developers using Delphi with a library of tools for the use, manipulation, and visualization of spatial data.

## Elixir

* [geo](https://github.com/bryanjos/geo) ⭐ 679 | 🐛 10 | 🌐 Elixir | 📅 2026-08-17 - A collection of GIS functions for Elixir.
* [GeoPostGIS](https://github.com/bryanjos/geo_postgis) ⭐ 330 | 🐛 11 | 🌐 Elixir | 📅 2026-08-13 - PostgreSQL extension for the PostGIS data types.
* [Geometry Library](https://github.com/pkinney/topo) ⭐ 173 | 🐛 2 | 🌐 Elixir | 📅 2025-01-25 - A Geometry library for Elixir that calculates spatial relationships between two geometries.
* [Topo](https://github.com/pkinney/topo) ⭐ 173 | 🐛 2 | 🌐 Elixir | 📅 2025-01-25 - A Geometry library for Elixir that calculates spatial relationships between two geometries.
* [geocalc](https://github.com/yltsrc/geocalc) ⭐ 156 | 🐛 3 | 🌐 Elixir | 📅 2022-10-14 - Geographic calculations for Elixir.
* [distance](https://github.com/pkinney/distance) ⭐ 64 | 🐛 0 | 🌐 Elixir | 📅 2025-01-25 - Provides a set of distance functions for use in GIS or graphic applications.
* [Proj](https://github.com/CandyGumdrop/proj) ⭐ 9 | 🐛 2 | 🌐 C | 📅 2021-01-13 - Elixir coordinate conversion library using OSGeo's PROJ.4.
* [SRTM](https://github.com/adriankumpf/srtm) ⭐ 7 | 🐛 0 | 🌐 Elixir | 📅 2026-08-19 - Query locations for elevation data from the NASA Shuttle Radar Topography Mission.

## Fortran

* [SPECFEM3D\_GLOBE](https://github.com/geodynamics/specfem3d_globe) ⭐ 113 | 🐛 35 | 🌐 Fortran | 📅 2026-07-23 - SPECFEM3D\_GLOBE simulates global and regional (continental-scale) seismic wave propagation.
* [SWAT](https://github.com/WatershedModels/SWAT) ⭐ 80 | 🐛 3 | 🌐 Fortran | 📅 2023-11-29 - Implementation of SWAT model.
* [FortranGIS](https://github.com/ARPA-SIMC/fortrangis) ⭐ 51 | 🐛 0 | 🌐 Fortran | 📅 2026-06-26 - A collection of Fortran interfaces to the most common Open Source GIS libraries.
* [6S](http://6s.ltdri.org/) - Second Simulation of the Satellite Signal in the Solar Spectrum (6S) open source algorithm.

## Go

* [BuntDB](https://github.com/tidwall/buntdb) ⭐ 4,863 | 🐛 32 | 🌐 Go | 📅 2026-05-19 - BuntDB is an embeddable, in-memory key/value database for Go with custom indexing and geospatial support.
* [S2](https://github.com/golang/geo) ⭐ 1,849 | 🐛 37 | 🌐 Go | 📅 2026-08-18 - S2 is a library for spherical geometry that aims to have the same robustness, flexibility, and performance as the best planar geometry libraries.
* [Tegola](https://github.com/go-spatial/tegola) ⭐ 1,501 | 🐛 181 | 🌐 Go | 📅 2026-08-20 - Tegola is a vector tile server delivering Mapbox Vector Tiles with support for PostGIS and GeoPackage data providers.
* [Draw2D](https://github.com/llgcode/draw2d) ⭐ 1,166 | 🐛 45 | 🌐 Go | 📅 2026-04-22 - 2D rendering for different output (raster, pdf).
* [orb](https://github.com/paulmach/orb) ⭐ 1,126 | 🐛 19 | 🌐 Go | 📅 2026-03-30 - A set of types for working with 2d geo and planar/projected geometric data in Golang
* [pg\_tileserv](https://github.com/CrunchyData/pg_tileserv) ⭐ 1,057 | 🐛 42 | 🌐 Go | 📅 2025-12-11 - A very thin PostGIS-only tile server in Go. Takes in HTTP tile requests, executes SQL, returns MVT tiles.
* [go-geom](https://github.com/twpayne/go-geom) ⭐ 971 | 🐛 9 | 🌐 Go | 📅 2026-08-19 - Go library for handling geometries.
* [pg\_featureserv](https://github.com/CrunchyData/pg_featureserv) ⭐ 540 | 🐛 62 | 🌐 Go | 📅 2025-09-17 - Lightweight RESTful Geospatial Feature Server for PostGIS in Go.
* [BoxTree](https://github.com/tidwall/boxtree) ⭐ 348 | 🐛 2 | 🌐 Go | 📅 2026-08-11 - An R-tree implementation for Go.
* [Go GDAL](https://github.com/lukeroth/gdal) ⭐ 319 | 🐛 27 | 🌐 Go | 📅 2026-05-31 - Go (golang) wrapper for GDAL, the Geospatial Data Abstraction Library.
* [Go-shp](https://github.com/jonas-p/go-shp) ⭐ 272 | 🐛 20 | 🌐 Go | 📅 2024-08-02 - Go library for reading and writing ESRI Shapefiles. Pure Golang implementation based on the ESRI Shapefile technical description.
* [gopostal](https://github.com/openvenues/gopostal) ⭐ 185 | 🐛 5 | 🌐 Go | 📅 2024-04-26 - Go (cgo) interface to libpostal for fast international address parsing/normalization.
* [godal](https://github.com/airbusgeo/godal) ⭐ 181 | 🐛 7 | 🌐 Go | 📅 2026-05-22 - Godal aims at providing an idiomatic go wrapper around the GDAL library.
* [cogger](https://github.com/airbusgeo/cogger) ⭐ 132 | 🐛 3 | 🌐 Go | 📅 2025-09-19 - cogger is a fast geotiff to COG converter.
* [go-spatial](https://github.com/jblindsay/go-spatial) ⭐ 64 | 🐛 3 | 🌐 Go | 📅 2018-04-24 - GoSpatial is a simple command-line interface program for manipulating geospatial data.
* [GoSpatial](https://github.com/jblindsay/go-spatial) ⭐ 64 | 🐛 3 | 🌐 Go | 📅 2018-04-24 - GoSpatial is a simple command-line interface program for manipulating geospatial data.
* [geom](https://github.com/ctessum/geom) ⭐ 61 | 🐛 6 | 🌐 Go | 📅 2024-06-04 - Geometry objects and functions for Go.
* [Go-proj-4](https://github.com/pebbe/go-proj-4) ⭐ 45 | 🐛 1 | 🌐 Go | 📅 2021-02-20 - Go bindings for the Cartographic Projections Library PROJ.4.
* [lidario](https://github.com/jblindsay/lidario) ⭐ 31 | 🐛 2 | 🌐 Go | 📅 2021-05-04 - A small Go library for reading and writing LiDAR (LAS) files.

## Groovy

* [GeoScript Groovy](https://github.com/geoscript/geoscript-groovy) ⭐ 48 | 🐛 14 | 🌐 Groovy | 📅 2024-04-19 - GeoScript Groovy is the Groovy implementation of GeoScript.

## Haskell

* [HGeometry](https://github.com/noinia/hgeometry) ⭐ 131 | 🐛 31 | 🌐 Haskell | 📅 2026-07-29 - HGeometry is a library for computing with geometric objects in Haskell. It defines basic geometric types and primitives, and it implements some geometric data structures and algorithms.
* [Naqsha](https://github.com/naqsha/naqsha) ⭐ 26 | 🐛 3 | 🌐 Haskell | 📅 2020-08-31 - Naqsha is a Haskell library to work with geospatial data types.
* [hgis](https://hackage.haskell.org/package/hgis) - Package containing functions to make graphs, read shapefiles, and compute areas/perimeters of geographic features.
* [TerraHS](https://wiki.haskell.org/TerraHS) - TerraHS is a software component that enables the development of geographical applications in a functional language, using the data handling capabilities and spatial operations of TerraLib.

## IDL

* [LandTrendr](https://github.com/KennedyResearch/LandTrendr-2012) ⭐ 42 | 🐛 0 | 🌐 IDL | 📅 2017-02-24 - LandTrendr (Landsat-based Detection of Trends in Disturbance and Recovery) attempt to capture, label, and map changes in Earth's surface for use in science, natural resource management, and education.

## Java

* [GraphHopper Routing Engine](https://github.com/graphhopper/graphhopper) ⭐ 6,640 | 🐛 243 | 🌐 Java | 📅 2026-08-23 - GraphHopper is a fast and memory efficient Java routing engine, released under Apache License 2.0. By default it uses OpenStreetMap and GTFS data, but it can import other data sources.
* [Photon](https://github.com/komoot/photon) ⭐ 3,000 | 🐛 44 | 🌐 Java | 📅 2026-08-18 - Photon is an open source geocoder built for OpenStreetMap data. It is based on elasticsearch.
* [JTS Topology Suite](https://github.com/locationtech/jts) ⭐ 2,226 | 🐛 223 | 🌐 Java | 📅 2026-08-13 - JTS Topology Suite is an API of 2D spatial predicates and functions.
* [Spatial4j](https://github.com/locationtech/spatial4j) ⭐ 962 | 🐛 76 | 🌐 Java | 📅 2026-08-17 - Spatial4j is a general purpose geospatial ASL licensed open-source Java library.
* [Proj4j](https://github.com/locationtech/proj4j) ⭐ 230 | 🐛 30 | 🌐 Java | 📅 2026-08-03 - Java port of the Proj.4 library for coordinate reprojection.
* [Geo Assist](https://github.com/thegeekyasian/geo-assist) ⭐ 214 | 🐛 4 | 🌐 Java | 📅 2023-05-02 - Geo Assist is an open source API for indexing and querying spatial data in the most efficient manner. It allows you to store 2D spatial data in-memory and support features such as find nearest neighbors, find in bounding box, etc.
* [jpostal](https://github.com/openvenues/jpostal) ⭐ 141 | 🐛 3 | 🌐 Java | 📅 2025-07-01 - Java/JNI bindings to libpostal for fast international street address parsing/normalization.
* [Openmap](https://github.com/openmap-java/openmap) ⭐ 83 | 🐛 33 | 🌐 Java | 📅 2026-05-21 - Open Source JavaBeans-based programmer's toolkit.
* [GDAL Warp Bindings](https://github.com/geotrellis/gdal-warp-bindings) ⭐ 19 | 🐛 14 | 🌐 C++ | 📅 2026-06-19 - Thread-safe bindings for GDAL's Warp functionality.
* [asgbook](https://github.com/lakshmanok/asgbook) ⭐ 14 | 🐛 1 | 🌐 Java | 📅 2012-05-15 - Implementation of GIS/RS features in Java. Its also the code accompanying the book "Automating the Analysis of Spatial Grids" by Valliappa Lakshmanan.
* [PDAL-Java](https://github.com/PDAL/java) ⭐ 11 | 🐛 10 | 🌐 Scala | 📅 2025-12-27 - Java extension and bindings for PDAL.
* [Apache SIS](http://sis.apache.org/) - Apache Spatial Information System (SIS) is a free software, Java language library for developing geospatial applications.
* [Geoapi](http://www.geoapi.org/) - GeoAPI provides a set of Java language programming interfaces for geospatial applications.
* [Geonetwork](http://geonetwork-opensource.org/) - GeoNetwork is a catalog application to manage spatially referenced resources.
* [GeoServer](http://geoserver.org/) - GeoServer is open source server for sharing geospatial data.
* [Geotools](http://www.geotools.org/) - GeoTools is an open source Java library that provides tools for geospatial data.
* [GeoWebCache](http://www.geowebcache.org/) - a Java web application used to cache map tiles coming from a variety of sources such as OGC Web Map Service (WMS). It implements various service interfaces (such as WMS-C, WMTS, TMS, Google Maps KML, Virtual Earth) in order to accelerate and optimize map image delivery. It can also recombine tiles to work with regular WMS clients.
* [GeOxygene](https://sourceforge.net/projects/oxygene-project/) - Provide an open framework which implements OGC/ISO specifications for the development and deployment of GIS applications.
* [Gisgraphy](http://www.gisgraphy.com/) - Open source framework that offers the ability to do geolocalisation and geocoding via Java APIs or REST webservices.
* [JGeocoder](http://jgeocoder.sourceforge.net/) - Free Java Geocoder.
* [LuciadLightspeed](http://www.luciad.com/solutions/luciadlightspeed) - A Java library that provides the foundations for advanced geospatial analytics applications
* [MapFish Print](https://mapfish.github.io/mapfish-print-doc/) - The purpose of Mapfish Print is to create reports that contain maps (and map related components) within them. The project is a Java based servlet/library/application based on the mature Jasper Reports Library.
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Weka is a collection of machine learning algorithms for data mining tasks written in Java.
* [World Wind Java SDK](http://worldwind.arc.nasa.gov/java/) - Nasa cross-platform Java SDK.

## JavaScript

* [CesiumJS](https://github.com/AnalyticalGraphicsInc/cesium) ⭐ 15,596 | 🐛 1,650 | 🌐 JavaScript | 📅 2026-08-21 - An open-source JavaScript library for world-class 3D globes and maps.
* [deck.gl](https://github.com/uber/deck.gl) ⭐ 14,510 | 🐛 478 | 🌐 TypeScript | 📅 2026-08-23 - WebGL2 powered geospatial visualization layers.
* [react-map-gl](https://github.com/uber/react-map-gl) ⭐ 8,488 | 🐛 96 | 🌐 TypeScript | 📅 2026-08-06 - React friendly API wrapper around MapboxGL JS.
* [gmaps.js](https://github.com/hpneo/gmaps) ⚠️ Archived - gmaps.js allows you to use the potential of Google Maps in a simple way.
* [pixelmatch](https://github.com/mapbox/pixelmatch) ⭐ 6,924 | 🐛 15 | 🌐 JavaScript | 📅 2026-07-07 - The smallest, simplest and fastest JavaScript pixel-level image comparison library.
* [SQLite3](https://github.com/mapbox/node-sqlite3) ⚠️ Archived - Asynchronous, non-blocking SQLite3 bindings for Node.js.
* [react-leaflet](https://github.com/PaulLeCam/react-leaflet) ⭐ 5,596 | 🐛 48 | 🌐 TypeScript | 📅 2025-12-31 - React components for Leaflet maps.
* [geolib](https://github.com/manuelbieh/geolib) ⭐ 4,278 | 🐛 70 | 🌐 JavaScript | 📅 2026-04-03 - Library to provide basic geospatial operations like distance calculation and rotation.
* [rbush](https://github.com/mourner/rbush) ⭐ 2,768 | 🐛 12 | 🌐 JavaScript | 📅 2026-07-21 - A high-performance JavaScript library for 2D spatial indexing.
* [leaflet-providers](https://github.com/leaflet-extras/leaflet-providers) ⭐ 2,378 | 🐛 19 | 🌐 JavaScript | 📅 2026-06-11 - An extension to Leaflet that contains configurations for various free tile providers.
* [Supercluster](https://github.com/mapbox/supercluster) ⭐ 2,352 | 🐛 32 | 🌐 JavaScript | 📅 2026-08-10 - A crazy fast geospatial point clustering library for browsers and Node.
* [proj4js](https://github.com/proj4js/proj4js) ⭐ 2,238 | 🐛 102 | 🌐 JavaScript | 📅 2026-08-12 - JavaScript library to transform coordinates from one coordinate system to another, including datum transformations.
* [Vue2Leaflet](https://github.com/KoRiGaN/Vue2Leaflet) ⭐ 1,955 | 🐛 42 | 🌐 JavaScript | 📅 2024-10-29 - Vue 2 components for Leaflet maps.
* [flatbush](https://github.com/mourner/flatbush) ⭐ 1,596 | 🐛 6 | 🌐 JavaScript | 📅 2026-07-08 - A really fast static spatial index for 2D points and rectangles in JavaScript.
* [JSTS](https://github.com/bjornharrtell/jsts) ⭐ 1,562 | 🐛 9 | 🌐 JavaScript | 📅 2025-01-02 - Port of the Java JTS library.
* [TerriaJS](https://github.com/TerriaJS/terriajs) ⭐ 1,357 | 🐛 891 | 🌐 TypeScript | 📅 2026-08-21 - A library for building rich, web-based geospatial data explorers.
* [procedural-gl-js](https://github.com/felixpalmer/procedural-gl-js) ⭐ 1,342 | 🐛 22 | 🌐 JavaScript | 📅 2021-05-11 - Procedural GL JS is a library for creating 3D map experiences on the web, written in JavaScript and WebGL. It is built on top THREE.js.
* [overpass-turbo](https://github.com/tyrasd/overpass-turbo) ⭐ 1,235 | 🐛 256 | 🌐 TypeScript | 📅 2026-07-19 - A web based data mining tool for OpenStreetMap using Overpass API.
* [Geodesy](https://github.com/chrisveness/geodesy) ⭐ 1,227 | 🐛 19 | 🌐 JavaScript | 📅 2024-07-10 - Libraries of geodesy functions implemented in JavaScript.
* [Geometric.js](https://github.com/HarryStevens/geometric) ⭐ 1,105 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-19 - A JavaScript library for doing geometry.
* [Terra Draw](https://github.com/JamesLMilner/terra-draw) ⭐ 1,088 | 🐛 51 | 🌐 TypeScript | 📅 2026-08-20 - A cross provider JavaScript library for drawing on maps
* [mapbox-gl-draw](https://github.com/mapbox/mapbox-gl-draw) ⭐ 1,083 | 🐛 242 | 🌐 JavaScript | 📅 2026-08-17 - Draw tools for mapbox-gl-js.
* [geotiff.js](https://github.com/geotiffjs/geotiff.js) ⭐ 1,043 | 🐛 93 | 🌐 JavaScript | 📅 2026-05-26 - geotiff.js is a small library to parse TIFF files for visualization or analysis.
* [geobuf](https://github.com/mapbox/geobuf) ⭐ 1,032 | 🐛 34 | 🌐 JavaScript | 📅 2026-06-29 - A compact binary encoding for geographic data.
* [NASA WebWorldWind](https://github.com/NASAWorldWind/WebWorldWind) ⭐ 997 | 🐛 271 | 🌐 JavaScript | 📅 2025-09-20 - The NASA WorldWind Javascript SDK (WebWW) includes the library and examples for creating geo-browser web applications and for embedding a 3D globe in HTML5 web pages.
* [Geo-Three](https://github.com/tentone/geo-three) ⭐ 947 | 🐛 41 | 🌐 TypeScript | 📅 2026-04-05 - Tile based geographic world map visualization library for threejs.
* [FlatGeoBuf](https://github.com/flatgeobuf/flatgeobuf) ⭐ 818 | 🐛 35 | 🌐 Rust | 📅 2026-08-21 - A performant binary encoding for geographic data based on flatbuffers.
* [flatten-js](https://github.com/alexbol99/flatten-js) ⭐ 651 | 🐛 13 | 🌐 JavaScript | 📅 2026-08-18 - For manipulating geometrical shapes, finding intersections, checking inclusion, calculating distance, transformations, and more.
* [leaflet TimeDimension](https://github.com/socib/Leaflet.TimeDimension) ⭐ 451 | 🐛 88 | 🌐 JavaScript | 📅 2026-06-01 - Add time dimension capabilities on a Leaflet map.
* [PGRestAPI](https://github.com/spatialdev/PGRestAPI) ⭐ 433 | 🐛 88 | 🌐 JavaScript | 📅 2018-04-28 - Node.js REST API for PostGres Spatial Entities.
* [gdal3.js](https://github.com/bugra9/gdal3.js) ⭐ 430 | 🐛 29 | 🌐 JavaScript | 📅 2026-05-13 - Convert raster and vector geospatial data to various formats using GDAL in the browser.
* [TileStrata](https://github.com/naturalatlas/tilestrata) ⭐ 426 | 🐛 8 | 🌐 JavaScript | 📅 2021-07-21 - A pluggable Node.js map tile server.
* [math.gl](https://github.com/uber-web/math.gl) ⭐ 422 | 🐛 8 | 🌐 TypeScript | 📅 2024-05-02 - JavaScript math library focused on Geospatial and 3D use cases.
* [Heatcanvas.js](https://github.com/sunng87/heatcanvas) ⭐ 404 | 🐛 11 | 🌐 JavaScript | 📅 2022-02-14 - Yet another heatmap implementation for Javascript.
* [arc.js](https://github.com/springmeyer/arc.js) ⭐ 385 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-28 - Calculate great circles routes as lines in GeoJSON or WKT format.
* [GeoPackage.js](https://github.com/ngageoint/geopackage-js) ⭐ 332 | 🐛 24 | 🌐 TypeScript | 📅 2026-08-20 - GeoPackage JS is an implementation of the OGC GeoPackage spec. This library works in both the browser and Node 4+.
* [Bertin.js](https://github.com/neocarto/bertin) ⭐ 316 | 🐛 9 | 🌐 JavaScript | 📅 2023-10-23 - A JavaScript library for visualizing geospatial data and make thematic maps for the web.
* [ui-leaflet](https://github.com/angular-ui/ui-leaflet) ⚠️ Archived - AngularJS directive to embed an interact with maps managed by Leaflet library.
* [leaflet-elevation](https://github.com/Raruto/leaflet-elevation) ⭐ 283 | 🐛 18 | 🌐 JavaScript | 📅 2026-07-26 - Leaflet plugin that allows to add elevation profiles using d3js
* [Galton](https://github.com/urbica/galton) ⭐ 279 | 🐛 28 | 🌐 JavaScript | 📅 2021-09-16 - Lightweight Node.js isochrone server. Build isochrones using OSRM, Turf and concaveman.
* [openrouteservice-js](https://github.com/GIScience/openrouteservice-js) ⭐ 248 | 🐛 16 | 🌐 JavaScript | 📅 2026-05-08 - The JavaScript API to consume openrouteservice(s) painlessly!
* [geojson-merge](https://github.com/mapbox/geojson-merge) ⭐ 244 | 🐛 17 | 🌐 JavaScript | 📅 2024-11-25 - Merge multiple GeoJSON files into one FeatureCollection.
* [Loam](https://github.com/azavea/loam) ⭐ 226 | 🐛 18 | 🌐 JavaScript | 📅 2023-11-09 - Javascript wrapper for GDAL in the browser.
* [reproject](https://github.com/perliedman/reproject) ⭐ 223 | 🐛 5 | 🌐 JavaScript | 📅 2022-11-08 - Change, convert, transform, reproject GeoJSON between different projections/CRS.
* [OpenSphere](https://github.com/ngageoint/opensphere#opensphere) ⭐ 201 | 🐛 78 | 🌐 JavaScript | 📅 2024-08-16 - A pluggable, single-page, GIS web application that supports both 2D and 3D views.
* [geoblaze](https://github.com/GeoTIFF/geoblaze) ⭐ 192 | 🐛 53 | 🌐 JavaScript | 📅 2024-08-05 - Geoblaze is a geospatial raster processing engine written purely in javascript.
* [spl.js](https://github.com/jvail/spl.js) ⭐ 192 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-09 - SpatiaLite and friends - sqlite, geos, proj, rttopo - for node (sync API) and browser (async API).
* [Bing Maps V8 Code Samples](https://github.com/Microsoft/BingMapsV8CodeSamples) ⚠️ Archived - A large collection of open source code samples for Bing Maps V8.
* [Euclid.ts](https://github.com/mathigon/euclid.js) ⭐ 134 | 🐛 17 | 🌐 TypeScript | 📅 2025-02-12 - 2D Euclidean geometry classes, utilities, and drawing tools.
* [gdal-js](https://github.com/ddohler/gdal-js/) ⭐ 132 | 🐛 16 | 🌐 C++ | 📅 2023-01-30 - An Emscripten port of GDAL 2.1.
* [mapboxgl-powerbi](https://github.com/mapbox/mapboxgl-powerbi) ⚠️ Archived - Mapbox GL PowerBI custom visual.
* [eurostat-map.js](https://github.com/eurostat/eurostat-map.js) ⭐ 101 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-18 - Reusable library to quickly create and customise web maps showing Eurostat data directly retrieved from Eurostat database.
* [tilegarden](https://github.com/azavea/tilegarden) ⭐ 101 | 🐛 46 | 🌐 JavaScript | 📅 2023-01-03 - Serverless raster and vector map tile generation using Mapnik and AWS Lambda.
* [geopouch](https://github.com/pouchdb/geopouch) ⭐ 88 | 🐛 17 | 🌐 JavaScript | 📅 2020-05-23 - Spatial plugin from PouchDB extracted and supporting N dimensional coordinates.
* [geotoolbox](https://github.com/neocarto/geotoolbox) ⭐ 75 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-12 - is javascript tool for geographers. It allows to simply deal with geojson properties (attribute data) and provides several GIS operations useful for thematic cartography.
* [landspeed.js](https://github.com/springmeyer/landspeed.js) ⭐ 54 | 🐛 1 | 🌐 JavaScript | 📅 2017-01-07 - WMS server using node-mapnik.
* [tilelive-postgis](https://github.com/stepankuzmin/tilelive-postgis) ⭐ 52 | 🐛 7 | 🌐 JavaScript | 📅 2026-08-10 - Implements the tilelive API for generating mapnik vector tiles from PostGIS.
* [landsat8.earth](https://github.com/kylebarron/landsat8.earth) ⭐ 40 | 🐛 16 | 🌐 JavaScript | 📅 2023-06-10 - 2D/3D WebGL-powered Landsat 8 satellite imagery analysis.
* [Bing Maps V8 TypeScript Definitions ](https://github.com/Microsoft/Bing-Maps-V8-TypeScript-Definitions) ⚠️ Archived - TypeScript Definitions for the Bing Maps V8 web control.
* [Geokit](https://github.com/developmentseed/geokit) ⭐ 38 | 🐛 6 | 🌐 Python | 📅 2026-04-02 - Geokit is a command-line interface (CLI) tool written in javascript, that contains all the basic functionalities for measurements, conversions and operations of geojson files.
* [mapshaper-proj](https://github.com/mbloch/mapshaper-proj) ⭐ 38 | 🐛 7 | 🌐 JavaScript | 📅 2026-08-01 - A JavaScript port of the Proj.4 map projection library.
* [TileMantle](https://github.com/naturalatlas/tilemantle) ⭐ 36 | 🐛 7 | 🌐 JavaScript | 📅 2018-03-06 - A tool to warm up your tile server cache. Give it a URL template, geometry, and list of zoom levels and it will request tiles incrementally to warm it up.
* [de9im](https://github.com/dpmcmlxxvi/de9im) ⭐ 31 | 🐛 4 | 🌐 JavaScript | 📅 2026-02-12 - A collection of fast functions for DE-9IM spatial operations.
* [Arabesque](https://github.com/gflowiz/arabesque) ⭐ 28 | 🐛 43 | 🌐 JavaScript | 📅 2022-12-09 - Arabesque is a web application for thematic mapping of flow and networks datasets.
* [geoverview ](https://github.com/neocarto/geoverview) ⭐ 26 | 🐛 4 | 🌐 JavaScript | 📅 2022-10-14 - Based on maplibre-gl, geoverview is a tool for giving a quick and easy geographic overview of any geojson (and the information it contains).
* [statsbreaks](https://github.com/riatelab/statsbreaks) ⭐ 24 | 🐛 9 | 🌐 JavaScript | 📅 2024-07-25 - Split a quantitative dataset into classes for thematic mapping.
* [pouchdb-geospatial](https://github.com/dpmcmlxxvi/pouchdb-geospatial) ⭐ 21 | 🐛 2 | 🌐 JavaScript | 📅 2026-01-31 - The PouchDB Geospatial plugin provides spatial querying of GeoJSON objects right in the browser.
* [openaq](https://github.com/nickolasclarke/openaq) ⭐ 18 | 🐛 1 | 🌐 JavaScript | 📅 2017-03-14 - A JS client for the OpenAQ API. OpenAQ is a non-profit organization empowering communities around the globe to clean their air by harmonizing, sharing, and using open air quality data.
* [Moveet](https://github.com/ivannovazzi/moveet) ⭐ 9 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-18 - Real-time vehicle fleet simulator with A\* pathfinding on real road networks.
* [tilestrata-mapnik](https://github.com/naturalatlas/tilestrata-mapnik) ⭐ 9 | 🐛 8 | 🌐 JavaScript | 📅 2020-09-23 - TileStrata provider for rendering tiles with mapnik.
* [Spatial](https://github.com/troufster/spatial) ⭐ 5 | 🐛 0 | 📅 2011-05-21 - A 2d spatial hash module for node.js.
* [Thermo.js](https://github.com/dazuma/thermo.js) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2012-04-19 - Another heatmap implementation for Javascript.
* [WebGISService](https://github.com/VicentGN/WebGISService) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-30 - Geospatial operations running as a service. Based on NodeJS/ExpressJS and TurfJS. Works with GeoJSON Features and FeaturesCollection.
* [ArcGIS Maps SDK for JavaScript](https://developers.arcgis.com/javascript/) - ArcGIS Maps SDK for JavaScript is a proprietary toolkit that enables developers to build web-based mapping and spatial analysis applications that integrate with the ArcGIS ecosystem.
* [Bing Maps V8 Interactive SDK](https://www.bing.com/api/maps/sdkrelease/mapcontrol/isdk#loadMapWithOptions+JS) - An interactive code sample gallery for Bing Maps V8.
* [Bing Maps V8 Web Control](https://msdn.microsoft.com/en-us/library/mt712542.aspx) - Bing Maps API for JavaScript.
* [d3-geomap](https://d3-geomap.github.io/) - A library for creating geographical maps based on D3.js.
* [GeoExt](https://geoext.github.io/geoext3/) - Open Source and enables building desktop-like GIS applications through the web. It is a JavaScript framework that combines the GIS functionality of OpenLayers with the user interface of the ExtJS library provided by Sencha.
* [Ginkgoch](https://ginkgoch.com) - Ginkgoch is a GIS visualization, analyze library on Node.js. It allows to build cross-platform GIS services, desktop and mobile apps.
* [Google Maps API](https://developers.google.com/maps/documentation/javascript/?hl=pt-br) - Google Maps API for JavaScript.
* [Heatmap.js](https://www.patrick-wied.at/static/heatmapjs/) - A heatmap implementation for Javascript.
* [hyperleaflet](https://hyperleaflet.dev/) - A library that allows you to use the popular Leaflet library with just HTML attributes.
* [iTowns](http://www.itowns-project.org/) - A Three.js-based framework written in Javascript/WebGL for visualizing 3D geospatial data. It can connect to WMS/WMTS/TMS servers including elevation data and load many different data formats (3dTiles, gpx, KML and much much more).
* [jVectorMap](https://jvectormap.com/) - jVectorMap is a vector-based, cross-browser and cross-platform component for interactive geography-related data visualization on the web. It provides numerious features like smooth zooming and panning, fully-customizable styling, markers, labels and tooltips.
* [kepler.gl](https://kepler.gl/) - kepler.gl is a data-agnostic, high-performance web-based application for visual exploration of large-scale geolocation data sets.
* [Koop](https://koopjs.github.io/) - An open source geospatial data server. Transform geospatial data on the fly and serve as GeoJSON, Vector Tiles, Feature Services and more.
* [leaflet](http://leafletjs.com/) - Open-Source JavaScript Library for Mobile-Friendly Interactive Maps.
* [LuciadRIA](http://www.luciad.com/solutions/luciadria) - A JavaScript library for 3D globes and maps, with support for military symbology and desktop-like performance
* [OpenGlobus](https://www.openglobus.org/) - A javascript library designed to display interactive 3d maps and planets with map tiles, imagery and vector data, markers and 3d objects. It uses the WebGL technology, open source and completely free.
* [OpenLayers](http://openlayers.org/) - Open source AJAX library.
* [OSM Building](https://osmbuildings.org) - A JavaScript library for visualizing OpenStreetMap building geometry on 2D and 3D maps.
* [SuperMap iClient for JavaScript](http://iclient.supermap.io) - Cloud GIS web client development platform supportted by SuperMap.
* [Turf.js](http://turfjs.org/) - Advanced geospatial analysis for browsers and node.

## Julia

* [ViziCities](https://github.com/UDST/vizicities#getting-started) ⭐ 2,715 | 🐛 105 | 🌐 JavaScript | 📅 2019-02-02 - A framework for 3D geospatial visualization in the browser.
* [DataFrames.jl](https://github.com/JuliaStats/DataFrames.jl) ⭐ 1,830 | 🐛 160 | 🌐 Julia | 📅 2026-08-23 - Tools for working with tabular data in Julia.
* [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) ⭐ 590 | 🐛 6 | 🌐 Julia | 📅 2026-08-22 - An extensible framework for high-performance geostatistics in Julia.
* [Images.jl](https://github.com/JuliaImages/Images.jl) ⭐ 550 | 🐛 44 | 🌐 Julia | 📅 2026-05-01 - An image processing library for Julia.
* [NearestNeighbors.jl](https://github.com/KristofferC/NearestNeighbors.jl) ⭐ 467 | 🐛 31 | 🌐 Julia | 📅 2026-07-13 - High performance nearest neighbor data structures and algorithms for Julia.
* [GeoData.jl](https://github.com/rafaqz/Rasters.jl) ⭐ 264 | 🐛 169 | 🌐 Julia | 📅 2026-08-19 - Standardising geospatial raster data in the Julia language.
* [DynamicGrids.jl](https://github.com/cesaraustralia/DynamicGrids.jl) ⭐ 227 | 🐛 36 | 🌐 Julia | 📅 2026-06-30 - Generalised framework for building high-performance grid-based spatial simulations, including cellular automata, but also allowing a wider range of behaviours like random jumps and interactions between multiple grids. It is extended by Dispersal.jl for modelling organism dispersal processes.
* [GMT.jl](https://github.com/GenericMappingTools/GMT.jl) ⭐ 221 | 🐛 27 | 🌐 Julia | 📅 2026-08-10 - Generic Mapping Tools Library Wrapper for Julia.
* [GeoMakie.jl](https://github.com/JuliaPlots/GeoMakie.jl) ⭐ 218 | 🐛 101 | 🌐 Julia | 📅 2026-08-21 - Geographical plotting utilities for Makie.jl
* [CoordinateTransformations.jl](https://github.com/JuliaGeometry/CoordinateTransformations.jl) ⭐ 185 | 🐛 17 | 🌐 Julia | 📅 2025-02-04 - Julia package to manage simple or complex networks of coordinate system transformations.
* [ArchGDAL](https://github.com/yeesian/ArchGDAL.jl) ⭐ 150 | 🐛 94 | 🌐 Julia | 📅 2026-08-21 - Vector and Raster interfaces.
* [GeoInterface.jl](https://github.com/JuliaGeo/GeoInterface.jl) ⭐ 139 | 🐛 33 | 🌐 Julia | 📅 2026-08-01 - A Julia Protocol for Geospatial Data.
* [OpenStreetMapX.jl](https://github.com/pszufe/OpenStreetMapX.jl) ⭐ 127 | 🐛 25 | 🌐 Julia | 📅 2025-12-23 - Provides basic functionality for parsing, viewing, and working with OpenStreetMap map data.
* [VoronoiDelaunay.jl](https://github.com/JuliaGeometry/VoronoiDelaunay.jl) ⭐ 125 | 🐛 14 | 🌐 Julia | 📅 2023-06-28 - Fast, robust construction of 2D Delaunay and Voronoi tessellations on generic point types.
* [ClimateTools.jl](https://github.com/Balinus/ClimateTools.jl) ⭐ 122 | 🐛 2 | 🌐 Julia | 📅 2026-07-23 - Collection of commonly-used tools in Climate Science.
* [NetCDF.jl](https://github.com/JuliaGeo/NetCDF.jl) ⭐ 117 | 🐛 27 | 🌐 Julia | 📅 2025-12-15 - NetCDF support for the julia programming language.
* [RegionTrees.jl](https://github.com/rdeits/RegionTrees.jl) ⭐ 115 | 🐛 6 | 🌐 Julia | 📅 2026-07-16 - Quadtrees, Octrees, and more in Julia.
* [Geodesy.jl](https://github.com/JuliaGeo/Geodesy.jl) ⭐ 114 | 🐛 28 | 🌐 Julia | 📅 2026-06-24 - Work with points defined in various coordinate systems.
* [ImageFiltering.jl](https://github.com/JuliaImages/ImageFiltering.jl) ⭐ 104 | 🐛 61 | 🌐 Julia | 📅 2025-12-15 - ImageFiltering implements blurring, sharpening, gradient computation, and other linear filtering operations, as well nonlinear filters like min/max.
* [Shapefile.jl](https://github.com/JuliaGeo/Shapefile.jl) ⭐ 86 | 🐛 27 | 🌐 Julia | 📅 2026-06-26 - Parsing .shp files in Julia.
* [GeoDataFrames.jl](https://github.com/evetion/GeoDataFrames.jl) ⭐ 70 | 🐛 25 | 🌐 Julia | 📅 2026-08-13 - Simple geographical vector interaction built on top of ArchGDAL.
* [GeoJSON.jl](https://github.com/JuliaGeo/GeoJSON.jl) ⭐ 70 | 🐛 25 | 🌐 Julia | 📅 2026-06-29 - This library is developed independently of, but is heavily influenced in design by the python-geojson package.
* [EcologicalNetwork.jl](https://github.com/PoisotLab/EcologicalNetwork.jl) ⚠️ Archived - This julia package provides a common interface to analyze all types of data on ecological networks.
* [OpenStreetMaps.jl](https://github.com/tedsteiner/OpenStreetMap.jl) ⭐ 52 | 🐛 19 | 🌐 Julia | 📅 2016-07-14 - This package provides basic functionality for parsing, viewing, and working with OpenStreetMap map data.
* [GeoArrays.jl](https://github.com/evetion/GeoArrays.jl) ⭐ 51 | 🐛 10 | 🌐 Julia | 📅 2026-06-29 - Simple geographical raster interaction built on top of ArchGDAL, GDAL and CoordinateTransformations.
* [Proj4.jl](https://github.com/JuliaGeo/Proj4.jl) ⭐ 51 | 🐛 19 | 🌐 Julia | 📅 2026-06-24 - A simple wrapper around the Proj.4 cartographic projections library.
* [EarthEngine.jl](https://github.com/KMarkert/EarthEngine.jl) ⭐ 50 | 🐛 4 | 🌐 Julia | 📅 2023-09-02 - Google Earth Engine in Julia.
* [ImageFeatures.jl](https://github.com/JuliaImages/ImageFeatures.jl) ⭐ 49 | 🐛 23 | 🌐 Julia | 📅 2026-07-01 - Image feature detection for the Julia language.
* [ImageTransformations.jl](https://github.com/JuliaImages/ImageTransformations.jl/tree/master/src) ⭐ 47 | 🐛 22 | 🌐 Julia | 📅 2026-06-30 - This package provides support for image resizing, image rotation, and other spatial transformations of arrays.
* [ImageSegmentation.jl](https://github.com/JuliaImages/ImageSegmentation.jl) ⭐ 45 | 🐛 12 | 🌐 Julia | 📅 2026-06-30 - Julia package for multiple Image Segmentation Algorithms.
* [SpatialIndexing.jl](https://github.com/alyst/SpatialIndexing.jl) ⭐ 36 | 🐛 4 | 🌐 Julia | 📅 2024-05-06 - Spatial data indexing in pure Julia (R\*-trees etc).
* [OpenStreetMapXPlot.jl](https://github.com/pszufe/OpenStreetMapXPlot.jl) ⭐ 35 | 🐛 4 | 🌐 Julia | 📅 2024-03-08 - Plotting functionality for the OpenStreetMapX.jl (Supports PyPlot.jl and Plots.jl with GR backend).
* [EarthDataLab.jl](https://github.com/JuliaDataCubes/EarthDataLab.jl) ⭐ 34 | 🐛 51 | 🌐 Julia | 📅 2026-08-23 - Interface for Reading from the Earth System Datacube.
* [STAC.jl](https://github.com/JuliaClimate/STAC.jl) ⭐ 33 | 🐛 7 | 🌐 Julia | 📅 2026-07-24 - SpatioTemporal Asset Catalog (STAC) julia client.
* [ImageMorphology.jl](https://github.com/JuliaImages/ImageMorphology.jl) ⭐ 28 | 🐛 28 | 🌐 Julia | 📅 2026-06-30 - This package provides morphology-related functionality to the Images.jl project.
* [RasterDataSources.jl](https://github.com/EcoJulia/RasterDataSources.jl) ⭐ 25 | 🐛 20 | 🌐 Julia | 📅 2026-08-08 - Downloads raster data for local use or for integration into other spatial data packages, like GeoData.jl.
* [SpectralIndices.jl](https://github.com/awesome-spectral-indices/SpectralIndices.jl) ⭐ 22 | 🐛 11 | 🌐 Julia | 📅 2026-08-15 - Julia package for working with spectral indices commonly used in remote sensing and earth observation applications.
* [LasIO.jl](https://github.com/visr/LasIO.jl) ⭐ 21 | 🐛 8 | 🌐 Julia | 📅 2021-04-27 - Native Julia package for working with .las pointcloud data.
* [RasterIO.jl](https://github.com/wkearn/RasterIO.jl) ⭐ 18 | 🐛 10 | 🌐 Julia | 📅 2017-12-19 - Simple Raster Formats for Julia.
* [ImageMetadata.jl](https://github.com/JuliaImages/ImageMetadata.jl) ⭐ 12 | 🐛 3 | 🌐 Julia | 📅 2024-11-06 - ImageMetadata is a simple package providing utilities for working with images that have metadata attached.
* [LibSpatialIndex.jl](https://github.com/JuliaGeo/LibSpatialIndex.jl) ⭐ 12 | 🐛 4 | 🌐 Julia | 📅 2026-06-24 - A library for spatially indexing kD bounding box data (based on libspatialindex).
* [LazIO.jl](https://github.com/evetion/LazIO.jl) ⭐ 11 | 🐛 5 | 🌐 Julia | 📅 2026-06-29 - Extends LasIO with Laszip integration.
* [NMEA.jl](https://github.com/zznop/NMEA.jl) ⭐ 8 | 🐛 2 | 🌐 Julia | 📅 2021-08-16 - NMEA.jl is a package for parsing NMEA GPS protocol sentences.
* [Watershed.jl](https://github.com/seung-lab/Watershed.jl) ⭐ 6 | 🐛 1 | 🌐 Julia | 📅 2018-10-30 - This is a translation of Zlateski's C++ Watershed code.
* [JuliaGIS](https://github.com/wkearn/GIS.jl) ⭐ 4 | 🐛 0 | 🌐 Julia | 📅 2014-03-26 - A package for the visualization and manipulation of geographic data.
* [LASindex.jl](https://github.com/evetion/LASindex.jl) ⭐ 4 | 🐛 6 | 🌐 Julia | 📅 2020-07-17 - Pure Julia reader of lasindex .lax files.
* [LibLAS.jl](https://github.com/visr/LibLAS.jl) ⚠️ Archived - Julia wrapper for LibLAS, a library for reading and writing the LAS LiDAR format.
* [Tinker.jl](https://github.com/JuliaImages/Tinker.jl) ⭐ 2 | 🐛 4 | 🌐 Julia | 📅 2020-12-24 - Interactive graphical tool for complex image analysis.
* [Turf.jl](https://github.com/yeesian/Turf.jl) ⭐ 1 | 🐛 2 | 🌐 Julia | 📅 2020-02-08 - This library is a port of Turf.js to the Julia programming language for geospatial analysis.
* [GDALfuns.jl](https://github.com/meggart/GDALfuns.jl) ⭐ 0 | 🐛 0 | 🌐 Julia | 📅 2015-09-04 - Auto-generated low-level wrapper for the GDAL library.
* [Interpolations.jl](https://github.com/juliohm/Interpolations.jl) ⭐ 0 | 🐛 0 | 🌐 Julia | 📅 2023-11-25 - This package implements a variety of interpolation schemes for the Julia language.
* [LibGEOS.jl](https://github.com/JuliaGeometry/LibGEOS.jl) - LibGEOS is a LGPL-licensed package for manipulation and analysis of planar geometric objects, based on the libraries GEOS (the engine of PostGIS) and JTS (from which GEOS is ported).

## Kotlin

* [Lets-Plot](https://github.com/JetBrains/lets-plot-kotlin/blob/master/docs/geotools.md) ⭐ 485 | 🐛 10 | 🌐 Kotlin | 📅 2026-07-02 - An open-source plotting library. Together with GeoTools it allows you to visualize geospatial data in Jupyter notebooks or a JVM application.
* [geospatial-messenger](https://github.com/sdeleuze/geospatial-messenger) ⭐ 220 | 🐛 1 | 🌐 Kotlin | 📅 2018-03-11 - Geospatial messenger application written with Spring Boot + Kotlin + PostgreSQL.
* [Spatial K](https://github.com/maplibre/spatial-k) ⭐ 138 | 🐛 45 | 🌐 Kotlin | 📅 2026-08-20 - Spatial K - A set of Kotlin Multiplatform Libraries for working with geospatial data

## Lisp

* [cl-ewkb](https://github.com/filonenko-mikhail/cl-ewkb/) ⭐ 14 | 🐛 0 | 🌐 Common Lisp | 📅 2011-06-08 - Common Lisp PostGIS EWKB data model and encoder/decoder.
* [utm](https://github.com/jl2/utm) ⭐ 8 | 🐛 2 | 🌐 Common Lisp | 📅 2025-01-28 - Lisp library for converting between latitude/longitude and UTM.
* [cl-proj](https://github.com/vityok/cl-proj) ⭐ 3 | 🐛 0 | 🌐 Common Lisp | 📅 2019-12-22 - CL-PROJ provides CFFI-based Common Lisp bindings for the PROJ.4 library.

## Lua

* [geo.lua](https://github.com/RedisLabs/geo.lua) ⭐ 145 | 🐛 4 | 🌐 Lua | 📅 2017-09-26 - A helper library for Redis geospatial indices.
* [Tarantool/GIS](https://github.com/tarantool/gis) ⭐ 48 | 🐛 4 | 🌐 Lua | 📅 2022-10-28 - A full-featured geospatial extension for Tarantool.
* [TerraME](http://www.terrame.org/doku.php) - TerraME is a programming environment for spatial dynamical modelling. It supports cellular automata, agent-based models, and network models running in 2D cell spaces.

## MATLAB

* [ChangeDetectionToolbox](https://github.com/Bobholamovic/ChangeDetectionToolbox) ⭐ 185 | 🐛 1 | 🌐 MATLAB | 📅 2021-02-24 - MATLAB Toolbox for Remote Sensing Change Detection.
* [CCDC](https://github.com/GERSL/CCDC) ⭐ 106 | 🐛 2 | 🌐 MATLAB | 📅 2024-10-30 - Algorithm developed for Continuous Change Detection and Classification (CCDC) of land cover using all available Landsat data.
* [COLD](https://github.com/GERSL/COLD) ⭐ 30 | 🐛 0 | 🌐 MATLAB | 📅 2023-02-03 - Algorithm for COntinuous monitoring of Land Disturbance (COLD) using Landsat time series.
* [MFmask](https://github.com/qsly09/MFmask) ⭐ 13 | 🐛 1 | 🌐 Matlab | 📅 2018-07-22 - Automated cloud and cloud shadow detection for Landsats 4-8 images.
* [Cmask](https://github.com/GERSL/Cmask) ⭐ 9 | 🐛 0 | 🌐 MATLAB | 📅 2020-08-17 - This tool called Cmask (Cirrus cloud mask) is used for cirrus cloud detection in Landsat 8 imagery using a time series of data from the Cirrus Band (1.36 – 1.39 µm).

## Nim

* [kdtree](https://github.com/jblindsay/kdtree) ⭐ 43 | 🐛 0 | 🌐 Nim | 📅 2020-11-10 - A pure Nim k-d tree implementation for efficient spatial querying of point data.
* [fp\_denoise](https://github.com/jblindsay/fp_denoise) ⭐ 19 | 🐛 2 | 🌐 Nim | 📅 2022-08-05 - A tool for de-noising raster digital elevation models.
* [wbt\_nim](https://github.com/jblindsay/wbt_nim) ⭐ 3 | 🐛 0 | 🌐 Nim | 📅 2022-01-29 - A Nim-based API for using the WhiteboxTools geospatial data analysis library.

## Perl

* [address formatting](https://github.com/OpenCageData/address-formatting) ⭐ 449 | 🐛 5 | 🌐 Perl | 📅 2026-07-19 - Templates to format geographic addresses.
* [Geo::GDAL](https://metacpan.org/pod/Geo::GDAL) - Perl extension for the GDAL library for geospatial data.

## Python

* [CuPy](https://github.com/cupy/cupy) ⭐ 12,268 | 🐛 706 | 🌐 Python | 📅 2026-08-20 - NumPy-like API accelerated with CUDA.
* [osmnx](https://github.com/gboeing/osmnx) ⭐ 5,827 | 🐛 2 | 🌐 Python | 📅 2026-07-31 - A tool for downloading, analyzing, and visualizing street networks based on OpenStreetMap data and networkx.
* [GeoPandas](https://github.com/geopandas/geopandas) ⭐ 5,226 | 🐛 431 | 🌐 Python | 📅 2026-08-12 - Python tools for geographic data.
* [geopy](https://github.com/geopy/geopy) ⭐ 4,852 | 🐛 53 | 🌐 Python | 📅 2026-07-12 - geopy is a Python 2 and 3 client for several popular geocoding web services.
* [geemap](https://github.com/giswqs/geemap) ⭐ 4,017 | 🐛 53 | 🌐 Python | 📅 2026-08-22 - A Python package for interactive mapping with Google Earth Engine, ipyleaflet, and ipywidgets.
* [som-tsp](https://github.com/DiegoVicen/som-tsp) ⭐ 3,932 | 🐛 0 | 🌐 Python | 📅 2023-12-24 - Solving the Traveling Salesman Problem using Self-Organizing Maps.
* [leafmap](https://github.com/giswqs/leafmap) ⭐ 3,762 | 🐛 3 | 🌐 Python | 📅 2026-08-17 - A Python package for geospatial analysis and interactive mapping with minimal coding in a Jupyter environment.
* [GeoAI](https://github.com/opengeos/geoai) ⭐ 3,318 | 🐛 6 | 🌐 Python | 📅 2026-08-17 - GeoAI: Artificial Intelligence for Geospatial Data
* [Rasterio](https://github.com/mapbox/rasterio) ⭐ 2,564 | 🐛 156 | 🌐 Python | 📅 2026-08-20 - Rasterio employs GDAL under the hood for file I/O and raster formatting.
* [city2graph](https://github.com/c2g-dev/city2graph) ⭐ 1,811 | 🐛 3 | 🌐 Python | 📅 2026-08-18 - Geospatial dataset → graphs (networks) for spatial network analysis and GeoAI with GNNs (Graph Neural Networks)
* [Python Geocoder](https://github.com/DenisCarriere/geocoder) ⭐ 1,656 | 🐛 123 | 🌐 Python | 📅 2024-04-20 - Simple and consistent geocoding library written in Python.
* [MovingPandas](https://github.com/anitagraser/movingpandas) ⭐ 1,407 | 🐛 34 | 🌐 Python | 📅 2026-08-22 - Implementation of Trajectory classes and functions built on top of GeoPandas.
* [PyProj](https://github.com/jswhit/pyproj) ⭐ 1,220 | 🐛 58 | 🌐 Python | 📅 2026-08-21 - For conversions between projections.
* [sentinelsat](https://github.com/sentinelsat/sentinelsat) ⚠️ Archived - Search and download Copernicus Sentinel satellite images.
* [xarray-spatial](https://github.com/makepath/xarray-spatial) ⭐ 966 | 🐛 81 | 🌐 Python | 📅 2026-08-18 - xarray-spatial implements common raster analysis functions using Numba and provides an easy-to-install, easy-to-extend codebase for raster analysis.
* [Mahotas](https://github.com/luispedro/mahotas) ⭐ 888 | 🐛 24 | 🌐 Python | 📅 2026-06-12 - Mahotas is a library of fast computer vision algorithms (all implemented in C++ for speed) operating over numpy arrays.
* [CoastSat](https://github.com/kvos/CoastSat) ⭐ 885 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2026-06-05 - CoastSat is an open-source software toolkit written in Python that enables users to obtain time-series of shoreline position at any coastline worldwide from 30+ years (and growing) of publicly available satellite imagery.
* [PyPostal](https://github.com/openvenues/pypostal) ⭐ 880 | 🐛 44 | 🌐 C | 📅 2025-11-01 - Python bindings to libpostal for fast international address parsing/normalization.
* [pyGMT](https://github.com/GenericMappingTools/pygmt) ⭐ 873 | 🐛 177 | 🌐 Python | 📅 2026-08-23 - Pythonic interface for the Generic Mapping Tools (GMT).
* [networkit](https://github.com/networkit/networkit) ⭐ 871 | 🐛 42 | 🌐 C++ | 📅 2026-08-17 - NetworKit is a growing open-source toolkit for large-scale network analysis.
* [PyKrige](https://github.com/GeoStat-Framework/PyKrige) ⭐ 860 | 🐛 41 | 🌐 Python | 📅 2025-10-16 - Kriging Toolkit for Python.
* [thunder](https://github.com/thunder-project/thunder) ⭐ 822 | 🐛 89 | 🌐 Python | 📅 2017-01-06 - Thunder is an ecosystem of tools for the analysis of image and time series data in Python.
* [scikit-mobility](https://github.com/scikit-mobility/scikit-mobility) ⭐ 806 | 🐛 67 | 🌐 Python | 📅 2024-05-25 - Mobility analysis in Python.
* [Open-Elevation](https://github.com/Jorl17/open-elevation) ⭐ 799 | 🐛 48 | 🌐 Python | 📅 2024-04-17 - A free and open-source alternative to Google Elevation API.
* [cuSpatial](https://github.com/rapidsai/cuspatial) ⚠️ Archived - GPU-Accelerated Spatial and Trajectory Data Management and Analytics Library.
* [Landsat-util](https://github.com/developmentseed/landsat-util) ⭐ 698 | 🐛 36 | 🌐 Python | 📅 2022-04-14 - Landsat-util is a command line utility that makes it easy to search, download, and process Landsat imagery.
* [mapboxgl-jupyter](https://github.com/mapbox/mapboxgl-jupyter) ⭐ 679 | 🐛 43 | 🌐 Python | 📅 2025-02-06 - Use Mapbox GL JS to visualize data in a Python Jupyter notebook.
* [Spectral Python](https://github.com/spectralpython/spectral) ⭐ 676 | 🐛 21 | 🌐 Python | 📅 2026-08-04 - Python module for hyperspectral image processing.
* [Verde](https://github.com/fatiando/verde) ⭐ 666 | 🐛 46 | 🌐 Python | 📅 2026-08-04 - Verde is a Python library for processing spatial data (bathymetry, geophysics surveys, etc) and interpolating it on regular grids (i.e., gridding).
* [GSTools](https://github.com/GeoStat-Framework/GSTools) ⭐ 649 | 🐛 36 | 🌐 Python | 📅 2026-08-14 - A geostatistical toolbox: random fields, variogram estimation, covariance models, kriging and much more.
* [rioxarray](https://github.com/corteva/rioxarray) ⭐ 621 | 🐛 80 | 🌐 Python | 📅 2026-07-27 - rasterio xarray extension.
* [pyroSAR](https://github.com/johntruckenbrodt/pyroSAR) ⭐ 612 | 🐛 47 | 🌐 Python | 📅 2026-08-20 - A Python Framework for Large-Scale SAR Satellite Data Processing.
* [GeoSQL](https://github.com/dekart-xyz/geosql) ⭐ 607 | 🐛 0 | 🌐 Python | 📅 2026-08-19 - Claude/Codex skill (Python package) for cost-safe geospatial SQL on BigQuery and Snowflake. Validates results, prunes partitions, renders interactive maps.
* [dask-geopandas](https://github.com/geopandas/dask-geopandas) ⭐ 592 | 🐛 77 | 🌐 Python | 📅 2026-07-21 - Parallelized GeoPandas with Dask.
* [rio-tiler](https://github.com/mapbox/rio-tiler) ⭐ 591 | 🐛 18 | 🌐 Python | 📅 2026-08-20 - Get mercator tile from landsat, sentinel or other AWS hosted raster.
* [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy) ⭐ 579 | 🐛 22 | 🌐 Jupyter Notebook | 📅 2025-09-30 - GSLIB reimplimented in Python
* [Rasterstats](https://github.com/perrygeo/python-rasterstats/) ⭐ 561 | 🐛 34 | 🌐 Python | 📅 2026-05-23 - Python module for summarizing geospatial raster datasets based on vector geometries.
* [urbansim](https://github.com/UDST/urbansim) ⭐ 544 | 🐛 26 | 🌐 Python | 📅 2026-08-21 - New version of UrbanSim, a platform for modeling metropolitan real estate markets.
* [EarthPy](https://github.com/earthlab/earthpy) ⭐ 536 | 🐛 44 | 🌐 Python | 📅 2026-08-16 - A package built to support working with spatial data using open source python.
* [openrouteservice-py](https://github.com/GIScience/openrouteservice-py) ⭐ 455 | 🐛 19 | 🌐 Python | 📅 2026-08-20 - The Python API to consume openrouteservice(s) painlessly!
* [PySTAC](https://github.com/stac-utils/pystac) ⭐ 455 | 🐛 81 | 🌐 Python | 📅 2026-08-10 - Python library for working with any SpatioTemporal Asset Catalog (STAC).
* [pymap3d](https://github.com/scivision/pymap3d) ⭐ 442 | 🐛 6 | 🌐 Python | 📅 2026-06-22 - Python 3D coordinate conversions for geospace ecef enu eci.
* [pyrosm](https://github.com/HTenkanen/pyrosm) ⭐ 436 | 🐛 22 | 🌐 Python | 📅 2026-08-01 - Read OpenStreetMap data from Protobuf files into GeoDataFrame with Python, faster.
* [geospatial](https://github.com/giswqs/geospatial) ⭐ 432 | 🐛 12 | 🌐 Dockerfile | 📅 2026-08-17 - A collection of Python packages for geospatial analysis and data visualization.
* [pandana](https://github.com/UDST/pandana) ⭐ 423 | 🐛 45 | 🌐 C++ | 📅 2026-08-21 - Pandas Network Analysis - dataframes of network queries, quickly.
* [whitebox](https://github.com/giswqs/whitebox) ⭐ 420 | 🐛 1 | 🌐 Python | 📅 2026-01-31 - Python frontend for [WhiteboxTools](https://github.com/jblindsay/whitebox-tools) ⭐ 1,192 | 🐛 175 | 🌐 Rust | 📅 2026-05-26.
* [Open Topo Data](https://github.com/ajnisbet/opentopodata) ⭐ 416 | 🐛 2 | 🌐 Python | 📅 2026-02-16 - Open Topo Data is a REST API server for your elevation data.
* [rio-cogeo](https://github.com/mapbox/rio-cogeo) ⭐ 394 | 🐛 18 | 🌐 Python | 📅 2026-06-23 - CloudOptimized GeoTIFF creation plugin for rasterio.
* [pyKriging](https://github.com/capaulson/pyKriging) ⭐ 392 | 🐛 20 | 🌐 Python | 📅 2026-01-03 - N-dimensional kriging.
* [pyGEOS](https://github.com/pygeos/pygeos) ⭐ 388 | 🐛 27 | 🌐 Python | 📅 2024-09-03 - Exposes geospatial operations from GEOS into Python.
* [srai](https://github.com/kraina-ai/srai) ⭐ 387 | 🐛 104 | 🌐 Python | 📅 2026-08-03 - Spatial Representations for Artificial Intelligence. Set of tools for geospatial machine learning, data acquisition and wrangling.
* [geocube](https://github.com/corteva/geocube) ⭐ 381 | 🐛 8 | 🌐 Python | 📅 2026-07-20 - Tool to convert geopandas vector data into rasterized xarray data.
* [QuackOSM](https://github.com/kraina-ai/quackosm) ⭐ 375 | 🐛 24 | 🌐 Python | 📅 2026-08-03 - Library and a CLI tool for downloading, filtering and transforming `*.osm.pbf` files into `GeoParquet` files using DuckDB.
* [Xee](https://github.com/google/Xee) ⭐ 370 | 🐛 32 | 🌐 Python | 📅 2026-08-19 - An Xarray extension for Google Earth Engine.
* [EOmaps](https://github.com/raphaelquast/EOmaps) ⭐ 362 | 🐛 20 | 🌐 Python | 📅 2026-04-23 - Create interactive maps to visualize, analyze and compare geographical datasets (based on matplotlib/cartopy).
* [localtileserver](https://github.com/banesullivan/localtileserver) ⭐ 349 | 🐛 0 | 🌐 Python | 📅 2026-08-10 - A Python package for serving tiles from large raster files in the Slippy Maps standard (i.e., `/zoom/x/y.png`) for visualization in Jupyter with `ipyleaflet` or `folium`.
* [routing-py](https://github.com/gis-ops/routing-py) ⭐ 347 | 🐛 12 | 🌐 Python | 📅 2026-08-18 - Python library to access all public routing, isochrones and matrix APIs in a consistent manner.
* [EOReader](https://github.com/sertit/eoreader) ⭐ 345 | 🐛 60 | 🌐 Python | 📅 2026-08-03 - EOReader is a multi-satellite reader allowing you to open optical and SAR data.
* [elevation](https://github.com/bopen/elevation) ⭐ 329 | 🐛 35 | 🌐 Python | 📅 2024-02-02 - Python script to download global terrain digital elevation models, SRTM 30m DEM and SRTM 90m DEM.
* [RichDEM](https://github.com/r-barnes/richdem) ⭐ 323 | 🐛 64 | 🌐 C++ | 📅 2024-06-24 - High-performance Terrain and Hydrology Analysis.
* [cdsapi](https://github.com/ecmwf/cdsapi) ⭐ 322 | 🐛 42 | 🌐 Python | 📅 2026-03-12 - Python API to access the Copernicus Climate Data Store (CDS).
* [stac-fastapi](https://github.com/stac-utils/stac-fastapi) ⭐ 321 | 🐛 45 | 🌐 Python | 📅 2026-08-19 - STAC API implementation with FastAPI.
* [Alpha Shape Toolbox](https://github.com/bellockk/alphashape) ⭐ 313 | 🐛 30 | 🌐 Python | 📅 2026-07-23 - Toolbox for constructing alpha shapes.
* [WhiteboxTools-ArcGIS](https://github.com/giswqs/WhiteboxTools-ArcGIS) ⭐ 313 | 🐛 3 | 🌐 Python | 📅 2025-08-12 - ArcGIS Python Toolbox for [WhiteboxTools](https://github.com/jblindsay/whitebox-tools) ⭐ 1,192 | 🐛 175 | 🌐 Rust | 📅 2026-05-26.
* [GeoLambda](https://github.com/developmentseed/geolambda) ⭐ 306 | 🐛 21 | 🌐 Dockerfile | 📅 2026-07-02 - Create and deploy Geospatial AWS Lambda functions Python.
* [lidar](https://github.com/giswqs/lidar) ⭐ 300 | 🐛 9 | 🌐 Python | 📅 2026-05-25 - Terrain and hydrological analysis using digital elevation models (DEMs).
* [GemGIS](https://github.com/cgre-aachen/gemgis) ⭐ 297 | 🐛 24 | 🌐 Python | 📅 2026-02-26 - Python-based, open-source geographic information processing library.
* [HyperCoast](https://github.com/opengeos/HyperCoast) ⭐ 285 | 🐛 3 | 🌐 Python | 📅 2026-08-17 - A Python package for visualizing and analyzing hyperspectral data in coastal regions.
* [Detectree](https://github.com/martibosch/detectree) ⭐ 278 | 🐛 6 | 🌐 Python | 📅 2026-08-17 - DetecTree is a Pythonic library to classify tree/non-tree pixels from aerial imagery.
* [geosnap](https://github.com/spatialucr/geosnap) ⭐ 274 | 🐛 18 | 🌐 Python | 📅 2026-03-09 - geosnap makes it easier to explore, model, analyze, and visualize the social and spatial dynamics of neighborhoods.
* [autoRIFT](https://github.com/leiyangleon/autoRIFT) ⭐ 270 | 🐛 21 | 🌐 Python | 📅 2026-06-22 - Python module of a fast and intelligent algorithm for finding the pixel displacement between two images.
* [stackstac](https://github.com/gjoseph92/stackstac) ⭐ 270 | 🐛 60 | 🌐 Python | 📅 2024-08-10 - Turn a STAC catalog into a dask-based xarray.
* [trackintel](https://github.com/mie-lab/trackintel) ⭐ 268 | 🐛 25 | 🌐 Python | 📅 2026-05-25 - A GeoPandas extension for tracking data
* [S2P - Satellite Stereo Pipeline](https://github.com/cmla/s2p) ⭐ 264 | 🐛 32 | 🌐 Python | 📅 2025-10-17 - S2P is a Python library and command line tool that implements a stereo pipeline which produces elevation models from images taken by high resolution satellites.
* [urbanaccess](https://github.com/UDST/urbanaccess) ⭐ 264 | 🐛 23 | 🌐 Python | 📅 2026-08-21 - A tool for computing GTFS transit and OSM pedestrian networks for accessibility analysis.
* [fastkml](https://github.com/cleder/fastkml) ⭐ 257 | 🐛 17 | 🌐 Python | 📅 2026-08-17 - Fastkml is a library to read, write and manipulate KML files. It aims to keep it simple and fast (using lxml if available).
* [RasterFrames](https://github.com/locationtech/rasterframes) ⭐ 256 | 🐛 143 | 🌐 Jupyter Notebook | 📅 2025-12-30 - RasterFrames brings together Earth-observation (EO) data access, cloud computing, and DataFrame-based data science.
* [spyndex](https://github.com/awesome-spectral-indices/spyndex) ⭐ 251 | 🐛 2 | 🌐 Python | 📅 2026-08-05 - Awesome Spectral Indices in Python.
* [Siphon](https://github.com/unidata/siphon) ⭐ 245 | 🐛 81 | 🌐 Python | 📅 2026-08-17 - A collection of Python utilities for retrieving atmospheric and oceanic data from remote sources, focusing on being able to retrieve data from Unidata data technologies, such as the THREDDS data server.
* [landsatxplore](https://github.com/yannforget/landsatxplore) ⭐ 240 | 🐛 65 | 🌐 Python | 📅 2024-11-30 - Search and download Landsat scenes from EarthExplorer.
* [geotiff](https://github.com/Open-Source-Agriculture/geotiff) ⭐ 237 | 🐛 14 | 🌐 Python | 📅 2024-03-01 - A noGDAL tool for reading geotiff files.
* [xcube](https://github.com/dcs4cop/xcube) ⭐ 230 | 🐛 171 | 🌐 Python | 📅 2026-08-20 - xcube is a Python package for generating and exploiting data cubes powered by xarray, dask, and zarr.
* [xyzservices](https://github.com/geopandas/xyzservices) ⭐ 229 | 🐛 13 | 🌐 Python | 📅 2026-08-15 - A unified source of XYZ tile providers in Python.
* [Mapchete](https://github.com/ungarj/mapchete) ⭐ 211 | 🐛 52 | 🌐 Python | 📅 2026-08-21 - Mapchete processes raster and vector geodata in digestable chunks. Tile-based geodata processing.
* [cubo](https://github.com/davemlz/cubo) ⭐ 210 | 🐛 2 | 🌐 Python | 📅 2026-02-12 - Easily create EO mini cubes from STAC in Python.
* [LANDSAT-Download](https://github.com/olivierhagolle/LANDSAT-Download) ⭐ 209 | 🐛 17 | 🌐 Python | 📅 2020-11-12 - Automated download of LANDSAT data from USGS website.
* [Peartree](https://github.com/kuanb/peartree) ⭐ 208 | 🐛 23 | 🌐 Python | 📅 2023-05-05 - Peartree: A library for converting transit data into a directed graph for network analysis.
* [geofileops](https://github.com/geofileops/geofileops) ⭐ 177 | 🐛 36 | 🌐 Python | 📅 2026-08-20 - Python toolbox to process large vector files faster.
* [pyinterpolate](https://github.com/DataverseLabs/pyinterpolate) ⭐ 175 | 🐛 8 | 🌐 Python | 📅 2026-05-23 - Ordinary Kriging, Simple Kriging, Indicator Kriging, Poisson Kriging, Area-to-Point Kriging, Semivariogram Deconvolution, and variogram modeling in Python
* [Tobler](https://github.com/pysal/tobler) ⭐ 169 | 🐛 22 | 🌐 Python | 📅 2026-07-30 - Tobler is a python package for areal interpolation, dasymetric mapping, and change of support.
* [prosail](https://github.com/jgomezdans/prosail) ⭐ 163 | 🐛 17 | 🌐 Python | 📅 2025-03-11 - Python bindings for the PROSAIL canopy reflectance model.
* [mapclassify](https://github.com/pysal/mapclassify) ⭐ 151 | 🐛 14 | 🌐 Jupyter Notebook | 📅 2026-08-11 - Classification schemes for choropleth mapping.
* [orbit-predictor](https://github.com/satellogic/orbit-predictor) ⭐ 151 | 🐛 18 | 🌐 Python | 📅 2025-06-16 - Orbit Predictor is a Python library to propagate orbits of Earth-orbiting objects (satellites, ISS, Santa Claus, etc) using TLE (Two-Line Elements set).
* [starfm4py](https://github.com/nmileva/starfm4py) ⭐ 150 | 🐛 1 | 🌐 Python | 📅 2023-02-08 - The STARFM fusion model for Python (image fusion).
* [sentle](https://github.com/cmosig/sentle) ⭐ 149 | 🐛 4 | 🌐 Python | 📅 2026-08-14 - Sentinel-1 & Sentinel-2 data cubes at large scale (bigger-than-memory) on any machine with integrated cloud detection, snow masking, harmonization, merging, and temporal composites. CDSE or PlanetaryComputer.
* [rio-color](https://github.com/mapbox/rio-color) ⭐ 147 | 🐛 4 | 🌐 Python | 📅 2026-06-29 - Color correction plugin for rasterio.
* [Ogcserver](https://github.com/mapnik/OGCServer) ⭐ 141 | 🐛 8 | 🌐 Python | 📅 2020-04-26 - Python WMS implementation using Mapnik.
* [geeup](https://github.com/samapriya/geeup) ⭐ 140 | 🐛 0 | 🌐 Python | 📅 2025-12-31 - Simple CLI for Earth Engine Uploads.
* [LARD](https://github.com/deel-ai/LARD) ⭐ 135 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2026-08-11 - A runway dataset and a generator of synthetic aerial images with automatic labeling.
* [pyDEM](https://github.com/creare-com/pydem) ⭐ 133 | 🐛 1 | 🌐 Python | 📅 2026-02-20 - Python library for Global Hydrology Analysis. Used to calculate upstream contributing area, aspect, slope, and topographic wetness index.
* [pyimpute](https://github.com/perrygeo/pyimpute) ⭐ 129 | 🐛 6 | 🌐 Python | 📅 2023-01-15 - Python module for geospatial prediction using scikit-learn and rasterio.
* [forestatrisk](https://github.com/ghislainv/forestatrisk) ⭐ 128 | 🐛 8 | 🌐 Python | 📅 2025-08-19 - Python package to model and forecast the risk of deforestation.
* [geojsonio.py](https://github.com/jwass/geojsonio.py) ⭐ 128 | 🐛 10 | 🌐 Python | 📅 2020-05-25 - Open GeoJSON data on geojson.io from Python. geojsonio.py also contains a command line utility that is a Python port of geojsonio-cli.
* [Turfpy](https://github.com/omanges/turfpy) ⭐ 127 | 🐛 29 | 🌐 Python | 📅 2026-04-13 - This is Python library for performing geo spatial data analysis. This is an python alternative for turf.js.
* [unmixing](https://github.com/arthur-e/unmixing) ⭐ 124 | 🐛 6 | 🌐 Python | 📅 2019-12-19 - Interactive tools and functions for performing linear spectral mixture analysis (LSMA) and spatially adaptive spectral mixture analysis (SASMA).
* [scikit-eo](https://github.com/ytarazona/scikit-eo) ⭐ 123 | 🐛 0 | 📅 2024-10-16 - A Python package for Remote Sensing Tools.
* [USGS API](https://github.com/kapadia/usgs) ⭐ 119 | 🐛 7 | 🌐 Python | 📅 2026-05-18 - USGS is a python module for interfacing with the US Geological Survey's API.
* [HPGL](https://github.com/hpgl/hpgl) ⭐ 118 | 🐛 2 | 🌐 HTML | 📅 2021-11-23 - High Perfomance Geostatistics Library.
* [Intake-stac](https://github.com/intake/intake-stac) ⭐ 113 | 🐛 27 | 🌐 Python | 📅 2026-08-17 - This is an intake data source for SpatioTemporal Asset Catalogs (STAC).
* [osm2geojson](https://github.com/aspectumapp/osm2geojson) ⭐ 113 | 🐛 2 | 🌐 Python | 📅 2026-07-19 - Parse OpenStreetMap (OSM) XML and Overpass JSON/XML.
* [stactools](https://github.com/stac-utils/stactools) ⭐ 113 | 🐛 43 | 🌐 Python | 📅 2024-12-23 - Command line utility and Python library for STAC.
* [geoalchemy](https://github.com/geoalchemy/geoalchemy) ⚠️ Archived - Using SQLAlchemy with spatial databases.
* [pymartini](https://github.com/kylebarron/pymartini) ⭐ 102 | 🐛 8 | 🌐 Python | 📅 2025-06-24 - A Cython port of Martini for fast RTIN terrain mesh generation
* [dask-rasterio](https://github.com/dymaxionlabs/dask-rasterio) ⭐ 98 | 🐛 2 | 🌐 Python | 📅 2020-11-28 - Read and write rasters in parallel using Rasterio and Dask.
* [geojson-area](https://github.com/scisco/area) ⭐ 97 | 🐛 5 | 🌐 Python | 📅 2018-10-31 - Calculate the area inside of any GeoJSON geometry.
* [geojson-area](https://github.com/scisco/area) ⭐ 97 | 🐛 5 | 🌐 Python | 📅 2018-10-31 - Calculate the area inside of any GeoJSON geometry. This is a port of Mapbox's geojson-area for Python.
* [rio-hist](https://github.com/mapbox/rio-hist) ⭐ 96 | 🐛 7 | 🌐 Python | 📅 2026-06-29 - Histogram matching plugin for rasterio.
* [Climata](https://github.com/heigeo/climata) ⭐ 89 | 🐛 7 | 🌐 Python | 📅 2018-09-25 - Python library for loading and iterating over climate and flow time series data (from ACIS/NOAA RCCs, CoCoRaHS, Hydromet/USBR, CNRFC ESP/NWS, SNOTEL/AWDB/NRCS, and NWIS/USGS).
* [pyle38](https://github.com/iwpnd/pyle38) ⭐ 89 | 🐛 7 | 🌐 Python | 📅 2026-08-03 - Asynchronous Client for the worlds fastest in-memory geo-database Tile38
* [python-opencage-geocoder](https://github.com/OpenCageData/python-opencage-geocoder) ⭐ 86 | 🐛 2 | 🌐 Python | 📅 2026-06-08 - A Python module that uses the OpenCage Geocoding API.
* [telluric](https://github.com/satellogic/telluric) ⭐ 86 | 🐛 52 | 🌐 Jupyter Notebook | 📅 2025-02-12 - telluric is a Python library to manage vector and raster geospatial data in an interactive and easy way.
* [pydelatin](https://github.com/kylebarron/pydelatin) ⭐ 85 | 🐛 6 | 🌐 C | 📅 2025-06-25 - Python bindings to `hmm` for fast terrain mesh generation
* [GIPPY](https://github.com/gipit/gippy) ⭐ 84 | 🐛 23 | 🌐 C++ | 📅 2020-01-06 - Geospatial Image Processing for Python.
* [aiocogeo](https://github.com/geospatial-jeff/aiocogeo) ⭐ 76 | 🐛 29 | 🌐 Python | 📅 2021-07-02 - Asynchronous cogeotiff reader.
* [aiocogeo](https://github.com/geospatial-jeff/aiocogeo) ⭐ 76 | 🐛 29 | 🌐 Python | 📅 2021-07-02 - Read Cloud Optimized GeoTiffs without GDAL.
* [geojson-shave](https://github.com/ben-nour/geojson-shave) ⭐ 76 | 🐛 0 | 🌐 Python | 📅 2025-05-04 - A Python command-line tool to reduce the size of GeoJSON files.
* [pygeoif](https://github.com/cleder/pygeoif) ⭐ 73 | 🐛 14 | 🌐 Python | 📅 2026-08-17 - PyGeoIf provides a GeoJSON-like protocol for geo-spatial (GIS) vector data. A simple, pure Python implementation of geometric objects and operations, useful for basic GIS tasks.
* [Mahotas-imread](https://github.com/luispedro/imread) ⭐ 71 | 🐛 2 | 🌐 C++ | 📅 2024-08-03 - Read images to numpy arrays.
* [cog\_validator](https://github.com/rouault/cog_validator) ⭐ 69 | 🐛 1 | 🌐 Python | 📅 2023-11-08 - This is a standalone (Python / Flask) service that allows users to submit GeoTIFF files (preferably by URL) and check their compliance with the Cloud Optimized GeoTIFF (COG) specification.
* [OSMnet](https://github.com/UDST/osmnet) ⭐ 66 | 🐛 1 | 🌐 Python | 📅 2026-08-21 - Tools for the extraction of OpenStreetMap street network data.
* [Urban Mapper](https://github.com/VIDA-NYU/UrbanMapper) ⭐ 66 | 🐛 4 | 🌐 Python | 📅 2025-12-20 – 🗺️ Spatial Join & Enrich any `urban layer` (Roads, Intersections, Sidewalks, Crosswalks, Neighborhoods, Cities, States, Countries) given any `external urban dataset` of interest, and streamline your urban analysis with Scikit-Learn-Like pipelines!
* [dsm2dtm](https://github.com/seedlit/dsm2dtm) ⭐ 64 | 🐛 0 | 🌐 Python | 📅 2026-05-10 - A Python library to convert Digital Surface Models (DSMs) to Digital Terrain Models (DTMs).
* [YATSM](https://github.com/ceholden/yatsm) ⚠️ Archived - Yet Another Timeseries Model (YATSM) is a Python package for utilizing a collection of timeseries algorithms and methods designed to monitor the land surface using remotely sensed imagery.
* [get\_modis](https://github.com/jgomezdans/get_modis) ⭐ 62 | 🐛 5 | 🌐 Python | 📅 2022-08-30 - Downloading MODIS data from the USGS repository.
* [landsat-extract-gee](https://github.com/loicdtx/landsat-extract-gee) ⭐ 62 | 🐛 3 | 🌐 Python | 📅 2019-09-11 - Get Landsat surface reflectance time-series from google earth engine.
* [sen2nbar](https://github.com/ESDS-Leipzig/sen2nbar) ⭐ 62 | 🐛 1 | 🌐 Python | 📅 2024-06-23 - Nadir BRDF Adjusted Reflectance (NBAR) for Sentinel-2 in Python.
* [GeoDaSpace](https://github.com/GeoDaCenter/GeoDaSpace) ⭐ 55 | 🐛 6 | 🌐 Python | 📅 2023-07-01 - Software for Advanced Spatial Econometrics.
* [geopatra](https://github.com/Sangarshanan/geopatra) ⭐ 55 | 🐛 15 | 🌐 Python | 📅 2026-03-11 - Interactive Maps with Geopandas.
* [gpdvega](https://github.com/iliatimofeev/gpdvega) ⭐ 51 | 🐛 5 | 🌐 Python | 📅 2020-06-24 - gpdvega is a bridge between GeoPandas and Altair that allows to seamlessly chart geospatial data.
* [chupaESRI](https://github.com/johnjreiser/chupaESRI) ⭐ 43 | 🐛 3 | 🌐 Python | 📅 2024-01-11 - ChupaESRI is a Python module/command line tool to extract features from ArcGIS Server map services.
* [AnaFlow](https://github.com/GeoStat-Framework/AnaFlow) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2025-10-17 - A python-package containing analytical solutions for the groundwater flow equation.
* [MuseoToolBox](https://github.com/nkarasiak/MuseoToolBox) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2020-08-03 - Museo ToolBox is a python library to simplify the use of raster/vector, especially for machine learning and remote sensing.
* [untiler](https://github.com/mapbox/untiler) ⚠️ Archived - Stitch image tiles into larger composite TIFs.
* [TerraTiff](https://github.com/Hejarshahabi/TerraTiff) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2026-06-02 - A lightweight, GDAL-free Python package for reading, writing, resampling, and masking GeoTIFF raster files using Numpy.
* [Centroids](https://github.com/lyzidiamond/centroids) ⭐ 23 | 🐛 4 | 🌐 JavaScript | 📅 2026-03-11 - This application reads a valid geojson FeatureCollection and returns a valid geojson FeatureColleciton of centroids.
* [geoconformal](https://github.com/pengtum/geoconformal) ⭐ 20 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-06-20 - Model-agnostic uncertainty quantification for geospatial prediction using conformal prediction.
* [Planet Movement](https://github.com/rhammell/planet-movement) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2020-08-16 - Python module enables the searching and processing of Planet imagery to highlight object movement between valid image pairs.
* [pipgeo](https://github.com/samapriya/pipgeo) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2025-12-06 - pipgeo: CLI for Unofficial windows Geospatial library wheels.
* [Pyncf](https://github.com/karimbahgat/pyncf) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2016-03-27 - Pure Python NetCDF file reading and writing.
* [geoapify](https://github.com/huels-originals/geoapify) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2023-06-03 - CLI and Python client for Geoapify's location services.
* [eo-box](https://github.com/benmack/eo-box) ⭐ 14 | 🐛 13 | 🌐 Python | 📅 2021-01-07 - Earth observation processing framework for machine learning in Python.
* [xarray\_leaflet](https://github.com/davidbrochart/xarray_leaflet) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2023-01-17 - An xarray extension for tiled map plotting.
* [cedar-datacube](https://github.com/ceholden/cedar-datacube) ⚠️ Archived - Create Earth engine Datacubes of Analytical Readiness.
* [momepy](https://github.com/martinfleis/momepy) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-08-13 - Momepy is a library for quantitative analysis of urban form - urban morphometrics.
* [LT-ChangeDB](https://github.com/eMapR/LT-ChangeDB) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2023-01-18 - Scripts to extract spectral change information from LandTrendr data to a geodatabase.
* [urban-worm](https://github.com/billbillbilly/urbanworm) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2026-05-21 - a Python library that integrates remote sensing imagery, street view data, and multi-modal models for spatial reasoning, focusing on built environments and urban units
* [ts-raster](https://github.com/adbeda/ts-raster) ⭐ 4 | 🐛 0 | 📅 2021-01-26 - ts-raster is a python package for analyzing time-series characteristics from raster data. It allows feature extraction, dimension reduction and applications of machine learning techniques for geospatial data.
* [xeo](https://github.com/awesome-spectral-indices/xeo) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - Awesome Earth Observation Instruments in Python.
* [ArcGIS Python API](https://developers.arcgis.com/python/) - ArcGIS API for Python is a Python library for working with maps and geospatial data, powered by web GIS.
* [Azure Planetary Computer](https://pypi.org/project/azure-planetarycomputer/1.0.0/) - Provides programmatic access to Microsoft Planetary Computer Pro, a geospatial data management service built on Azure's hyperscale infrastructure.
* [Cartopy](http://scitools.org.uk/cartopy/) - A library providing cartographic tools for python for plotting spatial data.
* [Descartes](https://pypi.python.org/pypi/descartes) - Plot geometries in matplotlib.
* [EODAG](https://eodag.readthedocs.io/en/latest/) - Command line tool and a plugin-oriented Python framework for searching, aggregating results and downloading remote sensed images while offering a unified API for data access regardless of the data provider.
* [Fiona](https://fiona.readthedocs.io/en/latest/) - For making it easy to read/write geospatial data formats.
* [FreeType](https://code.google.com/archive/p/freetype-py/) - For converting font glyphs to polygons.
* [GeoDjango](https://docs.djangoproject.com/en/2.2/ref/contrib/gis/) - Django geographic web framework.
* [HyRiver](https://hyriver.readthedocs.io) - A suite of Python packages for retrieving various geospatial/temporal data from public web services.
* [Lets-Plot](https://lets-plot.org) - An open-source plotting library supporting visualization of geospatial data on static or interactive maps.
* [networkx](http://networkx.github.io/) - To work with networks.
* [NodeBox-opengl](http://www.cityinabottle.org/nodebox/) - For playing around with animations.
* [planetary-computer](https://pypi.org/project/planetary-computer/) - Python library for interacting with the Microsoft Planetary Computer.
* [PODPAC](https://podpac.org/) - PODPAC is a python library that builds on the scientific python ecosystem to enable simple, reproducible geospatial analyses that run locally or in the cloud.
* [PyCanopy](https://github.com/pranav-walimbe) - A high-performance spatial query layer for Polars.
* [pyCSW](http://pycsw.org/) - Fully implements the OpenGIS Catalogue Service Implementation Specification (Catalogue Service for the Web). Initial development started in 2010 (more formally announced in 2011). The project is certified OGC Compliant, and is an OGC Reference Implementation.
* [pydeck](https://pydeck.gl) – Python bindings for deck.gl
* [pygeoapi](https://pygeoapi.io/)pygeoapi is a Python server implementation of the OGC API suite of standards. The project emerged as part of the next generation OGC API efforts in 2018 and provides the capability for organizations to deploy a RESTful OGC API endpoint using OpenAPI, GeoJSON, and HTML.
* [PyQGIS](http://docs.qgis.org/testing/en/docs/pyqgis_developer_cookbook/) - Python for QGIS.
* [PySAL](https://pysal.org/pysal/api.html) - For all your spatial econometrics needs.
* [PyShp](https://code.google.com/archive/p/pyshp/) - For reading and writing shapefiles.
* [pyWPS](http://pywps.org/) - An implementation of the Web Processing Service standard from the Open Geospatial Consortium. PyWPS is written in Python. It enables integration, publishing and execution of Python processes via the WPS standard.
* [RIOS](https://www.rioshome.org/en/latest/) - Raster I/O Simplification. A set of python modules which makes it easy to write raster processing code in Python.
* [RSGISLib](http://www.rsgislib.org/) - The Remote Sensing and GIS software library (RSGISLib) is a collection of tools for processing remote sensing and GIS datasets. The tools are accessed using Python bindings or an XML interface.
* [Rtree](http://toblerity.org/rtree/) - For efficiently querying spatial data.
* [satpy](https://satpy.readthedocs.io/en/latest/) - Satpy is a python library for reading, manipulating, and writing data from remote-sensing earth-observing meteorological satellite instruments.
* [SciKit-Gstat](https://scikit-gstat.readthedocs.io/en/latest/) - SciKit-Gstat is a scipy-styled analysis module for variogram analysis.
* [Scikit-image](http://scikit-image.org/) - Scikit-image is a collection of algorithms for image processing.
* [Shapely](https://pypi.python.org/pypi/Shapely) - Manipulation and analysis of geometric objects in the Cartesian plane.
* [Statsmodels](http://statsmodels.sourceforge.net/) - Python module that allows users to explore data, estimate statistical models, and perform statistical tests.
* [xarray](http://xarray.pydata.org/en/stable/) - xarray (formerly xray) is an open source project and Python package that aims to bring the labeled data power of pandas to the physical sciences, by providing N-dimensional variants of the core pandas data structures.

## PHP

* [FreeGeoDB](https://github.com/delight-im/FreeGeoDB) ⭐ 1,574 | 🐛 2 | 🌐 PHP | 📅 2018-10-19 - Free database of geographic place names and corresponding geospatial data.
* [geojson](https://github.com/jmikola/geojson) ⭐ 307 | 🐛 10 | 🌐 PHP | 📅 2024-01-17 - GeoJSON implementation for PHP.
* [geospatial](https://github.com/php-geospatial/geospatial) ⭐ 66 | 🐛 1 | 🌐 C | 📅 2025-07-01 - PHP Extension to handle common geospatial functions.
* [laravel-geo](https://github.com/eleven-lab/laravel-geo) ⭐ 49 | 🐛 5 | 🌐 PHP | 📅 2022-03-17 - GeoSpatial integration on Laravel 5.2+ that supports MySQL and PostgreSQL.
* [shapefile](https://github.com/phpmyadmin/shapefile) ⭐ 28 | 🐛 4 | 🌐 PHP | 📅 2026-08-14 - ESRI ShapeFile library for PHP.
* [PHP7 Mapnik](https://github.com/garrettrayj/php7-mapnik) ⭐ 20 | 🐛 5 | 🌐 C++ | 📅 2019-05-05 - PHP extension for geospatial rendering with Mapnik.
* [li3\_geo](https://github.com/nateabele/li3_geo) ⭐ 13 | 🐛 0 | 🌐 PHP | 📅 2018-01-25 - Adds geospatial support to Lithium for multiple databases, including MongoDB, CouchDB and MySQL.
* [laragis](https://github.com/ralphschindler/laragis) ⭐ 11 | 🐛 0 | 🌐 PHP | 📅 2017-07-22 - A standalone Geo/GIS Provider for Laravel.
* [ShapeReader](https://github.com/muka/ShapeReader) ⭐ 11 | 🐛 1 | 🌐 PHP | 📅 2021-06-24 - A PHP library to parse ESRI Shape files.
* [PHP Azure Maps Provider](https://github.com/geocoder-php/azure-maps-provider) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2025-11-21 - A PHP Azure Maps Geocoder Provider.
* [GeoPHP](https://geophp.net/) - Advanced geometry operations in PHP.

## R

* [rayshader](https://github.com/tylermorganwall/rayshader) ⭐ 2,174 | 🐛 48 | 🌐 R | 📅 2026-08-23 - rayshader is an open source R package for producing 2D and 3D hillshaded maps of elevation matrices using a combination of raytracing, spherical texture mapping, and ambient occlusion.
* [sf](https://github.com/r-spatial/sf) ⭐ 1,442 | 🐛 64 | 🌐 R | 📅 2026-08-21 - Simple Features for R.
* [geobr](https://github.com/ipeaGIT/geobr) ⭐ 939 | 🐛 19 | 🌐 R | 📅 2026-08-21 - Package to download official spatial data sets of Brazil.
* [ranger](https://github.com/imbs-hl/ranger) ⭐ 813 | 🐛 108 | 🌐 C++ | 📅 2026-02-01 - A Fast Implementation of Random Forests.
* [rgee](https://github.com/r-spatial/rgee) ⭐ 776 | 🐛 63 | 🌐 R | 📅 2026-08-17 - Google Earth Engine for R.
* [lidR](https://github.com/Jean-Romain/lidR) ⭐ 704 | 🐛 16 | 🌐 R | 📅 2026-08-14 - R package for airborne LiDAR data manipulation and visualisation for forestry application.
* [terra](https://github.com/rspatial/terra) ⭐ 617 | 🐛 14 | 🌐 C++ | 📅 2026-08-22 - terra is an R package that replaces raster. It has a very similar, but simpler, interface, and it is much faster.
* [stars](https://github.com/r-spatial/stars) ⭐ 611 | 🐛 26 | 🌐 R | 📅 2026-08-20 - Spatiotemporal tidy arrays for R.
* [sits](https://github.com/e-sensing/sits) ⭐ 546 | 🐛 25 | 🌐 R | 📅 2026-08-21 - Satellite image time series package for R.
* [stplanr](https://github.com/ropensci/stplanr) ⭐ 443 | 🐛 26 | 🌐 R | 📅 2025-04-28 - Sustainable transport planning with R.
* [wordcloud2](https://github.com/Lchiffon/wordcloud2) ⭐ 414 | 🐛 49 | 🌐 JavaScript | 📅 2022-02-03 - R interface to wordcloud for data visualization.
* [cartography](https://github.com/riatelab/cartography) ⭐ 403 | 🐛 0 | 🌐 R | 📅 2025-07-23 - Thematic Cartography with R.
* [sfnetworks](https://github.com/luukvdmeer/sfnetworks) ⭐ 398 | 🐛 28 | 🌐 R | 📅 2026-05-14 - Tidy Geospatial Networks in R.
* [ggspatial](https://github.com/paleolimbot/ggspatial) ⭐ 392 | 🐛 39 | 🌐 R | 📅 2025-08-24 - A ggplot2 R extension for plotting Spatial\* objects.
* [mapdeck](https://github.com/SymbolixAU/mapdeck) ⭐ 382 | 🐛 79 | 🌐 HTML | 📅 2025-03-21 - R interface to Deck.gl and Mapbox.
* [osmdata](https://github.com/ropensci/osmdata) ⭐ 342 | 🐛 25 | 🌐 R | 📅 2026-07-18 - R package for downloading OpenStreetMap data.
* [rnoaa](https://github.com/ropensci/rnoaa) ⭐ 340 | 🐛 28 | 🌐 R | 📅 2025-02-04 - R interface to many NOAA data sources.
* [getSpatialData](https://github.com/16EAGLE/getSpatialData) ⭐ 312 | 🐛 43 | 🌐 R | 📅 2023-07-10 - An R package making it easy to query, preview, download and preprocess multiple kinds of spatial data via R.
* [exactextractr](https://github.com/isciences/exactextractr) ⭐ 307 | 🐛 18 | 🌐 C++ | 📅 2026-06-03 - R package for fast and accurate raster zonal statistics.
* [rnaturalearth](https://github.com/ropensci/rnaturalearth) ⭐ 266 | 🐛 5 | 🌐 R | 📅 2026-07-09 - An R package to hold and facilitate interaction with Natural Earth map data.
* [landscapemetrics](https://github.com/r-spatialecology/landscapemetrics) ⭐ 262 | 🐛 12 | 🌐 R | 📅 2026-03-17 - landscapemetrics is an R package for calculating landscape metrics for categorical landscape patterns in a tidy workflow.
* [osrm R](https://github.com/rCarto/osrm) ⭐ 255 | 🐛 1 | 🌐 R | 📅 2026-03-12 - Interface Between R and the OpenStreetMap-Based Routing Service OSRM.
* [mapsf](https://github.com/riatelab/mapsf) ⭐ 245 | 🐛 2 | 🌐 R | 📅 2026-07-31 - Thematic cartography with R.
* [r5r](https://github.com/ipeaGIT/r5r) ⭐ 241 | 🐛 34 | 🌐 R | 📅 2026-07-21 - Package for rapid realistic routing on multimodal transport networks (walk, bike, public transport and car).
* [googleway](https://github.com/SymbolixAU/googleway) ⭐ 240 | 🐛 58 | 🌐 HTML | 📅 2024-09-24 - R Package for accessing and plotting Google Maps.
* [climateR](https://github.com/mikejohnson51/climateR) ⭐ 202 | 🐛 21 | 🌐 R | 📅 2026-04-09 - An R package for getting point and gridded climate data by AOI.
* [osmextract](https://github.com/ropensci/osmextract) ⭐ 195 | 🐛 28 | 🌐 R | 📅 2026-08-11 - Download and import OpenStreetMap data from Geofabrik and other providers.
* [fasterize](https://github.com/ecohealthalliance/fasterize) ⭐ 187 | 🐛 28 | 🌐 C++ | 📅 2025-03-08 - High performance raster conversion for modern spatial data.
* [whiteboxR](https://github.com/giswqs/whiteboxR) ⭐ 186 | 🐛 5 | 🌐 R | 📅 2025-10-21 - R frontend of [WhiteboxTools](https://github.com/jblindsay/whitebox-tools) ⭐ 1,192 | 🐛 175 | 🌐 Rust | 📅 2026-05-26.
* [tidytransit](https://github.com/r-transit/tidytransit) ⭐ 171 | 🐛 4 | 🌐 R | 📅 2026-06-23 - 'sf'-compatible package to analyze transit schedules, routes, and stops.
* [osmplotr](https://github.com/ropensci/osmplotr) ⭐ 142 | 🐛 14 | 🌐 R | 📅 2026-07-22 - Data visualisation using OpenStreetMap objects.
* [moveVis](https://github.com/16EAGLE/moveVis) ⭐ 139 | 🐛 64 | 🌐 R | 📅 2025-08-22 - An R package providing tools to visualize movement data (e.g. from GPS tracking) and temporal changes of environmental data (e.g. from remote sensing) by creating video animations.
* [edgebundle](https://github.com/schochastics/edgebundle) ⭐ 138 | 🐛 0 | 🌐 C++ | 📅 2026-07-24 - R package implementing edge bundling algorithms.
* [Prioritizr](https://github.com/prioritizr/prioritizr) ⭐ 137 | 🐛 14 | 🌐 R | 📅 2026-06-17 - The prioritizr R package uses integer linear programming (ILP) techniques to provide a flexible interface for building and solving conservation planning problems.
* [gdalcubes\_R](https://github.com/appelmar/gdalcubes_R) ⭐ 131 | 🐛 36 | 🌐 C++ | 📅 2026-05-29 - R package for gdalcubes to process collections of Earth observation image collection as on demand data cubes.
* [biomod2](https://github.com/biomodhub/biomod2) ⭐ 128 | 🐛 22 | 🌐 R | 📅 2026-07-17 - Computer platform for ensemble forecasting of species distributions, enabling the treatment of a range of methodological uncertainties in models and the examination of species-environment relationships.
* [mapboxapi](https://github.com/walkerke/mapboxapi) ⭐ 125 | 🐛 16 | 🌐 HTML | 📅 2026-01-23 - R interface to Mapbox web services.
* [spatialRF](https://github.com/BlasBenito/spatialRF) ⭐ 125 | 🐛 0 | 🌐 R | 📅 2026-07-15 - R package to fit spatial models with Random Forest.
* [rayvista](https://github.com/h-a-graham/rayvista) ⭐ 114 | 🐛 6 | 🌐 R | 📅 2023-03-20 - A package to view a 3D scene anywhere on earth.
* [openrouteservice-r](https://github.com/GIScience/openrouteservice-r) ⭐ 111 | 🐛 23 | 🌐 R | 📅 2025-02-08 - R package to query openrouteservice.org.
* [soilDB](https://github.com/ncss-tech/soilDB) ⭐ 100 | 🐛 30 | 🌐 R | 📅 2026-08-13 - Simplified Access to NCSS Soil Databases.
* [geotargets](https://github.com/njtierney/geotargets) ⭐ 97 | 🐛 28 | 🌐 R | 📅 2026-06-11 - Targets extensions for geospatial data.
* [geodist](https://github.com/hypertidy/geodist) ⭐ 96 | 🐛 9 | 🌐 C | 📅 2026-06-19 - Ultra lightweight, ultra fast calculation of geo distances.
* [bfastSpatial](https://github.com/loicdtx/bfastSpatial) ⭐ 95 | 🐛 40 | 🌐 R | 📅 2018-05-10 - Package to pre-process gridded time-series data in order for them to be analyzed with change detection algorithms such as bfast. Uses classes from the raster package and includes utilities to run the algorithms and post-process the results.
* [tidync](https://github.com/hypertidy/tidync) ⭐ 94 | 🐛 24 | 🌐 R | 📅 2026-07-31 - Systematic approaches to NetCDF data extraction, manipulation and visualization.
* [phenofit](https://github.com/kongdd/phenofit) ⭐ 91 | 🐛 3 | 🌐 R | 📅 2026-07-09 - A state-of-the-art Vegetation Phenology extraction package.
* [vapour](https://github.com/hypertidy/vapour) ⭐ 90 | 🐛 64 | 🌐 R | 📅 2026-07-12 - A lightweight GDAL API package for R.
* [mapscanner](https://github.com/ropensci/mapscanner) ⭐ 89 | 🐛 5 | 🌐 R | 📅 2025-02-07 - R package to print maps, draw on them, and scan them back in.
* [maxnet](https://github.com/mrmaxent/maxnet) ⭐ 87 | 🐛 10 | 🌐 R | 📅 2023-07-05 - R package for modelling species geographic distributions. It implements much of the functionality of the Maxent Java application.
* [geojsonsf](https://github.com/SymbolixAU/geojsonsf) ⭐ 85 | 🐛 8 | 🌐 R | 📅 2025-11-26 - Conversion between sf and geojson.
* [Tanaka](https://github.com/riatelab/tanaka) ⭐ 85 | 🐛 0 | 🌐 R | 📅 2023-11-28 - Tanaka Maps with R.
* [gtfs2gps](https://github.com/ipeaGIT/gtfs2gps) ⭐ 83 | 🐛 11 | 🌐 R | 📅 2026-06-30 - Convert GTFS data into a data.table with GPS-like records in R.
* [nngeo](https://github.com/michaeldorman/nngeo) ⭐ 83 | 🐛 0 | 🌐 C | 📅 2024-04-17 - k-Nearest Neighbor Join for Spatial Data.
* [rstac](https://github.com/brazil-data-cube/rstac) ⭐ 81 | 🐛 5 | 🌐 R | 📅 2026-05-07 - R Client Library for SpatioTemporal Asset Catalog.
* [giscoR](https://github.com/rOpenGov/giscoR) ⭐ 80 | 🐛 0 | 🌐 R | 📅 2026-08-22 - An API package that helps to retrieve data from Eurostat - GISCO (the Geographic Information System of the COmmission).
* [rgeoda](https://github.com/GeoDaCenter/rgeoda) ⭐ 78 | 🐛 18 | 🌐 R | 📅 2026-02-19 - rgeoda is a R package for spatial data analysis based on libgeoda and GeoDa.
* [supercells](https://github.com/Nowosad/supercells) ⭐ 77 | 🐛 10 | 🌐 R | 📅 2026-08-07 - The goal of supercells is to utilize the concept of superpixels to a variety of spatial data.
* [sfheaders](https://github.com/dcooley/sfheaders) ⭐ 76 | 🐛 14 | 🌐 R | 📅 2025-11-27 - Build sf objects from R and Rcpp.
* [kuenm](https://github.com/marlonecobos/kuenm) ⭐ 70 | 🐛 21 | 🌐 TeX | 📅 2023-12-04 - kuenm is an R package designed to make the process of model calibration and final model creation easier and more reproducible, and at the same time more robust.
* [geom](https://github.com/paleolimbot/geom) ⭐ 65 | 🐛 11 | 🌐 R | 📅 2026-08-11 - Vectorized geometries and low-level GEOS access.
* [geos](https://github.com/paleolimbot/geos) ⭐ 65 | 🐛 11 | 🌐 R | 📅 2026-08-11 - Open Source Geometry Engine ('GEOS') R API.
* [biodivMapR](https://github.com/jbferet/biodivMapR) ⭐ 63 | 🐛 2 | 🌐 R | 📅 2026-08-22 - R package for α- and β-diversity mapping using remotely-sensed images.
* [GeospatialLineGraphs](https://github.com/Brideau/GeospatialLineGraphs) ⭐ 62 | 🐛 0 | 🌐 R | 📅 2016-10-16 - A library for creating geospatial line graphs along lines of latitude.
* [ForesToolboxRS](https://github.com/ytarazona/ForesToolboxRS) ⭐ 61 | 🐛 1 | 🌐 R | 📅 2024-11-21 - R package providing a variety of tools and algorithms for the processing and analysis of satellite images for the various applications of Remote Sensing for Earth Observations.
* [OpenImageR](https://github.com/mlampros/OpenImageR) ⭐ 61 | 🐛 0 | 🌐 R | 📅 2023-07-08 - Image processing Toolkit in R.
* [gdalraster](https://github.com/USDAForestService/gdalraster) ⭐ 59 | 🐛 11 | 🌐 C++ | 📅 2026-08-23 - R Bindings to the GDAL Raster API.
* [Makurhini](https://github.com/connectscape/Makurhini) ⭐ 57 | 🐛 14 | 🌐 HTML | 📅 2026-06-22 - R package for calculating fragmentation and landscape connectivity indices used in conservation planning.
* [ribge](https://github.com/tbrugz/ribge) ⭐ 56 | 🐛 2 | 🌐 R | 📅 2026-01-29 - R package for (down)loading data from IBGE (Instituto Brasileiro de Geografia e Estatística).
* [earthEngineGrabR](https://github.com/JesJehle/earthEngineGrabR) ⭐ 55 | 🐛 8 | 🌐 R | 📅 2020-06-24 - The earthEngineGrabR is an interface between R and the Google Earth Engine, which simplifies the acquisition of remote sensing data.
* [sftrack](https://github.com/mablab/sftrack) ⭐ 55 | 🐛 1 | 🌐 HTML | 📅 2026-05-18 - Modern classes for tracking and movement data.
* [censobr](https://github.com/ipeaGIT/censobr) ⭐ 54 | 🐛 16 | 🌐 R | 📅 2026-07-29 - R package to download data from Brazil's Population Census.
* [wt](https://github.com/paleolimbot/wk) ⭐ 52 | 🐛 13 | 🌐 R | 📅 2025-12-21 - Lightweight Well-Known Geometry Parsing.
* [ModelR](https://github.com/Model-R/modelr_pkg) ⭐ 50 | 🐛 22 | 🌐 R | 📅 2025-08-09 - A workflow for ecological niche models based on dismo.
* [landmap](https://github.com/EnvirometriX/landmap) ⭐ 48 | 🐛 7 | 🌐 R | 📅 2022-06-16 - Provides methodology for automated mapping i.e. spatial interpolation and/or prediction using Ensemble Machine Learning.
* [tmaptools](https://github.com/mtennekes/tmaptools) ⭐ 43 | 🐛 10 | 🌐 R | 📅 2025-07-24 - This package offers a set of handy tool functions for reading and processing spatial data.
* [uavRst](https://github.com/gisma/uavRst) ⭐ 42 | 🐛 0 | 🌐 R | 📅 2024-06-18 - UAV related Remote Sensing Toolbox.
* [SpatialRDD](https://github.com/axlehner/SpatialRDD) ⭐ 41 | 🐛 3 | 🌐 R | 📅 2024-03-21 - R package to work spatialy with RDD files.
* [teamlucc](https://github.com/azvoleff/teamlucc) ⭐ 37 | 🐛 7 | 🌐 R | 📅 2016-06-10 -  Is designed to facilitate analysis of land use and cover change (LUCC) around the monitoring sites of the Tropical Ecology Assessment and Monitoring (TEAM) Network.
* [marmap](https://github.com/ericpante/marmap) ⭐ 35 | 🐛 5 | 🌐 R | 📅 2025-08-02 - Import, plot and analyze bathymetric and topographic data.
* [popRF](https://github.com/wpgp/popRF) ⭐ 35 | 🐛 2 | 🌐 R | 📅 2023-12-17 - Random Forest-informed Population Disaggregation.
* [LandsatTS](https://github.com/logan-berner/LandsatTS) ⭐ 34 | 🐛 0 | 🌐 R | 📅 2024-10-17 - An R package to facilitate retrieval, cleaning, cross-calibration, and phenological modeling of Landsat time-series data.
* [Rsagacmd](https://github.com/stevenpawley/Rsagacmd) ⭐ 34 | 🐛 3 | 🌐 R | 📅 2025-05-21 - A package for linking R with the open-source SAGA-GIS.
* [potential](https://github.com/riatelab/potential) ⭐ 30 | 🐛 0 | 🌐 R | 📅 2026-07-27 - An R package to compute the potential model as defined by Stewart (1941).
* [s2](https://github.com/spatstat/s2) ⭐ 30 | 🐛 0 | 🌐 C | 📅 2019-08-16 - R bindings for Google's s2 library for geometry on the sphere.
* [geocmeans](https://github.com/JeremyGelb/geocmeans) ⭐ 29 | 🐛 1 | 🌐 R | 📅 2026-04-19 - An R package to perform Spatial Fuzzy C-means.
* [rHarmonics](https://github.com/MBalthasar/rHarmonics/) ⭐ 29 | 🐛 0 | 🌐 R | 📅 2020-08-21 - R package for harmonic modelling of time-series data.
* [ROSM](https://github.com/paleolimbot/rosm) ⭐ 29 | 🐛 6 | 🌐 R | 📅 2026-01-24 - Plot Open Street Map and Other Tiles in R.
* [gdalio](https://github.com/hypertidy/gdalio) ⭐ 28 | 🐛 14 | 🌐 R | 📅 2022-06-06 - The goal of gdalio is to read data direct with GDAL warp, with an assumed grid specification.
* [forestError](https://github.com/benjilu/forestError) ⭐ 27 | 🐛 0 | 🌐 R | 📅 2021-08-10 - A Unified Framework for Random Forest Prediction Error Estimation.
* [rasterDT](https://github.com/JoshOBrien/rasterDT) ⭐ 27 | 🐛 2 | 🌐 R | 📅 2023-08-24 - rasterDT uses the fast indexing, aggregation, and assignment operations provided by data.table to power speedy alternatives to several raster package functions.
* [geovctrs](https://github.com/paleolimbot/geovctrs) ⭐ 26 | 🐛 3 | 🌐 R | 📅 2020-07-24 - Common Classes and Data Structures for Geometry Vectors.
* [quickglobe](https://github.com/daranzolin/quickglobe) ⭐ 22 | 🐛 1 | 🌐 R | 📅 2020-05-25 - View Country Data via a 3D, D3, Globe.
* [rasterdiv](https://github.com/mattmar/rasterdiv) ⭐ 22 | 🐛 3 | 🌐 R | 📅 2026-03-23 - Diversity Indices for Numerical Matrices.
* [rtsVis](https://github.com/JohMast/rtsVis) ⭐ 21 | 🐛 1 | 🌐 R | 📅 2023-10-19 - A lightweight R package to visualize large raster time series, building on a fast temporal interpolation core.
* [polyclip](https://github.com/baddstats/polyclip) ⭐ 20 | 🐛 6 | 🌐 C++ | 📅 2024-07-22 - R package polyclip: a port of the Clipper library for polygon geometry.
* [ncdfgeom](https://github.com/USGS-R/ncdfgeom) ⭐ 19 | 🐛 9 | 🌐 R | 📅 2026-04-22 - NetCDF-CF Geometry and Timeseries Tools for R.
* [libproj](https://github.com/paleolimbot/libproj) ⭐ 16 | 🐛 1 | 🌐 C | 📅 2024-03-06 - C API for high-performance geometry operations within the R package framework.
* [elsa](https://github.com/babaknaimi/elsa) ⭐ 15 | 🐛 1 | 🌐 R | 📅 2025-10-02 - ELSA (entropy-based local indicator of spatial association) is a novel spatial statistic to measure local spatial autocorrelation in both categorical and continuous spatial data.
* [spflow](https://github.com/LukeCe/spflow) ⭐ 15 | 🐛 6 | 🌐 R | 📅 2023-11-08 - Spatial Econometric Interaction Models in R.
* [tmap](https://github.com/mtennekes/tmap) ⭐ 15 | 🐛 0 | 📅 2022-11-10 - R-library for drawing thematic maps. The API is based on A Layered Grammar of Graphics and resembles the syntax of ggplot2.
* [stlnpp](https://github.com/Moradii/stlnpp) ⭐ 13 | 🐛 0 | 🌐 R | 📅 2025-08-19 - Spatio-temporal point patterns on linear networks.
* [pepair](https://github.com/dickoa/prepair) ⭐ 12 | 🐛 3 | 🌐 C++ | 📅 2022-11-09 - An R package to repair broken GIS polygons using the prepair cpp library.
* [tiff](https://github.com/s-u/tiff) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2023-11-27 - Read and write TIFF images in R.
* [LPDynR](https://github.com/xavi-rp/LPDynR) ⭐ 8 | 🐛 0 | 🌐 R | 📅 2024-09-10 - An R-package to calculate Land Productivity Dynamics using variables derived from Earth Observation imagery.
* [MTA](https://github.com/riatelab/MTA) ⭐ 7 | 🐛 0 | 🌐 R | 📅 2025-05-12 - Multiscalar Territorial Analysis is an R package for multiscalar territorial analysis based on various contexts.
* [bivariatemaps](https://github.com/hidasi/bivariatemaps) ⭐ 5 | 🐛 2 | 🌐 R | 📅 2024-10-14 - Generates bivariate maps and intersects shapefiles with grids and excludes cells based on area coverage.
* [ffraster](https://github.com/hypertidy/ffraster) ⭐ 5 | 🐛 1 | 🌐 R | 📅 2018-10-15 - Treat ff arrays as raster objects, and vice versa.
* [streetscape](https://github.com/land-info-lab/streetscape) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2024-08-31 - A collection of functions to search and download Mapillary street view images and to extract, quantify, and visualize visual features.
* [viewscape](https://github.com/land-info-lab/viewscape) ⭐ 3 | 🐛 5 | 🌐 R | 📅 2026-06-20 - The viewscape package provides an accessible method of carrying out landscape spatial analysis based on the viewshed within the R environment
* [dtwSat](https://github.com/vwmaus/dtwSat) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2023-12-26 - Time-Weighted Dynamic Time Warping for satellite image time series analysis.
* [secciones-nacionalidades](https://github.com/GeiserX/secciones-nacionalidades) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2026-06-23 - R Shiny app to visualize population by nationality at census section level in Spain using INE data, with interactive Leaflet maps and Highcharter charts.
* [dsmSearch](https://github.com/land-info-lab/dsmSearch) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2026-06-24 - The package dsmSearch offers functions for retrieving high-resolution Digital Surface Models (DSM) and Light Detection and Ranging (LiDAR) data
* [ade4](https://cran.r-project.org/web/packages/ade4/index.html) - Tools for multivariate data analysis. Several methods are provided for the analysis (i.e., ordination) of one-table (e.g., principal component analysis, correspondence analysis), two-table (e.g., coinertia analysis, redundancy analysis), three-table (e.g., RLQ analysis) and K-table (e.g., STATIS, multiple coinertia analysis).
* [adehabitat](https://cran.r-project.org/web/packages/adehabitat/index.html) - A collection of tools for the analysis of habitat selection by animals.
* [adehabitatHR](https://cran.r-project.org/web/packages/adehabitatHR/index.html) - A collection of tools for the estimation of animals home range.
* [adehabitatHS](https://cran.r-project.org/web/packages/adehabitatHS/index.html) - A collection of tools for the analysis of habitat selection.
* [adehabitatLT](https://cran.r-project.org/web/packages/adehabitatLT/index.html) - A collection of tools for the analysis of animal movements.
* [adehabitatMA](https://cran.r-project.org/web/packages/adehabitatMA/index.html) - A collection of tools to deal with raster maps.
* [Akima](https://cran.r-project.org/web/packages/akima/index.html) - Interpolation of Irregularly and Regularly Spaced Data.
* [AMOEBA](https://cran.r-project.org/web/packages/AMOEBA/index.html) - A function to calculate spatial clusters using the Getis-Ord local statistic. It searches irregular clusters (ecotopes) on a map.
* [CARBayes](https://cran.r-project.org/web/packages/CARBayes/index.html) - Package implements Bayesian hierarchical spatial areal unit models.
* [classInt](https://cran.r-project.org/web/packages/classInt/index.html) - Selected commonly used methods for choosing univariate class intervals for mapping or other graphics purposes.
* [CompRandFld](https://cran.r-project.org/web/packages/CompRandFld/index.html) - A set of procedures for the analysis of Random Fields using likelihood and non-standard likelihood methods is provided.
* [constrainedKriging](https://cran.r-project.org/web/packages/constrainedKriging/index.html) - Provides functions for efficient computations of nonlinear spatial predictions with local change of support.
* [cshapes](https://cran.r-project.org/web/packages/cshapes/index.html) - Package for CShapes, a GIS dataset of country boundaries (1946-today). Includes functions for data extraction and the computation of distance matrices and -lists.
* [dbmss](https://cran.r-project.org/web/packages/dbmss/index.html) - Simple computation of spatial statistic functions of distance to characterize the spatial structures of mapped objects.
* [deldir](https://cran.r-project.org/web/packages/deldir/index.html) - Calculates the Delaunay triangulation and the Dirichlet or Voronoi tessellation (with respect to the entire plane) of a planar point set.
* [dggridR](https://cran.r-project.org/web/packages/dggridR/index.html) - Provides an interface to DGGRID for working with discrete global grids, using hexagons, triangles, and diamonds to overcome the issue that every bin have the same area.
* [DSpat](https://cran.r-project.org/web/packages/DSpat/index.html) - Fits inhomogeneous Poisson process spatial models to line transect sampling data and provides estimate of abundance within a region.
* [ecespa](https://cran.r-project.org/web/packages/ecespa/index.html) - Functions for Spatial Point Pattern Analysis.
* [ExceedanceTools](https://cran.r-project.org/web/packages/ExceedanceTools/index.html) - Tools for constructing confidence regions for exceedance regions and contour lines.
* [FieldSim](https://cran.r-project.org/web/packages/FieldSim/index.html) - Tools for random fields and bridges simulations.
* [FRK](https://cran.r-project.org/web/packages/FRK/index.html) - Is a tool for spatial/spatio-temporal modelling and prediction with large datasets.
* [geoaxe](https://cran.r-project.org/web/packages/geoaxe/index.html) - Split 'geospatial' objects into pieces. Includes support for some spatial object inputs, 'Well-Known Text', and 'GeoJSON'.
* [geojsonio](https://cran.r-project.org/web/packages/geojsonio/index.html) - Convert data to 'GeoJSON' or 'TopoJSON' from various R classes, including vectors, lists, data frames, shape files, and spatial classes.
* [GEOmap](https://cran.r-project.org/web/packages/GEOmap/index.html) - Topographic and Geologic Mapping.
* [geoR](https://cran.r-project.org/web/packages/geoR/index.html) - Analysis of Geostatistical Data.
* [geoRglm](https://cran.r-project.org/web/packages/geoRglm/index.html) - Functions for inference in generalised linear spatial models.
* [georob](https://cran.r-project.org/web/packages/georob/index.html) - Provides functions for fitting linear models with spatially correlated errors by robust and Gaussian Restricted Maximum Likelihood and for computing robust and customary point and block kriging predictions, along with utility functions for cross-validation and for unbiased back-transformation of kriging predictions of log-transformed data.
* [geospacom](https://cran.r-project.org/web/packages/geospacom/index.html) - Generates distance matrices from shape files and represents spatially weighted multilevel analysis results.
* [geosphere](https://cran.r-project.org/web/packages/geosphere/index.html) - Permits computations of distance and area to be carried out on spatial data in geographical coordinates.
* [geospt](https://cran.r-project.org/web/packages/geospt/index.html) - Contains some geostatistical and radial basis functions, including prediction and cross validation.
* [GeoXp](https://cran.r-project.org/web/packages/GeoXp/index.html) - Permits interactive graphical exploratory spatial data analysis.
* [ggmap](https://cran.r-project.org/web/packages/ggmap/index.html) - Spatial Visualization with ggplot2.
* [ggsn](https://cran.r-project.org/web/packages/ggsn/index.html) - Adds north symbols and scale bars in kilometers to maps in geographic or metric coordinates.
* [glmmBUGS](https://cran.r-project.org/web/packages/glmmBUGS/index.html) - Automates running Generalized Linear Mixed Models, including spatial models, with WinBUGS, OpenBUGS and JAGS.
* [gmt](https://cran.r-project.org/web/packages/gmt/index.html) - Interface between the GMT map-making software and R.
* [Grid2Polygons](https://cran.r-project.org/web/packages/Grid2Polygons/index.html) - Converts a spatial object from class SpatialGridDataFrame to SpatialPolygonsDataFrame.
* [GriegSmith](https://cran.r-project.org/web/packages/GriegSmith/index.html) - Uses the Grieg-Smith method on 2 dimensional spatial data.
* [gstat](https://cran.r-project.org/web/packages/gstat/index.html) - Spatio-Temporal Geostatistical Modelling, Prediction and Simulation.
* [gwrr](https://cran.r-project.org/web/packages/gwrr/index.html) - Fits geographically weighted regression (GWR) models and has tools to diagnose and remediate collinearity in the GWR models.
* [hdeco](https://cran.r-project.org/web/packages/hdeco/index.html) -  Provides hierarchical decomposition of entropy for categorical map comparisons.
* [HSAR](https://cran.r-project.org/web/packages/HSAR/index.html) - A library of the Hierarchical Spatial Autoregressive Model (HSAR), based on a Bayesian Markov Chain Monte Carlo (MCMC) algorithm.
* [intamap](https://cran.r-project.org/web/packages/intamap/index.html) - Procedures for automated interpolation.
* [ipdw](https://cran.r-project.org/web/packages/ipdw/index.html) - Functions are provided to interpolate geo-referenced point data via Inverse Path Distance Weighting.
* [Landsat](https://cran.r-project.org/web/packages/landsat/index.html) - Radiometric and topographic correction of satellite imagery.
* [latticeDensity](https://cran.r-project.org/web/packages/latticeDensity/index.html) -  Contains functions that compute the lattice-based density estimator of Barry and McIntyre.
* [lawn](https://cran.r-project.org/web/packages/lawn/index.html) - Client for 'Turfjs' for 'geospatial' analysis. The package revolves around using 'GeoJSON' data.
* [lctools](https://cran.r-project.org/web/packages/lctools/index.html) - Package provides researchers and educators with easy-to-learn user friendly tools for calculating key spatial statistics and to apply simple as well as advanced methods of spatial analysis in real data.
* [leafletR](https://cran.r-project.org/web/packages/leafletR/index.html) - Interactive Web-Maps Based on the Leaflet JavaScript Library.
* [lucCalculus](https://github.com/e-sensing/lucCalculus) - Spatiotemporal calculus for land use change trajectories.
* [magclass](https://cran.r-project.org/web/packages/magclass/index.html) - Data class for increased interoperability working with spatial- temporal data together with corresponding functions and methods (conversions, basic calculations and basic data manipulation).
* [mapproj](https://cran.r-project.org/web/packages/mapproj/index.html) - Map Projections.
* [maps](https://cran.r-project.org/web/packages/maps/index.html) - Draw Geographical Maps.
* [maptools](https://cran.r-project.org/web/packages/maptools/index.html) - Tools for Reading and Handling Spatial Objects.
* [mapview](https://r-spatial.github.io/mapview/index.html) - mapview provides functions to very quickly and conveniently create interactive visualisations of spatial data.
* [marmap](https://cran.r-project.org/web/packages/marmap/index.html) - Package is designed for downloading, plotting and manipulating bathymetric and topographic data in R.
* [McSpatial](https://cran.r-project.org/web/packages/McSpatial/index.html) - Provides functions for locally weighted regression, semiparametric and conditionally parametric regression, fourier and cubic spline functions, GMM and linearized spatial logit and probit, k-density functions and counterfactuals, nonparametric quantile regression and conditional density functions, Machado-Mata decomposition for quantile regressions, spatial AR model, repeat sales models, and conditionally parametric logit and probit.
* [micromap](https://cran.r-project.org/web/packages/micromap/index.html) - Package provides linked micromaps using ggplot2.
* [ModelMap](https://cran.r-project.org/web/packages/ModelMap/index.html) - Creates sophisticated models of training data and validates the models with an independent test set, cross validation, or in the case of Random Forest Models, with Out Of Bag (OOB) predictions on the training data.
* [ncdf4](https://cran.r-project.org/web/packages/ncdf4/index.html) - Provides a high-level R interface to data files written using Unidata's netCDF library (version 4 or earlier).
* [ngspatial](https://cran.r-project.org/web/packages/ngspatial/index.html) - Provides tools for analyzing spatial data, especially non- Gaussian areal data.
* [nlme](https://cran.r-project.org/web/packages/nlme/index.html) - Fit and compare Gaussian linear and nonlinear mixed-effects models.
* [OasisR](https://cran.r-project.org/web/packages/OasisR/index.html) - A set of indexes and tests for the analysis of social segregation.
* [OpenStreetMap](https://cran.r-project.org/web/packages/OpenStreetMap/index.html) - Access to Open Street Map Raster Images.
* [osmar](https://cran.r-project.org/web/packages/osmar/index.html) - Provides infrastructure to access OpenStreetMap data from different sources.
* [pastecs](https://cran.r-project.org/web/packages/pastecs/index.html) - Regulation, decomposition and analysis of space-time series.
* [PBSmapping](https://cran.r-project.org/web/packages/PBSmapping/index.html) - Mapping Fisheries Data and Spatial Analysis Tools.
* [PBSmodelling](https://cran.r-project.org/web/packages/PBSmodelling/index.html) - Provides modelling support.
* [phenopix](https://cran.r-project.org/web/packages/phenopix/index.html) - A collection of functions to process digital images, depict greenness index trajectories and extract relevant phenological stages.
* [plotGoogleMaps](https://cran.r-project.org/web/packages/plotGoogleMaps/index.html) - Interactive plot device for handling the geographic data for web browsers.
* [plotKML](https://cran.r-project.org/web/packages/plotKML/index.html) - Visualization of Spatial and Spatio-Temporal Objects in Google Earth.
* [PReMiuM](https://cran.r-project.org/web/packages/PReMiuM/index.html) - Dirichlet Process Bayesian Clustering, Profile Regression.
* [ProbitSpatial](https://cran.r-project.org/web/packages/ProbitSpatial/index.html) - Binomial Spatial Probit models for big data.
* [RandomFields](https://cran.r-project.org/web/packages/RandomFields/index.html) - Methods for the inference on and the simulation of Gaussian fields are provided, as well as methods for the simulation of extreme value random fields.
* [rangeMapper](https://cran.r-project.org/web/packages/rangeMapper/index.html) - Tools for easy generation of (life-history) traits maps based on species range (extent-of-occurrence) maps.
* [RArcInfo](https://cran.r-project.org/web/packages/RArcInfo/index.html) - Functions to import data from Arc/Info V7.x binary coverages.
* [raster](https://cran.r-project.org/web/packages/raster/raster.pdf) - Reading, writing, manipulating, analyzing and modeling of gridded spatial data.
* [rasterVis](https://cran.r-project.org/web/packages/rasterVis/index.html) - Visualization Methods for Raster Data.
* [Rcitrus](http://www.leg.ufpr.br/Rcitrus/) - Spatial analysis of plant disease incidence.
* [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html) - Provides color schemes for maps and other graphics.
* [recmap](https://cran.r-project.org/web/packages/recmap/index.html) - Package provides rectangular cartograms with rectangle sizes reflecting for example population
* [regress](https://cran.r-project.org/web/packages/regress/index.html) - Functions to fit Gaussian linear model by maximising the residual log likelihood where the covariance structure can be written as a linear combination of known matrices.
* [rgdal](https://cran.r-project.org/web/packages/rgdal/index.html) - Bindings for the Geospatial Data Abstraction Library.
* [rgeos](https://cran.r-project.org/web/packages/rgeos/index.html) - Interface to Geometry Engine - Open Source (GEOS) using the C API for topology operations on geometries.
* [Rgooglemaps](https://cran.r-project.org/web/packages/RgoogleMaps/index.html) - Overlays on Google map tiles in R.
* [rgrass7](https://cran.r-project.org/web/packages/rgrass7/index.html) - Interface Between GRASS 7 GIS and R.
* [Rnetcdf](https://cran.r-project.org/web/packages/RNetCDF/index.html) - Interface to NetCDF Datasets.
* [RODBC](https://cran.r-project.org/web/packages/RODBC/index.html) - ODBC Database Access.
* [RPyGeo](https://cran.r-project.org/web/packages/RPyGeo/index.html) - ArcGIS Geoprocessing in R via Python.
* [RQGIS](https://cran.r-project.org/web/packages/RQGIS/index.html) - Establishes an interface between R and QGIS.
* [RSAGA](https://cran.r-project.org/web/packages/RSAGA/index.html) - SAGA Geoprocessing and Terrain Analysis in R.
* [rsMove](https://cran.r-project.org/web/packages/rsMove/index.html) - Tools that support the combined use of animal movement and remote sensing data.
* [RStoolbox](https://cran.r-project.org/web/packages/RStoolbox/index.html) - Toolbox for remote sensing image processing and analysis such as calculating spectral indices, principal component transformation, unsupervised and supervised classification or fractional cover analyses.
* [rworldmap](https://cran.r-project.org/web/packages/rworldmap/index.html) - Mapping Global Data.
* [S2sls](https://cran.r-project.org/web/packages/S2sls/index.html) - Fit a spatial instrumental-variable regression by two-stage least squares.
* [sfarrow](https://wcjochem.github.io/sfarrow/index.html) - Package for reading and writing Parquet and Feather files with sf objects using arrow in R.
* [sgeostat](https://cran.r-project.org/web/packages/sgeostat/index.html) - An Object-oriented Framework for Geostatistical Modeling in S+ containing functions for variogram estimation, variogram fitting and kriging as well as some plot functions.
* [shapefiles](https://cran.r-project.org/web/packages/shapefiles/index.html) - Read and Write ESRI Shapefiles.
* [siplab](https://cran.r-project.org/web/packages/siplab/index.html) - A platform for experimenting with spatially explicit individual-based vegetation models.
* [smacpod](https://cran.r-project.org/web/packages/smacpod/index.html) - Various statistical methods for analyzing case-control point data.
* [smerc](https://cran.r-project.org/web/packages/smerc/index.html) - Provides statistical methods for the analysis of data areal data, with a focus on cluster detection.
* [sp](https://cran.r-project.org/web/packages/sp/index.html) - Classes and Methods for Spatial Data.
* [spacetime](https://cran.r-project.org/web/packages/spacetime/index.html) - Classes and Methods for Spatio-Temporal Data.
* [spacom](https://cran.r-project.org/web/packages/spacom/index.html) - Provides tools to construct and exploit spatially weighted context data.
* [spaMM](https://cran.r-project.org/web/packages/spaMM/index.html) - Inference in mixed-effect models, including generalized linear mixed models with spatial correlations and models with non-Gaussian random effects.
* [spanel](https://cran.r-project.org/web/packages/spanel/index.html) - Fit the spatial panel data models: the fixed effects, random effects and between models.
* [sparr](https://cran.r-project.org/web/packages/sparr/index.html) - Provides functions to estimate kernel-smoothed spatial and spatio-temporal densities and relative risk functions, and perform subsequent inference.
* [spatcounts](https://cran.r-project.org/web/packages/spatcounts/index.html) - Fit spatial CAR count regression models using MCMC.
* [spatgraphs](https://cran.r-project.org/web/packages/spatgraphs/index.html) - Graphs (or networks) and graph component calculations for spatial locations
* [spatialCovariance](https://cran.r-project.org/web/packages/spatialCovariance/index.html) - Supports the computation of spatial covariance matrices for data on rectangles.
* [SpatialEpi](https://cran.r-project.org/web/packages/SpatialEpi/index.html) - Methods and data for cluster detection and disease mapping.
* [SpatialPosition](https://cran.r-project.org/web/packages/SpatialPosition/index.html) - Computes spatial position models: Stewart potentials, Reilly catchment areas, Huff catchment areas.
* [spatialprobit](https://cran.r-project.org/web/packages/spatialprobit/index.html) - Bayesian Estimation of Spatial Probit and Tobit Models.
* [spatialsegregation](https://cran.r-project.org/web/packages/spatialsegregation/index.html) - Summaries for measuring segregation/mingling in multitype spatial point patterns with graph based neighbourhood description.
* [SpatialTools](https://cran.r-project.org/web/packages/SpatialTools/index.html) - Tools for spatial data analysis. Emphasis on kriging. Provides functions for prediction and simulation.
* [spatstat](https://cran.r-project.org/web/packages/spatstat/index.html) - Spatial Point Pattern Analysis, Model-Fitting, Simulation, Tests.
* [spatsurv](https://cran.r-project.org/web/packages/spatsurv/index.html) - Bayesian inference for parametric proportional hazards spatial survival models; flexible spatial survival models.
* [spBayesSurv](https://cran.r-project.org/web/packages/spBayesSurv/index.html) - Bayesian Modeling and Analysis of Spatially Correlated Survival Data.
* [spcosa](https://cran.r-project.org/web/packages/spcosa/index.html) - Spatial coverage sampling and random sampling from compact geographical strata created by k-means.
* [spdep](https://cran.r-project.org/web/packages/spdep/index.html) - Spatial Dependence: Weighting Schemes, Statistics and Models.
* [sperrorest](https://cran.r-project.org/web/packages/sperrorest/index.html) - Implements spatial error estimation and permutation-based variable importance measures for predictive models using spatial cross-validation and spatial block bootstrap.
* [spind](https://cran.r-project.org/web/packages/spind/index.html) - Functions for spatial methods based on generalized estimating equations (GEE) and wavelet-revised methods (WRM), functions for scaling by wavelet multiresolution regression (WMRR), conducting multi-model inference, and stepwise model selection.
* [splancs](https://cran.r-project.org/web/packages/splancs/index.html) - Spatial and Space-Time Point Pattern Analysis.
* [splm](https://cran.r-project.org/web/packages/splm/index.html) - ML and GM estimation and diagnostic testing of econometric models for spatial panel data.
* [spmoran](https://cran.r-project.org/web/packages/spmoran/index.html) - Functions for estimating fixed and random effects eigenvector spatial filtering models.
* [spselect](https://cran.r-project.org/web/packages/spselect/index.html) - Fits spatial scale (SS) forward stepwise regression, SS incremental forward stagewise regression, SS least angle regression (LARS), and SS lasso models.
* [spsurvey](https://cran.r-project.org/web/packages/spsurvey/index.html) - Provides a range of sampling functions.
* [spTimer](https://cran.r-project.org/web/packages/spTimer/index.html) - Fits, spatially predicts and temporally forecasts large amounts of space-time data.
* [SSN](https://cran.r-project.org/web/packages/SSN/index.html) - Spatial statistical modeling and prediction for data on stream networks, including models based on in-stream distance.
* [starma](https://cran.r-project.org/web/packages/starma/index.html) - Statistical functions to identify, estimate and diagnose a Space-Time AutoRegressive Moving Average (STARMA) model.
* [taRifx](https://cran.r-project.org/web/packages/taRifx/index.html) - A collection of various utility and convenience functions.
* [tgp](https://cran.r-project.org/web/packages/tgp/index.html) - Bayesian nonstationary, semiparametric nonlinear regression and design by treed Gaussian processes (GPs) with jumps to the limiting linear model (LLM).
* [trip](https://cran.r-project.org/web/packages/trip/index.html) - Extends sp classes to permit the accessing and manipulating of spatial data for animal tracking.
* [tripack](https://cran.r-project.org/web/packages/tripack/index.html) - A constrained two-dimensional Delaunay triangulation package providing both triangulation and generation of voronoi mosaics of irregular spaced data.
* [tripEstimation](https://cran.r-project.org/web/packages/tripEstimation/index.html) - Data handling and estimation functions for animal movement estimation from archival or satellite tags.
* [vec2dtransf](https://cran.r-project.org/web/packages/vec2dtransf/index.html) - Package for applying affine and similarity transformations on vector spatial data (sp objects).
* [vegan](https://cran.r-project.org/web/packages/vegan/index.html) - Ordination methods, diversity analysis and other functions for community and vegetation ecologists.
* [Watersheds](https://cran.r-project.org/web/packages/Watersheds/index.html) - Methods for watersheds aggregation and spatial drainage network analysis.

## Ruby

* [Geokit](https://github.com/geokit/geokit) ⭐ 1,628 | 🐛 21 | 🌐 Ruby | 📅 2024-07-29 - A Ruby gem & Rails plugin for easier map-based applications.
* [Rgeo](https://github.com/rgeo/rgeo) ⭐ 1,060 | 🐛 37 | 🌐 Ruby | 📅 2026-04-28 - RGeo is a geospatial data library for Ruby. It provides an implementation of the Open Geospatial Consortium's Simple Features Specification
* [PostGIS ActiveRecord Adapter](https://github.com/rgeo/activerecord-postgis-adapter) ⭐ 936 | 🐛 15 | 🌐 Ruby | 📅 2026-04-16 - ActiveRecord adapter for PostGIS.
* [Rgeo GeoJSON](https://github.com/rgeo/rgeo-geojson) ⭐ 205 | 🐛 13 | 🌐 Ruby | 📅 2024-10-10 - RGeo component for reading and writing GeoJSON.
* [ruby\_postal](https://github.com/openvenues/ruby_postal) ⭐ 146 | 🐛 6 | 🌐 C | 📅 2025-01-30 - Ruby bindings to libpostal for fast international address parsing/normalization.
* [Rgeo Shapefile](https://github.com/rgeo/rgeo-shapefile) ⭐ 98 | 🐛 3 | 🌐 Ruby | 📅 2024-10-10 - Optional module for RGeo for reading geospatial data from ESRI shapefiles.
* [Mongoid Geospatial](https://github.com/nofxx/mongoid-geospatial) ⭐ 80 | 🐛 12 | 🌐 Ruby | 📅 2025-08-09 - A Mongoid Extension that simplifies the use of MongoDB spatial features.
* [ffi-geos](https://github.com/dark-panda/ffi-geos) ⭐ 59 | 🐛 3 | 🌐 Ruby | 📅 2024-08-02 - Low-level ruby bindings to GEOS library.
* [Agroclimatology](https://github.com/beaorn/agroclimatology) ⭐ 19 | 🐛 1 | 🌐 Ruby | 📅 2017-08-30 - Ruby client for interacting with the NASA (POWER) Agroclimatology Web Resource.
* [Evapotranspiration](https://github.com/beaorn/evapotranspiration) ⭐ 14 | 🐛 0 | 🌐 Ruby | 📅 2017-08-30 - Ruby library for calculating reference crop evapotranspiration (ETo).
* [SpatiaLite ActiveRecord Adapter](https://github.com/rgeo/activerecord-spatialite-adapter) ⚠️ Archived - ActiveRecord adapter for Spatialite.
* [Ruby Geocoder](http://www.rubygeocoder.com/) - Integration with geocoding services.

## Rust

* [Arnis](https://github.com/louis-e/arnis) ⭐ 17,577 | 🐛 136 | 🌐 Rust | 📅 2026-08-23 - Generate any location from the real world in Minecraft Java Edition with a high level of detail.
* [A/B Street](https://github.com/dabreegster/abstreet) ⭐ 8,155 | 🐛 234 | 🌐 Rust | 📅 2025-09-10 - A traffic simulation game exploring how small changes to roads affect cyclists, transit users, pedestrians, and drivers.
* [Martin](https://github.com/urbica/martin) ⭐ 3,845 | 🐛 77 | 🌐 Rust | 📅 2026-08-23 - Martin is a PostGIS vector tiles server suitable for large databases. Martin is written in Rust using Actix web framework.
* [geo](https://github.com/georust/rust-geo) ⭐ 1,916 | 🐛 120 | 🌐 Rust | 📅 2026-08-22 - Geospatial primitives and algorithms for Rust.
* [rustworkx](https://github.com/Qiskit/rustworkx) ⭐ 1,745 | 🐛 135 | 🌐 Rust | 📅 2026-08-17 - A high-performance, general-purpose graph library for Python, written in Rust.
* [maplibre-rs](https://github.com/maplibre/maplibre-rs) ⭐ 1,568 | 🐛 68 | 🌐 Rust | 📅 2026-08-21 - About Native Maps for Web, Mobile and Desktop.
* [WhiteboxTools](https://github.com/jblindsay/whitebox-tools) ⭐ 1,192 | 🐛 175 | 🌐 Rust | 📅 2026-05-26 - An advanced geospatial data analysis platform.
* [GeoPolars](https://github.com/geopolars/geopolars) ⭐ 909 | 🐛 27 | 🌐 Python | 📅 2025-12-10 - Geospatial extensions for Polars.
* [FlatGeobuf](https://github.com/flatgeobuf/flatgeobuf) ⭐ 818 | 🐛 35 | 🌐 Rust | 📅 2026-08-21 - A performant binary encoding for geographic data based on flatbuffers.
* [Galileo](https://github.com/Maximkaaa/galileo) ⭐ 636 | 🐛 43 | 🌐 Rust | 📅 2026-07-30 - General purpose cross-platform geo-rendering library.
* [Gauzilla](https://github.com/BladeTransformerLLC/gauzilla) ⭐ 635 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-23 - 3D Gaussian Splatting renderer for WebAssembly with lock-free multithreading.
* [Skeleton Tracing](https://github.com/LingDong-/skeleton-tracing/tree/master/rs) ⭐ 605 | 🐛 17 | 🌐 C | 📅 2022-07-21 - A new algorithm for retrieving topological skeleton as a set of polylines from binary images.
* [t-rex](https://github.com/t-rex-tileserver/t-rex) ⭐ 577 | 🐛 54 | 🌐 Rust | 📅 2024-09-24 - Vector tile server specialized on publishing MVT tiles from your own data.
* [rstar](https://github.com/georust/rstar) ⭐ 556 | 🐛 42 | 🌐 Rust | 📅 2026-08-23 - R\*-tree library for the rust ecosystem.
* [h3o](https://github.com/HydroniumLabs/h3o) ⭐ 540 | 🐛 0 | 🌐 Rust | 📅 2026-06-08 - Rust implementation of the H3 geospatial indexing system.
* [sguaba](https://github.com/helsing-ai/sguaba) ⭐ 508 | 🐛 2 | 🌐 Rust | 📅 2026-07-08 - Types for points and vectors in coordinate spaces and transformations based on rigid body transforms.
* [SedonaDB](https://github.com/apache/sedona-db) ⭐ 495 | 🐛 133 | 🌐 Rust | 📅 2026-08-23 - Single-node analytical database engine with geospatial as the first-class citizen.
* [geozero](https://github.com/georust/geozero) ⭐ 469 | 🐛 45 | 🌐 Rust | 📅 2026-08-17 - Zero-Copy reading and writing of geospatial data.
* [gdal](https://github.com/georust/rust-gdal) ⭐ 448 | 🐛 62 | 🌐 Rust | 📅 2026-07-06 - Rust bindings for GDAL.
* [geoarrow-rs](https://github.com/kylebarron/geoarrow-rs) ⭐ 422 | 🐛 84 | 🌐 Rust | 📅 2026-08-11 - GeoArrow in Rust and WebAssembly with vectorized geometry operations.
* [Ferrostar](https://github.com/stadiamaps/ferrostar) ⭐ 408 | 🐛 152 | 🌐 Kotlin | 📅 2026-08-18 - A FOSS navigation SDK built from the ground up for the future.
* [Airmail](https://github.com/ellenhp/airmail) ⭐ 381 | 🐛 17 | 🌐 Rust | 📅 2025-08-08 - Lightweight geocoder in pure Rust.
* [hdf5-rust](https://github.com/aldanor/hdf5-rust) ⭐ 346 | 🐛 57 | 🌐 Rust | 📅 2024-08-08 - Thread-safe Rust bindings and high-level wrappers for the HDF5 library API.
* [geojson](https://github.com/georust/rust-geojson) ⭐ 344 | 🐛 22 | 🌐 Rust | 📅 2026-04-29 - Library for serializing the GeoJSON vector GIS file format.
* [spade](https://github.com/Stoeoef/spade) ⭐ 336 | 🐛 14 | 🌐 Rust | 📅 2026-03-24 - Delaunay Triangulations for the Rust ecosystem.
* [rgis](https://github.com/frewsxcv/rgis) ⭐ 331 | 🐛 32 | 🌐 Rust | 📅 2026-06-13 - Performant, cross-platform (web, desktop) GIS app written in Rust
* [Fast Paths](https://github.com/easbar/fast_paths) ⭐ 295 | 🐛 7 | 🌐 Rust | 📅 2024-05-07 - Fast shortest path calculations for Rust.
* [kdtree](https://github.com/mrhooray/kdtree-rs) ⭐ 283 | 🐛 2 | 🌐 Rust | 📅 2026-07-23 - K-dimensional tree in Rust for fast geospatial indexing and nearest neighbors lookup
* [kdtree-rs](https://github.com/mrhooray/kdtree-rs) ⭐ 283 | 🐛 2 | 🌐 Rust | 📅 2026-07-23 - K-dimensional tree in Rust for fast geospatial indexing and nearest neighbors lookup.
* [zarrs](https://github.com/LDeakin/zarrs) ⭐ 267 | 🐛 23 | 🌐 Rust | 📅 2026-08-23 - A rust library for the Zarr V3 storage format for multidimensional arrays and metadata.
* [Hecate](https://github.com/mapbox/Hecate) ⚠️ Archived - Fast Geospatial Feature Storage API.
* [delaunator-rs](https://github.com/mourner/delaunator-rs) ⭐ 252 | 🐛 5 | 🌐 Rust | 📅 2026-05-12 - A very fast static 2D Delaunay triangulation library for Rust.
* [Cavalier Contours](https://github.com/jbuckmccready/cavalier_contours) ⭐ 230 | 🐛 8 | 🌐 Rust | 📅 2026-08-20 - 2D polyline/shape library for offsetting, combining, etc.
* [iOverlay](https://github.com/iShape-Rust/iOverlay) ⭐ 204 | 🐛 2 | 🌐 Rust | 📅 2026-08-16 - Boolean Operations for 2D Polygons: Supports intersection, union, difference, xor, and self-intersections for all polygon varieties.
* [geo-index](https://github.com/kylebarron/geo-index) ⭐ 198 | 🐛 31 | 🌐 Rust | 📅 2026-04-17 - Fast, immutable, ABI-stable spatial indexes.
* [Polars ST](https://github.com/Oreilles/polars-st) ⭐ 194 | 🐛 9 | 🌐 Python | 📅 2026-08-06 - Spatial extension for Polars DataFrames.
* [proj](https://github.com/georust/rust-proj) ⭐ 184 | 🐛 39 | 🌐 Rust | 📅 2026-06-17 - Rust bindings for Proj.
* [rgeometry](https://github.com/rgeometry/rgeometry) ⭐ 180 | 🐛 12 | 🌐 Rust | 📅 2026-08-17 - Computational Geometry library written in Rust.
* [image-tiff](https://github.com/image-rs/image-tiff) ⭐ 167 | 🐛 30 | 🌐 Rust | 📅 2026-08-10 - TIFF decoding and encoding library in pure Rust.
* [BBOX services](https://github.com/bbox-services/bbox) ⭐ 166 | 🐛 21 | 🌐 Rust | 📅 2025-10-11 - Composable spatial services.
* [osmpbf](https://github.com/b-r-u/osmpbf) ⭐ 163 | 🐛 18 | 🌐 Rust | 📅 2026-08-16 - Library for reading the OpenStreetMap PBF file format.
* [osm-renderer](https://github.com/dfyz/osm-renderer) ⭐ 160 | 🐛 0 | 🌐 Rust | 📅 2025-02-10 - OpenStreetMap raster tile renderer.
* [iTriangle](https://github.com/iShape-Rust/iTriangle) ⭐ 157 | 🐛 4 | 🌐 Rust | 📅 2026-08-23 - A fast, stable, and robust 2d triangulation library.
* [geos](https://github.com/georust/geos) ⭐ 147 | 🐛 16 | 🌐 Rust | 📅 2026-03-03 - Rust bindings for GEOS C API.
* [Solari](https://github.com/ellenhp/solari) ⭐ 147 | 🐛 0 | 🌐 Rust | 📅 2025-06-24 - Multimodal routing in Rust.
* [stac-rs](https://github.com/gadomski/stac-rs) ⭐ 144 | 🐛 30 | 🌐 Rust | 📅 2026-08-18 - Rust implementation of the SpatioTemporal Asset Catalog (STAC) specification.
* [osmpbfreader-rs](https://github.com/TeXitoi/osmpbfreader-rs) ⭐ 133 | 🐛 7 | 🌐 Rust | 📅 2026-04-07 - Read OpenStreetMap PBF files.
* [GeoTIFF](https://github.com/georust/geotiff) ⭐ 132 | 🐛 10 | 🌐 Rust | 📅 2026-07-31 - Work with GeoTIFF raster files.
* [RINEX](https://github.com/georust/rinex) ⭐ 125 | 🐛 27 | 🌐 Rust | 📅 2026-07-21 - RINEX analysis & and processing.
* [gpx](https://github.com/georust/rust-gpx) ⭐ 122 | 🐛 5 | 🌐 Rust | 📅 2025-08-19 - Rust read/write support for GPS Exchange Format (GPX).
* [geohash](https://github.com/georust/rust-geohash) ⭐ 121 | 🐛 5 | 🌐 Rust | 📅 2026-08-19 - Geohash for Rust.
* [tzf-rs](https://github.com/ringsaturn/tzf-rs) ⭐ 108 | 🐛 0 | 🌐 Rust | 📅 2026-08-02 - Get timezone via longitude\&latitude in Rust in a fast way
* [PMTiles (for Rust)](https://github.com/stadiamaps/pmtiles-rs) ⭐ 107 | 🐛 10 | 🌐 Rust | 📅 2026-08-15 - Rust implementation of PMTiles
* [Robust](https://github.com/georust/robust) ⭐ 107 | 🐛 8 | 🌐 Rust | 📅 2025-05-10 - Robust primitives for computational geometry.
* [netcdf](https://github.com/georust/netcdf) ⭐ 105 | 🐛 4 | 🌐 Rust | 📅 2026-08-12 - Medium-level netCDF bindings for Rust, allowing easy reading and writing of array-like structures to a file.
* [rust-geo-booleanop](https://github.com/21re/rust-geo-booleanop) ⭐ 105 | 🐛 14 | 🌐 Rust | 📅 2023-10-16 - Rust implementation of the Martinez-Rueda Polygon Clipping Algorithm.
* [las-rs](https://github.com/gadomski/las-rs) ⭐ 103 | 🐛 6 | 🌐 Rust | 📅 2026-08-11 - Read and write ASPRS las files.
* [plateau-gis-converter](https://github.com/MIERUNE/plateau-gis-converter) ⭐ 102 | 🐛 54 | 🌐 Rust | 📅 2026-08-17 - A GUI and CLI tool for converting PLATEAU's 3D city models (CityGML) of Japan into various geospatial formats, including 3D Tiles, MVT, and GeoPackage.
* [pasture](https://github.com/Mortano/pasture) ⭐ 93 | 🐛 4 | 🌐 Rust | 📅 2025-09-30 - A Rust library for working with point cloud data.
* [Karttapullautin](https://github.com/karttapullautin/karttapullautin) ⭐ 88 | 🐛 8 | 🌐 Rust | 📅 2026-08-22 - A fast and accurate map generator from classified LiDAR data.
* [density mesh](https://github.com/PsichiX/density-mesh) ⭐ 84 | 🐛 6 | 🌐 Rust | 📅 2023-09-15 - Image density/height map to mesh generator.
* [geocoding](https://github.com/georust/rust-geocoding) ⭐ 82 | 🐛 8 | 🌐 Rust | 📅 2026-05-16 - Geocoding library for Rust.
* [Proj4rs](https://github.com/3liz/proj4rs) ⭐ 78 | 🐛 2 | 🌐 Rust | 📅 2026-07-16 - Rust adaptation of Proj4
* [gtfs-structures](https://github.com/rust-transit/gtfs-structure) ⭐ 77 | 🐛 22 | 🌐 Rust | 📅 2026-08-20 - Read GTFS files into structs, with smart references.
* [Rust Geodesy](https://github.com/busstoptaktik/geodesy/) ⭐ 77 | 🐛 10 | 🌐 Rust | 📅 2026-03-03 - A geodesy library written in Rust.
* [shapefile](https://github.com/tmontaigu/shapefile-rs) ⭐ 76 | 🐛 3 | 🌐 Rust | 📅 2026-07-24 - Rust read/write support for shapefiles.
* [shapefile-rs](https://github.com/tmontaigu/shapefile-rs) ⭐ 76 | 🐛 3 | 🌐 Rust | 📅 2026-07-24 - Rust library to read & write shapefiles.
* [transit\_model](https://github.com/hove-io/transit_model) ⭐ 72 | 🐛 14 | 🌐 Rust | 📅 2026-08-18 - Manage, convert and enrich transit data.
* [Bevy Point Cloud](https://github.com/rlamarche/bevy_pointcloud) ⭐ 67 | 🐛 0 | 🌐 Rust | 📅 2026-08-21 - A Bevy plugin to render point clouds.
* [Polylabel-rs](https://github.com/urschrei/polylabel-rs) ⭐ 61 | 🐛 2 | 🌐 Rust | 📅 2026-08-21 - A Rust implementation of the Polylabel algorithm, with FFI.
* [earcut-rs](https://github.com/ciscorn/earcut-rs) ⭐ 57 | 🐛 3 | 🌐 Rust | 📅 2026-07-26 - Port of the Earcut polygon triangulation library with performance in mind.
* [wkt](https://github.com/georust/rust-wkt) ⭐ 56 | 🐛 19 | 🌐 Rust | 📅 2026-08-19 - Rust read/write support for well-known text (WKT).
* [geographiclib-rs](https://github.com/georust/geographiclib-rs) ⭐ 51 | 🐛 12 | 🌐 Rust | 📅 2026-02-19 - A subset of geographiclib implemented in Rust.
* [Geo Engine](https://github.com/geo-engine/geoengine) ⭐ 49 | 🐛 53 | 🌐 Jupyter Notebook | 📅 2026-08-22 - Cloud-ready geospatial data processing platform with workflows, raster *and* vector support and OGC-compliant interfaces.
* [Sailor](https://github.com/Yatekii/sailor) ⭐ 49 | 🐛 1 | 🌐 Rust | 📅 2026-08-09 - A sailing navigation application.
* [earcutr](https://github.com/frewsxcv/earcutr) ⚠️ Archived - Port of MapBox's earcut triangulation code to Rust language.
* [rusterize](https://github.com/ttrotto/rusterize) ⭐ 48 | 🐛 0 | 🌐 Rust | 📅 2026-07-30 - High performance rasterization tool for python built in Rust.
* [geo-rasterize](https://github.com/msalib/geo-rasterize/) ⭐ 46 | 🐛 10 | 🌐 Rust | 📅 2023-08-29 - A pure-rust 2D rasterizer for geospatial applications.
* [MVT Server](https://github.com/mvt-proj/mvt-rs) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-08-23 - Simple and high-speed vector tile server with a built-in web-based admin interface.
* [geom3d](https://github.com/J-F-Liu/geom3d) ⭐ 45 | 🐛 1 | 🌐 Rust | 📅 2024-01-02 - Data structures and algorithms for 3D geometric modeling.
* [linesweeper](https://github.com/jneem/linesweeper) ⚠️ Archived - Two-dimensional geometric primitives like boolean operations on sets bounded by Bézier paths.
* [rust\_road\_router](https://github.com/kit-algo/rust_road_router) ⭐ 43 | 🐛 2 | 🌐 Rust | 📅 2026-04-22 - Rust routing framework and toolkit.
* [OGC API](https://github.com/georust/ogcapi) ⭐ 42 | 🐛 4 | 🌐 Rust | 📅 2026-08-22 - OGC API building blocks.
* [osmflat](https://github.com/boxdot/osmflat-rs) ⭐ 42 | 🐛 7 | 🌐 Rust | 📅 2024-09-02 - OpenStreetMap flatdata format and compiler.
* [startin](https://github.com/hugoledoux/startin) ⭐ 41 | 🐛 2 | 🌐 Rust | 📅 2025-07-28 - A Delaunay triangulator for processing TINs.
* [FastGtfs](https://github.com/nicomazz/fastgtfs) ⭐ 40 | 🐛 13 | 🌐 Rust | 📅 2025-03-06 - GTFS parsing, navigation, time table creation, and real-time network simulation.
* [osm-lump-ways](https://github.com/amandasaurus/osm-lump-ways) ⭐ 40 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - Group OSM ways based on topology & shared tags
* [coord\_transforms](https://github.com/DaveKram/coord_transforms) ⚠️ Archived - Rust crate for performing coordinate transforms.
* [kml](https://github.com/georust/kml) ⭐ 33 | 🐛 5 | 🌐 Rust | 📅 2026-07-08 - Rust support for reading and writing KML with a focus on conversion to geo-types primitives.
* [polyline](https://github.com/georust/rust-polyline) ⭐ 33 | 🐛 7 | 🌐 Rust | 📅 2025-07-26 - Google Encoded Polyline encoding & decoding in Rust.
* [osm-pbf-parquet](https://github.com/OvertureMaps/osm-pbf-parquet) ⭐ 32 | 🐛 1 | 🌐 Rust | 📅 2026-08-20 - Transcode OSM PBF file to parquet files.
* [georaster](https://github.com/pka/georaster) ⭐ 30 | 🐛 3 | 🌐 Rust | 📅 2025-08-09 - Rust library for accessing geospatial raster images (GeoTIFF).
* [utiles](https://github.com/jessekrubin/utiles) ⭐ 29 | 🐛 3 | 🌐 Rust | 📅 2026-08-23 - utils & tiles w/ (rs & pyo3).
* [RouteE Compass](https://github.com/NREL/routee-compass) ⭐ 28 | 🐛 87 | 🌐 Rust | 📅 2026-08-22 - An energy-aware vehicle routing engine.
* [geojson-vt-rs](https://github.com/maxammann/geojson-vt-rs) ⭐ 27 | 🐛 4 | 🌐 Rust | 📅 2025-09-12 - Crate for slicing GeoJSON into vector tiles on the fly.
* [The Roaring Landmask](https://github.com/gauteh/roaring-landmask) ⭐ 27 | 🐛 8 | 🌐 Rust | 📅 2026-08-10 - A fast and memory-limited landmask based on GSHHG for determing whether a point on Earth is on land or in the ocean.
* [anime](https://github.com/JosiahParry/anime) ⭐ 25 | 🐛 14 | 🌐 Rust | 📅 2026-06-16 - Approximate Network Matching, Integration, and Enrichment.
* [copc-rs](https://github.com/pka/copc-rs) ⭐ 25 | 🐛 1 | 🌐 Rust | 📅 2026-07-19 - Cloud Optimized Point Cloud (COPC) reader and writer.
* [PlanetVectorTile](https://github.com/planet-vector-tile/planet-vector-tile) ⭐ 24 | 🐛 2 | 🌐 Rust | 📅 2023-02-28 - A map engine enabling you to have the entire map of the OSM planet on your own computer.
* [cql2-rs](https://github.com/developmentseed/cql2-rs) ⭐ 23 | 🐛 11 | 🌐 Rust | 📅 2026-08-17 - Library for parsing the OGC CQL2 filter language.
* [osm\_ch](https://github.com/Stunkymonkey/osm_ch) ⭐ 22 | 🐛 1 | 🌐 Rust | 📅 2026-04-22 - OSM-Contraction-Hierarchies.
* [flat-projection](https://github.com/Turbo87/flat-projection-rs) ⭐ 20 | 🐛 9 | 🌐 Rust | 📅 2026-08-20 - Fast geodesic distance approximations via flat surface projection.
* [osmx](https://github.com/jake-low/osmx-rs) ⭐ 20 | 🐛 2 | 🌐 Rust | 📅 2026-05-12 - Rust port of OSMExpress, a fast database file format for OpenStreetMap.
* [country-boundaries](https://github.com/westnordost/country-boundaries-rust) ⭐ 19 | 🐛 0 | 🌐 Rust | 📅 2026-03-09 - A fast offline reverse geocoder: Find the area in which a geo position is located.
* [N5](https://github.com/aschampion/rust-n5) ⭐ 17 | 🐛 20 | 🌐 Rust | 📅 2022-12-06 - N5 "Not HDF5" tensor file system format.
* [osm](https://github.com/georust/rust-osm) ⭐ 17 | 🐛 4 | 🌐 Rust | 📅 2019-05-24 - OSM XML serialization and other OpenStreetMap utilities.
* [Transit](https://github.com/georust/transitfeed) ⭐ 17 | 🐛 4 | 🌐 Rust | 📅 2021-11-14 - Work with GTFS files.
* [poly2tri-rs](https://github.com/shuoli84/poly2tri-rs) ⭐ 16 | 🐛 4 | 🌐 Rust | 📅 2023-03-29 - Calculate CDT (Constrained Delaunay Triangulation) on a polygon.
* [tilejson](https://github.com/georust/tilejson) ⭐ 16 | 🐛 1 | 🌐 Rust | 📅 2026-08-17 - tilejson is a crate for serializing/deserializing the TileJSON format.
* [jord](https://github.com/ofmooseandmen/jord-rs) ⭐ 15 | 🐛 1 | 🌐 Rust | 📅 2026-08-23 - Geographical Position Calculations (spherical + ellipsoidal models and local frames).
* [maplibre-legend](https://github.com/mvt-proj/maplibre-legend) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-08-15 - Maplibre legend generator crate.
* [offset-polygon](https://github.com/anlumo/offset_polygon) ⭐ 14 | 🐛 1 | 🌐 Rust | 📅 2024-06-06 - A Rust crate for offsetting (shrinking/expanding) polygons.
* [postal](https://github.com/kodemartin/rustpostal) ⭐ 14 | 🐛 4 | 🌐 Rust | 📅 2022-03-28 - Rust bindings to libpostal.
* [rusqlite-gpkg](https://github.com/yutannihilation/rusqlite-gpkg) ⭐ 14 | 🐛 2 | 🌐 Rust | 📅 2026-07-23 - GeoPackage reader/writer built on top of rusqlite.
* [earclip](https://github.com/Open-S2/earclip) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-02-10 - Triangle mesh designed to be fast, efficient, and sphere capable.
* [rasters.rs](https://github.com/AspecScire/rasters.rs) ⭐ 13 | 🐛 2 | 🌐 Rust | 📅 2024-06-23 - Raster processing library and tools written in rust.
* [kdbush](https://github.com/pka/rust-kdbush) ⭐ 12 | 🐛 2 | 🌐 Rust | 📅 2022-09-27 - A Rust port of kdbush, a fast static spatial index for 2D points.
* [Vector Tile Builder](https://github.com/ShogoHirasawa/web-vector-tile-maker) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-03-15 - Web application for generating vector tiles in the browser
* [CGAR](https://github.com/aseverino/cgar) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2025-11-27 - Computational Geometry Algorithms for Rust.
* [topojson](https://github.com/georust/rust-topojson) ⭐ 11 | 🐛 2 | 🌐 Rust | 📅 2023-11-27 - TopoJSON bindings and utilities for Rust.
* [zonebuilder](https://github.com/zonebuilders/zonebuilder-rust) ⭐ 11 | 🐛 8 | 🌐 Rust | 📅 2021-12-28 - Build zones for large geographic regions.
* [boostvoronoi](https://github.com/eadf/boostvoronoi.rs) ⭐ 10 | 🐛 3 | 🌐 Rust | 📅 2023-12-08 - Segmented Voronoi for Rust.
* [cheap-ruler-rs](https://github.com/vipera/cheap-ruler-rs) ⭐ 10 | 🐛 2 | 🌐 Rust | 📅 2025-02-06 - Collection of very fast approximations to common geodesic measurements.
* [Quadbin](https://github.com/atsyplenkov/qbin) ⭐ 10 | 🐛 2 | 🌐 Rust | 📅 2026-03-03 - Hierarchical geospatial index tiling, similar to Quadkey.
* [pgstac-rs](https://github.com/gadomski/pgstac-rs) ⚠️ Archived - Rust interface for [pgstac](https://github.com/stac-utils/pgstac) ⭐ 221 | 🐛 68 | 🌐 PLpgSQL | 📅 2026-08-10.
* [spatial-join](https://github.com/msalib/spatial-join) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2020-07-12 - Perform streaming geospatial-joins on geographic data.
* [auto-sea-way](https://github.com/auto-sea-way/asw) ⭐ 8 | 🐛 7 | 🌐 Rust | 📅 2026-08-03 - Open source maritime auto-routing engine that builds a global water-surface routing graph from OSM land polygons using an adaptive H3 hexagonal grid cascade.
* [osm\_boundaries\_utils\_rs](https://github.com/Qwant/osm_boundaries_utils_rs) ⚠️ Archived - Read OpenStretMap relations with type=boundary as valid MultiPolygon.
* [static-bushes](https://github.com/apendleton/static-bushes) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2025-07-29 - Port of the Flatbush and KDBush JS libraries to Rust.
* [etiles](https://github.com/tum-gis/etiles) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-05-21 - A Rust library for processing 3D Tiles data.
* [gpkg-rs](https://github.com/cjriley9/gpkg-rs) ⭐ 7 | 🐛 1 | 🌐 Rust | 📅 2022-06-14 - A Rust crate for reading and writing GeoPackages.
* [Proj4wkt](https://github.com/3liz/proj4wkt-rs) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2025-09-19 - Parse WKT to Proj strings
* [routrs](https://github.com/routrs/routrs) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2024-10-19 - Geograph-based shortest distance calculation for Rust.
* [World file](https://github.com/georust/world-file) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2018-08-11 - Work with World-files.
* [Louvre](https://github.com/acheul/louvre) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-08-03 - Computational Geometry Library with Rust
* [polygon-offsetting](https://github.com/Akirami/polygon-offsetting) ⭐ 5 | 🐛 1 | 🌐 Rust | 📅 2024-06-15 - Offset a polygon (only margin).
* [sif-rtree](https://github.com/adamreichold/sif-rtree) ⚠️ Archived and [sif-kdtree](https://github.com/adamreichold/sif-kdtree) ⚠️ Archived - R and K-D trees which can be memory-mapped directly from disk.
* [geometry-rs](https://github.com/ringsaturn/geometry-rs) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-02 - Partial port of tidwall/geometry (efficient 2D geometry library for Go).
* [intersect2d](https://github.com/eadf/intersect2d.rs) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2023-12-28 - Line intersection sweep-line algorithm.
* [geo-quadkey-rs](https://github.com/masaishi/geo-quadkey-rs) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2023-08-29 - Rust library for encoding and decoding geographical coordinates to and from QuadKeys.
* [geocentric-rs](https://github.com/ciscorn/geocentric-rs) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-02-04 - Conversion between geodetic (geographic) and geocentric (cartesian) coordinates.
* [geoserde](https://github.com/p4ken/geoserde) ⭐ 3 | 🐛 1 | 🌐 Rust | 📅 2026-05-31 - Adapter between geographic feature and GIS files.
* [pbfhogg](https://github.com/folknor/pbfhogg) ⭐ 3 | 🐛 2 | 🌐 Rust | 📅 2026-08-21 - Fast library and CLI to read, write, and transform OSM PBF files; parallel and pipelined decoding, planet-scale on modest hardware.
* [s2-pmtiles](https://github.com/Open-S2/s2-pmtiles) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-12-22 - Read/Write PMTiles V3.0 as well as S2PMTiles V1.0
* [sst](https://github.com/hugoledoux/sst) ⭐ 3 | 🐛 1 | 🌐 Rust | 📅 2025-01-06 - streaming startin.
* [Pbfextractor](https://github.com/Lesstat/pbfextractor) ⭐ 2 | 🐛 1 | 🌐 Rust | 📅 2026-04-22 - Create graph files out of OSM and SRTM data
* [rout3serv](https://github.com/nmandery/rout3serv) ⭐ 2 | 🐛 2 | 🌐 Rust | 📅 2024-02-23 - H3-grid based Routing server with GRPC-API and dataframe integration.
* [Routers](https://github.com/routers-org/routers) ⭐ 2 | 🐛 14 | 🌐 Rust | 📅 2026-08-13 - Set of routing tools designed for system-agnostic maps.
* [S2](https://github.com/danhhz/s2) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2017-08-10 - S2 spherical geometry library in Rust.
* [geocart](https://github.com/HectorMRC/geocart) ⭐ 0 | 🐛 1 | 🌐 Rust | 📅 2025-11-24 - A bridge between geographic and cartesian coordinates.
* [A5](https://a5geo.org/docs/quickstart/rust) - Rust library for the A5 geospatial indexing system, a new alternative to S2 and H3 using irregular, equilateral pentagons.
* [cosmo](https://codeberg.org/mvexel/cosmo) - Filter & transform OSM PBF data to geoparquet or geojson.
* [Discord](https://discord.gg/Fp2aape) - GeoRust Discord channel
* [latlong\_bng](https://docs.rs/lonlat_bng/latest/lonlat_bng/index.html) - Provides functions that convert decimal (WGS84 / ETRS89) longitude and latitude coordinates into British National Grid coordinates, and vice versa. This library makes use of the OSTN02 transformations.
* [map-engine](https://gitlab.com/spadarian/map-engine/) - A rust library to work with tiled geospatial (raster) data.
* [Miniproj](https://git.geomar.de/flemming-staebler/miniproj) - Geographic transformations between different coordinate systems defined by the European Petroleum Survey Group.
* [osm-transit-extractor](https://github.com/CanalTP/osm-transit-extractor) - Extract OSM public transport data and write to CSV files.
* [tile-grid](https://crates.io/crates/tile-grid) - Library for map tile grid calculations.

## Scala

* [GeoTrellis](https://github.com/locationtech/geotrellis) ⭐ 1,372 | 🐛 250 | 🌐 Scala | 📅 2026-08-11 - GeoTrellis is a Scala library and framework that uses Spark to work with raster data.
* [RTree2D](https://github.com/plokhotnyuk/rtree2d) ⭐ 145 | 🐛 11 | 🌐 Scala | 📅 2026-08-21 - RTree2D is a 2D immutable R-tree with STR (Sort-Tile-Recursive) packing for ultra-fast nearest and intersection queries.
* [Franklin](https://github.com/azavea/franklin) ⭐ 87 | 🐛 109 | 🌐 Scala | 📅 2025-10-31 - A STAC/OGC API Features Web Service.
* [mapnik2geotools](https://github.com/dwins/mapnik2geotools) ⭐ 64 | 🐛 16 | 🌐 Scala | 📅 2016-09-01 - Using the Scala XML API to translate from Mapnik XML to GeoTools' SLD dialect.
* [geoscript.scala](https://github.com/dwins/geoscript.scala) ⭐ 47 | 🐛 17 | 🌐 Scala | 📅 2016-04-13 - Scala implementation of the GeoScript API.
* [fulgurite](https://github.com/SatelliteApplicationsCatapult/fulgurite) ⭐ 19 | 🐛 13 | 🌐 Scala | 📅 2019-08-14 - Fulgurite is a way to use Apache Spark to process GeoTIFF images in a distributed way.
* [Stac4s](https://github.com/azavea/stac4s) ⭐ 17 | 🐛 28 | 🌐 Scala | 📅 2026-07-19 - a scala library with primitives to build applications using the SpatioTemporal Asset Catalogs specification.
* [osm4scala](https://simplexspatial.github.io/osm4scala/) - High perfromance Scala library and Spark Polyglot (Scala, Python, SQL, etc.) connector for OpenStreetMap Pbf files.

## Swift

* [GEOSwift](https://github.com/GEOSwift/GEOSwift) ⭐ 1,504 | 🐛 8 | 🌐 Swift | 📅 2025-11-09 - The Swift Geographic Engine.
* [Mapbox Navigation SDK for iOS](https://github.com/mapbox/mapbox-navigation-ios) ⭐ 917 | 🐛 214 | 🌐 Swift | 📅 2026-08-21 - Turn-by-turn navigation logic and UI in Swift or Objective-C on iOS.
* [turf-swift](https://github.com/mapbox/turf-swift) ⭐ 270 | 🐛 29 | 🌐 Swift | 📅 2026-06-29 - A Swift language port of Turf.js.
* [MapboxDirections.swift](https://github.com/mapbox/MapboxDirections.swift) ⭐ 206 | 🐛 33 | 🌐 Swift | 📅 2026-08-21 - Traffic-aware directions in Swift or Objective-C on iOS, macOS, tvOS, and watchOS.
* [Apple MapKit](https://developer.apple.com/documentation/mapkit) - Display map or satellite imagery directly from your app's interface, call out points of interest, and determine placemark information for map coordinates.

## Mobile Development

* [Organic Maps](https://github.com/organicmaps/organicmaps) ⭐ 15,182 | 🐛 3,466 | 🌐 C++ | 📅 2026-08-23 - Organic Maps is a better fork of MAPS.ME, an Android & iOS offline maps app for travelers, tourists, hikers, and cyclists based on top of crowd-sourced OpenStreetMap data and curated with love by MAPS.ME founders. No ads, no tracking, no data collection, no crapware.
* [MAPS.ME](https://github.com/mapsme/omim) ⭐ 4,602 | 🐛 997 | 🌐 C++ | 📅 2022-10-05 - MAPS.ME — Offline OpenStreetMap maps for iOS and Android.
* [flutter\_map](https://github.com/fleaflet/flutter_map) ⭐ 3,011 | 🐛 52 | 🌐 Dart | 📅 2026-08-03 - A Dart implementation of Leaflet for Flutter apps.
* [MapLibre GL Native](https://github.com/maplibre/maplibre-gl-native) ⭐ 2,160 | 🐛 569 | 🌐 C++ | 📅 2026-08-23 - The open-source alternative to Mapbox GL Native. SDKs for iOS, Android and other platforms
* [mapbox-navigation-android](https://github.com/mapbox/mapbox-navigation-android) ⭐ 651 | 🐛 518 | 🌐 Kotlin | 📅 2026-08-21 - Mapbox Navigation SDK for Android.
* [MapLibre Compose](https://github.com/maplibre/maplibre-compose) ⭐ 545 | 🐛 47 | 🌐 Kotlin | 📅 2026-08-23 - Add interactive vector tile maps to your Compose app
* [XaMaps](https://github.com/AlexPshul/XaMaps) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2018-10-19 - Xamarin + Azure Maps.
* [XFAzureMapTrials](https://github.com/Druffl3/XFAzureMapTrials) ⭐ 3 | 🐛 1 | 🌐 C# | 📅 2022-12-08 - Use Azure Maps REST APIs with Xamarin.Forms.
* [Apple MapKit](https://developer.apple.com/documentation/mapkit) - Display map or satellite imagery directly from your app's interface, call out points of interest, and determine placemark information for map coordinates.
* [Google Maps API for Android](https://developers.google.com/maps/android/) - Google maps for Android.
* [Google Maps API for iOS](https://developers.google.com/maps/ios/) - Google maps for iOS.
* [Mapbox Android SDK](https://www.mapbox.com/android-sdk/) - An open source toolset for building mapping applications for Android devices.
* [Mapbox iOS SDK](https://www.mapbox.com/ios-sdk/) - An open source toolset for building mapping applications for iPhone and iPad devices.
* [Nutiteq Maps SDK](https://github.com/nutiteq) - C++ maps library for iOS, Android, Windows Phone and Xamarin with bindings for Java, ObjectiveC and C#.
* [WhirlyGlobe/Maply](http://mousebird.github.io/WhirlyGlobe/) - Objective C code that is able to read and render vector tiles(and style with mapnik xml) on iOS devices.

## Geospatial Big Data

* [GeoMesa](https://github.com/locationtech/geomesa) ⭐ 1,494 | 🐛 199 | 🌐 Scala | 📅 2026-08-21 - GeoMesa is a suite of tools for working with big geo-spatial data in a distributed fashion.
* [GeoTrellis](https://github.com/locationtech/geotrellis) ⭐ 1,372 | 🐛 250 | 🌐 Scala | 📅 2026-08-11 - GeoTrellis is a geographic data processing engine for high performance applications.
* [GeoWave](https://github.com/locationtech/geowave) ⭐ 527 | 🐛 91 | 🌐 Java | 📅 2025-09-29 - GeoWave provides geospatial and temporal indexing on top of Accumulo and HBase.
* [geobeam](https://github.com/GoogleCloudPlatform/dataflow-geobeam) ⚠️ Archived - geobeam adds GIS capabilities to your Apache Beam pipelines and enables you to ingest and analyze massive amounts of geospatial data in parallel using Dataflow.
* [Apache Sedona](https://sedona.apache.org/latest-snapshot/) - Cluster computing system for processing large-scale spatial data
* [Google Earth Engine](https://earthengine.google.com/) - Is a cloud computing platform for processing satellite imagery and other Earth observation data.

## Visualization

* [Blender GIS](https://github.com/domlysz/BlenderGIS) ⭐ 9,311 | 🐛 321 | 🌐 Python | 📅 2025-12-20 - Blender addons to make the bridge between Blender and geographic data.
* [Folium](https://github.com/python-visualization/folium) ⭐ 7,393 | 🐛 70 | 🌐 Python | 📅 2026-08-23 - Python Data. Leaflet.js Maps.
* [PlotJuggler](https://github.com/facontidavide/PlotJuggler) ⭐ 6,124 | 🐛 161 | 🌐 C++ | 📅 2026-08-10 - PlotJuggler is a tool to visualize time series that is fast, powerful and intuitive.
* [tippecanoe](https://github.com/mapbox/tippecanoe) ⭐ 3,110 | 🐛 217 | 🌐 C++ | 📅 2026-06-29 - Build vector tilesets from large collections of GeoJSON features.
* [procedural-gl-js](https://github.com/felixpalmer/procedural-gl-js) ⭐ 1,342 | 🐛 22 | 🌐 JavaScript | 📅 2021-05-11 - Procedural GL JS is a library for creating 3D map experiences on the web, written in JavaScript and WebGL. It is built on top THREE.js.
* [geoplot](https://github.com/ResidentMario/geoplot) ⭐ 1,211 | 🐛 33 | 🌐 Python | 📅 2024-06-08 -  High-level Python geospatial plotting library. It's an extension to cartopy and matplotlib which makes mapping easy.
* [circlize](https://github.com/jokergoo/circlize) ⭐ 1,019 | 🐛 67 | 🌐 R | 📅 2023-11-11 - Circular visualization in R. Circular layout is an efficient way for the visualization of huge amounts of information.
* [lonboard](https://github.com/developmentseed/lonboard) ⭐ 960 | 🐛 122 | 🌐 Python | 📅 2026-08-17 - Fast, interactive geospatial data visualization in Jupyter.
* [Kosmtik](https://github.com/kosmtik/kosmtik) ⭐ 750 | 🐛 112 | 🌐 JavaScript | 📅 2025-03-13 - Very lite but extendable mapping framework to create Mapnik ready maps with OpenStreetMap data (and more).
* [Peak map](https://github.com/anvaka/peak-map) ⭐ 642 | 🐛 13 | 🌐 JavaScript | 📅 2025-12-27 - Allows you to visualize elevation of any area on the map with filled area charts.
* [GeoViews](https://github.com/holoviz/geoviews) ⭐ 633 | 🐛 116 | 🌐 Python | 📅 2026-08-21 - GeoViews is a Python library that makes it easy to explore and visualize any data that includes geographic locations.
* [Strava](https://github.com/marcusvolz/strava) ⭐ 585 | 🐛 10 | 🌐 R | 📅 2024-01-01 - Create artistic visualisations with your exercise data.
* [mplleaflet](https://github.com/jwass/mplleaflet) ⭐ 519 | 🐛 48 | 🌐 Python | 📅 2022-03-20 - Easily convert matplotlib plots from Python into interactive Leaflet web maps.
* [GeoJs](https://github.com/OpenGeoscience/geojs) ⭐ 470 | 🐛 46 | 🌐 JavaScript | 📅 2026-08-17 - High-performance visualization and interactive data exploration of scientific and geospatial location aware datasets.
* [mapdeck](https://github.com/SymbolixAU/mapdeck) ⭐ 382 | 🐛 79 | 🌐 HTML | 📅 2025-03-21 - R interface to Deck.gl and Mapbox.
* [PostGIS Preview](https://github.com/NYCPlanning/labs-postgis-preview) ⚠️ Archived - A lightweight node api and frontend for quickly previewing PostGIS queries.
* [bv](https://github.com/daleroberts/bv) ⭐ 233 | 🐛 1 | 🌐 Python | 📅 2017-01-17 - bv is a small tool to quickly view high-resolution multi-band imagery directly in your iTerm 2.
* [deck.gl-raster](https://github.com/developmentseed/deck.gl-raster) ⭐ 222 | 🐛 98 | 🌐 TypeScript | 📅 2026-08-03 - Client-side, GPU-accelerated Cloud-Optimized GeoTIFF visualization in deck.gl.
* [Go Cart](https://github.com/Flow-Based-Cartograms/go_cart) ⚠️ Archived - Fast cartogram generator written in C.
* [CityEngine-Twitter](https://github.com/urschrei/CityEngine-Twitter) ⭐ 73 | 🐛 0 | 🌐 Python | 📅 2017-08-04 - Visualise Twitter activity using a procedurally-generated 3D city model.
* [CometTS](https://github.com/CosmiQ/CometTS) ⭐ 62 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2019-10-23 - Comet Time Series Toolset for working with a time-series of remote sensing imagery and user defined polygons.
* [xarray\_leaflet](https://github.com/davidbrochart/xarray_leaflet) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2023-01-17 - An xarray extension for tiled map plotting.
* [Cinder](https://libcinder.org/) - Cinder is a free and open source library for professional-quality creative coding in C++.
* [D3.js](https://d3js.org/) - D3.js is a JavaScript library for manipulating documents based on data.
* [Kongsberg Geospatial's TerraLens SDK](https://www.kongsberggeospatial.com/products/terralens) - SDK designed for easy project integration and quick implementation in virtually any development environment. TerraLens provides real-time 2D and 3D mapping with powerful data visualization tools.
* [openFrameworks](http://openframeworks.cc/) - openFrameworks is an open source C++ toolkit for creative coding.
* [P5.js](https://p5js.org/) - Javascript library that starts with the original goal of Processing.
* [Processing.py](http://py.processing.org/) - Python mode for Processing.
* [Processing](https://processing.org/) - Processing is a flexible software sketchbook and a language for learning how to code within the context of the visual arts.
* [Skia](https://skia.org/) - Skia is a complete 2D graphic library for drawing Text, Geometries, and Images.
* [three.js](https://threejs.org/) - A javascript 3D library which makes WebGL simpler

## Tools

* [Open Location Code](https://github.com/google/open-location-code) ⭐ 4,346 | 🐛 60 | 🌐 Java | 📅 2026-03-30 - Open Location Code is a library to generate short codes, called "plus codes", that can be used as digital addresses where street addresses don't exist.
* [Mapus](https://github.com/alyssaxuu/mapus) ⭐ 3,531 | 🐛 9 | 🌐 JavaScript | 📅 2022-07-02 - Mapus is a tool to explore and annotate collaboratively on a map.
* [Planetiler](https://github.com/onthegomap/planetiler) ⭐ 2,151 | 🐛 114 | 🌐 Java | 📅 2026-08-18 - Flexible tool to build planet-scale vector tilesets from OpenStreetMap data in a few hours.
* [Osm2pgsql](https://github.com/openstreetmap/osm2pgsql) ⭐ 1,680 | 🐛 36 | 🌐 C++ | 📅 2026-07-24 - osm2pgsql is a tool for loading OpenStreetMap data into a PostgreSQL.
* [Generic Mapping Tools](https://github.com/GenericMappingTools/gmt) ⭐ 975 | 🐛 233 | 🌐 C | 📅 2026-08-23 - GMT is an open source collection of about 90 command-line tools for manipulating geographic and Cartesian data sets.
* [eodag](https://github.com/CS-SI/eodag) ⭐ 426 | 🐛 179 | 🌐 Python | 📅 2026-08-23 - Command line tool and a plugin-oriented Python framework for searching, aggregating results and downloading remote sensed images while offering a unified API for data access regardless of the data provider.
* [veins](https://github.com/sommer/veins) ⭐ 327 | 🐛 8 | 🌐 C++ | 📅 2026-06-16 - Open source vehicular network simulation framework.
* [exactextract](https://github.com/isciences/exactextract) ⭐ 318 | 🐛 28 | 🌐 C++ | 📅 2026-02-24 - Provides a fast and accurate algorithm for summarizing values in the portion of a raster dataset that is covered by a polygon, often referred to as zonal statistics.
* [DroneDB](https://github.com/DroneDB/DroneDB) ⭐ 280 | 🐛 22 | 🌐 C++ | 📅 2026-08-21 - Effortless aerial data management and sharing.
* [nextgisweb](https://github.com/nextgis/nextgisweb) ⭐ 276 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - Server based application/server-side framework for geodata storage, management and visualization.
* [fresco](https://github.com/go-spatial/fresco) ⚠️ Archived - Fresco is an open source Mapbox Vector Tile Style editor that allows cartographers to craft stylesheets for use with Mapbox GL maps.
* [sat-search](https://github.com/sat-utils/sat-search) ⭐ 195 | 🐛 23 | 🌐 Python | 📅 2021-06-22 - Sat-search is a Python 3 library and a command line tool for discovering and downloading publicly available satellite imagery using STAC compliant API.
* [Magrit](https://github.com/riatelab/magrit) ⭐ 160 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-17 - Magrit is an online application for thematic mapping.
* [imscript](https://github.com/mnhrdt/imscript) ⭐ 122 | 🐛 1 | 🌐 C | 📅 2026-08-03 - A collection of small and standalone utilities for image processing.
* [DataPillager](https://github.com/gdherbert/DataPillager) ⭐ 75 | 🐛 0 | 🌐 Python | 📅 2026-08-13 - Download data from Esri service.
* [DsgTools](https://github.com/dsgoficial/DsgTools) ⭐ 64 | 🐛 1 | 🌐 Python | 📅 2026-08-12 - DSGTools is a QGIS plugin that allow users to create and manipulate Geospatial Data according to Brazilian Law (ET-EDGV 2.1.3 and ET-EDGV 3.0)
* [opensarkit](https://github.com/openforis/opensarkit) ⭐ 55 | 🐛 5 | 🌐 Shell | 📅 2018-10-03 - Tools for Automatic Preprocessing of SAR Imagery.
* [landsat-espa-util](https://github.com/loicdtx/landsat-espa-util) ⭐ 23 | 🐛 4 | 🌐 Python | 📅 2020-08-04 - Library for querying and ordering Landsat Surface Reflectance data via ESPA.
* [gdal-mini](https://github.com/rouault/gdal-mini) ⭐ 19 | 🐛 0 | 🌐 C++ | 📅 2021-01-26 - Minimal version of GDAL.
* [gisweep](https://github.com/enisgetmez/gisweep) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-05-06 - GIS vulnerability scanner for ArcGIS REST, OGC (WMS/WFS), and embedded web maps. Audits anonymous write capabilities, exposed admin endpoints, PII fields in feature schemas, and outdated server / client-side libraries; every finding is mapped to KVKK / GDPR articles. Active-mode probes are gated behind explicit opt-in.
* [52North SOS](http://52north.org/communities/sensorweb/sos/) - A reference implementation of the \[OGC Sensor Observation Service specification (version 2.0)]
* [AeroCartwright Drone Mapping Calculators](https://aerocartwright.com/tools/) - Free browser-based ground sample distance (GSD) and ground control point (GCP) calculators for drone survey flight planning and accuracy; no signup.
* [Bounding Box Tool](https://vibhorsingh.com/boundingbox) - Interactive tool for drawing bounding boxes on a map and exporting as WKT, GeoJSON, KML, Overpass API, OGC BBOX, STAC and more. Supports 3,900+ EPSG projections and Uber H3 grid tools.
* [CODA](http://stcorp.github.io/coda/doc/html/index.html) - The Common Data Access toolbox (CODA) provides a set of tools for ingesting, processing, and analyzing remote sensing data.
* [CoordinateMapper](https://coordinatemapper.com/) - Free browser-based tool for converting between lat/long, UTM, UK Grid References, Easting/Northing, MGRS, DMS and DDM. Includes map preview and CSV/KML/DXF export.
* [Galileo](https://galileo.gisdata.io/) - Geospatial data discovery and management platform. Search over 1,890+ data sources using advanced filters, spatial search, and previews. Manage your data with collections and downloads to 5 file types.
* [GeoGig](http://geogig.org/) - GeoGig is a Distributed Version Control System (DVCS) specially designed to handle geospatial data efficiently.
* [Geo Hound](https://www.geohound.app/) - Chrome extension that detects the GIS data behind any web map and lets you save it as a live layer to query and analyze in the browser.
* [GISWATER](https://www.giswater.org/?lang=en) - Open-source software for water cycle management (water supply and urban drainage).
* [GrADS](http://cola.gmu.edu/grads/) - The Grid Analysis and Display System (GrADS) is an interactive desktop tool that is used for easy access, manipulation, and visualization of earth science data.
* [Kart](https://kartproject.org/) - Distributed version-control
  for geospatial and tabular data.
* [Kongsberg Geospatial's TerraLens SDK](https://www.kongsberggeospatial.com/products/terralens) - SDK designed for easy project integration and quick implementation in virtually any development environment. TerraLens provides real-time 2D and 3D mapping with powerful data visualization tools.
* [Maparz](https://maparz.com/) - Free online geospatial file converter powered by GDAL. Converts between Shapefile, GeoJSON, KML/KMZ, GeoPackage, GPX, DXF, GML, FlatGeobuf and CSV — 81 conversion pairs, live map preview, no signup or installation required.
* [MapShaper](http://mapshaper.org/) - Tools for editing Shapefile, GeoJSON, TopoJSON and CSV files.
* [MapTiler Desktop](https://www.maptiler.com/desktop/) - Software for converting your data into fast zoomable maps. Load your image or geodata and get a tiled map.
* [Namazue Console](https://github.com/Hybirdss/namazue-console) - Japan-wide earthquake intelligence console with GMPE intensity computation, real-time P/S wave propagation, PLATEAU 3D Tiles, and infrastructure fragility assessment.
* [Projection  Wizard](http://projectionwizard.org/) - Helps you select an appropriate projection for your map, depending on the area that you are mapping.
* [Quick Map Tools](https://www.quickmaptools.com/) - Free browser-based GIS toolkit for viewing, converting, and processing geospatial files such as GeoJSON, Shapefile, KML, and GeoTIFF, plus coordinate conversion and open data downloads.
* [Satellite Optical Sensor Calculator](https://opticalsatellitetools.space/) - A calculator that simplifies complex satellite sensor design by providing approximate calculations for optical parameters.
* [StoryRoute](https://storyroute.netlify.app) - Free web application that applies large language models to geospatial context to generate immersive, location-aware travel narratives.
* [TileMill](https://tilemill-project.github.io/tilemill/) - TileMill is a modern map design studio powered by Node.js and Mapnik.

## Cheat sheets

* [GDAL](https://github.com/dwtkns/gdal-cheat-sheet) ⭐ 1,222 | 🐛 5 | 📅 2024-06-13 - Cheat sheet for GDAL/OGR command-line tools.
* [Fiona-Rasterio-Shapely Cheat Sheet](https://github.com/sgillies/frs-cheat-sheet) ⭐ 102 | 🐛 0 | 📅 2016-03-23 - A cheat sheet for Fiona/Rasterio/Shapely command-line geodata tools.
* [GNU Parallel](https://www.gnu.org/software/parallel/parallel_cheat.pdf) - Cheat sheet for the GNU Parallel CLI tool.
* [PostGIS 2](https://gist.github.com/kidpixo/5698476) - Cheat sheet for PostGIS (version 2)
* [PostGIS Raster](http://www.postgis.us/downloads/postgis20_raster_cheatsheet.pdf) - Cheat sheet for PostGIS Raster manipulation.
* [PostGIS](http://www.postgis.us/downloads/postgis21_cheatsheet.pdf) - Cheat sheet for PostGIS.

## Data Sources

* [World Atlas TopoJSON](https://github.com/topojson/world-atlas) ⚠️ Archived - Natural Earth's vector data as TopoJSON.
* [RoadDetections](https://github.com/microsoft/RoadDetections) ⭐ 634 | 🐛 9 | 🌐 C# | 📅 2026-05-05 - Road detections from Microsoft Maps aerial imagery.
* [AIforEarthDataSets](https://github.com/microsoft/AIforEarthDataSets) ⭐ 315 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2024-12-17 - Notebooks and documentation for AI-for-Earth-managed datasets on Azure Open Datasets.
* [Ookla internet speed data](https://github.com/teamookla/ookla-open-data) ⭐ 312 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2026-04-16 - Global network performance metrics.
* [Callisto Generated Datasets](https://github.com/Agri-Hub/Callisto-Dataset-Collection) ⭐ 187 | 🐛 1 | 📅 2023-11-21 - A list of datasets aiming to enable Artificial Intelligence applications that use Copernicus data.
* [CBERS on AWS](https://github.com/fredliporace/cbers-on-aws) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2019-08-20 - Information, tools and data related to the China-Brazil Earth Resources Satellite (CBERS) PDS on AWS.
* [ZipCheckup](https://github.com/artakulov/us-water-quality-data) ⭐ 4 | 🐛 0 | 📅 2026-08-20 - Free ZIP-level environmental safety data platform covering water quality, air quality, PFAS, radon, lead, flood risk and 11 more verticals across 42K US ZIP codes. Public API, CC BY 4.0.
* [99 Boundaries](https://99boundaries.com/) - Download or generate maritime and land country boundaries from OpenStreetMap in GeoJSON and other file formats.
* [ArcGIS Hub](https://hub.arcgis.com/) - Over 380,000 open datasets.
* [ASTER Data](https://terra.nasa.gov/data/aster-data) - Download ASTER data.
* [Cityscapes Dataset](https://www.cityscapes-dataset.com/) -  large-scale dataset that contains a diverse set of stereo video sequences recorded in street scenes from 50 different cities, with high quality pixel-level annotations of 5 000 frames in addition to a larger set of 20 000 weakly annotated frames.
* [Copernicus global DEM](https://ec.europa.eu/eurostat/web/gisco/geodata/digital-elevation-model/copernicus#Elevation) - Global elevation tiles.
* [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/home) - Sentinel data from scihub.
* [ETOPO1](https://www.ngdc.noaa.gov/mgg) - 1 arc-minute global relief model of Earth's surface.
* [European population grids - GISCO](https://ec.europa.eu/eurostat/web/gisco/geodata/grids) - Population figures in grid cells.
* [European Postcodes Point Data](https://ec.europa.eu/eurostat/web/gisco/geodata/administrative-units/postal-codes) - Location of postal codes across Europe.
* [GBIF](https://www.gbif.org/) - Open access to biodiversity data.
* [Geoboundaries](https://www.geoboundaries.org/) - The world's largest open, free political boundaries database.
* [Geofabrik](http://download.geofabrik.de/) - This is another source of prepared OpenStreetMap data. This distribution is generally built nightly and comes in OSM XML, pbf, and shapefile (for very popular areas) formats.
* [GeoNames](http://www.geonames.org/) - The GeoNames geographical database covers all countries and contains over eight million place names (cities, postal codes, countries) that are available for download free of charge.
* [Global Climate Monitor](https://kerdoc.cica.es/) - Global open climate data.
* [Global power plant database](https://datasets.wri.org/dataset/globalpowerplantdatabase) - Open source database of power plants.
* [Healthcare Services in Europe](https://ec.europa.eu/eurostat/web/gisco/geodata/basic-services#Healthcare) - Locations of healthcare services in Europe.
* [HydroSHEDS](https://www.hydrosheds.org/) - Consistent hydrographic data for global applications.
* [INPE CBERS4A and Amazonia1 Database](http://www2.dgi.inpe.br/catalogo/explore) - Download free CBERS 4A and Amazonia 1 images.
* [INPE Database](http://www.dgi.inpe.br/CDSR/) - Download free satellite data including MODIS, Landsat (1-8), ResourceSat (1-2) and CBERS (2 and 2B) data.
* [Japan Neighborhoods](https://japanneighborhoods.com) - Free English-language dataset of Tokyo crime statistics covering 5,078 neighborhoods (chōme) across Tokyo 23 wards + Tama area, 7 years (2018-2024, 36,222 records) sourced from Tokyo Metropolitan Police open data. Includes interactive Leaflet crime map, safety grading (A+ to F), and cost-of-living index. CC BY licensed.
* [MapTiler Data](https://www.maptiler.com/data/) - Ready-to-use geographic data. The very best of open geospatial data, processed and packaged for your next on-prem project. Available as vector/raster tiles and in GIS formats.
* [Mapzen](https://mapzen.com/metro-extracts) - It provides data in OSM/PBF and Esri shapefile formats for popular cities.
* [NASA Earth Data](https://search.earthdata.nasa.gov/search) - Search, discover, visualize, refine, and access NASA Earth Observation data in your browser with Earthdata Search.
* [NASA Earth Observations](https://neo.gsfc.nasa.gov/) - Browse and download satellite data imagery.
* [Natural Earth](http://www.naturalearthdata.com/) - This site offers public domain map data sets that contain both raster and vector data.
* [OpenAerialMap](https://openaerialmap.org/) - Open service for accessing licensed imagery.
* [OpenWaterAtlas](https://openwateratlas.com/en/datasets/) - Open (CC BY 4.0) dataset joining 2,928 dive/kite/surf/freedive sites to 112,548 OBIS + GBIF marine species occurrences within 5 km, per-spot 5-year daily climate aggregates (Open-Meteo + ERA5), and 34,876 OpenFlights direct routes. Versioned Zenodo DOI, mirrored on Kaggle and Hugging Face.
* [Overture Maps open data](https://overturemaps.org/download/) - Free and open (CDLA Permissive 2.0) global GeoParquet datasets, updated monthly on AWS S3 and Azure.
* [Scale Open Datasets](https://scale.com/open-datasets?utm_campaign=Spatial%20Awareness\&utm_medium=email\&utm_source=Revue%20newsletter) - Open Datasets for Autonomous Driving.
* [Sentinel 2 AWS](http://sentinel-pds.s3-website.eu-central-1.amazonaws.com/) - Sentinel 2 data on Amazon S3.
* [Sunshine Atlas](https://sunshineatlas.com/data/) - Open dataset (CC BY 4.0, DOI) of monthly sunshine hours, temperature, rainfall and sea-surface-temperature climate normals for 3,833 destinations worldwide; interactive globe, mirrored on GitHub, Zenodo, Hugging Face and Kaggle.
* [TZ Timezone Shapefiles](http://efele.net/maps/tz/world/) - Polygon boundaries of world timezones.
* [USGS Earth Explorer](http://earthexplorer.usgs.gov/) - Provides online search,metadata export, and data download for earth science data from the archives of the USGS.
* [World Bank](https://www.unccd.int/resources/knowledge-sharing-system/world-banks-open-data) - Free access to global development data.
* [WorldPop](https://www.worldpop.org/) - Open access spatial demographic datasets.

## Resources

* [GeoParquet](https://github.com/opengeospatial/geoparquet) ⭐ 1,080 | 🐛 50 | 🌐 Python | 📅 2026-08-22 - Specification for storing geospatial vector data (point, line, polygon) in Parquet.
* [Geopython](https://github.com/urschrei/Geopython) ⭐ 381 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-08-17 - Notebooks and libraries for spatial/geo Python explorations.
* [Cloud Optimized Point Cloud Specification](https://github.com/copcio/copcio.github.io) ⭐ 139 | 🐛 3 | 🌐 Shell | 📅 2026-08-18 - Geospatial, compressed, range-readable, LAZ-compatible point cloud format.
* [LOLManuscriptMonday](https://github.com/ladiesoflandsat/LOLManuscriptMonday) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2023-09-29 - Hold the links to the Ladies of Landsat Manuscript Monday series.
* [Cartographical Map Projections](http://www.progonos.com/furuti/MapProj/Normal/TOC/cartTOC.html) - A good introduction to projected coordinate systems.
* [ESRI Shapefile Specs](http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf) - Shapefile specifications.
* [GDAL/OGR Cookbook](https://pcjericks.github.io/py-gdalogr-cookbook/) - Simple code snippets on how to use the Python GDAL/OGR API.
* [GeoJSON.io](http://geojson.io/) - geojson.io is a quick, simple tool for creating, viewing, and sharing maps.
* [GIGS](https://gigs.iogp.org/) - GIGS comprises qualitative test series checklists and quantitative test dataset files.
* [IndexDatabase](http://www.indexdatabase.de/) - A database for remote sensing indices.
* [Spatialreference.org](http://spatialreference.org/) - Source for coordinate system information.
* [TileJSON.io](http://tilejson.io/) - tilejson.io is a simple viewer for raster tile sets (Enter tile URL, layer properties, share).

### Icons

* [font-GIS](https://github.com/Viglino/font-gis) ⭐ 323 | 🐛 2 | 🌐 CSS | 📅 2025-07-16 - A very very cool icon font set for use with GIS and spatial analysis tools.
* [Map Icons Collection](https://mapicons.mapsmarker.com/) - A set of more than 1000 free and customizable icons to use as placemarks for your POI.
* [Material Symbols](https://fonts.google.com/icons?icon.query=map) - Over 2,990 glyphs in a single font file with a wide range of design variants.

### Color Advice

* [Textures.js](https://github.com/riccardoscalco/textures) ⭐ 6,090 | 🐛 21 | 🌐 JavaScript | 📅 2023-01-01 - JavaScript library for creating SVG patterns, designed for data visualization.
* [CartoColor](https://github.com/CartoDB/CartoColor) ⭐ 236 | 🐛 9 | 🌐 TypeScript | 📅 2025-02-11 - A set of custom color palettes built on top of standards for color use on maps.
* [Chroma.js Color Palette Helper](https://gka.github.io/palettes/) - Chroma.js-powered tool for mastering multi-hued, multi-stop color scales.
* [ColorBrewer](https://colorbrewer2.org/) - Colour advice for maps, based on Dr. Cynthia Brewer's research.

## Free and Open Source Books

* [An Introduction to Spatial Data Analysis and Statistics: A Course in R](https://paezha.github.io/spatial-analysis-r/)
* [Cloud-Based Remote Sensing with Google Earth Engine](https://www.eefabook.org/)
* [Elegant and informative maps with tmap](https://r-tmap.github.io/tmap-book/)
* [Geocomputation with Python](https://py.geocompx.org/)
* [Geocomputation with R](https://r.geocompx.org/)
* [Geographic Data Science with Python](https://geographicdata.science/book/)
* [Geographic Data Science with R: Visualizing and Analyzing Environmental Change](https://bookdown.org/mcwimberly/gdswr-book/)
* [Geospatial Analysis](https://www.spatialanalysisonline.com/)
* [Geospatial Data Science with Julia](https://juliaearth.github.io/geospatial-data-science-with-julia/)
* [Google Earth Engine Applications](https://www.mdpi.com/books/reprint/1262-google-earth-engine-applications)
* [Intro to GIS and Spatial Analysis](https://mgimond.github.io/Spatial/index.html)
* [Introduction to Spatial Data Programming with R](https://github.com/michaeldorman)
* [Introduction to urban accessibility: A practical guide with R](https://ipeagit.github.io/intro_access_book/)
* [R for Geographic Data Science](https://sdesabbata.github.io/r-for-geographic-data-science/index.html)
* [SAR Handbook - Comprehensive Methodologies for Forest Monitoring and Biomass Estimation](https://servirglobal.net/resources/sar-handbook)
* [Spatial Data Science With Applications in R](https://r-spatial.org/book/)
* [Spatial Microsimulation with R](https://spatial-microsim-book.robinlovelace.net/)
* [Spatial Modelling for Data Scientists](https://gdsl-ul.github.io/san/)
* [Spatial Statistics for Data Science: Theory and Practice with R](https://www.paulamoraga.com/book-spatial/index.html)
* [sits: Satellite Image Time Series Analysis on Earth Observation Data Cubes](https://e-sensing.github.io/sitsbook/)
* [The Language of Spatial Analisys](https://www.esri.com/content/dam/esrisites/sitecore-archive/Files/Pdfs/library/books/the-language-of-spatial-analysis.pdf)

## Conferences

* [ESRI User Conference](https://www.esri.com/en-us/about/events/uc/overview) - Esri International User Conference is an event dedicated to geographic information system technology.
* [FOSS4G](http://foss4g.org/) - Free and Open Source Software for Geospatial.
* [FOSSGIS](https://fossgis.de/) - Yearly conference of the German OpenStreetMap chapter and FOSS GIS community
* [Geo For Good Summit](https://earthoutreachonair.withgoogle.com/events/geoforgood21) - Annual conference, hosted by Google, geared toward nonprofits, scientists, government agencies and other change-makers who want to leverage mapping tools and technology for positive impact in the world.
* [GEOINFO](http://www.geoinfo.info/) - The GEOINFO series (Brazilian Symposium on Geoinformatics) is an annual conference for exploring ongoing research, development and innovative applications on geographic information science and related areas.
* [GeoPython](https://2021.geopython.net/) - The conference is focused on Python and Geo, its toolkits and applications.
* [International Syposium on Digital Earth](https://pcoconvin.eventsair.com/isde23/) - Event dedicated to bring together policy makers and scientists and will explore pathways towards the vision of a ‘Digital Earth
* [International Society for Photogrammetry and Remote Sensing](https://www.isprs2020-nice.com/) - The ISPRS Congress is the leading forum where classical and emergent topics related to photogrammetry, remote sensing, and spatial information sciences are discussed.
* [RCMRD International Conference](https://www.rcmrd.org/) - Annual conference held in Nairobi - Kenya, bringing together policymakers, executives, experts, researchers, developers, and innovators worldwide to exchange insights in Earth observation (EO) and Geographic Information System (GIS).
* [SBSR](https://2023.sbsr.com.br/) - Bi-annual Brazilian National Symposium on Remote Sensing.
* [Spatial Data Conference](https://spatial-data-science-conference.com/) -  Annual Conferece that intersects GIS, Advanced Analytics & Data Science that is growing rapidly & answering some of the most pressing questions in both the private & public sector.
* [State of the Map](https://stateofthemap.org/) - Annual event for all mappers and OpenStreetMap users.

## Podcasts

* [Down To Earth: A podcast for Geoscientists by Geoscientist](https://podcasts.apple.com/us/podcast/down-to-earth-a-podcast-for-geoscientists-by-geoscientist/id1549020890) - 30-minute podcast about innovative geoscience and the incredible people behind it. Each week, we host a different guest to talk about science, careers, and passions.
* [Eyes on Earth](https://www.usgs.gov/centers/eros/science/eyes-earth?qt-science_center_objects=0#qt-science_center_objects) - Eyes on Earth is a podcast on remote sensing, Earth observation, land change and science, brought to you by the USGS Earth Resources Observation and Science (EROS) Center.
* [ESRI & The Science of Where](https://www.esri.com/about/newsroom/podcast/) - Talks about business and technology leaders who share analysis, insights, and stories on data science, the Internet of Things, Smart Communities and other forces driving digital transformation and leveraging the power of location intelligence.
* [GIS Directions](https://esriaustralia.com.au/gis-directions-podcast) - Chat with inspiring GIS users, discuss new industry trends, and dish out plenty of practical pointers.
* [Geoadorable](https://geodorable.com/) - A podcast that may include anything and everything about the geospatial world. From news articles about the GIS industry that take our fancy, interviews with GIS practitioners, random acts of geospatial madness and of course the legendary game Export to Shapefile.
* [Geographical Thinking](https://www.esri.ca/en-ca/news-events/news/podcasts) - Tune in for inspiring stories from thought leaders and GIS users across business, government and education in Canada.
* [Geointeresting](https://podcasts.apple.com/us/podcast/geointeresting/id990858116) - Official podcast of the National Geospatial-Intelligence Agency. Geointeresting features conversations with innovators, explorers and pathfinders.
* [Geomob Podcast](https://thegeomob.com/podcast/) - weekly podcast interviewing anyone doing interesting things in geo, be it for fun or profit.
* [The MapScaping](https://mapscaping.com/blogs/the-mapscaping-podcast) - Weekly podcast featuring interesting people doing amazing work in the geospatial world.
* [Minds Behind Maps](https://minds-behind-maps.simplecast.com/) - Informal conversations with those creating maps, understanding how and why they build them. Earth Observation, Data Science, Business and how smart people combine them all to impact our world.
* [More Than Just Maps](https://urisatexas.org/podcast) - Talks with GIS veterans and geniuses who know a thing or two about how to find your way from student to professional and beyond, while also chatting about some neat tools, tricks, and trends. Presented by the URISA Texas Chapter.
* [Project Geospatial](https://www.projectgeospatial.com/) - Project Geospatial is a web series and blog dedicated to increasing awareness of Geospatial Technology, industry best practices, and GIS resources.
* [Scene From Above](https://scenefromabove.podbean.com/) - Earth observation, remote sensing, geospatial and geeky chat
* [A VerySpatial](https://veryspatial.com/) - A VerySpatial Podcast is your weekly source for information on Geography and geospatial technologies.

## References and other awesome lists

* [Awesome Python](https://github.com/vinta/awesome-python/blob/master/README.md) ⭐ 315,671 | 🐛 16 | 🌐 Python | 📅 2026-08-23
* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision) ⭐ 23,512 | 🐛 91 | 📅 2024-05-17
* [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision) ⭐ 11,185 | 🐛 47 | 📅 2023-08-15
* [Awesome Semantic Segmentation](https://github.com/mrgloom/awesome-semantic-segmentation) ⭐ 10,848 | 🐛 17 | 📅 2021-05-08
* [satellite-image-deep-learning](https://github.com/robmarkcole/satellite-image-deep-learning) ⭐ 10,237 | 🐛 0 | 📅 2026-08-02
* [Awesome Object Detection](https://github.com/amusi/awesome-object-detection) ⭐ 7,503 | 🐛 7 | 📅 2022-12-17
* [Awesome GIS - sshuair](https://github.com/sshuair/awesome-gis) ⭐ 5,496 | 🐛 60 | 📅 2026-07-21
* [Awesome Satellite Imagery Datasets](https://github.com/chrieke/awesome-satellite-imagery-datasets) ⚠️ Archived
* [Vector Tiles](https://github.com/mapbox/awesome-vector-tiles) ⭐ 2,622 | 🐛 3 | 📅 2026-08-10
* [GeoJSON](https://github.com/tmcw/awesome-geojson) ⭐ 2,529 | 🐛 1 | 📅 2026-07-23
* [Awesome-EarthObservation-Code](https://github.com/acgeospatial/awesome-earthobservation-code) ⭐ 1,378 | 🐛 6 | 🌐 HTML | 📅 2026-05-13
* [Awesome SAR](https://github.com/RadarCODE/awesome-sar) ⭐ 1,199 | 🐛 8 | 📅 2025-07-22
* [Awesome Spectral Indices](https://github.com/awesome-spectral-indices/awesome-spectral-indices) ⭐ 1,169 | 🐛 22 | 🌐 Python | 📅 2026-08-21
* [Awesome Frontend GIS](https://github.com/joewdavies/awesome-frontend-gis) ⭐ 847 | 🐛 8 | 📅 2026-08-18 - Geographic Information Systems (GIS) for web browsers. For managing, analyzing, editing, and visualizing geographic data.
* [Awesome Sentinel](https://github.com/Fernerkundung/awesome-sentinel) ⭐ 583 | 🐛 3 | 📅 2025-02-20
* [Digital Earth Australia notebooks and tools repository](https://github.com/GeoscienceAustralia/dea-notebooks) ⭐ 535 | 🐛 47 | 🌐 Jupyter Notebook | 📅 2026-08-21
* [Awesome DEM](https://github.com/DahnJ/Awesome-DEM) ⭐ 452 | 🐛 6 | 📅 2024-05-25 - Overview of Digital Elevation Model (DEM) datasets.
* [Awesome Geo Rust](https://github.com/pka/awesome-georust) ⭐ 413 | 🐛 1 | 📅 2026-03-01
* [Awesome SQLite](https://github.com/planetopendata/awesome-sqlite) ⭐ 404 | 🐛 5 | 📅 2026-08-22
* [Awesome Forests](https://github.com/blutjens/awesome-forests) ⭐ 377 | 🐛 8 | 📅 2025-08-01 - A curated list of ground-truth forest datasets for the machine learning and forestry community.
* [Awesome Spatial](https://github.com/RoboDonut/awesome-spatial/blob/master/README.md) ⭐ 221 | 🐛 101 | 📅 2018-01-04
* [Awesome Earth Engine Apps](https://github.com/philippgaertner/awesome-earth-engine-apps) ⭐ 189 | 🐛 2 | 📅 2024-01-03
* [Cartography / Mapping / Web design resources](https://github.com/tolomaps/resources) ⭐ 129 | 🐛 2 | 📅 2020-11-24
* [Awesome Earth Observation Instruments](https://github.com/awesome-spectral-indices/awesome-earth-observation-instruments) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-08-23 - A machine-readable catalogue of Earth observation instruments with spectral, spatial, temporal, and operational characteristics.
* [Awesome GERS](https://github.com/OvertureMaps/awesome-gers) ⭐ 1 | 🐛 0 | 📅 2026-05-01 - A curated list of GERS resources: docs, tools (overturemaps-py, overtureR, Fused UDFs), platform integrations (Esri, CARTO, Databricks, Wherobots), tutorials, talks, and case studies.
* [Essential Python Geospatial Libraries](http://carsonfarmer.com/2013/07/essential-python-geo-libraries/)
* [GeoRails](http://daniel-azuma.com/articles/georails/)
* [JuliaGeo](https://juliageo.org/)
* [Spatial R](https://cran.r-project.org/web/views/Spatial.html)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-23._
