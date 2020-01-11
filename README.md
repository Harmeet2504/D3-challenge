# Creating Visualizations using D3

## Summary
The project aims to understand health risks facing particular demographics by examining information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System and creating visualizations using D3.

## Source of Data
[https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml). The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

### Visualizations 
Using the D3 techniques, a scatter plot is created between two of the data variables `Smokers vs. Age` each circle elements representing each state.  This graphic is coded in the `app.js` file with data from `data.csv` by using the `d3.csv` function. The scatter plot appears like the image below: 
![4-scatter](Images/4-scatter.jpg)

* State abbreviations are included in the circles.

* Axes and labels are situated to the left and bottom of the chart.

* Note:  `python -m http.server` is used to run the visualization. This hosts the page at `localhost:8000` in web browser.


* Check out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how to implement tooltips with d3-tip.
