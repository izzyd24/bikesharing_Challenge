# bikesharing_Challenge
## Overview: 
### Purpose:
The purpose of this challenge was to explore the CitiBike dataset in New York City. 
We had to import the unedited CSV, create worksheets and a story via Tableau. As well as portray the data results to then pitch the city of Des Moines on the opportunity of replicating this bike program. 
### Background:
The city of Des Moines was interested in a proposal featuring the dataset above, specifically showcasing the geo data against user types and genders to understand the feasability of the project with their own community. 
### Link to Tableau: 

## Results: 
### Cleaning the CSV: 
Please refer to the gif below. This process was fairly simple, nothing new introduce in pandas, and we essentially only 'cleaned' one column with the datetime documentation:
![challenge 14 d1](https://user-images.githubusercontent.com/102266450/178197395-c6d708f7-d78f-4a60-b59e-15bda6f46eef.png)
![challenge 14d1 pic2](https://user-images.githubusercontent.com/102266450/178197414-4ae17597-6b2c-4109-a695-42a0b28a5695.png)

### Number of Rides:
![number of rides](https://user-images.githubusercontent.com/102266450/178197430-ff6a1ca1-4983-4a9c-94b7-b82a39a22fc8.gif)

### August Peak Hours:
Nothing too surprising here, but we did see that between hours "0-5" is basically empty when compared to the data of the busiest times (look at times 8 onward). We might question if there is a true need to have so many available hours for the bikes, or if we should scale back. 
![August Peak Hours](https://user-images.githubusercontent.com/102266450/178197612-18255ec6-e72d-4601-b006-9b54847c2346.gif)

### Checkout Time by Users:
Looking back, this graph seems a bit underwhelming when compared to the "Checkout Time by Gender". It does offer some insight however for trip durations. If we select "All" in our filter, we noticed that most bikes occurences are within the first two hours. 
![Checkout Times for Users](https://user-images.githubusercontent.com/102266450/178197765-d21a7e95-5df2-4aee-b9ab-442504ac3f75.gif)

### Checkout Time by Gender:
This graph, as mentioned, is much more interesting... The checkout times by gender shows that males seem to ride our bikes at a higher rate. This is most drastically seen when filtering by "0" for our hour on the tripduration filter.
![Checkout Times by Gender](https://user-images.githubusercontent.com/102266450/178197757-b5451623-0117-489c-92d5-be4ded8c03d4.gif)

### Heatmaps:
Of the 3 heatmaps, we recommend looking at the third, "User Trips by Gender (Weekday per Hour)". This shows that male subscribers are the highest users. We spent most of our time here, filtering along the highest count of CitiBikes with our "slider" filter. 

#### Trips by Weekday:
![Trips by Weekday Per Hour Adjusted](https://user-images.githubusercontent.com/102266450/178197740-6c9b8d80-9072-49b0-b7f7-854102451f37.gif)

#### Trips by Gender (weekday):
![Trips by Gender (weekday per hour)](https://user-images.githubusercontent.com/102266450/178197728-56d3cefe-2ba7-4056-bfd7-5cfef5b2754f.gif)

#### User Trips by Gender:
![User Trips by Gender (Weekday)](https://user-images.githubusercontent.com/102266450/178197707-facd8f10-b9bb-4843-a776-c00caefe14d0.gif)

### Start and End Locations: 
This offer the most interaction from a user perspective. We chose to show start locations only through a green color overlay, whereas in the second location graph, we wanted to offer a color scale from blue to red (lowest to highest in count). 
We noticed the following with the highest end locations: 12th and W St, 8th and W St, Pershing Square, E 17st Broadway. Perhsing Square had over 16,000 counts!

#### Top Starting Locations:
![Top Starting Locations](https://user-images.githubusercontent.com/102266450/178197639-a8e1992a-afb3-4882-bf9b-41cb12c5c6e9.gif)

#### Top Ending Locations:
![Top Ending Locations](https://user-images.githubusercontent.com/102266450/178197656-977274a2-aa0c-4e1d-9595-d5cc86ee523c.gif)

## Final Working Story Visualization: 
The final product shows a comprehensive view of New York City biking data, with an multitude of overlays in Tableau to understand our customers. Yet, to push this forward, we recommend using the start and end location data to map out by user type and gender. Adding these two key categories may help our business proposal or future clients understand how the demographics seem to move about our city. One concern I have with the dataset is that we have downloaded from a CSV, and likely could benefit by going back to our Jupyter notebook to check the data types---change as necessary for any columns of interest. 
![Tableau Story](https://user-images.githubusercontent.com/102266450/178197628-3b9e783d-62fc-4edd-822e-c3b0fc6f3cdc.gif)
