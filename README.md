# Plotly
![website](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/Website.png)

## Deliverable 1: Horizontal Bar Chart
Full code can be found at [charts.js](https://github.com/pfrivas/Plotly/blob/main/Challenge/charts.js)

### Code is written to create the arrays when a sample is selected from the dropdown menu
```
function buildCharts(sample) {}
```
### Code is written to create the trace object in the buildCharts() function
- The y values are the otu_ids in descending order
```
```
- The x values are the sample_values in descending order
```
```
- The hover text is the otu_labels in descending order.
```
```
### Code is written to create the layout array in the buildCharts() function that creates a title for the chart
```
```
### Code is written to create the trace object in the buildCharts() function
- The top 10 sample_values are sorted in descending order
```
```
- The top 10 sample_values as values
```
```
- The otu_ids as the labels
```
```
![bar_chart](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/Horizontal%20Bar%20Chart.png)
![working_bar_chart](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/Working%20Bar%20Chart.png)

## Deliverable 2: Bubble Chart
Full code can be found at [charts.js](https://github.com/pfrivas/Plotly/blob/main/Challenge/charts.js)

### The code for the trace object in the buildCharts(); function does the following:
- Sets the otu_ids as the x-axis values
```
```
- Sets the sample_values as the y-axis values
```
```
- Sets the otu_labels as the hover-text values
```
```
- Sets the sample_values as the marker size
```
```
- Sets the otu_ids as the marker colors
```
```
### The code for the layout in the buildCharts(); function does the following:
- Creates a title
```
```
- Creates a label for the x-axis
```
```
- The text for a bubble is shown when hovered over
```
```

### When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu

![bubble_chart](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/Bubble%20Chart.png)
![working_bubble_chart](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/Working%20Bubble%20Chart.png)

## Deliverable 3: Gauge Chart
Full code can be found at [charts.js](https://github.com/pfrivas/Plotly/blob/main/Challenge/charts.js)

### The code to build the gauge chart does the following: 
- Creates a title for the chart.
```
```
- Creates the ranges for the gauge in increments of two, with a different color for each increment.
```
```
- Adds the washing frequency value on the gauge chart.
```
```
- The indicator shows the level for the washing frequency on the gauge.
```
```
- The gauge is added to the dashboard.
```
```
- The gauge fits in the margin of the <div> element.
```
```
### When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working
  
![gauge_chart](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/Gauge%20Chart.png)
![working_gauge_chart](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/Working%20Gauge%20Chart.png)
  
  
## Deliverable 4: Customization of the Dashboard
  
Full customization code can be found at [style.css](https://github.com/pfrivas/Plotly/blob/main/Challenge/style.css)
  
### 3 Customizations
- Changed background color and body text color
```
  body {
    background-color: rgb(40, 190, 190);
    color: #18979e;
   
  }
```
- Changed jumbotron background image
```
   .jumbotron {
    background-image: url("./Images/bacteria.png");
    background-size: 100% 100%;
    text-align: center;
    color: rgb(252, 250, 250);
}
```
- Changed jumbotron font size
```
  .jumbotron h1 {
  font-size: 60px;
  font-weight: 500;
}
```
  
![customized_webpage](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/Website_Customized.png)
  
### ID 940’s data as default and all three charts working when a sample is selected from the dropdown menu
  
**940 Sample Data**

  ![940](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/All%20Charts%20with%20940%20Data.png)

**Different Sample Selected**

  ![960](https://github.com/pfrivas/Plotly/blob/main/Challenge/Images/All%20Charts%20with%20960%20Data.png)
