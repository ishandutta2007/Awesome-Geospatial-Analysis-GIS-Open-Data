# Awesome-Geospatial-Analysis-GIS-Open-Data

<p align="center">
  <img src="./assets/banner.svg" alt="Top Geospatial Analysis & GIS Open Data" width="100%" />
</p>

<p align="center">
  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>
  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>
  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>
</p>

# 🗺️ Top Geospatial Analysis & GIS Open Data

**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  
*Focused on Open Web Mapping (Leaflet, Cesium, MapLibre GL, deck.gl), Desktop & Cloud GIS (QGIS, PostGIS, GeoServer), Python Spatial Data Science (GeoPandas, GDAL, Leafmap, Shapely) & Earth Observation / Open Data*  
**Last updated: November 2026**

This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Geospatial Analysis & GIS Open Data**. These tools power GPU-accelerated vector web maps (`Leaflet`, `Cesium`, `deck.gl`, `MapLibre GL JS`, `Kepler.gl`), desktop & spatial database GIS (`QGIS`, `PostGIS`, `GeoServer`, `Martin`), Python geospatial analytics & Earth observation (`GeoPandas`, `GDAL`, `Leafmap`, `Rasterio`, `Shapely`), and global open geospatial datasets (`Overture Maps`, `OpenStreetMap`, `STAC`) for GIS analysts, urban planners, and earth-observation researchers.

**Examples** include Google Earth Engine (Google), ArcGIS Online (Esri), Nearmap (Thoma Bravo), Mapbox, Planet Insights / Sentinel Hub (Planet Labs), CARTO, Felt, and QGIS Cloud (Sourcepole).

**🚀 Open-source emphasis**: This section is heavily expanded with major active projects for web GIS & vector-tile mapping (`Leaflet`, `Cesium`, `deck.gl`, `MapLibre GL JS`, `Kepler.gl`, `PMTiles`, `Martin`), desktop & enterprise spatial servers (`QGIS`, `PostGIS`, `GeoServer`), Python geospatial & satellite data science (`GeoPandas`, `Leafmap`, `GDAL`, `Rasterio`, `Shapely`, `H3`, `Apache Sedona`), and open map ecosystems (`Overture Maps`, `OpenStreetMap`) — ideal for teams building sovereign spatial pipelines without per-seat or map-load SaaS lock-in.

🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📑 Table of Contents
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)
- [💖 Support & Thank You](#-support--thank-you)

## 📊 Sector Overview & Market Dynamics

The global Geographic Information Systems (GIS), Spatial Analytics & Earth Observation SaaS market is estimated at **$16.5B–$20.8B+ in 2026** and projected to grow at a **12%–16% CAGR**, driven by cloud-native geospatial data lakes (GeoParquet, Cloud Optimized GeoTIFFs, STAC), high-frequency commercial satellite constellations, and AI geospatial foundation models. The market exhibits a **moderately fragmented, dual-structured dynamic**: the traditional proprietary enterprise GIS and satellite analytics tier is concentrated around dominant market anchors like Esri and Google Earth Engine, while web rendering, spatial indexing, cloud-native vector tiling, and programmatic data science remain extensively fragmented and governed by flourishing open-source standards.

## ☁️ SaaS/Hosted & Commercial Platforms

*Sorted descending by company scale (valuation / annual revenue).*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Google Earth Engine](https://earthengine.google.com)** | Planetary-scale cloud geospatial analysis platform combining petabytes of satellite imagery (Landsat, Sentinel, MODIS) with parallel Python/JS compute. | **Part of Alphabet Inc.** (~$350B+ Alphabet revenue; ~$2T+ market cap) | **$500 / month** (Basic commercial tier platform fee; compute usage at ~$0.40/EECU-hour) | **Forever Free Non-Commercial & Research Plan** (Free petabyte-scale access and compute for academic, research, and non-profit usage) |
| **[ArcGIS Online (Esri)](https://www.esri.com/en-us/arcgis/products/arcgis-online/overview)** | Industry-standard cloud GIS, spatial analytics, StoryMaps, and enterprise location-intelligence SaaS platform powering governments and enterprises globally. | **~$2.0B+ Annual Revenue** (Privately held GIS market leader) | **$700 / user / year** ($700/yr for Creator license; $100/yr for Viewer license) | **Forever Free Developer Account** (Includes **2,000,000 free basemap & tile requests/month**, 20,000 geocodes/month, and 100 MB data hosting) |
| **[Mapbox](https://www.mapbox.com)** | Developer-first cloud location platform offering vector maps, Mapbox GL, turn-by-turn navigation, geocoding, and Isochrone APIs. | **~$1.0B–$1.2B Valuation** (~$150M+ est. ARR; backed by SoftBank/Foundry) | **$5.00 per 1,000 web map loads** (Pay-as-you-go pay scale once exceeding the free monthly tier) | **Forever Free Developer Tier** (**50,000 free web map loads/month**, 25,000 mobile MAUs, and 100,000 free geocoding requests/month) |
| **[Nearmap (Thoma Bravo)](https://www.nearmap.com)** | High-resolution aerial orthomosaic, oblique imagery, 3D reality mesh, and AI property/infrastructure attribute SaaS covering North America, Australia, and NZ. | **~$730M Take-Private Valuation** (~$150M+ ARR; backed by Thoma Bravo) | **$3,500 / year** (Entry annual subscription for municipal/business spatial packages) | **14-Day Guided Evaluation Trial** (Custom 14-day proof-of-concept trial evaluation arranged via sales demo; no open self-serve tier) |
| **[Planet Insights / Sentinel Hub (Planet Labs)](https://www.planet.com)** | Cloud Earth-observation platform and Sentinel Hub API providing daily high-resolution satellite imagery, planetary variables, and on-the-fly spectral processing. | **~$220M+ Annual Revenue** (~$1B+ public market cap on NYSE: PL) | **€25 / month** (€300 billed annually for Sentinel Hub Exploration Plan, 30,000 Processing Units/month) | **30-Day Full-Access Free Trial** (Includes 30,000 Processing Units, EO Browser, and Copernicus Sentinel/Landsat API endpoints for 30 days) |
| **[CARTO](https://carto.com)** | Cloud-native spatial analytics platform running directly on top of Snowflake, BigQuery, Databricks, and PostgreSQL for large-scale location intelligence. | **~$100M–$200M Est. Valuation** ($61M+ Series C led by Insight Partners) | **$199 / month** billed annually ($299/mo monthly for Starter cloud workspace) | **14-Day Full-Access Free Trial** (Full access to cloud data warehouse connectors, spatial SQL analytics, and CARTO Builder maps for 14 days) |
| **[Felt](https://felt.com)** | Modern, collaborative browser-native GIS and internet mapping platform featuring real-time multiplayer editing, spatial SQL, and instant data styling. | **~$50M–$100M Est. Valuation** ($34M+ VC funding led by Footwork/Bain Capital) | **$200 / month** billed annually ($240/mo monthly for Team plan, 5 editors) | **Forever Free Starter Plan** (**Unlimited maps**, up to **3 editors**, 100 MB file upload limit, and public web sharing) |
| **[QGIS Cloud (Sourcepole)](https://qgiscloud.com)** | Hosted cloud Web-GIS publishing service letting users publish desktop QGIS projects directly to OGC WMS/WFS web maps and PostGIS databases. | **Independent Swiss Open-Core GIS Vendor** (Sourcepole AG; core QGIS project contributors) | **€65 / month** (QGIS Cloud Pro with unlimited databases, password protection, and custom domains) | **Forever Free Community Plan** (**Unlimited public web maps**, 1 PostGIS database, and **50 MB storage** free forever with QGIS Cloud branding) |

## 💻 Open-Source GitHub Projects

*Sorted descending by repository star count. Badges link directly to each repository's stargazers page.*

| Project | Stars | Category / Focus | Description |
| :--- | :--- | :--- | :--- |
| **[Leaflet](https://github.com/Leaflet/Leaflet)** | [![Leaflet Stars](https://img.shields.io/github/stars/Leaflet/Leaflet?style=social&color=white)](https://github.com/Leaflet/Leaflet/stargazers) | Web Mapping | Leading open-source JavaScript library for mobile-friendly interactive maps. |
| **[CesiumJS](https://github.com/CesiumGS/cesium)** | [![Cesium Stars](https://img.shields.io/github/stars/CesiumGS/cesium?style=social&color=white)](https://github.com/CesiumGS/cesium/stargazers) | 3D Geospatial & Globe | Open-source JavaScript library for creating world-class 3D globes and maps. |
| **[QGIS](https://github.com/qgis/QGIS)** | [![QGIS Stars](https://img.shields.io/github/stars/qgis/QGIS?style=social&color=white)](https://github.com/qgis/QGIS/stargazers) | Desktop GIS Application | Free, Open Source Geographic Information System desktop suite for spatial data creation, editing, and analysis. |
| **[deck.gl](https://github.com/visgl/deck.gl)** | [![deck.gl Stars](https://img.shields.io/github/stars/visgl/deck.gl?style=social&color=white)](https://github.com/visgl/deck.gl/stargazers) | WebGL Data Visualization | WebGL2-powered framework for exploratory large-scale geospatial data analytics and visual rendering. |
| **[OpenLayers](https://github.com/openlayers/openlayers)** | [![OpenLayers Stars](https://img.shields.io/github/stars/openlayers/openlayers?style=social&color=white)](https://github.com/openlayers/openlayers/stargazers) | Web Mapping | High-performance, feature-packed library for displaying dynamic map data in web browsers. |
| **[MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js)** | [![MapLibre GL JS Stars](https://img.shields.io/github/stars/maplibre/maplibre-gl-js?style=social&color=white)](https://github.com/maplibre/maplibre-gl-js/stargazers) | Vector Tile Web Mapping | Open-source, community-led TypeScript library for vector-tile rendering maps with WebGL. |
| **[kepler.gl](https://github.com/keplergl/kepler.gl)** | [![kepler.gl Stars](https://img.shields.io/github/stars/keplergl/kepler.gl?style=social&color=white)](https://github.com/keplergl/kepler.gl/stargazers) | Large-scale Geo-Visualization | Kepler.gl is a data-agnostic, high-performance web-based application for visual exploration of large-scale geolocation data. |
| **[GeoLibre](https://github.com/opengeos/GeoLibre)** | [![GeoLibre Stars](https://img.shields.io/github/stars/opengeos/GeoLibre?style=social&color=white)](https://github.com/opengeos/GeoLibre/stargazers) | Open Geospatial Ecosystem | Open-source geospatial mapping and GIS library by OpenGeos empowering vendor-free spatial analysis and web visualization. |
| **[H3](https://github.com/uber/h3)** | [![H3 Stars](https://img.shields.io/github/stars/uber/h3?style=social&color=white)](https://github.com/uber/h3/stargazers) | Hexagonal Spatial Indexing | Hexagonal hierarchical spatial index developed by Uber for grid-based spatial partition and optimization. |
| **[GDAL](https://github.com/OSGeo/gdal)** | [![GDAL Stars](https://img.shields.io/github/stars/OSGeo/gdal?style=social&color=white)](https://github.com/OSGeo/gdal/stargazers) | Geospatial Data Abstraction | Translator library for raster and vector geospatial data formats released under an MIT style Open Source License. |
| **[GeoPandas](https://github.com/geopandas/geopandas)** | [![GeoPandas Stars](https://img.shields.io/github/stars/geopandas/geopandas?style=social&color=white)](https://github.com/geopandas/geopandas/stargazers) | Python Geospatial Data Science | Extends pandas data structures to enable spatial operations and geometric algorithms on geometric types. |
| **[Shapely](https://github.com/shapely/shapely)** | [![Shapely Stars](https://img.shields.io/github/stars/shapely/shapely?style=social&color=white)](https://github.com/shapely/shapely/stargazers) | Geometric Analysis | Manipulation and analysis of planar geometric objects, based on GEOS. |
| **[GeoServer](https://github.com/geoserver/geoserver)** | [![GeoServer Stars](https://img.shields.io/github/stars/geoserver/geoserver?style=social&color=white)](https://github.com/geoserver/geoserver/stargazers) | Spatial Map Server | Open source software server written in Java that allows users to share, process, and edit geospatial data via OGC standards. |
| **[Martin](https://github.com/maplibre/martin)** | [![Martin Stars](https://img.shields.io/github/stars/maplibre/martin?style=social&color=white)](https://github.com/maplibre/martin/stargazers) | Vector Tile Server | Blazing-fast tile server generating vector tiles on the fly from PostGIS, PMTiles, and MBTiles. |
| **[Leafmap](https://github.com/opengeos/leafmap)** | [![Leafmap Stars](https://img.shields.io/github/stars/opengeos/leafmap?style=social&color=white)](https://github.com/opengeos/leafmap/stargazers) | Python Geospatial Analysis | A Python package for interactive mapping and geospatial analysis with minimal coding in Jupyter environments. |
| **[PMTiles](https://github.com/protomaps/PMTiles)** | [![PMTiles Stars](https://img.shields.io/github/stars/protomaps/PMTiles?style=social&color=white)](https://github.com/protomaps/PMTiles/stargazers) | Cloud-Native Vector Tiles | Cloud-optimized single-file tile archive format for pyramids of map tiles enabled by HTTP Range requests. |
| **[Rasterio](https://github.com/rasterio/rasterio)** | [![Rasterio Stars](https://img.shields.io/github/stars/rasterio/rasterio?style=social&color=white)](https://github.com/rasterio/rasterio/stargazers) | Python Raster Analysis | Rasterio reads and writes geospatial raster datasets like GeoTIFFs using Python idiom and GDAL C APIs. |
| **[Apache Sedona](https://github.com/apache/sedona)** | [![Apache Sedona Stars](https://img.shields.io/github/stars/apache/sedona?style=social&color=white)](https://github.com/apache/sedona/stargazers) | Distributed Spatial Compute | Cluster computing system for processing large-scale spatial data with Apache Spark and Apache Flink. |
| **[PostGIS](https://github.com/postgis/postgis)** | [![PostGIS Stars](https://img.shields.io/github/stars/postgis/postgis?style=social&color=white)](https://github.com/postgis/postgis/stargazers) | Spatial Database Engine | Spatial database extender for PostgreSQL object-relational database, adding support for geographic objects. |

## 🛠️ How to Contribute
1. Fork this repository.
2. Add your tool, platform, or open-source library to the appropriate section maintaining existing table formats and sort orders.
3. Open a pull request with a clear description of the project.

## ⚠️ Disclaimer
All product names, logos, and brands are property of their respective owners. Company scale metrics and pricing are estimated from public corporate disclosures and subject to change.

## 💖 Support & Thank You
If you find this repository helpful, consider starring ⭐ the repository and sharing it with the spatial and GIS community!
