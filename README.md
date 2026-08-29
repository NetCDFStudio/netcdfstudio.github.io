# NetCDF Studio

### Explore. Visualize. Understand Scientific Data.

**NetCDF Studio** is a cross-platform scientific desktop application for exploring, visualizing, and analyzing **NetCDF and multidimensional scientific datasets** through an intuitive graphical interface.

Built with **Python and PySide6 (Qt 6)**, NetCDF Studio aims to bring powerful scientific-data workflows into a single, accessible desktop environment.

---

## 🌐 Website

**Official Website:**
https://netcdfstudio.github.io/

**Main Project:**
https://github.com/NetCDFStudio

---

## 🔬 About NetCDF Studio

Scientific datasets often contain multiple dimensions such as:

```text
time × level × latitude × longitude
```

Working with these datasets can require programming, command-line tools, or several specialized applications.

**NetCDF Studio** aims to simplify this workflow by providing a unified graphical environment where users can:

* Open and explore NetCDF datasets
* Inspect variables, dimensions, coordinates, and metadata
* Slice and subset multidimensional data
* Create scientific visualizations
* Explore spatial and temporal patterns
* Perform scientific data analysis
* Produce publication-quality figures
* Export processed data and visualizations

The project is designed for researchers, students, educators, and scientists working with multidimensional scientific data.

---

## 🚀 Vision

Our vision is to develop NetCDF Studio into a comprehensive scientific-data workspace that connects:

```text
Scientific Data
      │
      ▼
Dataset Exploration
      │
      ▼
Data Selection & Processing
      │
      ▼
Visualization
      │
      ▼
Scientific Analysis
      │
      ▼
Publication-Ready Results
```

The long-term goal is to make scientific data analysis more **visual, accessible, reproducible, and efficient**.

---

## ✨ Key Features

### 📂 Dataset Explorer

Explore the internal structure of scientific datasets:

* Dimensions
* Variables
* Coordinates
* Attributes
* Data types
* Shapes
* Units
* Metadata

### 📊 Scientific Visualization

Create scientific plots directly from NetCDF data:

* Line plots
* Time-series plots
* Heatmaps
* Contour plots
* Filled contour plots
* Scatter plots
* Profiles
* Vector-field visualization

### 🌍 Geographic Visualization

Visualize spatial datasets using geographic maps and scientific projections.

Planned capabilities include:

* Latitude–longitude maps
* Map projections
* Coastlines
* Country boundaries
* Geographic subsetting
* Shapefile overlays
* GeoJSON layers
* Raster-data visualization

### ⏱️ Multidimensional Data

Work with datasets containing dimensions such as:

```text
time
latitude
longitude
level
pressure
depth
height
```

Select and visualize individual slices or regions through the graphical interface.

### 📈 Scientific Analysis

Planned analysis tools include:

* Descriptive statistics
* Temporal analysis
* Spatial analysis
* Correlation
* Regression
* Anomaly analysis
* Derived variables

### 🖼️ Publication-Quality Output

Export scientific figures in formats such as:

```text
PNG
JPEG
TIFF
SVG
PDF
```

with control over resolution, dimensions, labels, color scales, and other figure properties.

---

## 🖥️ Cross-Platform

NetCDF Studio is designed as a **multiplatform desktop application**.

```text
              NetCDF Studio
                    │
       ┌────────────┼────────────┐
       │            │            │
    Windows       Linux        macOS
       │            │            │
      .exe       AppImage       .app
```

The application is built using **PySide6 and Qt 6**, allowing a common codebase to support major desktop platforms.

---

## 🧪 Technology

NetCDF Studio is built around the Python scientific-computing ecosystem.

| Technology | Purpose                  |
| ---------- | ------------------------ |
| Python     | Core development         |
| PySide6    | Desktop GUI              |
| Qt 6       | Cross-platform framework |
| xarray     | Multidimensional data    |
| netCDF4    | NetCDF access            |
| h5netcdf   | HDF5/NetCDF support      |
| NumPy      | Numerical computing      |
| SciPy      | Scientific computing     |
| Matplotlib | Scientific visualization |
| Cartopy    | Geographic visualization |
| Dask       | Large dataset processing |
| GeoPandas  | Geospatial analysis      |

---

## 🛠️ Development Status

**NetCDF Studio is currently under active development.**

### Phase 1 — MVP

* [x] NetCDF dataset loading
* [x] Dataset exploration
* [x] Variable inspection
* [x] Dimension inspection
* [x] Coordinate inspection
* [x] Metadata inspection
* [x] Initial plotting interface

### Phase 2 — Scientific Visualization

* [ ] Advanced dimension slicing
* [ ] Line plots
* [ ] Heatmaps
* [ ] Contour plots
* [ ] Filled contours
* [ ] Interactive time controls
* [ ] Scientific color scaling
* [ ] Publication-quality export

### Phase 3 — Geographic & GIS

* [ ] Geographic maps
* [ ] Map projections
* [ ] Shapefile support
* [ ] GeoJSON support
* [ ] Raster overlays
* [ ] Vector visualization

### Phase 4 — Scientific Analysis

* [ ] Statistical analysis
* [ ] Temporal analysis
* [ ] Spatial analysis
* [ ] Correlation
* [ ] Regression
* [ ] Anomaly analysis

### Phase 5 — Advanced Data Processing

* [ ] Dask integration
* [ ] Lazy computation
* [ ] Multi-file datasets
* [ ] Large-data optimization
* [ ] Data transformation
* [ ] NetCDF export

---

## 🎯 Designed For

NetCDF Studio is intended for users working in fields such as:

* Atmospheric science
* Climate science
* Meteorology
* Oceanography
* Geophysics
* Environmental science
* Earth science
* Hydrology
* Remote sensing
* GIS
* Scientific computing

---

## 🤝 Open Source & Collaboration

NetCDF Studio is being developed as an open scientific-software project.

We welcome contributions involving:

* Python development
* PySide6/Qt development
* Scientific visualization
* NetCDF/xarray workflows
* GIS
* Data analysis
* UI/UX design
* Documentation
* Testing
* Performance optimization

Visit the **NetCDF Studio GitHub organization** to explore the project's repositories and development work.

---

## 📚 Project Ecosystem

The NetCDF Studio project is organized around several components:

```text
NetCDFStudio
│
├── Application
│   └── NetCDF Studio
│
├── Documentation
│
├── Website
│   └── netcdfstudio.github.io
│
├── Examples
│
└── Development Tools
```

---

## 🌟 Why NetCDF Studio?

NetCDF Studio aims to bridge the gap between:

```text
Command-Line Scientific Tools
              │
              │
              ▼
       NetCDF Studio
              │
              ▼
     Interactive GUI
              │
              ▼
      Scientific Analysis
```

Instead of requiring users to write code for every basic exploration task, NetCDF Studio provides a visual workflow while retaining the power and flexibility of the Python scientific ecosystem.

---

## 📄 License

The project's license and individual repository licensing information will be provided as development progresses.

---

## 📬 Contact & Community

**GitHub Organization:**
https://github.com/NetCDFStudio

**Website:**
https://netcdfstudio.github.io/

---

# NetCDF Studio

> **A modern scientific workspace for exploring, visualizing, and understanding multidimensional data.**
