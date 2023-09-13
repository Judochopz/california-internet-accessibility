# california-internet-accessibility
Average internet speeds in California's counties

## Intro
The goal of this project was to collect internet speeds in counties throughout \
California and explore the reasoning behind the differing county speeds.
## Work
The internet speed tests were pulled from Ookla's API and the shapefile was pulled
from the U.S. Census Burea into two GeoPandas dataframes. I then isolated rows
containing data from California and then merged the dataframes. Afterwards I compiled the
individual tests and grouped them by county. I then used MatPlotLib to plot the data,
shading each county by their average download speed (Mbps) and labeled the 11
most populated counties for reference.