# UFOs

## Project Overview
This assignment was designed for us to build a dynamic webpage that takes in user inputs and then displays relevant UFO sightings.
To properly conduct analysis, user are able to filter the UFO sightings based on various criteria which includes event state, event date, country, city, and shape.

## Resources
- Data Source: [UFO data]( https://github.com/gonzalesbarrett/UFOs/blob/main/static/js/data.js)
- Software: HTML/CSS, JavaScript, Visual Studio Code 1.66.2, BootStrap 5.1.3

## Results

### Link to UFO Sightings webpage
The deployed webpage is accessible at [https://github.com/gonzalesbarrett/bagonzales.github.io]( https://gonzalesbarrett/bagonzales.github.io).

### Search Criteria Procedure

#### Front Page
This is the beginning of the page. Clicking the ‘UFO Sightings’ in the top left refreshes the page.
![Screenshot](https://github.com/gonzalesbarrett/UFOs/blob/main/static/images/Header.png)

#### Filters
The user can enter any desired date and when the change is detected the table will display the updated results.
![Screenshot]( https://github.com/gonzalesbarrett/UFOs/blob/main/static/images/Filters.png)
The user also has the option to filter by city, state, country, and shape. 

#### Results
The embedded table will display default results unless filters are used. All the filters can be utilized at the same time to narrow down results. 
![Screenshot]( https://github.com/gonzalesbarrett/UFOs/blob/main/static/images/Results.png)

## Summary
This website provides a practical way for people to deep dive into specific sightings. With the use of several filters it allows a user with little experience to comb through a significant list of data to find what is relevant to them. The website does have some drawbacks that could be remedied:
- The filters do not offer drop-down selection and the user has no way of knowing if their search will generate results prior to searching. This can cause a time sink. Implementing a drop-down search would allow the user to know what they can search for prior to searching.
- The filters are all lowercase, meaning if a user searches for a state’s initials using uppercase letters(which we do not even clarify is required) then the search would not return anything. A drop-down would resolve this or creating input recognition of upper and lower case including the full state name.
- There is no quick way to clear filters short of refreshing the page or deleting entries. Creating a button and clears inputs would be the easiest fix.
