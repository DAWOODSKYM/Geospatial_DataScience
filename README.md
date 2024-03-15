# Satelite data Classification in Google Earth engine
This repo contains javascript code used via the Js Api in Google Earth engine to perform a Random forest calssificaton on landsat satellite images
The code utilizes Google earth engines own archive of landsat images croped to our region on interest using a shapefile.
# Problem Statement
1. [Determination of various land use land cover of our study area using Landsat data at 30m spatial resolution](https://github.com/DAWOODSKYM/GEE/blob/f480b3849ce462a0015ae48d725446a6d473a98b/Random%20Forest%20Supervised%20claassification)
2. [Perform a tassled cap transformation on satlellite data to analyze and map vegetation and urban development changes in our AOI](https://github.com/DAWOODSKYM/GEE/blob/f480b3849ce462a0015ae48d725446a6d473a98b/Tasseled%20Cap)
3. [Assesment of drought using Vegetation health Index (VHI) drought indices](https://github.com/DAWOODSKYM/GEE/blob/f480b3849ce462a0015ae48d725446a6d473a98b/Drought) 

# Methodology
> -LULC Classification is the process of appointing land cover classes to pixels and categorize them. For instance, water, metropolitan, woodland, horticulture, buildings, woodlands, agriculture, grasslands, mountains, and highlands
   - load the satellite data
  - Prepare LULC training data
  - train a Random Forest Classifier on this data
  - RF model classifies the Satellite image
  - Assess the accuracy of the classified map
> -The basic idea of tasseled cap transformation is compressing spectral data into a few bands associated with physical scene characteristics. Principal component analysis is frequently used to evaluate the data dimensionality.
  - Load the satellite data
  - Perform Tassled cap transformation
  - Viz and exportation
 > - The Vegetation Health Index (VHI) provides an indication of drought severity by assessing vegetation health and the impact of temperature on plant conditions. VHI integrates both the Vegetation Condition Index (VCI) and the Temperature Condition Index (TCI).
   - Load MODIS data
   - Scale the data
   - Calculate VHI
   - Visualize the data

