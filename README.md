# Week-6-Challege


WeatherPy
# First import dependencies that will be used in the code below.
# Set output file to a variable
# Set latitude and longitude ranges
# Then create empty lists to hold lat_lng and cities.
# Create random lat and lng combinations.
# Identify nearest city for each lat, lng combination
# Add city to cities list if it is unique
# THen print the len of the list "cities" to find out the number of unique cities. 
# After that, create a data frame using the cities list, and add new coloumns for information that will be populated later. 
# Construct the url with the API which will be used in a loop.
# Use iterrows() to loop through requests.get().json, and populate the coloumns added in the data frame above.
# Save the data frame to a .csv file
# Remove empty cells by first populating them with "NAN" and then use .dropna.
# Now plot different scatter plots using data from the data frame above.
# Then break data into "Northern Hemisphere" and "Southern Hemisphre" data by using the "Lat" line = 0 as a reference point.
# Plot different scatter plots for the northern and southern hemisphere, along with using "linregress" to show statistical data and come up with the line equation which will be annotated on the plot. 
# Each plot has a few observations beneath each one. 


VacationPy
# First import dependencies that will be used in the code below.
# Read .csv file created in WeatherPy
# After that, configure API key for gmaps.
# Then, drop NAN values
# Store cities lat and lng values to a variable called "locations"
# Find maximum "Humidity" value which will be used in the heatmap below.
# Create a heat map using the locations variable above and by using humidity values. 
# Create new data frames for ideal weather conditions
# Delete "index" and "Unamed: 0" columns.
# Add new coloumn "Nearest Hotel" to data frame created above. 
# Set correct params to find hotels for ideal cities. 
# Use .iterrows() and the correct url to find hotels for the "lat" and "lng" values for the ideal weather cities. 
# Add marks on the heatmap that give the name, city, and country for each hotel.
