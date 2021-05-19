---
layout: page
title: Data Graphs on articles
---

* TOC
{:toc}

## Introduction
In this page, I present almost all the graphs  I created from `data.csv`, the main dataframes of the nCovMemory project. I chose not to make a selection. Some graphs are more useful than others in my opinion, but perhaps you might see something I didn't. Some of them are clearly created with an interpretation in mind. To know more about them, contact me to receive the whole essay.

Here is a screenshot of the str function in R presenting the columns of the dataframe:

![image](/website-nCovMemory-analysis/image/str_data.png?raw=true "str function of R presenting the columns of data.csv")

The code to generate the graphs is available [here](https://github.com/Alqua/projet-analyse-Ncov/tree/master/ANALYSIS/GRAPHS%20with%20R/graphs). 

There is a little toolbar available on hover for the graphs.

## Number of censored articles per category

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_category.html" height="600px" width="100%" style="border:none;"> </iframe>

## Number of articles per date

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_date.html" height="1100px" width="100%" style="border:none;"> </iframe>

## Number of newspapers' articles per date

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_date_newspaper.html" height="1100px" width="100%" style="border:none;"> </iframe>

## Number of jiemian's articles per date

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_date_jiemian.html" height="1100px" width="100%" style="border:none;"> </iframe>

## Number of articles per media

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_media.html" height="2500px" width="100%" style="border:none;"> </iframe>

## Number of articles per publication website

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_websites.html" height="800px" width="100%" style="border:none;"> </iframe>

## Number of articles per publication website without wechat/weixin

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_websites_without_weixin.html" height="800px" width="100%" style="border:none;"> </iframe>

## Number of articles per publication website crossing with media

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_media_x_website.html" height="2500px" width="100%" style="border:none;"> </iframe>

## Number of articles per publication website without wechat/weixin crossing with media

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_media_x_website_without_weixin.html" height="1200px" width="100%" style="border:none;"> </iframe>

## Number of articles per media category

This graph and the next one uses data on the type of media that I harvested myself and then merge with `data.csv`. Dataframes are available [here](https://github.com/Alqua/projet-analyse-Ncov/tree/master/ANALYSIS/DATAFRAMES).

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_media-category.html" height="600px" width="100%" style="border:none;"> </iframe>

## Number of articles per website crossing with media category

<iframe src="/website-nCovMemory-analysis/graphs/whole_data/graph_website-X-media-category.html" height="600px" width="100%" style="border:none;"> </iframe>
