# UFO

Overview of Project: Explain the purpose of this analysis.
Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.
Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.


## Overview

I've been helping my client Dana design a responsive, dynamic website covering UFO sighting data. Initially, we designed the site to allow visitors to search sighting information by date. After mulling the website design over, Dana asked if it would be possible to add additional filters based on the other data points in the sightings - search criteria by City, State, Country, and finally by the Shape of the UFO itself. Our end goal is to have a crisp, professional website where visitors can search by single or multiple criteria to find the exact sighting they seek. 

## Results Description for my Client, Dana

Hello, Dana! I hope you'll be as excited for our latest website draft as I am. Our latest idea for the design is in place. The new site looks like the following:

![](/Resources/default_view.PNG)

now with fields for users to search for specific dates of sightings and city, state, and country location, as well as specific UFO shapes. We have a placeholder date of "1/10/2010" appear that does not affect any data, but once a date is entered as a search criteron, then our filters activate. 

![](/Resources/filter_date.PNG)

Should a visitor wish to further drill-down for any reason, perhaps to have an easier time reading a single result, the search fields allow for multiple criteria to be filtered at the same time. An example can be seen below, where a user has searched for the date "1/1/2010" and the city "benton."

![](/Resources/filter_date_city.PNG)

Now is also a good time to note certain search criteria limitations. Our date field will only accept a single-digit number for dates that are single digits, such as "1/1/2020." This date can *not* currently be entered as "01/01/2010" and return valid search results. In addition, you may have noticed the lower-case entry for "benton" as well as its lower-case entry in the data table on the site - along with its state, country, and shape. *All* of our text search fields must be entered for now in lower case to function properly. Some additional examples follow:


Here is a search by a city:

![](/Resources/filter_city.PNG)

