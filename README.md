# Opening an Ice Cream Business in Seattle - Analysis
Using k-means clustering and other analysis techniques, to suggest the best neighbourhood to open an Ice Cream business in Seattle, Washington, USA.

## 1. Introduction
### 1.1 Background
Seattle is not only the largest city in the state of Washington, but it is also the largest city in the Pacific Northwestern region of North America. Many of us know Seattle for its rainy weather and tech giants, being as it’s the birthplace of companies such as Microsoft and Amazon, to name a few. Thanks to its tech scene, Seattle is now one of the fastest growing major cities in the United States. Any savvy entrepreneur would consider business possibilities in this thriving city, and for me, that means opening my dream ice cream business. Catering to Seattle’s outdoorsy population and for my love of ice cream, I was tempted to explore the possibility of opening an ice cream business in this city. [1]

### 1.2 Business Problem
The audience for this analysis is any business owner trying to figure out where to open an ice cream shop or ice cream truck, given they want to be situated in a populous area and in an area where the general population is young and outdoorsy, in the city of Seattle, Washington, USA.

## 2. Data
Based on the business problem discussed earlier, factors that will be affecting the recommendation are:

* A populous area
* Young and Outdoorsy Inhabitants

Having said that, I needed to keep these 2 factors in mind when recommending the best possible neighbourhood for an ice cream business to be opened.

### 2.1 Neighbourhood Data
Neighbourhood Data for Seattle, Washington was imported from US CENSUS. This data is obtained from seattle.gov (US census) website [2]. This data set includes data on population, housing, and ethnicity information for each neighbourhood. Total number of neighbourhoods provided were 53. The data was presented in a CSV format, since the dataset was not too big, I chose to remove unwanted headers, footers and columns within the CSV file using Excel. Later high-level data cleaning was carried out in Python. [a link](https://github.com/ShaheerKhan200/Ice-Cream-Business-in-Seattle---Analysis/blob/master/Seattle%20Project%20Data%20Census.csv)

### 2.2. Location Data
The location data is provided by Foursquare API. The Foursquare API was used to gather the data regarding most common venues for each respective neighbourhood using the explore function of the Foursquare API. This is discussed in more detail later in the Methodology section.

### 2.3. Coordinates Data
The coordinates data for each respective neighbourhood was obtained using Geopy and Geocoder packages. 

## References
[1] Wikipedia Contributors, “Seattle,” Wikipedia, 27-Aug-2020. [Online]. Available: https://en.wikipedia.org/wiki/Seattle. [Accessed: 27-Aug-2020]

[2] “About Seattle - OPCD | seattle.gov,” Seattle.gov, 2019. [Online]. Available: https://www.seattle.gov/opcd/population-and-demographics/about-seattle. [Accessed: 27-Aug-2020]
