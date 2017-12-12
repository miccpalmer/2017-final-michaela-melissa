# Final project proposal

# Title & description of the project
**California ISO Electric Grid Data Analysis**

### Your name & partner's name

- Michaela Palmer, [michpalmer](https://github.com/michpalmer)
- Melissa Ferriter, [mferriter](https://github.com/mferriter)

### A description of the data required, and how it will be obtained (e.g. URL/DOI to data source)

- The data used in this analysis comes from [California Independent System Operator Corporation (CAISO)](http://www.caiso.com/green/renewableswatch.html) renewables watch reports, which aggregates raw grid data from electricity producers in California. 
- The renewables watch reports provide actual daily renewable production  (at hourly intervals) within the ISO grid.
- Renewable energy sources included in the reports are Solar Thermal, Solar, Wind, Small Hydro, Biogas, Biomass, and Geothermal.
- An hourly breakdown of total production by resource type is also given for Renewables, Nuclear, Thermal, Imports, and Hydro. 

### 3 questions / analysis tasks you will perform on the data; in the spirit of the assignments we have been doing.

- Clean and aggregate data into usuable forms (daily values --> dataframe per month)
- Look at daily average renewables generation by source. 
- Explore high-demand/peak periods during August and September. (Compare with baseload)
- Explore seasonality/time series 
- Which sources have the most output during Peak (Jan-Feb 4-9pm) and Super Peak (July-Aug 4-9pm) time frames. 

## Preliminary Rubric (additional areas will be added)

### Project questions must illustrate all of the following tasks:

- Some form of data access / reading into R
- Data tidying preparation
- Initial data visualization
- Use of GitHub
- Reproducible execution with use of Travis
- RMarkdown writeup, with final submission as a nicely formatted PDF document that includes code and results.
- Overall clean and clear presentation of repository, code, and explanations.

### and at least three of the following skills (this list may be modified/extended):

- **Use of at least 5 `dplyr` verbs / functions**
- **Writing / working with custom R functions**
- Creating an R package for functions used in the analysis
- Interaction with an API
- **Use of regular expressions**
- Use of an external relational database
- **Preparing processed data for archiving / publication**
- Parsing extensible data formats (JSON, XML)
- Use of spatial vector data (`sf` package) and visualization of spatial data
- Creation of an R package

