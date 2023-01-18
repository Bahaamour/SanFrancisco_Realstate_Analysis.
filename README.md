# SanFrancisco_Realstate_Analysis.
# Financial-Planner
![An image for the header of the Repository](/Images/Snf_realstate.png)

This project uses data visualization, including aggregation, interactive visualizations, and geospatial analysis, to find  and analyze properties in the San Francisco market that are viable investment opportunities.

## Technologies
This platform uses `python 3.7.13` with the following libraries imported in the first code block includes: `Pandas`, `hvplot`, `Pathlib`.

---
## Installation Guide 

In case Pandas library is not available, run the following code in your terminal:

```python

pip install pandas
```



PyViz is a Python visualization package that provides a single platform for accessing multiple visualization libraries. Two of these libraries are hvPlot and GeoViews, which was used in this application.

To install PyViz and its dependencies, run the following code in your terminal:

```python
conda install -c pyviz hvplot geoviews
```

To confirm the  installation of all the PyViz packages, run the following code in your terminal:

```python
 conda list hvplot
 
 conda list geoviews
 ```

---

## Usage

Analyzed the data and visualized it by the number of Housing Units per year.

![Sample Report](/Images/bokeh_plot.png) 

Analyzed and Visualized the data by Sale Price Per Square Foot and Average Gross Rent per year.

![Sample Report](/Images/bokeh_plot-2.png) 

Analyzed and Visualized the data by comparing the Average Sale Prices by Neighborhood.

![Sample Report](/Images/Neighborhood.png)

Used  interactive visualizations with hvPlot and GeoViews to explore the geospatial relationships in the data.

![Sample Report](/Images/bokeh_plot-4.png)



---
## Contributors

Baha Amour
---

## License

MIT.