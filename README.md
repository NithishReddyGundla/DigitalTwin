# DigitalTwin
### Built a city-scale digital twin of Bexar County, Texas. 
### The digital twin is a geo-physically accurate virtual representation of the real world and is composed of several layers that individually represent buildings, vegetation, roads and highways, and infrastructures (e.g., power transmission lines).

## Analysis
### In-depth analysis done in ArcGIS Pro
![](Images/Img1.png)
![](Images/Img2.png)
![](Images/Img3.png)
![](Images/Img4.png)
![](Images/Img5.png)
![](Images/Img6.png)
![](Images/Img7.png)
![](Images/Img8.png)

### Performed complex street network analysis using OpenStreetMaps and OSMNx
### Extracted geospatial data from OpenStreetMap, modeling and analysis of real-time street networks is done using OSMnx (an open-source Python library use to work with street network data from OpenStreetMap).

![](Images/Img12.png)
![](Images/Img13.png)
![](Images/Img14.png)
![](Images/Img15.png)

## Challenges
### Addressed and resolved overlapping issues of geo-referenced roads and buildings in CityEngine where the data consists of 200K+ 3D objects.
### Initially, default get map data functionality was used in CityEngine to get the base map for 3D models generation where we had misalignment issues. Then, we used only the OpenStreetMap data to generate 3D models for streets and the results are pretty accurate, but we still have few misalignment of roads at the overlays (highway(s) on top of roads(s)).

![](Images/Img16.png)
![](Images/Img17.png)

## Data integration into CityEngine
### After the overlapping issues of geo-referenced roads and buildings is resolved then the data is imported into CityEngine. This is the complex data which consists of 200K+ 3D objects.

## Data integration into NVIDIA OMNIVERSE
### To perform real-time 3D physics simulations and virtual inspection capabilities, the twin was simulated in NVIDIA Omniverse and integrated with VR & AR tech (Meta’s Oculus Quest 2, Microsoft’s Hololens) for visualization and teleporting of grid engineers. * * 

*NVIDIA said this is the largest project in Universal Scene Description (USD) format within Omniverse till date.

![](Images/Img10.png)
![](Images/Img11.png)

### Also integrated Microsoft's AirSim (with Unity plugin) to test and train autonomous systems (tested on drone) in a safe and controlled environment (Digital Twin).

## Work in progress
### Developing an optimization model that aims to incentivize the time and location of electric vehicle charging stations, taking into account the data of existing EV charging stations, parking lots, population density, as well as businesses such as H-E-B, Walmart, UPS, Amazon, and many others in Bexar County, Texas, that operate fleet vehicles on a daily basis.
![](Images/Img18.png)
