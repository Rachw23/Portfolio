## Script to determine solar storm level as defined by NOAA

This is a short program that calculates and plots the total integrated proton flux above 10 MeV for a given month from GOES satellite data, available in CSV format from the NOAA website. 

The program reads in the variables for the month, number of days in the month, year and number of the GOES satellite for the data to be processed, as defined by the user via input boxes.

A good example of solar storm data requires: year=2015, month=06, days=30, satellite number=13
This particular set of data shows very visible solar storm activity in the final plot.

The maximum proton flux for the month, when it happened and what solar storm level it was are found below and displayed with the graph of the integrated proton flux above 10 MeV as a function of time. The data is plotted using a log scale for the flux axis and changing the index to the 'time_tag' column. 

On the resultant plot, the highest peak of the total integrated proton flux above 10 MeV on a log scale illustrates the storm level as defined by NOAA, where:

10^1 = level 1 (minor)

10^2 = level 2 (moderate)

10^3 = level 3 (strong)

10^4 = level 4 (severe)

10^5 = level 5 (extreme)

More information on these categories can be found at : https://www.swpc.noaa.gov/noaa-scales-explanation