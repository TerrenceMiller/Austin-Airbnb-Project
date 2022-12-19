# Austin-Airbnb-Project

Came across Inside Airbnb, a source for data on Airbnb listings in different cities.
I was interested in what Airbnb looks like in Austin, since it is a city that I have visited many times and have stayed in a airbnb most of the times I went.

## Dataset

[Inside Airbnb](http://insideairbnb.com/get-the-data)

18,338 Listings, 649,000 Reviews

Interested in trends in properties, pricing, location, and the best time of year for Airbnb in Austin.
I was also interested in how different types of properties performed but was not able to look into that with this dataset due to not having 
data on historical bookings and the price. The price shown is current price and bookings shown are for the next upcoming year.

## Data Cleaning 

Cleaned the data with both Excel and Python.
(Excel was only used to remove unit codes in the amenities)

### Selecting the columns

Dataset has 74 different columns of data.
I narrowed this down to id, neighbourhood, neighbourhood cleansed(zip code), latitude, longitude, property_type, room type,  
accommodates, bathrooms_text, bedrooms, beds,amenities,price, minimum_nights, maximum_nights, and availability_365 \

These are the areas I felt would be most important to someone thinking about becoming an Airbnb host with a property they have or aquiring a property to become a host.
I ignored data related to the hosts of the properties and reviews for now.

### Outliers

There are some outliers for the price per night of these properties.
The average price of properties is $346 but the max price is $10,000.
I only kept properties with a price of $1000 or lower a night to get a clearer view of what the typical listing looks like.
Used reviews to make sure that the quality of the listings for properties that accomodate 

## Interesting findings

Majority of properties range from $100 - $200 a night. 
March is the most expensive time of the year. (Most likely due to SXSW)
Friday and Saturday are most expensive but not that different from the other days.






