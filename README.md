# Weather and Vacation Analysis
I created a robust Jupyter Notebook with two API calls to pull in weather data and hotel data based on location. 

## Weather

### The Data
To create a list of cities for this analysis, I randomly generated latitudes and longitudes. I used citipy to find the city nearest the coordinates generated. 

![APIgeneratecities](https://user-images.githubusercontent.com/74504885/123317639-daec6900-d4f3-11eb-878d-bdc428e0418f.PNG)

I ran an API call on Open Weather Map with the randomly generated list of citites. Using a for loop, I called and appended the cities, lat, lon, temperatures, weather data, and date. 

![APIapicall](https://user-images.githubusercontent.com/74504885/123317867-23a42200-d4f4-11eb-89c0-81da9f3ec542.PNG)

### Use Pandas to disect the information
I used pandas to convert the raw data pulled from the randomly generated cities and weather data to create a dataframe. I used if statements to set parameters on weather and created a new datafram. 

### Use Pyplot to create charts to display the data
I used pandas to pull in the weather data and make various charts based on weather type and location. 

![APIplotting](https://user-images.githubusercontent.com/74504885/123320121-f4db7b00-d4f6-11eb-8e73-9474302502fb.PNG)

To predict weather patterns, I created a linear regression on the various weather types and locations. 

![APIlinregression](https://user-images.githubusercontent.com/74504885/123320184-0c1a6880-d4f7-11eb-8d14-c3674c3088f0.PNG)



