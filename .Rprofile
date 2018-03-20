source("_R/utilities.R")

setwd("_working")
proj_dir <- getwd()
library(showtext)
library(ggplot2)
library(scales)
library(grDevices)
library(stats)
library(extrafont)

font_add_google("Poppins", "myfont")
showtext.auto()
showtext.opts(dpi = 600)

myfont <- "Century Gothic"

theme_set(theme_light(base_family = myfont) + 
             theme(legend.position = "bottom") +
             theme(plot.caption = element_text(colour = "grey50"),
                   strip.text = element_text(size = rel(1), face = "bold"))) 
update_geom_defaults("text", list(family = myfont))

# update the "most popular" pages page
source("../_R/_analytics.R")