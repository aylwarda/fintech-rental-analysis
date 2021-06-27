# fintech-rental-analysis
This project is my FinTech homework, incorporating hvPlot, PyViz, Plot.ly, Mapbox and some analysis of real-estate data, graphing of results, et cetera. It uses Jupyter Labs Notebooks and my work builds on coursework that I am involved in.

---
## Instructions
Within this Project, there are 2 Jupyter Notebooks.  The primary one being the "Dashboard".
 - Rental Analysis (rental_analysis.ipynb)
 - The Dashboard (dashboard.ipynb)

As the reader/user, all you need do in order to make the most of the dashboard and the analysis within it, is: -  
1. execute run_dashboard.sh
2. interact with the Dashboard

### The Dashboard (primary)
The dashboard is the main reason for this project and shows some real estate analysis of Toronto from 2001 to 2016. Once it has been served, it shows an hvPlot Panel with a number of tabs, each of which shows a specific category of the analysis, e.g. "yearly market analysis" or "most expensive neighbourhoods". There are 5 tabs in total, with a number of them showing static plots, while others allow one to interact with them, changing inputs.

### Rental Analysis (secondary)
The rental analysis is effectively everything served to the main Dashboard, but individually, i.e. the data is extracted and prepared, section by section, then the data for that section plotted.  As part of the Notebook, a file with some data sliced by year is written to `.\Data\toronto_unit_type_totals_per_year.csv` ... just an FYI.

*Note 1*: All data and plots within `rental_analysis.ipynb` are the same as are presented for the Dashboard.

*Note 2*: Before you begin, the sample data, which is used for the analysis, is available within the `Data` folder and supplied by the University and their partner Trinity Education LLC.

---
## Acknowledgements
### Sources
More on some of the components/libraries used for this little project: -
 - Mapbox and all of its amazingness [here](https://docs.mapbox.com/)
 - Plot.ly (and express) found [here](https://panel.holoviz.org/api/panel.layout.html?highlight=tabs#panel.layout.tabs.Tabs) 
    - Specifically the references to sunbursts [here](https://plotly.com/python/sunburst-charts/), but there are tons of awesome graphs available
 - hvPlot and all about it, found [here](https://hvplot.holoviz.org/index.html)
    - hvPlot Tabs (panels), found [here](https://panel.holoviz.org/api/panel.layout.html?highlight=tabs#panel.layout.tabs.Tabs)
 
