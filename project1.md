# Project 1
## Emory Data Think Invest Atlanta

### Skills Associated
1. Data Cleaning with Python Pandas
2. Web Scraping with Python Beautiful Soup
3. Geospatial Data Analysis with Python GeoPandas
4. Visual and Spoken Communication Skills

### Background
I led a team under the guidance of Invest Atlanta to explore whether the construction of the beltline had an impact on the rising house prices. My main contribution in this project was learning how to use beautiful soup for web scraping in order to collect property price data from Trulia and using geopandas to process and analyze data.

The Beltline is a large-scale adaptive reuse project with an ultimate goal of connecting "45 intown Atlanta neighborhoods via a 22-mile loop of trails, parks, and eventually a planned streetcar, all of which will follow abandoned railroad tracks that encircle Atlanta." 
According to Dan Immergluck, researcher in urban housing
and professor of urban studies, "from 2011 to 2015, values
rose between 17.9 percent and 26.6 percent more for
homes within a half-mile of the beltline than for properties
located elsewhere in the city". This is posited to be because of green gentrification. Green gentrification is the process by which the
development of "green space" increases the perception of
elevated community and desirability, which in turn attracts
the wealthier and produces higher living costs. Ultimately,
this pushes out low-income residents, effectively lighting
up the rate of displacement.
### Methodology
1. Used geopandas to
merge NSA dataset
(geojson) with Tax
Parcels 2008 dataset to
match properties to NSA.
2. Web scraped property
prices in ATL off
Trulia.com
3. Selected 4 NSA regions
near the BeltLine,
compared means of
property values with
mean tax appraisal of
properties in 2008.

### Results and Conclusions
![box plot of nsas tot appr distr](https://github.com/user-attachments/assets/6c6eff82-6515-454e-a4f3-83a6e6c5e0c7)  
In the above visual, we compare the distribution of tax appraisal values for properties in the four selected NSA regions. We recognize variability in prices of houses within
the same NSA, especially NSAs closer to the BeltLine like E04.

![sidebyside](https://github.com/user-attachments/assets/8840e390-dcf3-449d-845e-fff4d5fc3046)

Mean values in 2008 are pretty low and homogeneous, while mean values today are
substantially different  
  For example, C06 vs E04 shows community
migrations and shifts in living conditions in the
same place   
Due to time constraints, we were only able to scrape
data for 4 NSAs, future research can look at more  
However, we can already notice that property price variation is largely determined by how close the property is to the beltline, indicating that there is a possibility that the beltline is influencing the rising property prices



### References

Immergluck, Daniel. “Atlanta’s BeltLine
shows how urban parks can drive ‘green
gentrification’ if cities don’t think about
affordable housing at the start.” (2023).
The Conversation. 


Immergluck, Daniel and Balan,
Tharunaya, "Sustainable for Whom?
Green
Urban Development,

Environmental Gentrification, and the
Atlanta Beltline" (2017). USI
Publications. 14. 


“Project Goals.” Atlanta Beltline,
beltline.org/the-project/project-goals/.
Accessed 24 Apr. 2024.

[Back to Home](index.md)
