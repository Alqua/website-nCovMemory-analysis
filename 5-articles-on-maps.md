---
layout: page
title: Articles on maps
---

* TOC
{:toc}

## Introduction

The first map shows the number of articles per publication's places. The data to generate the map and the graph comes from this [dataframe](https://github.com/Alqua/projet-analyse-Ncov/blob/master/ANALYSIS/DATAFRAMES/5table_media_nCov_handmade.xlsx) that I created. I did my best to extract the places of publication for each media. For newspaper or any other official media, it is rather easy to find. For a blogger, like an exchange student in Europe who came back to China, it is harder to select a place, that is why I chose to use the location provided by WeChat for every account on the app. Because the majority of articles were published on this app, this is the main source of location for the [Number of articles per publication’s places](https://alqua.github.io/website-nCovMemory-analysis/5-articles-on-maps/#number-of-articles-per-publications-places). The graph was quickly made using Python instead of R that is why it looks different then the other graphs. The code to generate the graph and the map is available [here](https://github.com/Alqua/projet-analyse-Ncov/blob/master/ANALYSIS/MAPS/merging.ipynb).

The second map shows the first 100 places' occurence in the nCovMemory Corpus. The places are extracted with [Jieba](https://github.com/fxsjy/jieba). Then we can count how many times a places appear in the list and get rid of errors if necessary (the places' extraction do not work 100%). For more details, check the code [here](https://github.com/Alqua/projet-analyse-Ncov/blob/master/ANALYSIS/MAPS/places_text.ipynb).

## Number of articles per publication's places

![image](/website-nCovMemory-analysis/image/graph_place-of-publication.png?raw=true "Number of articles per place of publication")

<iframe src="/website-nCovMemory-analysis/files/freq_places_of_publication.html" height="870px" width="100%" style="border:none;"> </iframe>

## First 100 places' occurence in nCovMemory corpus
<iframe src="/website-nCovMemory-analysis/files/places_1st100freq.html" height="870px" width="100%" style="border:none;"> </iframe>
