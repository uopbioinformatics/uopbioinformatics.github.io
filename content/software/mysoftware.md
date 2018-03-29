+++
# Date this page was created.
date = "2018-04-01"

# Project title.
title = "NGS Pipeline"

# Project summary to display on homepage.
summary = "A pipeline for analysis of NGS data"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["NGS", "pipeline"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
caption = ""

+++

I have written and implemented a pipeline for the analysis of NGS data from various sources (ChIP-Seq, RNA-Seq, 16S rDNA, *de novo* assembly, etc.) which I have been using in my analyses. It utilises a number of well documented and curated tools and tracks each step of the process using a centralised mysql database. I am currently working to make this portable as I believe that it may be of use to other researchers. Once this is complete, I will make the code available here.