# nmkmapr
Code to generate an empty map of municipalities (plus the Ohrid lake) in North Macedonia to be used for plotting in R.

Following [this explanation](https://stackoverflow.com/questions/17723822/administrative-regions-map-of-a-country-with-ggmap-and-ggplot2) the Rmd creates dataframes to be used for mapping data to municipalities in North Macedonia.

The latest data are from [6 May 2018](https://gadm.org/data.html) and I'm not sure if they correctly represent the current municipalities (they don't, see [issue](https://github.com/novica/nmkmapr/issues/1)) in North Macedonia. If there are any mistakes, report them here.

![map](map.png?raw=true "map")
