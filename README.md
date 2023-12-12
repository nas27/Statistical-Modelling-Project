# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
This project seeks to explore python for data analytics, being able to utilize APIs effectively, employ data wrangling tactics that are transferable to other tech. I will be further using statistical modelling techniques to interpret and practice using packages to create models and start thinking about future uses.

## Process
#### Step 1
Started by checking out the API documentation and testing out a provided endpoint.
Ran the below GET req via Postman to confirm working data.
http://api.citybik.es/v2/networks?fields=EcoBici,name,company

### Step 2
Pull data from Foursquare and Yelp and start cleaning the data.

### Step 3
Combine the data if necessary. Ran into some issues with parsing, accidentally created tuples as a result of an extra comma. Got some NaN data in my combined dataframe. Future goal: fix this and produce a dataframe with combined data and remove redundant columns.

### Step 4
Review statistically modelling and chose the simplest way forward as I am still learning how to employ these techniques properly.
Interpret the calculations generated for me.


## Results
I found that Yelp and Foursquare provide different data as such serve two different purposes. Yelp is all about rating and tracking the restaurant/bar/establishment reviews.
Foursquare seems to focus on location data has additional feature such as sorting by distance, because proximity is relevant to their use case.

## Challenges 

I couldnt figure out for the life of me why my df was objects or tuples. thanks to larry i found out i had extra commas in my for loop when grabbing the data
**ChatGPT: The issue you're facing might be related to the extra commas in your assignment statements. When you use a comma at the end of an assignment, Python creates a tuple instead of a single value. This might result in unexpected behavior, especially when building a list of dictionaries for a DataFrame

I found it challenging to make sense of the dense statistical concepts. I had the desire to apply them here.

## Future Goals
Focus on the datasets and combining them correctly. I would explore weather APIs and try to derive some more interesting insights.