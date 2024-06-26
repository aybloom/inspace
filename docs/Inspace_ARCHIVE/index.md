## InSpace Information Page

This page houses all of the instructions you will need for using the ACMT to pull measures for your dataset. 

As an InSpace partner, you will be following our detailed instructions to gather data on the social and built environment surrounding each of your participant's residential address. Once data has been gathered, you will share with us the de-identified data, allowing us to examine how built environment factors modify the effect of physical activity interventions. 

For this study, partners will be pulling data from the following datasets: 
   -  [The American Community Survey](https://www.census.gov/programs-surveys/acs/about.html)
   -  [Walkability Index](https://www.epa.gov/smartgrowth/smart-location-mapping#walkability)
   -  [CDC PLACES data](https://www.cdc.gov/places/index.html)
   -  [National Land Cover Database](https://www.usgs.gov/centers/eros/science/national-land-cover-database)
   -  [Modified Retail Food Environment Index (mRFEI)](https://www.cdc.gov/obesity/downloads/census-tract-level-state-maps-mrfei_TAG508.pdf)
   -  [Trust for Public Lands' ParkServe](https://www.tpl.org/parkserve)
   -  [Applied Geographic Solutions CrimeRisk Data](https://appliedgeographic.com/crimerisk/)
   -  [Sidewalk Score](https://journals.sagepub.com/doi/10.1177/0033354920968799)
   -  [Regional Price Parity](https://www.bea.gov/data/prices-inflation/regional-price-parities-state-and-metro-area)
   -  [Gentrification Measure](https://drexel.edu/uhc/resources/briefs/Measure-of-Gentrification-for-Use-in-Longitudinal-Public-Health-Studies-in-the-US/)


### Step 1: [Installing the Docker & Setting up the ACMT](https://aybloom.github.io/inspace/ACMT-setup-Inspace.html)

The first step in using the ACMT is to install the Docker, which creates a container on your local destop and and allows the ACMT to gather measures for your data without sending our data outside of your local machine. Once you install Docker, you will download the ACMT source code and install it. 

   * *Instructions for installing the Docker, downloading the ACMT source code can be found [HERE](https://aybloom.github.io/inspace/ACMT-setup-Inspace.html)*
      * *Follow [THIS LINK](https://youtu.be/hHCyvDOB3TY) for a video guide to setting up the ACMT*

### Step 2: [Geocoding your dataset](https://aybloom.github.io/inspace/Mapping-geocodes---Protocol.html)

If your addresses are not already gecoded to latitude and longitude, you can use the ACMT to geocode your data.
   * *To ensure the most accurate geocode locations possible, the geocoding process is an iterative process of mapping locations and cleaning addresses. This step is the most hands-on, and will require a few to several hours of work, depending on the size of your dataset. Mapping and addresses cleaning can all be done in R by following **[THESE INSTRUCTIONS](https://aybloom.github.io/inspace/Mapping-geocodes---Protocol.html)** *
   * *Use these instructions to map the geocodes and update any that have high ratings and/or look incorrect when mapped. With the final addresses, make a note of any that have high ratings, but look accurate, or have low ratings, but do not look accurate. Video instructions for this step can be found [here](https://youtu.be/3YF3F4-bLOo).*
   * 

### Step 3: Pull Measures from each dataset

The pages with instructions for each dataset and the code are linked below for you to review, as are instructional videos walking through how to pull data from each dataset. Note that while most of the datasets only have one year of data available, you will need to pull specific years of data for the ACS data, the CDC PLACES data, and the NLCD data. Each partner will be pulling data from 2015 (or centered around 2015 in the case of ACS), as well as data from the year program enrollment began for their trial. If you ave questions about what years of data to pull, feel free to reach out. 

To measures for your dataset, follow these instructions: 

   1. If you haven't already done so, download a zipped folder with all of the R files [HERE](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/aybloom/inspace/tree/main/docs/Inspace)
   2. Navigate to R in your browser, click the upload button in your files window, and upload the zipped Inspace folder that you just downloaded.
   3. Once the files are all uploaded, you should have a folder called ‘Inspace’ in your workspace in R, and in the Inspace folder is R code for each of the dataset. The HTML versions of each of these documents are also linked below.

To see the full list of dataset and variables that will be pulled from each dataset click [here](https://aybloom.github.io/inspace/InSPACE-Measures-list.html)

1. [American Community Survey Data Pull Instructions](https://aybloom.github.io/inspace/ACS-Data-Pull.html)
   * [ACS Data - VIDEO GUIDE](https://youtu.be/wYz1r26XG5A)
   * *Years of data to pull: 2017 and first year of your program's enrollment + 2 (i.e., if enrollment year was 2016, you would want to pull the 2018 data, which are estimates based on 2014-2018)*
2. [Walkability Index Data Pull Instructions](https://aybloom.github.io/inspace/epa-walkability-data-pull.html)
   * [Walkability data - VIDEO GUIDE](https://youtu.be/iY3y1hxBFQQ)
   * *Only year available is 2018.*
3. [CDC PLACES Data Pull Instructions](https://aybloom.github.io/inspace/PLACES-data-pull.html)
   * [CDC PLACES - VIDEO GUIDE](https://youtu.be/0pWVMQRp__0)
   * *Years of data to pull: only data available for 2017 and 2018. Choose the year closest to enrollment.
4. [National Land Cover Database Data Pull Instructions](https://aybloom.github.io/inspace/NLCD-data-pull.html)
   * [NLCD Data - VIDEO GUIDE](https://youtu.be/sUp2LKcmQHo)
   * *Years of data to pull: 2016, and if your year of enrollment is 2018 or later, also pull 2019 data.*
5. [Modified Retail Food Environment Index Data Pull Instructions](http://aybloom.github.io/inspace/mfrei-data-pull.html)
   * [mRFEI Data - VIDEO GUIDE](https://youtu.be/4WGegaBN_w4)
   * *Only year available is 2011.*
6. [Trust for Public Lands' ParkServe Data Pull Instructions](http://aybloom.github.io/inspace/ParkScore-data-pull.html)
   * [ParkServe Data - VIDEO GUIDE](https://youtu.be/Hqp61KTvPnE)
   * *Only year available is 2021*
7. [AGS Crime Risk Data Pull Instructions](http://aybloom.github.io/inspace/CrimeRisk-data-pull.html)
   * [Crime Risk Data - VIDEO GUIDE](https://youtu.be/ZywbGsG6vZ0)
   * *Only year available is 2022*
8. [Sidewalk Score Data Pull Instructions](http://aybloom.github.io/inspace/Sidewalk-View.html)
   * [Sidewalk Score Data - VIDEO GUIDE](https://youtu.be/tk2W6r1RjEA)
   * *Only year available is 2017*
9. [Regional Price Parity Data Pull Instructions](http://aybloom.github.io/inspace/Price-Parity-Data-Pull.html)
   * *Available for 2008 through 2020. Years to pull: 2015 and the first year of your program's enrollment*
10. [Gentrification Data Pull Instructions](http://aybloom.github.io/inspace/Gentrification-Data-Pull.html)
   * *Measures include gentrification from 1990 to 2000 and from 2000 to 2010. Both measures will be pulled (no years need to be designated)*
   * [Video Guide for Regional Price Parity & Gentrification data pulls](https://youtu.be/v5JWq0a4NYQ)

Each dataset will be separately saved. Once you have pulled the variables for each year, contact the InSpace team for instructions on sharing the de-identified data with the team. 

### Support or Contact. 

If you run into any issues along the way, don't hesitate to reach out to [Amy](mailto:aybloom@uw.edu)
