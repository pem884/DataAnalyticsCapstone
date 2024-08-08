# Patrick Moore: Data Analytics capstone project

## Analyzing and visualizing air traffic subject to noise complaints

Flights noticed at a location in New Jersey were logged using the webapp [airnoise.io](airnoise.io). The data was then exported and combined with public ownership information, research, and local knowledge to establish who operates the aircraft, where they were likely coming from or going, and where they might be based.

The analysis is performed in R, first using RStudio and later moving to VSCode for development. See the GitHub "Projects", "Issues", and past commits for more insights about the development process. Though I was the sole contributor, my intent was to tailor the process to invite collaboration and review.

From a technical perspective, I embedded the R code within a Quarto document which outputs a Shiny app (dashboard). The dashboard is published using `quarto::quarto_publish_app(server = "shinyapps.io")`, and is now hosted with shinyapps.io at the following URL:

[https://nz1ytm-patrick-moore.shinyapps.io/aircraftactivity/](https://nz1ytm-patrick-moore.shinyapps.io/aircraftactivity/)

The first "page" or overarching tab of this dashboard presents some information about the analytical process, and subsequent tabs visualize the data.

If I started another project similar to this one, I might use Quarto again, but I would likely not use Shiny because of its hosting requirements. As impressive and educational as I found Shiny to be - and capable, if one has a server for it - it may not be the most efficient choice on a "Free Tier" budget. On the other hand, it really is quite powerful and I found it to be rather accessible for the end-user (see the text size and plot bar width controls I added). It may be that this interactivity outweighs the development time, increased requirements, and other potential drawbacks.
