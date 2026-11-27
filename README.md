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

*Focused on Open Web Mapping (GeoLibre, MapLibre GL, Leaflet, deck.gl), Desktop & Cloud GIS (QGIS, PostGIS, GeoServer), Python Spatial Data Science (GeoPandas, Leafmap, GDAL) & Earth Observation / Open Data*  

**Last updated: November 2026**



This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Geospatial Analysis & GIS Open Data**. These tools power GPU-accelerated vector web maps (`opengeos/GeoLibre`, `MapLibre GL JS`, `deck.gl`, `Kepler.gl`), desktop & spatial database GIS (`QGIS`, `PostGIS`, `GeoServer`, `Martin`), Python geospatial analytics & Earth observation (`GeoPandas`, `Leafmap`, `GDAL`, `Rasterio`, `Xarray`), and global open geospatial datasets (`Overture Maps`, `OpenStreetMap`, `STAC`) for GIS analysts, urban planners, and earth-observation researchers.



**Examples** include Google Earth Engine (Google), ArcGIS Online (Esri), Nearmap (Thoma Bravo), Mapbox, Planet Insights / Sentinel Hub (Planet Labs), CARTO, Felt, QGIS Cloud (Sourcepole), and Placemark (the category leaders).



**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for web GIS & vector-tile mapping (`opengeos/GeoLibre`, `MapLibre GL JS`, `Leaflet`, `OpenLayers`, `deck.gl`, `Kepler.gl`, `PMTiles`, `Martin`), desktop & enterprise spatial servers (`QGIS`, `PostGIS`, `GeoServer`, `GRASS GIS`), Python geospatial & satellite data science (`GeoPandas`, `Leafmap`, `GDAL`, `Rasterio`, `Shapely`, `PySTAC`, `Sedona`), and open map ecosystems (`Overture Maps`, `OpenStreetMap`) — ideal for teams building sovereign spatial pipelines without per-seat or map-load SaaS lock-in.



🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)

- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)

- [💻 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#️-how-to-contribute)

- [⚠️ Disclaimer](#️-disclaimer)

- [💖 Support & Thank You](#-support--thank-you)



## 📊 Sector Overview & Market Dynamics



The global Geographic Information Systems (GIS), Spatial Analytics & Earth Observation SaaS market is valued at approximately **$16.5B–$20.8B+ in 2026**, expanding at a ~12%–16% CAGR propelled by cloud-native GeoParquet/STAC data lakes, real-time satellite imagery analytics, and AI geospatial foundation models. The enterprise desktop/SaaS GIS layer exhibits **strong winner-take-most consolidation** around Esri (ArcGIS Online), Google Earth Engine, and Mapbox, while the **web vector-tile rendering, spatial database, and Python geoprocessing ecosystems are overwhelmingly driven by open-source standards** (`QGIS`, `PostGIS`, `MapLibre`, `GDAL`, `GeoPandas`, `PMTiles`, `Overture Maps`).



## ☁️ SaaS/Hosted & Commercial Platforms



*Sorted descending by company valuation / annual revenue scale.*



| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |

| :--- | :--- | :--- | :--- | :--- |

| **[Google Earth Engine](https://google.com)** | Planetary-scale cloud geospatial analysis platform combining petabytes of satellite imagery (Landsat, Sentinel, MODIS) with parallel Python/JS compute. | **Part of Alphabet Inc.** (~$350B+ Alphabet revenue; ~$2T+ market cap) | **Pay-as-you-go / Google Cloud Billing** (Commercial EECU compute & storage tiers starting ~$50+/mo) | **Forever Free Non-Commercial & Research Tier** (100% free petabyte-scale Earth observation compute for academic, non-profit & research projects) |

| **[ArcGIS Online (Esri)](https://arcgis.com)** | Industry-standard cloud GIS, spatial analytics, StoryMaps, and enterprise location-intelligence SaaS platform powering governments and enterprises globally. | **~$2.0B+ Annual Revenue** (Privately held GIS market leader) | **$100 / user / year** (Viewer) or **$700 / user / year** (Creator license for full web GIS & map authoring) | **Forever Free Public Account & Developer Tier** (Free public map viewing/basic creation + **2,000,000 free map tile/basemap requests/month** on ArcGIS Location Platform) |

| **[Nearmap (Thoma Bravo)](https://nearmap.com)** | High-resolution aerial orthomosaic, oblique imagery, 3D reality mesh, and AI property/infrastructure attribute SaaS covering North America, Australia, and NZ. | **~$730M Take-Private Valuation** (~$150M+ ARR; backed by Thoma Bravo) | **~$5,000 – $15,000+ / year** indicative commercial area/seat subscription | **Guided Commercial Demo** (No public self-serve free tier; sample high-res aerial imagery and custom evaluations via sales) |

| **[Mapbox](https://mapbox.com)** | Developer-first cloud location platform offering vector maps, Mapbox GL, turn-by-turn navigation, geocoding, and Isochrone APIs. | **~$1.0B–$1.2B Valuation** (~$150M+ est. ARR; backed by SoftBank/Foundry) | **Pay-as-you-go API Usage** (Mapbox GL JS web loads from **$5.00 per 1,000 loads** beyond free tier) | **Forever Free Developer Tier** (**50,000 free web map loads/month**, 25,000 mobile MAUs, and 100,000 free geocoding/directions requests/month) |

| **[Planet Insights / Sentinel Hub (Planet Labs)](https://planet.com)** | Cloud Earth-observation platform and Sentinel Hub API providing daily high-resolution satellite imagery, planetary variables, and on-the-fly spectral processing. | **~$220M+ Annual Revenue** (~$1B+ public market cap on NYSE; acquired Sinergise / Sentinel Hub) | **€25 / month** billed annually (€30/mo monthly for Sentinel Hub Exploration plan, 30,000 processing units/mo) | **30-Day Full-Access Free Trial** (Includes Sentinel Hub EO Browser, Copernicus Sentinel/Landsat APIs, and custom evalscripts; free Copernicus Data Space tier) |

| **[CARTO](https://carto.com)** | Cloud-native spatial analytics platform running directly on top of Snowflake, BigQuery, Databricks, and PostgreSQL for large-scale location intelligence. | **~$100M–$200M Est. Valuation** ($61M+ Series C led by Insight Partners) | **$199 / month** billed annually ($299/mo monthly for Starter cloud workspace) | **14-Day Full-Access Free Trial** (Full cloud spatial SQL workflows, Builder maps, and data warehouse connectors for 14 days; free student program) |

| **[Felt](https://felt.com)** | Modern, collaborative browser-native GIS and internet mapping platform featuring real-time multiplayer editing, spatial SQL, and instant data styling. | **~$50M–$100M Est. Valuation** ($34M+ VC funding led by Footwork/Bain Capital Ventures) | **$200 / month** billed annually ($240/mo monthly for Team plan, 5 editors) | **Forever Free Starter Plan** (**Unlimited maps**, up to **3 editors**, 100 MB spatial data uploads, and public map sharing) |

| **[QGIS Cloud (Sourcepole)](https://qgiscloud.com)** | Hosted cloud Web-GIS publishing service letting users publish desktop QGIS projects directly to OGC WMS/WFS web maps and PostGIS databases. | **Independent Swiss Open-Core GIS Vendor** (Sourcepole AG; core QGIS contributors) | **€65 / month** for QGIS Cloud Pro (unlimited databases, password protection, and custom domains) | **Forever Free Community Plan** (**Unlimited public web maps**, 1 PostGIS database, and **50 MB storage** free forever with QGIS Cloud branding) |

| **[Placemark](https://placemark.com)** | Fast, browser-based GeoJSON, TopoJSON, KML, and Shapefile editor and spatial data converter built for developers and data analysts (now open-source + hosted). | **Open-Source / Community Hosted** (Created by Tom MacWright; MIT open-source) | **$0 / Free Open-Source** (Self-hosted or community browser instances at zero cost) | **100% Free Forever** (Unlimited browser-based vector geometry editing, format conversion, and map styling) |



## 💻 Open-Source GitHub Projects



| Project | License / Hosting Cost | Free Tier / Self-Hosted Limit | Description |

| :--- | :--- | :--- | :--- |

| **[GeoLibre (`opengeos/GeoLibre`)](https://github.com)** | **Open-Source** ($0 open geospatial web-mapping & GIS toolkit) | **100% Free forever** (Unlimited interactive open-source web maps, spatial layers, and geospatial analysis workflows) | Open-source geospatial mapping and GIS library by OpenGeos empowering open, vendor-free interactive web mapping and spatial analysis. |
