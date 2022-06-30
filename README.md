# Italian Earthquake Catalogue 1985 2020

The earthquake catalogue was fetched from the following link: [http://terremoti.ingv.it/en](http://terremoti.ingv.it/en). 
All the earthquakes with a magnitude equal or greater than 1.5, within 1985 and April 2020 and in a range of latitude and longitude between 36.1°N-47.1°N and 6.3°E-18.4°E respectively were selected.
A total of 181777 events were obtained.

The columns `Catalog`,`Contributor`,`ContributorID`,`MagAuthor` were removed from the catalogue since they didn't contain any data.

Click the following file [catalogue_manipulation.ipynb](https://github.com/Iron486/Italian_Earthquake_Catalogue_1985_2020/blob/main/catalogue_manipulation.ipynb) to take a look at the preprocessing steps.

Star the repository if you found the dataset useful and inspiring :).

### **Inspiration** 

It is possible to perform an exploratory data analysis of the catalogue, analyzing and plotting earthquakes in the three dimensions, geolocating them, plotting the earthquakes in time and studying the occurrence of the events in the space-time domain. 

Furthermore, it's possible to perform more advanced analysis derived from statistical seismology, such as analyzing the number of events for each bin magnitude in time and space, analyzing multivariate plots or visualizing the type of magnitude over time.

This notebook [italian-earthquake-catalogue-eda-and-plots.ipynb](https://github.com/Iron486/Italian_Earthquake_Catalogue_1985_2020/blob/main/italian-earthquake-catalogue-eda-and-plots.ipynb) is an example of what can be done. 

In [THIS](https://github.com/Iron486/Bachelor_Thesis) repository there are instead more complex notebooks to perform more complex analysis.

### **License**

[Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
