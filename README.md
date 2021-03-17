# Web Design Homework - Web Visualization Dashboard (Latitude)

## Background

This repository contains a full web site displaying data and visualisations (graphs).

Head to index.html as the landing page for the website.

## Latitude - Latitude Analysis Dashboard with Attitude

The website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. 
* Four [visualization pages](#visualization-pages):
  * Max Temperature vs. Latitude
  * Humidity  vs. Latitude
  * Cloudiness  vs. Latitude
  * Wind Speed  vs. Latitude
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page to easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
  * The grid has two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data comes from exporting the `.csv` file as HTML using Python Pandas

