# earl18-presentation

<!-- badges: start -->
[![Blog post](https://img.shields.io/badge/rostrum.blog-post-008900?labelColor=000000&logo=data%3Aimage%2Fgif%3Bbase64%2CR0lGODlhEAAQAPEAAAAAABWCBAAAAAAAACH5BAlkAAIAIf8LTkVUU0NBUEUyLjADAQAAACwAAAAAEAAQAAAC55QkISIiEoQQQgghRBBCiCAIgiAIgiAIQiAIgSAIgiAIQiAIgRAEQiAQBAQCgUAQEAQEgYAgIAgIBAKBQBAQCAKBQEAgCAgEAoFAIAgEBAKBIBAQCAQCgUAgEAgCgUBAICAgICAgIBAgEBAgEBAgEBAgECAgICAgECAQIBAQIBAgECAgICAgICAgECAQECAQICAgICAgICAgEBAgEBAgEBAgICAgICAgECAQIBAQIBAgECAgICAgIBAgECAQECAQIBAgICAgIBAgIBAgEBAgECAgECAgICAgICAgECAgECAgQIAAAQIKAAAh%2BQQJZAACACwAAAAAEAAQAAAC55QkIiESIoQQQgghhAhCBCEIgiAIgiAIQiAIgSAIgiAIQiAIgRAEQiAQBAQCgUAQEAQEgYAgIAgIBAKBQBAQCAKBQEAgCAgEAoFAIAgEBAKBIBAQCAQCgUAgEAgCgUBAICAgICAgIBAgEBAgEBAgEBAgECAgICAgECAQIBAQIBAgECAgICAgICAgECAQECAQICAgICAgICAgEBAgEBAgEBAgICAgICAgECAQIBAQIBAgECAgICAgIBAgECAQECAQIBAgICAgIBAgIBAgEBAgECAgECAgICAgICAgECAgECAgQIAAAQIKAAA7)](https://www.rostrum.blog/2018/09/12/crosstalk-memes/)
<!-- badges: end -->

## tl;dr

* [View the presentation in your browser](https://matt-dray.github.io/earl18-presentation/)
* [Access the code for reproducing the demos in my talk](https://github.com/matt-dray/earl18-crosstalk)
* [Blog post about this presentation](https://www.rostrum.blog/2018/09/12/crosstalk-memes/)
* [I did an 'advent of memes' on Twitter leading up to the talk; I know that's why you're really here](https://github.com/matt-dray/earl18-presentation/blob/master/memes/links.md)

## Summary

This repo contains source code for a presentation I gave at the [EARL (Enterprise Applications of the R Language) conference](https://earlconf.com/) in London on 12 September 2018.

The presentation was about use of [Joe Cheng](https://twitter.com/jcheng)'s [`crosstalk` package](http://rstudio.github.io/crosstalk/) to help solve a business problem. `crosstalk` lets you create [Shiny](https://shiny.rstudio.com/)-like 'apps' without Shiny. You might want to do this because you don't have a server to host a Shiny app. It lets filtering of one `crosstalk`-compatible [htmlwidget](https://www.htmlwidgets.org/) (e.g. `leaflet`, `DT` and `plotly`) filter other `crosstalk`-compatible htmlwidgets.

I gave this talk while I worked for the [Department for Education](https://www.gov.uk/government/organisations/department-for-education), part of the UK government. My talk was restricted to **published data only** and the content of the talk **does not reflect or constitute official government policy**. Schools were selected **at random** from open data.

## Full conference blurb

>Crosstalk: Shiny-like without Shiny
>
>Self-service interactive tools have great power to support decisions by policy-makers. Shiny apps are a natural fit for this, but it's not always easy to share them within the public sector. This is due to issues like a lack of server space, highly sensitive data and users who aren't R-savvy. 
>
>We've approached this problem in the UK's Department for Education by sharing interactive HTML widgets – embeddable JavaScript visualisation libraries – within RMarkdown outputs. Interactivity is, however, limited because selections in one widget don’t impact the data presented in another. 
>
>Joe Cheng's [Crosstalk package](http://rstudio.github.io/crosstalk/) overcomes this with shared data objects that react to user inputs, altering the content of multiple widgets on the fly. I'll explain how I used Crosstalk to develop a 'pseudo-app' for exploring schools data with the Leaflet (maps), Plotly (charts) and DT (tables) widgets inside the Flexdashboard framework and how I shared it easily with policy-making users as a static HTML file for exploration in the browser.

## Xaringan

The presentation was built using [the excellent `xaringan` package](https://bookdown.org/yihui/rmarkdown/xaringan.html) from ninja-presentation master [Yihui Xie](https://yihui.name/).

You should know about some [keyboard shortcuts](https://bookdown.org/yihui/rmarkdown/xaringan-key.html):

* to present: use `c` to clone the window (for your audience) then `p` for presenter mode (in the window on your own screen)
* `f` for fullscreen
* `t` to reset timer in presenter mode
* `b` to blackout
* `h` for more keyboard help
