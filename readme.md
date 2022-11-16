# Awesome Volcano Resources 🌋

<p align="center">
    <em>Volcano research ranging from fundamental processes to impacts of eruptions.</em>
</p>
<p align="center">
<a href="https://github.com/sindresorhus/awesome" target="_blank">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome">
</a>
</p>

--- 


## Table of content

- [Table of content](#table-of-content)
- [Codes](#codes)
  - [Deposit characterisation](#deposit-characterisation)
  - [Eruption history & analogues](#eruption-history--analogues)
  - [Exposure & impact assessment](#exposure--impact-assessment)
  - [Hazard assessment](#hazard-assessment)
    - [Lava flow inundation](#lava-flow-inundation)
    - [Lahars & PDCs inundation](#lahars--pdcs-inundation)
    - [Tephra dispersal and fallout](#tephra-dispersal-and-fallout)
  - [Miscellaneous tools](#miscellaneous-tools)
- [Databases](#databases)
  - [Eruptive history](#eruptive-history)
  - [Eruption source parameters](#eruption-source-parameters)
  - [Impacts](#impacts)
  - [Monitoring](#monitoring)
  - [Miscellaneous](#miscellaneous)
- [Web-based platforms](#web-based-platforms)
  - [Monitoring](#monitoring-1)
- [Contribute](#contribute)


---

## Codes 

### Deposit characterisation

- [AshCalc](https://github.com/MatthewDaggitt/AshCalc) - Calculation of the volume of tephra deposits in Python ([reference](https://appliedvolc.biomedcentral.com/articles/10.1186/2191-5040-3-7)).
- [CareySparks86_Matlab](https://github.com/e5k/CareySparks86_Matlab) - Matlab implementation of the Carey and Sparks (1986) model to estimate plume height from isopleth data ([reference](https://link.springer.com/article/10.1007/BF01046546)).
- [Tephra2 inversion](https://github.com/geoscience-community-codes/tephra2-inversion) - Tephra2 inversion method written in C with some [post-processing tools](https://github.com/e5k/Tephra2Utils) in Matlab ([reference](https://pubs.geoscienceworld.org/gsl/books/book/1732/chapter/107601115/Inversion-is-the-key-to-dispersionunderstanding)).
- [TephraFits](https://github.com/e5k/TephraFits) - Matlab function to estimate the volume of and characterise tephra deposits from field-based methods ([reference](https://link.springer.com/article/10.1186/s13617-018-0081-1)).
- [TOTGS](https://github.com/e5k/TOTGS) - Calculation of the total grain-size distribution of tephra deposits using the VORONOI method in Matlab ([reference](https://link.springer.com/article/10.1007/s00445-004-0386-2)).

### Eruption history & analogues

- [PyVOLCANS](https://github.com/BritishGeologicalSurvey/pyvolcans) - Python library to explore similarity between volcanic systems ([reference](https://link.springer.com/article/10.1007/s00445-019-1336-3)).

### Exposure & impact assessment 

- [RNDS](https://github.com/vharg/RNDS/) - Method to integrate road criticality into road disruption assessments ([reference](https://appliedvolc.biomedcentral.com/articles/10.1186/s13617-022-00118-x)).
- [VolcGIS](https://github.com/vharg/VolcGIS) - Python framework for exposure analyses ([reference](https://nhess.copernicus.org/articles/22/1233/2022/)).

### Hazard assessment

#### Lava flow inundation 

- [Molasses](https://github.com/geoscience-community-codes/MOLASSES) - Lava flow inundation model written in C ([reference](https://link.springer.com/article/10.1186/2191-5040-1-3)).
- [MrLavaLoba](https://github.com/demichie/MrLavaLoba) - Stochastic model for stochastic for pahōehoe lava flow inundation written in Python ([reference](https://www.sciencedirect.com/science/article/abs/pii/S0377027317303876)).
- [PyFlowGo](https://github.com/pyflowgo/pyflowgo) - Python version of FLOWGO for lava flow inundation ([reference](https://www.sciencedirect.com/science/article/pii/S0098300417306738)).
- [Q-LavHA](https://we.vub.ac.be/en/q-lavha) - Probabilistic hazard assessment for lava inundation in QGis ([reference](https://www.sciencedirect.com/science/article/pii/S0098300416303715)).
  
#### Lahars & PDCs inundation

- [ECMapProb](https://github.com/AlvaroAravena/ECMapProb) - Probability maps of PDC inundation using a modified energy cone model approach ([reference](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2019JB019271)).
- [LaharFlow](https://www.laharflow.bristol.ac.uk) - Model of lahar dynamics on evolving topography. Only as a web interface.
- [LaharZ](https://pubs.usgs.gov/of/2014/1073/) - Statistical model to estimate lahar inundation. Requires ArcGIS ([reference](https://pubs.usgs.gov/of/2014/1073/pdf/ofr2014-1073.pdf)).

#### Tephra dispersal and fallout

- [Ash3D](https://vsc-ash.wr.usgs.gov/ash3d-gui/#!/) - Online 3D ash dispersal model ([reference](http://onlinelibrary.wiley.com/doi/10.1029/2011JB008968/abstract)).
- [Fall3d](https://gitlab.com/fall3d-distribution) - 3D atmospheric tephra dispersal ([reference](https://gmd.copernicus.org/articles/13/1431/2020/)).
- [GBF](https://github.com/unigeSPC/gbf) - Probabilistic hazard assessment for ballistic impacts written in Matlab ([post processing](https://github.com/e5k/GBF-Post-Processing)) ([reference](https://www.sciencedirect.com/science/article/pii/S0377027316301317)).
- [Hysplit](https://www.ready.noaa.gov/READYVolcAsh.php) - Online based version of Hysplit for volcanic ash ([reference](https://www.arl.noaa.gov/hysplit/hysplit-references/)).
- [LagTrack](https://github.com/e5k/LagTrack) - Particle tracking tool written in Matlab ([reference](https://www.sciencedirect.com/science/article/abs/pii/S0012821X21002399)).
- [Tephra2](https://github.com/geoscience-community-codes/tephra2) - 2D model for ground tephra accumulation written in C with some [additional functions](https://github.com/e5k/Tephra2Utils) in Matlab ([reference](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2003JB002896)).
- [TephraProb](https://github.com/e5k/TephraProb) - Probabilistic hazard assessment for tephra fallout written in Matlab ([reference](https://appliedvolc.biomedcentral.com/articles/10.1186/s13617-016-0050-5)).

### Miscellaneous tools

- [CDSAPItools](https://github.com/e5k/CDSAPItools) - Python functions to download wind and atmospheric data from ERA5 formatted to work with different models (e.g., [TephraProb](https://github.com/e5k/TephraProb), [Fall3d](https://gitlab.com/fall3d-distribution)).
- [TopoToolbox](https://github.com/wschwanghart/topotoolbox) - Matlab library for terrain analyses ([reference](https://esurf.copernicus.org/articles/2/1/2014/)).

## Databases

### Eruptive history

- [Active Volcanoes of Japan](https://gbank.gsj.jp/volcano/Act_Vol/index.html) - Database of active volcanoes by the [Geological Survey of Japan](https://www.gsj.jp/en/). Also contains the [Quaternary Volcanoes of Japan](https://gbank.gsj.jp/volcano/Quat_Vol/index_e.html) database ([reference](https://researchmap.jp/read0139229/presentations/35736250)).
- [LaMEVE](https://www2.bgs.ac.uk/vogripa/searchVOGRIPA.cfc?method=searchForm) - Database of large magnitude explosive eruptions ([reference](https://appliedvolc.biomedcentral.com/articles/10.1186/2191-5040-1-4)).
- [Volcanoes of the World](https://volcano.si.edu) - Catalogue of Holocene and Pleistocene volcanoes and eruptions from the past 12,000 years ([reference](https://www.ucpress.edu/book/9780520268777/volcanoes-of-the-world)).

### Eruption source parameters

- [CCDB](http://gvb-csic.es/CCDB/) - Caldera collapse database ([reference](https://www.sciencedirect.com/science/article/pii/S0377027308001182)).
- [IVESPA](http://www.ivespa.co.uk) - Archive of published volcano eruption information relevant for constraining eruption source parameters ([reference](https://www.sciencedirect.com/science/article/pii/S0377027321001244?via%3Dihub)).

### Impacts 

- [EIVE](https://data.cerdi.uca.fr/erup-vol/) - Database on the economic impacts of volcanic eruptions ([reference](https://hal-emse.ccsd.cnrs.fr/MSHC/hal-03518989v1)).

### Monitoring

- [WOVOdat](https://www.wovodat.org) - Database on volcanic unrest from the World Organization of Volcano Observatories ([reference](https://www.sciencedirect.com/science/article/pii/S0377027317302718)).

### Miscellaneous

- [List of volcano observatories](https://wovo.iavceivolcano.org/observatories) from [WOVO](https://wovo.iavceivolcano.org). Includes an [interactive map](https://wovo.iavceivolcano.org/component/wrapper/?Itemid=110).

## Web-based platforms
  
### Monitoring

- [HOTVOLC](https://hotvolc.opgc.fr/www/index.php) - Web-based monitoring system for volcanic hot spots using geostationary satellite data ([reference](https://www.lyellcollection.org/doi/abs/10.1144/sp426.31)).
- [MIROVA](https://www.mirovaweb.it) - Near real time volcanic hotspot detection system based on mid-IR MODIS observations ([reference](https://www.frontiersin.org/articles/10.3389/feart.2019.00362/full)).
- [MOUNTS](http://www.mounts-project.com/home) - Sentinel-based automated volcano monitoring system providing data on gas emission, thermal anomaly and deformation ([reference](https://www.mdpi.com/2072-4292/11/13/1528)).

## Contribute

Follow the [contribution guidelines](https://github.com/CERG-C/awesome-volcano/blob/main/contributing.md).