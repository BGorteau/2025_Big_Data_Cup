# 2025 Big Data Cup

This hockey data analysis project was carried out as part of the [2025 Big Data Cup](https://stathletes.com/big-data-cup) organized by [Stathletes](https://stathletes.com/). This project focuses on the creation of a metric called Close Availability Score ($CAS$). Calculated using the Voronoi diagram method, it allows the calculation of the availability of teammates of a player who is in possession of the puck. Two other metrics called mean $CAS$ ($\overline{CAS}$) and find top $CAS$ ($FTCAS$) are derived from the first metric.

Once these metrics were in place, we were able to apply them to tracking data from three hockey games to analyze the performance of the players involved.

A detailed report of the project is available at this [link](https://github.com/BGorteau/2025_Big_Data_Cup/blob/main/Big_Data_Cup_Report.pdf) and in the repository (`Big_Data_Cup_Report.pdf`).

# Directory composition

- `Big_Data_Cup_Report.pdf`: A six pages PDF report describing the project.
- `close_availability_score.ipynb`: A notebook that contains the code of the project.
- `data`: Folder containing the action data selected to analyze our metric, plus an NHL rink representation for the plots.
- `visualizations`: Folder that contains the video of an action with the evolution of the $CAS$ metric and a plot related to player availability.
