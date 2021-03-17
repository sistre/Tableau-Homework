# Tableau-Homework

This homework is an analysis of the Citi Bike program using the data available at https://www.citibikenyc.com/system-data. Due to the contraints of Tableau Public and the shear size of the data set involved, I was unable to do a meaningful analysis of the NYC data, at least with anything current. However, in the data repository there is also data for Jersey City, NJ, a suburb of NYC just across the Hudson River from Manhattan. With the lower size of this dataset I was able to conduct an analysis of the Citi Bike Program in Jersey City for the years 2018-2020.

## Gathering and combining the data
On the System Data page of the Citi Bike site, the date is stored month by month in zipped CSV files. Once I downloaded all twelve months for 2018-2020, I used a Jupyter Notebook with Pandas to read in all the CSVs as individual dataframes, combine all the dataframes, write the combined dataframe to disk as a CSV, and then read that CSV back into the Jupyter Notebook to check that everything was correct. The notebook is contained in this repsoitory as "DataAggregation.ipynb" and the zipped combined CSV is "2018-2020_JC-citibike-tripdata.csv.zip"

## Analysis in Tableau
Once the CSV was loaded into Tableau, I started my analysis. I created chart and vizualizations:

• Starting Location Popularity Map
• Ending Location Popularity Map
• Top 10 Start Locations
• Bottom 10 Start Locations
• Top 10 End Locations
• Bottom 10 End Locations
• Average Distance Per Trip (miles)
• Age vs. Trip Duration
• Gender vs. Trip Duration
• Gender Breakdown
• Female Ridership
• Peak Winter Hours
• Peak Summer Hours
• Subscriber Breakdown

After creating the vizualizations, I combine several related vizualizations into the following dashboards: 

• Starting and Ending Locations
• Peak Winter and Summer Hours
• Gender Anaylsis

And finally, I combined the following vizualizations and dashboards into the Jersey City, NJ Citi Bike Analysis Story:
• Starting Location Popularity Map
• Ending Location Popularity Map
• Starting and Ending Locations Dashboard
• Peak Winter and Summer Hours Dashboard
• Gender Anaylsis Dashboard
• Subscriber Breakdown

The vizualizations, dashboards, and story can be found at https://public.tableau.com/profile/sean2841#!/vizhome/TableauHomework-CitiBikeAnalytics_16145916399890/JerseyCityNJCitiBikeAnalysis


