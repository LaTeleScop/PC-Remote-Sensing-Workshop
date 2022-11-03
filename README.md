# Workshop: RS data processing with Python and Microsoft's Planetary Computer
This notebook was initially made for the "Remote Sensing" module (EPF MDE, Montpellier, FR).  
Open an issue if you have any code related question (with reproductible the code snippet and error traceback).

## Startup
Clone this repository using a shell in the Planetary Computer Jupyterlab interface.  
You can connect your PC hub instance to VSCode [see the docs here](https://planetarycomputer.microsoft.com/docs/overview/ui-vscode/).  


**If you don't have a Planetary Computer account yet**  
Ask it. 
You can also create a local conda env using the provided YAML file. 
```
conda env create -f conda_env.yml
```

It should work without an account for some images, but I fear some data (16bit images) requires an API key.  


## Evaluation
Before the second session, find another area and change to analyze with index (dNBR, NDVI, NDWI, NDSI).  
Explore other datasets like Landsat that allow you to go back earlier in time (see the catalog).  
Create a notebook with commented functions for your pipeline + plots and maps to show off your results.  

Some ideas:
* wildfires
* deforestation
* coastal erosion
* floods
* snow cover
* ...

# Ressources

## Planetary Computer
[Docs](https://planetarycomputer.microsoft.com/docs/overview/about)  
[Catalog](https://planetarycomputer.microsoft.com/catalog)  

## More docs
[GDAL](https://gdal.org/)  
[Matplotlib](https://matplotlib.org/stable)  
[Numpy](https://numpy.org/doc/stable/)  
[Rasterio](https://rasterio.readthedocs.io/)  
[Leafmap](https://leafmap.org/)  
[Xarray](https://docs.xarray.dev/en/stable/)  
[Xarray-Spatial](https://xarray-spatial.org/index.html)  
[StackSTAC](https://stackstac.readthedocs.io/en/latest/)  

## DB of remote sensing index
[Index DataBase](https://www.indexdatabase.de/)  

## Communities
[Pangeo](https://pangeo.io/index.html)  
[Group on Earth Observations](https://www.earthobservations.org/)  

## Useful GitHub repositories
See topics https://github.com/topics/earth-observation and https://github.com/topics/satellite-imagery   
[GDAL cheatsheet](https://github.com/dwtkns/gdal-cheat-sheet)  
[Rasterstats](https://github.com/perrygeo/python-rasterstats)  
[SentinelSat](https://github.com/sentinelsat/sentinelsat)  
[EODAG](https://github.com/CS-SI/eodag)  
[PyTorch + Geo](https://github.com/microsoft/torchgeo)  

## Exhaustive lists of tools and datasets
https://github.com/sacridini/Awesome-Geospatial  
https://github.com/chrieke/awesome-geospatial-companies  
https://github.com/robmarkcole/satellite-image-deep-learning  
https://github.com/NRCan/geo-deep-learning  
https://github.com/Seyed-Ali-Ahmadi/Awesome_Satellite_Benchmark_Datasets  
https://github.com/DahnJ/Awesome-DEM  