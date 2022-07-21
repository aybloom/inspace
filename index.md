## Welcome to the Inspace Repository Page
This page houses all of the instructions you will need for using the ACMT to pull measures for your dataset. 

As an InSpace partner, you will be..... 

For this study, partners will be pulling data from the following datasets: 
   -  [The American Community Survey](https://www.census.gov/programs-surveys/acs/about.html)
   -  [Walkability Index](https://www.epa.gov/smartgrowth/smart-location-mapping#walkability)
   -  [CDC PLACES data](https://www.cdc.gov/places/index.html)
   -  [National Land Cover Database](https://www.usgs.gov/centers/eros/science/national-land-cover-database)
   -  [Smart Location Database](https://www.epa.gov/smartgrowth/smart-location-mapping#SLD)
   -  [Modified Retail Food Environment Index (mRFEI)](https://www.cdc.gov/obesity/downloads/census-tract-level-state-maps-mrfei_TAG508.pdf)
   -  [Trust for Public Lands' ParkServe](https://www.tpl.org/parkserve)
   -  [Applied Geographic Solutions CrimeRisk Data](https://appliedgeographic.com/crimerisk/)
   -  [Sidewalk Score](https://journals.sagepub.com/doi/10.1177/0033354920968799)


### Installing the Docker

The first step in using the ACMT is to install the Docker, which creates a container on your local destop and and allows the ACMT to gather measures for your data without sending our data outside of your local machine. 

Instructions for installing the Docker can be found [here](link to Docker install setup)


### Geocoding your dataset

Geocode your dataset: If your addresses are not already gecoded to latitude and longitude, you can use the ACMT to do this step! The ACMT Geocoder instructions are [here](link to geocoding vignette)

``` Markdown



### Structure your dataset for pulling variables

To ensure the code for pulling the variables will run accurately with your data, your data should be formatted as follows: 

| id  |  lat      | long        | 
|-----|-----------|-------------|
| 01  | 47.568922 | -122.306422 |
| 02  | 47.632264 | -122.314978 |
| 03  | 47.634820 | -122.292769 |
| ..  | ......... | ........... |

Ensure your dataset is named 'inspace_dataset', save it in your workspace, and you are ready to start pulling measures!

### Run each step of code 


### Support or Contact

