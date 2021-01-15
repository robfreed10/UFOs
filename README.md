# UFOs

## Overview of Project
The main objective of this project was to build a dynamic table and webpage using Java Script to provide a more in-depth analysis of UFO sightings based on certain variables like date, city, state, country, and shape of the UFO that they have claimed to see. 

## Results of Project
The webpage allows the user to refresh the searches of their criteria by pressing "UFO Sightings" in the top left corner, as shown below. At the bottom of this screen grab is where the user is able to input just some of the possible filters.
![webpage_layout](https://user-images.githubusercontent.com/68922663/104669615-61309380-56a8-11eb-89b7-c718ac671659.png)

#### Filtering by Date
The webpage allows the user to filter the UFO data by date. For example, in the image below, searching for the date 1/10/2010 will yield all 11 of the UFO data gathered from that specific date in time! 
![webpage_filter_date](https://user-images.githubusercontent.com/68922663/104669958-00558b00-56a9-11eb-9489-d8c21f505cff.png)

#### Filtering by City
The webpage allows the user to lookup cities that have experienced UFO sightings based on the data at hand. For example, in the image below, I searched for the town located closest to my current location in Southampton, New York, and the corresponding data was provided in the image below.
![webpage_filter_city](https://user-images.githubusercontent.com/68922663/104670198-65a97c00-56a9-11eb-98c7-8128f0f2c6f7.png)

#### Filtering by State
Similarly to filtering by city, the user is able to filter data by state. In the image below, you can see that I searched "ny" in the state filter section which yielded 4 different results across New York State. 
![webpage_filter_state](https://user-images.githubusercontent.com/68922663/104670404-c5a02280-56a9-11eb-9b01-f7a79661cb29.png)

#### Filtering by Country
The user of the webpage is also able to filter the data by country, however, there is only data from the US and Canada regarding UFO sightings. To search for these countries, the user must input "us" for the United States and "ca" for Canada. My search of the US data, which is a majority of the data, will be shown below. 
![webpage_filter_country](https://user-images.githubusercontent.com/68922663/104670751-6c84be80-56aa-11eb-969d-b00f474b1c90.png)

#### Filtering by Shape
The user will also be able to filter by the type of shape of the UFO that is present in the data. There are many different shapes in the data, and in the image below i searched for "light" which then returned all data with the shape "light"
![webpage_filter_shape](https://user-images.githubusercontent.com/68922663/104670917-bf5e7600-56aa-11eb-9491-055df0696141.png)

## Summary
The new and improved webpage lets the user input more filters then previously when we were only filtering by date.

#### Drawbacks
One drawback I have for this webpage is that if the city the user is searching for is not found in the data, then nothing will arise. It would be really great for the user to get the next closest city that they were searching for, instead of nothing. 

#### Recommendations
My first recommendation is that the filter for California and Canada are the same "ca". This could cause slight confusion for the user as they might be looking for data in Canada, but are searching "ca" in the state filter area. 
My second recommendation is that the webpage should not be case sensitive. Throughout testing the webpage during the challenge, I would occassionally begin my search with a capital letter and no results would show up. This could cause another user to come to the conclusion that maybe there are no records for a certain city, state, country, or shape.
