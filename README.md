# Hi, I'm Hasan 👋

**I build physics-aware machine learning models for floods and storm surge.**

I'm a PhD student in Civil and Environmental Engineering at the University of Louisville, working on
**differentiable hydrology**: models that couple neural networks with process-based equations and learn
from data end to end, so they stay physically interpretable while gaining the accuracy of deep learning.
Before my PhD I built high-resolution **Delft3D storm surge models** for the Bay of Bengal coast at IWFM, BUET.

The thread through both: keep the physics, make it learnable, make it fast enough for early warning.

---

### Differentiable and ML hydrology (PhD)

**Differentiable parameter learning.** Neural networks that learn the parameters of conceptual hydrologic
models from basin attributes and forcing, trained through the model with automatic differentiation.

**Stream temperature and routing.** Differentiable stream temperature modeling coupled with river routing
through basin networks.

**Deep learning for streamflow.** LSTM and attention-based models on large-sample datasets (CAMELS),
evaluated across basins with NSE and KGE.

### Coastal hazard modeling (before PhD)

**Storm surge.** Delft3D-FLOW for cyclone surge in data-scarce tidal estuaries: bathymetry and DEM integration,
multi-domain decomposition with nested grids, tidal boundary calibration against coastal gauges, and wind-drag
formulations for extreme cyclone forcing.

**Forcing and observations.** Gauge rainfall pipelines for model forcing, extreme water levels from tide gauges,
and flood mapping from Sentinel-1 SAR.

### Where they meet

Physics-aware ML surrogates for storm surge and compound flooding: fast enough for operational warning,
constrained by the hydrodynamics.

---

### Public projects

Most of my PhD code lives in private lab repositories. These are public:

| Project | What it does |
| --- | --- |
| [coastal-extremes-gev](https://github.com/hrahmanwave/coastal-extremes-gev) | Extreme water levels from tide gauges: GEV/GPD fits and return levels |
| [sentinel1-flood-py](https://github.com/hrahmanwave/sentinel1-flood-py) | Flood mapping from Sentinel-1 SAR with Google Earth Engine, in Python |
| [delft3d-dd-boundary-enforcer](https://github.com/hrahmanwave/delft3d-dd-boundary-enforcer) | Consistent bathymetry across Delft3D domain decomposition boundaries |
| [bmd-rainfall-processing](https://github.com/hrahmanwave/bmd-rainfall-processing) | Gauge rainfall to hydrodynamic model forcing (Thiessen polygons + temporal disaggregation) |
| [cyclone-tracks-arcpy](https://github.com/hrahmanwave/cyclone-tracks-arcpy) | Cyclone track polylines from best-track lat–lon data with ArcPy |
| [us-weather-explorer](https://github.com/hrahmanwave/us-weather-explorer) | Live forecast maps and automatic highlights from ECMWF Open Data ([open the page](https://hrahmanwave.github.io/us-weather-explorer/)) |

### Methods and tools

**Methods:** differentiable modeling, LSTM and attention models, physics-based hydrodynamic modeling,
extreme value analysis, SAR change detection

**Tools:** `PyTorch` `Python` `xarray` `Delft3D` `Google Earth Engine` `ArcGIS / ArcPy` `MATLAB` `LaTeX`

### Publications

See [Google Scholar](https://scholar.google.com/citations?user=Kc736lkAAAAJ&hl).

### Get in touch

Happy to talk about differentiable modeling, storm surge, and ML for flood hazards.

[![Website](https://img.shields.io/badge/Website-4285F4?style=flat&logo=googlechrome&logoColor=white)](https://sites.google.com/view/rahmanhasanur/home)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=Kc736lkAAAAJ&hl)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Md-Rahman-1059)
