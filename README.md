# UC Berkeley MIDS Capstone Project
Capstone project Team: Diana Chacon, Sudhrity Mondal, Carlos Ortiz-Gomez, Jorge Dayer, Vaishali Khandelwal, Hassan Saad, Sam Temlock

The Southwest United States is in a massive state of drought, [40 -60% of residential water use is dedicated to landscape irrigation](https://ucanr.edu/sites/UrbanHort/Water_Use_of_Turfgrass_and_Landscape_Plant_Materials/Drought_and_Landscape_Water_Use_-_Some_Persspective/#:~:text=Lawns%2C%20which%20have%20been%20especially,annual%20residential%20water%20consumption%20statewide.)

In this project, we are attempting to quantify lawn square footage in Los Angeles county, and to correlate these findings with:
* Aggregate socioeconomic factors within certain districts and communities
* The availability of landscape-conversion subsidies and rebates from the CA government
* Negative impacts that landscape changes might have on microclimates

We hope that our findings will help us paint a better picture of our progress in combating the drought as well as what work remains to be done (e.g. policy changes related to more subsidies, stricter water use regulations, etc.).

We are utilizing two different tools:
1. Google Earth Engine, which provides us with data in the form of raster files capturing R,G,B and near-infrared bands on a square meter level throughout Los Angeles county.
2. Google Maps API, which will provide us with .png image data and will be conducive to building a user-friendly web application.
