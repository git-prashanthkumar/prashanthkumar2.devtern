 Imports the pandas library as 'pd' for data manipulation. 
 Imports the pyplot module from the matplotlib library for data visualization.
 pd.read_csv("uber-raw-data-sep14-Copy1.csv") Reads the Uber trip data from a CSV file named "uber-raw-data-sep14-Copy1.csv" into a pandas DataFrame called uber_df.
 uber_df.head(5): Displays the first 5 records (rows) of the DataFrame
 uber_df.info(): Provides information about the DataFrame including the data types 
 uber_df['Date/Time'] = pd.to_datetime(uber_df['Date/Time']): Converts the "Date/Time" column from string data type to datetime data type
 plt.hist(uber_df.Day, width=0.6, bins=30): Creates a histogram showing the density of trips per day of the month.
 plt.hist(uber_df.Hour, width=0.6, bins=24, color="red"): Creates a histogram showing the density of trips per hour of the day.
 plt.scatter(x, y, color="purple"): Creates a scatter plot showing the density of trips per location using longitude ("Lon") on the x-axis and latitude ("Lat") on the y-axis.
 
![Screenshot 2024-04-21 154018](https://github.com/git-prashanthkumar/prashanthkumar2.devtern/assets/162727418/a97a3a52-d291-436a-968d-0dc8df75ef5a)
![Screenshot 2024-04-21 154030](https://github.com/git-prashanthkumar/prashanthkumar2.devtern/assets/162727418/f5d07858-40d9-4b97-bee5-c3d7ecfe8abe)
![Screenshot 2024-04-21 154050](https://github.com/git-prashanthkumar/prashanthkumar2.devtern/assets/162727418/c8898916-553c-44a2-90f4-94272f068900)
![Screenshot 2024-04-21 154101](https://github.com/git-prashanthkumar/prashanthkumar2.devtern/assets/162727418/60e64501-f474-4a34-846d-4c6d3f61607d)
