# Class Project : Exploratory and explanatory analysis
This is a class project to carry out exploratory and explanatory analysis of the dataset contained in the csv file marked "booking_of_hotel" here.

# Preamble
The hotel-booking datasets csv file is uploaded here and it awaits Exploratory Data Analysis in the open-source web application.

**Open-source web application used:** Jupyter Notebook. 

Refer to the jupyter notebook marked "Exploratory Data Analysis" which contains the codes in performing the analysis as ypu read or implement the steps below.

# Exploratory Data Analysis (EDA)
The Exploratory Data Analysis enables one to get in-depth understanding of dataset. Typically, EDA is carried out in order to detect any errors, outliers as well as to understand different patterns in the dataset. 
In performing an EDA on "booking_of-hotel' dataset, the major steps below were carried out. Refer to the jupyter notebook marked "Exploratory Data Analysis" as you go through the steps.

**STEP 1**
Loading the libraries and importing datasets. Pandas is used in reading the csv file marked "booking_of_hotel". Open the jupyter notebook marked "Exploratory Data Analysis" to view.


**STEP 2**
We check for missing values. 

****Observation:**** From the "booking-of hotel" dataset, some data values are missing in some cells marked as "NULL". 

**STEP 3** 
Now, we visualize the missing values.

**STEP 4** 
The actual visualization of the dataset answering specific questions.

***1: Checking for the correlation between the variables***

Fiding the correlation between the variables indicates the extent to which they are related to one another. For instance, from the headmap showing the correlation, the extent to which adults is related to the stays_in_week_nights and stays in weekend nights are 0.093 and 0.092 respectively. From here, we can observe that there is no significant disparity bewteen number of adults staying in the two hotels on weekday and weekend nights.

***2: Visualizing the overall number of stays in weekend nights in each hotel using barplot***

From the visulaization, it is observed that the number of stays on weekend nights in Resort Hotel is higher than that of City Hotel as City hotel's frequency of stays (0.8) is two-third of Resort hotel's (1.2).  

***3: Visualizing the overall number of stays in week nights in each hotel using barplot.***

From the visulaization, it is observed that the number of stays on week nights in Resort Hotel is higher than that of City Hotel as City hotel's frequency of stays (2.2) is eleven-fifteenth of Resort hotel's (3.0).
Also, by comparing the barplot in (2) and (3), it is oberved that the number of stays on week nights is more than stays on weekend nights for both hostels.

***4: Plotting scatterplot of stays in weekend nights against lead time.***

Plotting the scatterplots of lead time (the number of days between making hotel reservation and the actual check-in) against the stays on weekend nights, the outliers present are distinguishes clearly and 3 outliers are observed to be extremely far from the rest of the datapoints. 
Also, this scatterplot shows that lead time against stays on weekend nights does not follow a normal distribution (i.e not dumb-bell shaped).
Although there are outliers in the set, there is no infinite lead time; meaning that everyone who made a booking in the hotels shows up.

***5: Visualizing the number of stays in weekend nights for each hotel using boxplot.***

Using boxplot to visualize the number of stays on weekend nights for each hotel gives the number of outliers directly since outliers are the datapoints falling outside the fence (minimum and maximum values).So, there are 10 outliers for stays on weekend nights in Resort hotel and 8 outliers for that of City hotel.
Also, lower quartiles for both boxplots are zero (booking).

***6: Visualizing the number of stays in week nights for each hotel using boxplot.***

As already established, outliers are the datapoints falling outside the minimum and maximum value fence. Hence, there are 19 outliers in the number of stays on week nights in Resort hotel and 22 outliers for that of City hotel. 
Also, these boxplots have their lower quartiles as non-zero positive values differing from the minimum value (of zero booking) unlike the boxplots in 5 (ie., stays on weekend nights for each hotel) having their lower quartiles as zero (booking).  

***7: To know the number of country in the dataset.***
This shows that there are 177 distinct nationalities in the record.

***8: Visualizing the relationship between country and lead time (the time between initiation, making hotel reservations 
and actual check-in) using barchart.***

Aparently, from the visualization, barchart is not the best of the representation tool for how the lead time differs for each country since the bars are clustered together and y-labels are difficult to read.

***9: Finding the relationship between stays on week and weekend nights using scatterplot.***

The datapoints will follow a positive linearity if line of best fit is plotted; stays on weekend nights rise with the increasing stays on week nights with few outliers.

***10: Finding the relationship between stays on week nights and the arrival month using Boxplot.***

This gives a clear visualization of the outliers present in the number of stays on week nights for each month. All months have the same lower quartile (non-zero booking entry) and minimum value of zero days. All months except August and July have same upper quartile (stay entries on week nights). August and July have the highest upper quartile (same) but July has the highest outlier value of 50 days stays on week night). May has the smallest outlier value of 16 stay days on week night. January has 18 outliers which is the most number of outliers. April has 8 outliers which the least number of outliers (stay entries on week night) amongst the months.

***11: Finding the relationship between stays on weekend nights and the arrival month using Boxplot.***

As established above, boxplots give clear visualization of outliers. In this case, the boxplots represent the number of stays on weekend nights for each month. All months have the same lower quartile (zero entry). All months except January and November have interquartile range and upper quartile (stay on weekend nights). January and November have the same interquartile range and lowest maximum value. Other than January, November and March, the months have identical maximum value which is the highest maximum value as well. July has the highest outlier value (ie., the most extreme number of stay on a particular week night). May has the smallest outlier value. January has 10 outliers which is the most number of outliers. May has 1 outliers which the least number of outliers (stay on weekend night) amongst the months.

Although boxplot shows the outliers, it does not show the frequency of an outlier value in the dataset. For instance, in the boxplot, January has one of its outliers as 8 - 8 stays on a weekend night; meaning 8 entries/bookings on a weekend night in January. Universally, January has at least 8 weekend nights. Now, one cannot tell how many of the weekend nights (frequency) has 8 booking since the boxplot only tells that 8 bookings happens on a weekend night. A suiltable reperesentation will need to be used to address this issue.

# Conclusion
The preceeding section contains the Exploratory Data Aanalysis (EDA) carried out on the "hostel_booking" dataset. 
Refer to the jupyter notebook marked "Exploratory Data Aanalysis (EDA)" while implementing the steps outlined above on your own.







