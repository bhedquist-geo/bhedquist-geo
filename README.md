# Hi, I'm Brent 👋

**Geography Professor & GIS Educator** | GeoAI · Python · Google Earth Engine | Climate & environmental applications

## About Me

I'm a geography professor at Texas A&M University-Kingsville with 20+ years of experience in GIS, remote sensing, and climate science. I teach in our GIS certificate program and in geography and geoscience courses. Alongside that work, I'm building GeoAI skills (Python, machine learning, Google Earth Engine) to bring remote sensing foundation models and applied ML into my research and teaching.

## Resources for Modernizing Your Geospatial Stack (Python & SQL)

Free introductory resources for geospatial students and professionals moving from desktop GIS toward the modern Python and SQL stack.

**Python:** Start with **[Geospatial Python Tutorials](https://www.geopythontutorials.com/)** ([repo](https://github.com/spatialthoughts/geopython-tutorials)) from Spatial Thoughts. Each tutorial is a self-contained Google Colab notebook with datasets and, for many, a video walkthrough, covering GeoPandas, Xarray, satellite imagery, and more. They're written for learners who want to advance their skills, so if you're brand new to Python, take the free [Python Foundation for Spatial Analysis](https://spatialthoughts.com/courses/python-foundation-for-spatial-analysis/) course first. When you're ready for a full textbook, continue with **[pyGIS](https://github.com/bhedquist-geo/pyGIS)** (pinned above; [original by Michael Mann](https://github.com/mmann1123/pyGIS), [read it online](https://pygis.io)), which covers vector and raster data, remote sensing, and machine learning with GeoPandas, Rasterio, and scikit-learn. It is still under development, and it expects some Python experience.

**SQL:** **[Spatial Data Management with DuckDB](https://github.com/giswqs/duckdb-spatial)** ([book site](https://duckdb.gishub.org)) by Qiusheng Wu starts at SQL basics and builds to spatial queries, joins, and real datasets. DuckDB installs like a Python package, so there's no database server to set up, and the examples run in Colab or Binder, with a companion video playlist. It can also query cloud-hosted GeoParquet files directly, without downloading them.

**Next steps (cloud-native and big data):**

- **Cloud-native formats:** the [Cloud-Optimized Geospatial Formats Guide](https://guide.cloudnativegeo.org/) explains COG, GeoParquet, and Zarr, which let software read just the part of a file it needs over the web instead of downloading the whole thing.
- **Data too big for memory:** [Xarray Tutorial](https://tutorial.xarray.dev) for rasters and climate data, then the Dask tutorials in [Geospatial Python Tutorials](https://www.geopythontutorials.com/) for parallel processing.
- **Spatial SQL at cluster scale (awareness only):** [Apache Sedona](https://sedona.apache.org/) runs spatial SQL across clusters; see its [Spatial SQL tutorial](https://sedona.apache.org/latest/tutorial/sql/).

## Current Focus

- 🔭 **Building:** a multi-temporal El Niño climate risk pipeline. Google Earth Engine (MODIS LST, ERA5-Land soil moisture, NOAA ONI) → Cloud Storage → partitioned, clustered BigQuery tables with spatial joins. Next: matrix construction and ConvLSTM prototyping.
- 💧 **Applied focus:** ongoing research on the South Texas Sand Sheets (geomorphology and spatio-temporal change, using remote sensing and GeoAI), and Southern High Plains / Ogallala Aquifer depletion and long-term drought, using GRACE/GRACE-FO gravimetry and USGS groundwater data.
- 🌱 **Learning:** intermediate Python and SQL, BigQuery GIS, ML fundamentals, and turning Colab notebooks into modular, tested Python.
- 🧭 **Exploring:** geospatial foundation models (Prithvi, Clay), SAM/SamGeo, and Hugging Face for use in my courses and research.

## Tech Stack

**Languages & data:**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Xarray](https://img.shields.io/badge/-xarray-1F6FB2?style=flat)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat)

**Geospatial & remote sensing:**
![Google Earth Engine](https://img.shields.io/badge/-Google%20Earth%20Engine-4285F4?style=flat&logo=googleearth&logoColor=white)
![GeoPandas](https://img.shields.io/badge/-GeoPandas-139C5A?style=flat)
![rioxarray](https://img.shields.io/badge/-rioxarray-2E8B57?style=flat)
![GDAL](https://img.shields.io/badge/-GDAL%2FRasterio-5CAE58?style=flat)
![QGIS](https://img.shields.io/badge/-QGIS-589632?style=flat&logo=qgis&logoColor=white)
![ArcGIS Pro](https://img.shields.io/badge/-ArcGIS%20Pro-2C7AC3?style=flat)

**Cloud & data engineering:**
![BigQuery GIS](https://img.shields.io/badge/-BigQuery%20GIS-669DF6?style=flat&logo=googlebigquery&logoColor=white)
![Cloud Storage](https://img.shields.io/badge/-Google%20Cloud%20Storage-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Colab](https://img.shields.io/badge/-Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)
![JupyterLab](https://img.shields.io/badge/-JupyterLab-F37626?style=flat&logo=jupyter&logoColor=white)

**Dev workflow:**
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white)
![Conda](https://img.shields.io/badge/-Conda-44A833?style=flat&logo=anaconda&logoColor=white)
![pytest](https://img.shields.io/badge/-pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Claude Code](https://img.shields.io/badge/-Claude%20Code-D97757?style=flat&logo=anthropic&logoColor=white)

**Building toward:**
![Vertex AI](https://img.shields.io/badge/-Vertex%20AI-4285F4?style=flat&logo=googlecloud&logoColor=white)
![PyTorch / TorchGeo](https://img.shields.io/badge/-PyTorch%20%2F%20TorchGeo-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)

## GeoAI Resource Lists

I keep curated GitHub star lists for learning the modern geospatial data science, remote sensing, climate, and GeoAI stack. They are meant for students and professionals who want a short, vetted path through the tools instead of searching millions of repositories. Suggested order for newcomers is top to bottom:

- [education-training-resources](https://github.com/stars/bhedquist-geo/lists/education-training-resources): Start here: courses, textbooks, and tutorials for learning geospatial Python, SQL, ML, and data science.
- [geospatial-python-tools](https://github.com/stars/bhedquist-geo/lists/geospatial-python-tools): Core Python stack: GeoPandas, Shapely, Rasterio, GDAL, rioxarray, Dask, Zarr, STAC clients, and mapping widgets.
- [geospatial-sql-bigdata](https://github.com/stars/bhedquist-geo/lists/geospatial-sql-bigdata): Spatial SQL and big data: DuckDB, PostGIS, Apache Sedona, BigQuery, and cloud-scale spatial SQL tools.
- [earth-observation-rs-list](https://github.com/stars/bhedquist-geo/lists/earth-observation-rs-list): Remote sensing and Earth observation: Google Earth Engine, STAC and cloud-native tools, NASA data tutorials, and spectral indices.
- [climate-weather-data](https://github.com/stars/bhedquist-geo/lists/climate-weather-data): Climate and weather data science: Xarray, xclim, MetPy, Iris, ERA5 and CMIP tools, and tutorials.
- [geospatial-ai-ml](https://github.com/stars/bhedquist-geo/lists/geospatial-ai-ml): Machine learning for geospatial data: TorchGeo, GeoAI, segmentation, deep learning for remote sensing, and agents.
- [geoai-foundation-models-hf](https://github.com/stars/bhedquist-geo/lists/geoai-foundation-models-hf): Geospatial foundation models (Prithvi, Clay, SAM and relatives) with Hugging Face weights and fine-tuning toolkits.
- [open-source-gis](https://github.com/stars/bhedquist-geo/lists/open-source-gis): Open-source desktop and server GIS: QGIS, GRASS, GeoNode, pygeoapi, and curated awesome lists.
- [ai-ml-models](https://github.com/stars/bhedquist-geo/lists/ai-ml-models): General AI/ML model collections and curated lists.
- [ai-assisted-coding-tools](https://github.com/stars/bhedquist-geo/lists/ai-assisted-coding-tools): AI-assisted coding tools for research and teaching workflows.
- [agentic-gis-data-warehouses](https://github.com/stars/bhedquist-geo/lists/agentic-gis-data-warehouses): Agentic GIS and data-warehouse tooling.

## Research Experience

- Collaborations in geophysics, ecology, and geoscience; field research design and data collection, including UAS remote sensing, weather and climate, and environmental sensors; grant and proposal writing.

## Let's Connect

- LinkedIn: [in/brent-hedquist-94267612](https://www.linkedin.com/in/brent-hedquist-94267612)
- Hugging Face: [huggingface.co/bhedquist](https://huggingface.co/bhedquist)
- ORCID: [0000-0003-1840-8779](https://orcid.org/0000-0003-1840-8779)
