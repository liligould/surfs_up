# surfs_up

## Purpose 
After previously collecting weather data, the task at hand is to pull information based on temperature trends in June and December before a new surf and ice cream shop opens in Hawaii. The previous information gathered looked at precipitation and temperature data in the last 12 months, the most active stations, the highest, lowest, and average temperature of the most active station as well. This information helped us find the summary statistics for the months of June and December. We first wanted to look at the month of June and began by writing a query that filtered through the date column from the Measurement table previously created. We then retrieved the temperature data for the all the months of June from 2010 to present (2017). By applying a list function we were able to see the data more clearly and turned it into a Pandas Data Frame to add index and headers. Then with the describe() function we were able to generate the summary statistics for June temperatures. A similar process was applied in order to find the summary statistics for December.

## Results
Three key differences between June and Decemeber summary statistics

* December standard deviation is higher than June which indicates the data is spread out around the mean.
* Summary statistics for the months of June are warmer than December

* June Summary Statistics                                           * December Summary Statistics
<img width="135" alt="June Temps" src="https://user-images.githubusercontent.com/80358062/119173438-e2b87980-ba2c-11eb-9b2f-d3c87d5b7d06.png"> <img width="169" alt="December Temps" src="https://user-images.githubusercontent.com/80358062/119173474-eba94b00-ba2c-11eb-8d9d-cfd39f732afd.png">

* December Summary Statistics
<img width="169" alt="December Temps" src="https://user-images.githubusercontent.com/80358062/119173474-eba94b00-ba2c-11eb-8d9d-cfd39f732afd.png">

## Summary 
The summary statistics say a lot about how the temperature behaves throughout the months of June vs December. While the standard deviation for June is lower than December it is safe to assume that June has more consistent temperatures ranging between 64 and 85 degrees while December temperatures are more spread out around the mean of 71 degrees ranging from 56 to 83 degrees. Although the range is greater for December, the total count for December (1517) is still lower than that of June (1700). With this information we can conclude that June has a higher probability of being more profitable for the surf and ice cream shop. This is excluding all tourist/holiday data that could tell us more.
