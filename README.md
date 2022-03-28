# dac_closing_celly

Final Project for DAC 2022 through University of Chicago's Harris School

All data courtesty of Chicago Open Data Traffic - Crashes data set

Calendar Photo by Pedro Lastra via unsplash

https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

Originally deployed as a reactive dashboard with shiny features, but removed them for presentation.  Reactive features can be re-added by adding the sidebar slider
from closing_celebration.rmd to the first two pages and enveloping those plots in renderPlot({}).  Additionally you will need to remove the year filter from
the munging section and replace the year == in the plot with input$output.
