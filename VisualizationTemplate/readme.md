# Visualization template
This template collects some often used methods for digital storytelling. In particular the scrolling aspect is common, using a fixed background image with text scrolling over it.

For diagrams/charts, we have included the JavaScript library [Chart.js](https://www.chartjs.org/), and initialized a bar chart for displaying comparative data from a dataset. The dataset is found in the file election_halden_approvedvotes_complete.csv, and was converted to JavaScript arrays using [ConvertSimple](https://www.convertsimple.com/convert-csv-to-javascript-array/).

We have also included a script that allow to check if HTML elements are within the viewport. In this template, we are using the script to change a background image of a scrolling section depending on what information is currently in the browser viewport.