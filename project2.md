# Project 2
## Emory AI Data Lab Invest Atlanta

### Skills Associated
1. Data Cleaning with Python Pandas
2. Geospatial Data Analysis with Python GeoPandas
3. Data Visualization with ArcGIS
4. Visual and Spoken Communication Skills

### Background
I led a team under the guidance of Invest Atlanta to explore whether college demographics influence which businesses choose to develop in specific areas. My main contribution in this project was collecting geospatial data on colleges, using GeoPandas to create 1 mile buffers, merging the provided business license data with college data, and using ArcGIS to create visuals.

Atlanta is home to a diverse array of colleges and universities,
each with its own distinct focus. Morehouse, Spelman, and Clark
Atlanta are renowned historically Black colleges and universities
(HBCUs). Georgia Institute of Technology specializes in science
and engineering, offering a range of Bachelor of Science
programs. Georgia State University stands out as a large, public
institution. Emory University is a private university, that
emphasizes liberal arts.

As highlighted by Liberty Street Economics, institutions of higher
education can act as economic anchors, driving consumer
demand and attracting diverse businesses to their surrounding
areas. This project explores the types of businesses that form
around colleges, analyzing the local economy shaped by
universities.
### Methodology
1. Selected colleges located in the
metro Atlanta area (including
Emory).
2.  Used Overpass Turbo to collect geospatial data on colleges in metro Atlanta.
3.  Created 1 mile buffers around each college using GeoPandas.
4. Cleaned the dataset with business
data to focus on industry
classification.
5. Used ArcGIS to create visuals

### Results and Conclusions

![Screenshot 2025-01-05 220635](https://github.com/user-attachments/assets/fd73fc3b-4b31-4679-8df4-9882d593d466)

The top 5 business category counts for each
university:  
ATL University: Real estate and rental (23),
Professional, Scientific & Technical Services (19),
Construction & Real Estate (14), Health & Social
Services (5), Food Services & Restaurants (4)  
Emory: Professional, Scientific & Technical Services
(6), Food Services & Restaurants (3), Construction &
Real Estate (2), Real Estate & Rental (1)  
GSU: Professional, Scientific & Technical Services
(76), Real Estate & Rental (61), Construction & Real
Estate (13), Food Services & Restaurants (13), Health
& Social Services (5)  
Tech: Professional, Scientific & Technical Services
(144), Real Estate & Rental (103), Construction & Real
Estate (43), Food Services & Restaurants (17), Health
& Social Services (16)  

The Real estate and Rental businesses are the most
prevalent because many students prefer to live near
college campuses. Many schools also have research
facilities which is why Professional, Scientific, &
Technical is common. Tech has the most Health &
Social Services nearby

### Future Work

We plan to analyze businesses near colleges in more rural
areas. This is because the colleges we analyzed were mostly in midtown
Atlanta, which is an area that has many offices and
apartments that businesses may cater to as well.  
Due to Emory's location not actually being in the city of Atlanta, there is little business data
compared to the other colleges, future research can
improve at this.

### References

Federal Reserve Bank of New York. (2012, February 15). How colleges and universities
can help their local economies. Liberty Street Economics. https://
libertystreeteconomics.newyorkfed.org/2012/02/how-colleges-and-universitiescan-help-their-local-economies/ 

[Back to Home](index.md)
