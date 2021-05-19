---
layout: page
title: Data Graphs on deleted articles
---

* TOC
{:toc}

## Introduction
On this page are published data graphs on deleted or censored articles of the nCovMemory database, as they are labeled in the main dataframe of the project `data.csv`. in R, they are selected like this: `censored_articles <- subset(data, data$is_deleted==TRUE)`

In the context of the internet in China, deleted articles are often a result of censorship or self-censorship. We must keep cautious with this data though, as it might as well be real technical problems that triggered the deletion. Furthermore, the deletion of an article is only recorded up to the update date stated in `data.csv`, it won't appear as deleted if that event happened after.

As for the general graphs of the articles, I chose to published almost all the graphs I created for this subset of the data without making a selection, in case a reader can see something I did not and because the format makes the navigation rather easy.

The code to generate the graphs is available [here](https://github.com/Alqua/projet-analyse-Ncov/blob/master/ANALYSIS/GRAPHS%20with%20R/deleted_articles_graphs/censored_articles_graph.R)

## Number of censored articles per category

<iframe src="/website-nCovMemory-analysis/graphs/censored/censored_graph_category.html" height="600px" width="100%" style="border:none;"> </iframe>


## Number of censored articles per date

<iframe src="/website-nCovMemory-analysis/graphs/censored/censored_graph_date.html" height="1100px" width="100%" style="border:none;"> </iframe>

## Number of censored articles per media

<iframe src="/website-nCovMemory-analysis/graphs/censored/censored_graph_media.html" height="1100px" width="100%" style="border:none;"> </iframe>

## Number of censored articles per publication website

<iframe src="/website-nCovMemory-analysis/graphs/censored/censored_graph_websites.html" height="600px" width="100%" style="border:none;"> </iframe>

## Number of censored articles per media, crossing with publication website

<iframe src="/website-nCovMemory-analysis/graphs/censored/censored_graph_websites_x_media.html" height="1100px" width="100%" style="border:none;"> </iframe>

## Number of articles per alternative publication website

<iframe src="/website-nCovMemory-analysis/graphs/censored/censored_graph_alternative.html" height="1100px" width="100%" style="border:none;"> </iframe>

## Number of articles per alternative publication website crossing with original publication website

<iframe src="/website-nCovMemory-analysis/graphs/censored/censored_graph_alternative_x_website.html" height="1100px" width="100%" style="border:none;"> </iframe>

## Number of articles per media category

<iframe src="/website-nCovMemory-analysis/graphs/censored/censored_graph_media-category.html" height="600px" width="100%" style="border:none;"> </iframe>

## Number of articles per publication website crossing with media category

<iframe src="/website-nCovMemory-analysis/graphs/censored/censored_graph_website-X-media-category.html" height="700px" width="100%" style="border:none;"> </iframe>


