![SFO rental market analysis](images/SFO_pic.png)

# San Francisco rental market analysis 

This application looks for viable investment opportunities in San Francisco using data visualization, including aggregation, interactive visualizations, and geospatial analysis. 

The main features of the application are:

* Calculating and ploting the housing units per year.
![housing units per year](images/houseing_units_plot.png)

* Calculating and ploting the average prices per square foot.
![square foot per year](images/square_foot_gross_rent_plot.png)

* Interactive visualization of gross rent and average prices by neighborhood.
![Interactive visualization per neighborhood](images/neighborhood_hvplot.png)

* Interactive neighborhood map.
![neighborhood map](images/neighborhood_map.png)

The trend in rental income growth grew faster than the trend in sales prices. While all neighborhoods have registered gross rent increases, we can't say the same for sale price. Some neighborhoods recorded year-on-year sale price growth throughout while others trended down in 2015/2016. Looking at the data and visualizations, there seems to be a potential opportunity in particular in those neighborhoods where the sale price decreased during 2015/2016 as the gross rent kept on raising. Ana Vista and Outer Mission have some of the biggest drops in sale price per square footage while their gross rents grew strongly.

## Technologies

This application uses python 3.7.11 and the following packages:

* **pandas

* **GeoViews

* **hvPlot

* **Jupyter 

## Instructions

Use the `san_francisco_housing.ipynb` notebook to visualize and analyze the real-estate data.

Note that this application requires the use of hvPlot and GeoViews for the visualizations.

## Contributors

Jaime Aranda


---

## License

Licensed under the MIT License.

