---
title: "Key data"
tags:
  - data/nonhuman
---

Data for the City of Port Phillip council area and the State Government of Victoria will be the most relevant for Fishermans Bend.
## Data relevant to non-human design
- Location of trees
	- Important to identify shelter, habitats, and connectivity between green spaces.
	- [Fishermans Bend Trees dataset](https://digitaltwin.vic.gov.au/portals/44/map/?share=f6b495e2-b1d8-4df3-98d7-b821e2965a5c)
- Proximity to water bodies, existing and planned green spaces, and transit corridors
	- Can generally be derived from [OpenStreetMap](https://www.openstreetmap.org/) with reasonable confidence urban areas
	- More granular and accurate data can be obtained from relevant government organisations via Digital Twin Victoria and Data Vic
		- [City of Port Phillip Tree Canopy dataset](https://digitaltwin.vic.gov.au/portals/44/map/?share=0305f9ee-1efe-42dd-b7e8-b1c39b4fd44f)
		- [City of Port Phillip Council Park sites](https://digitaltwin.vic.gov.au/portals/44/map/?share=697a199d-c273-4714-bb93-a24cc125e9fe) and [Community Gardens](https://digitaltwin.vic.gov.au/portals/44/map/?share=54240a25-83e1-48b5-892d-1f982b7b6f8b)
- Measures of species population
	- Interventions should target areas with established populations of target species.
	- Occurrence sightings are a reasonable proxy of local species population and distribution.
		- Available via [Atlas of Living Australia](https://www.ala.org.au/) and [Victorian Biodiversity Atlas](https://vba.biodiversity.vic.gov.au/vba/#/)
	- The [Clean Air and Urban Landscapes Hub](https://nespurban.edu.au/platforms/threatened-species-map/) manage a dataset of observations of threatened species in urban areas.
- Measures of local biodiversity
	- Species richness is a standard measure of biodiversity for an area. Typically, these measures are not available at high resolutions.
	- [CSIRO provides an Australia-wide dataset estimating species richness for birds, reptiles, and fungi](https://data.csiro.au/collection/csiro:55986?_st=browse&_str=3&_si=1&browseType=kw&browseValue=species%20richness).
	- The [[../Resources/Fishermans Bend#Fishermans Bend Urban Ecology Strategy Biodiversity Report (2019)|Biodiversity Report]] does not estimate species richness or biodiversity measures, but instead focuses on supporting existing target species.
- Presence of colours and other sensory data in the environment
	- Non-human species do not interpret their environment the same way as humans. For example, many species [perceive a wider colour spectra](https://www.smithsonianmag.com/smart-news/see-the-world-through-the-eyes-of-animals-with-these-stunning-new-videos-180983647/) than humans.
	- Some species associate particular colours with threats, prospective mates, or as a method of spotting each other. For example, a group of researchers argue that [[../Stakeholders/Superb fairywren|fairy-wrens]] have evolved plumage colouration that they can easily perceive but birds of prey cannot.[^1]
- Exposure to pollution
	- [Fishermans Bend groundwater studies 2015–2017](https://discover.data.vic.gov.au/dataset/fishermans-bend-groundwater-studies-2015-2017) assess the pollution of water bodies.
- Exposure to noise and human activity, e.g., traffic, construction activity
	- The majority of non-human species prefer habitats that are removed from busy pedestrian and transit corridors. 
	- Transit corridors also pose a risk to species crossing them and disrupt habitat connectivity.
	- Proximity to traffic corridors are a reasonable predictor, but local governments increasingly provide sensor data about traffic speed and volume
		- [City of Port Philip transport data for bikes, pedestrians, and traffic](https://www.data.gov.au/data/dataset/transport)
## Data about non-human species

- Atlas of Living Australia contains geolocated occurence records and species information.
- iNaturalist provides crowd sourced images, identification, and audio files for species globally.

## Platforms

3D buildings and topography are available for Fishermans Bend and Port Melbourne via the[ Digital Twin Victoria platform](https://digitaltwin.vic.gov.au/).

Other datasets relating to Fishermans Bend are available on the [data.gov.au platform](https://www.data.gov.au/data/dataset?_organization_limit=0&organization=city-of-port-phillip&_groups_limit=0) courtesy of the City of Port Phillip.

[Data Vic](https://www.data.vic.gov.au/) provides open access to a range of data for Victoria. Most geospatial data is also available via Digital Twin Victoria.

[OpenStreetMap](https://www.openstreetmap.org/) is an open access geographic database. Data can be downloaded and interpreted using GIS software like [QGIS](https://www.qgis.org/).

[Terrestrial Ecosystem Research Infrastructure (TERN)](https://www.tern.org.au/) provides data about ecosystems and biodiversity for Australia.

[CSIRO](https://data.csiro.au) provides open-access geospatial data sets about biodiversity, ecology, and ecosystems. These are often for specific locations and research projects.

The [Atlas of Living Australia](https://www.ala.org.au/) contains occurrence records for 5,820 species. For example, you can search for the [[../Stakeholders/Superb fairywren|Superb fairywren]] to access a [dataset of sightings](https://bie.ala.org.au/species/https://biodiversity.org.au/afd/taxa/ae56080e-4e73-457d-93a1-0be6a1d50f34) and information about the species.

The [Victorian Biodiversity Atlas](https://vba.biodiversity.vic.gov.au/vba/#/) also provides occurrence records for Victoria, but these are incorporated into ALA.

[iNaturalist](https://www.inaturalist.org/) is a global citizen science database where users can upload geotagged images and sounds using a phone application that identifies the species automatically.

[City Nature Challenge](https://www.citynaturechallenge.org/) is a global citizen science project where volunteers upload observations to iNaturalist. See the [outcomes for Greater Melbourne](https://inaturalist.ala.org.au/projects/city-nature-challenge-2024-greater-melbourne).
## Types of data
- 3D scans: documents the structure of physical reality, e.g., LIDAR, STL, point clouds.
- Geospatial data: describes and position objects in physical space in relation to a coordinate system, e.g., cadastral maps, location of trees, transit networks, animal sightings, etc.
	- OpenStreetMap
	- Digital Twin Victoria
	- Australian Living Atlas
- Sensor data: in situ measurements of values using sensors, e.g., noise levels, light levels, movement tracking.
	- Arduino sensors
	- Specialist equipment, e.g., light meters
	- Consumer monitoring devices like cameras
- Statistical values: estimates for a specific geographical region based on an average of observations, e.g., a local government area or Federal electorate; useful for design and planning, but not always accurate. For example, solar exposure, rainfall, average number of cars per person.
	- AURIN
	- Australian Bureau of Statistics

[^1]: Anders Ödeen et al., “Multiple Shifts Between Violet and Ultraviolet Vision in a Family of Passerine Birds with Associated Changes in Plumage Coloration,” _Proceedings of the Royal Society B: Biological Sciences_ 279, no. 1732 (2012): 1269–76, [https://doi.org/10.1098/rspb.2011.1777](https://doi.org/10.1098/rspb.2011.1777).