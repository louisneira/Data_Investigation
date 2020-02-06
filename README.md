# Data Investigation
## Simple investigation of data set from Udacity's Data Analyst Nanodegree Program

This code is an investigation of medical appointment data that recorded whether patients showed up to their medical appointments or not.
The data is analyzed in order to determine if any factors recorded in this data can be linked to patients not arriving to their medical apointments.

Initially, data was inspected for duplicates and missing data. Then columns that did not appear useful for this analysis were dropped, and remaining
columns were renamed as appropriate. Data was then cleaned, which included removing any invalid data (e.g., age less than zero), and 
data types were converted to those that were appropriate for analysis.

After inspecting and cleaning the data, the data is explored visually with basic histograms. After this, we are ready to analyze our data.
The first analysis was to determine if receiving a text message was linked to changes in no-show appointments. Data is also analyzed
to determine if having a reported health issue impacts the rate of patients who do not show up for their medical appointments.

Analysis of this data is done in Python and includes calculating proportions and plotting data using the matplotlib plotting library.
