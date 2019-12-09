# D3 Homework - Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

The editor of a major metro paper wants to run a series of feature stories about the health risks facing particular demographics. She's counting on to sniff out the first story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included with the assignment is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml). The current data set incldes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

### Level 1: D3 Dabbler

![4-scatter](Images/4-scatter.jpg)

Task is to create a scatter plot between two of the data variables `Smokers vs. Age`.

Using the D3 techniques, a scatter plot is created that represents each state with circle elements. This graphic is coded in the `app.js` file with data from `data.csv` by using the `d3.csv` function. The scatter plot ultimately appears like the image at the top of this section.

* State abbreviations are included in the circles.

* Axes and labels are situated to the left and bottom of the chart.

* Note:  `python -m http.server` is used to run the visualization. This hosts the page at `localhost:8000` in web browser.


* Check out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how to implement tooltips with d3-tip.
