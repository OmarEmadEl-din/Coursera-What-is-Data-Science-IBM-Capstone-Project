# Coursera-What-is-Data-Science-IBM-Capstone-Project
# first of all, thank you Coursera for this great course, and thank you peers even I pass or not
## Introduction/Business Problem
The City of New York is famous for its excellent cuisine. It's food culture includes an array of international cuisines influenced by the city's immigrant history. Sushi restaurants have become so popular in the United States now it seems that there is one on every corner, not only in major cities but also in smaller cities. Starting a sushi restaurant can be a great business opportunity, but you need to distinguish yourself from others to enjoy long-term success.

My client desires to open his business in the Manhattan area, thus I concentrate on that borough throughout my analysis. we tend to outline potential neighborhoods supported by the number of dish bars that are operative right in every neighborhood. Manhattan has full potential but is also an awfully difficult district to open a business thanks to high competition. The new bar ought to be open in a part that inadequate neighborhood during this means the bar will attract additional customers. Therefore, this analysis necessary to make sure that we've got enough customers which we tend to don't seem to be so on the brink of alternative dish places.

## Data Selection
To identify the characteristics of our competitors' venues in Manhattan, I would first need to find out the number of sushi bars in Manhattan currently and their location.

I then used Google Map API to find their geographic coordinates based on their postal code addresses. I also used Google Map API to find their geographic coordinates of the 5 locations shortlisted for our sushi bar. https://geo.nyu.edu/catalog/nyu_2451_34572

for venues from foursquare https://api.foursquare.com

and for suchi categorie https://developer.foursquare.com/docs/resources/categories

In Manhattan, there is 1115 sushi bars are currently operating.

## Methodology
Aaddresses are transformed into their equivalent latitude and longitude values.

Foursquare API is used to explore neighborhoods in Manhattan, New York.

After that, explore function to get sushi restaurant categories in each neighborhood.

Then using this feature to group the neighborhoods into clusters K-means clustering algorithm will be use to complete this task. And also, the Folium library to visualize the neighborhoods in Manhattan and its emerging clusters.

## Result
Using K-mean to clustering data area with less number of sushi bars

Based on dataframe analysis this areas are the best places to open a new sushi bar business.




## Discussion
This analysis is performed on limited data. This may be right or may be wrong. But if good amount of data is available there is scope to come up with better results.

There is high competition in south and mid of town so it is very risky to open business in these areas.

It can be done more detailed analysis by adding other factors such as transportation, demographics of inhabitants.

## Conclusion
although all of the goals of this project were met there is positively space for any improvement and development as noted below. However, the goals of the project were met and, with some a lot of work, could simply be developed into a totally pledged application that would support the gap a business the idea in associate degree unknown location.
