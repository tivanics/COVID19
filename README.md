# COVID19 interactive flexdashboard app
This application was made as an assignment for the Data Science for Public Health class at Johns Hopkins Bloomberg School of Public Health

Temporal (time-series) data for the application come from [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19), and individual data for outcomes can be found here: 
[Cases](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv) 
[Deaths](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv) and 
[Recoveries](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv).

The application is built with the [Shiny](http://shiny.rstudio.com) framework for the [R programming language](https://www.r-project.org/). The application layout is produced with the [flexdashboard](http://rstudio.github.io/flexdashboard/index.html) package, and the charts and maps use [Plotly](http://plot.ly), [Leaflet.js](http://leafletjs.com/),  and [ggplot2](http://ggplot2.org/), all accessed through their corresponding R packages.  

I welcome feedback and suggestions!  [Please visit my GitHub](https://github.com/tivanics/) for contact information or [connect with me on Twitter](https://twitter.com/ivanics_t). 

The link to the app can be found [here](https://tivanics.shinyapps.io/assignment6/)
