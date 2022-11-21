# UFO_Website

## Overview

I've been helping my client Dana design a responsive, dynamic website covering UFO sighting data. Initially, we designed the site to allow visitors to search sighting information by date. After mulling the website design over, Dana asked if it would be possible to add additional filters based on the other data points in the sightings - search criteria by City, State, Country, and finally by the Shape of the UFO itself. Our end goal is to have a crisp, professional website where visitors can search by single or multiple criteria to find the exact sighting they seek. 

## Results Description for my Client, Dana

Hello, Dana! I hope you'll be as excited for our latest website draft as I am. Our latest idea for the design is in place. The new site looks like the following:

![](/Resources/default_view.PNG)

now with fields for users to search for specific dates of sightings and city, state, and country location, as well as specific UFO shapes. We have a placeholder date of "1/10/2010" appear that does not affect any data, but once a date is entered as a search criteron and a user tabs to or manually clicks into another field, then our filters activate. 

![](/Resources/filter_date.PNG)

Should a visitor wish to further drill-down for any reason, perhaps to have an easier time reading a single result, the search fields allow for multiple criteria to be filtered at the same time. An example can be seen below, where a user has searched for the date "1/1/2010" and the city "benton."

![](/Resources/filter_date_city.PNG)

Now is also a good time to note certain search criteria limitations. Our date field will only accept a single-digit number for dates that are single digits, such as "1/1/2020." This date can *not* currently be entered as "01/01/2010" and return valid search results. In addition, you may have noticed the lower-case entry for "benton" as well as its lower-case entry in the data table on the site - along with its state, country, and shape. *All* of our text search fields must be entered for now in lower case to function properly. In subsequent drafts we can address these issues. 

Some additional search examples follow.


Here is a search by a city:

![](/Resources/filter_city.PNG)

One by a state:

![](/Resources/filter_state.PNG)

And, finally, one by UFO shape:

![](/Resources/filter_shape.PNG)

I hope that these examples illustrate just how easy it's becoming to navigate our UFO sighting resource webpage! Please let me know if you have any questions about the site's navigation and I will be more than glad to answer them. 

## Summary

I was so focused on making our search fields operate properly that it wasn't until late in the project when I realized *nearly everything* in the data tables is written in lower case, and in some instances, being loaded with incorrect formatting! One improvement I'd suggest implementing is coding an ETL function(s) on the raw data itself so it just looks *professional* to any site visitor. Along with this function, I also would suggest transforming the data field from the raw data to an mmddyyyy date format.  

One aspect of our former design that really "popped" for me was the button we clicked to filter by an entered date. I probably sound a little silly, but it was kind of fun to click it and watch the data sort itself out. But more importantly, it was an obvious pull-in/draw for a *user* to go "oh hey, *clicking this* is how I narrow down all of this data." We really don't have anything like that with our new version - it's not intuitive that a user needs to enter a value in the search box and then *tab out or click out.* So with this downside in mind, a final improvement would be to filter the data as a person types, if that's at all possible - plus a change like this would just have that "pop" factor too!  
