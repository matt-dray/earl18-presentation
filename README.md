# earl18-presentation

Slides for a presentation given at the (EARL (Enterprise Applications of the R Language) conference)[https://earlconf.com/2018/london/#speakers] in London on 12 September 2018.

# Blurb

>Crosstalk: Shiny-like without Shiny

>Self-service interactive tools have great power to support decisions by policy-makers. Shiny apps are a natural fit for this, but it's not always easy to share them within the public sector. This is due to issues like a lack of server space, highly sensitive data and users who aren't R-savvy. 

>We've approached this problem in the UK's Department for Education by sharing interactive HTML widgets – embeddable JavaScript visualisation libraries – within RMarkdown outputs. Interactivity is, however, limited because selections in one widget don’t impact the data presented in another. 

>Joe Cheng's Crosstalk package (http://rstudio.github.io/crosstalk/) overcomes this with shared data objects that react to user inputs, altering the content of multiple widgets on the fly. I'll explain how I used Crosstalk to develop a 'pseudo-app' for exploring schools data with the Leaflet (maps), Plotly (charts) and DT (tables) widgets inside the Flexdashboard framework and how I shared it easily with policy-making users as a static HTML file for exploration in the browser.

>(Note that this talk is restricted to published data and the content of this talk does not reflect or constitute official policy.)