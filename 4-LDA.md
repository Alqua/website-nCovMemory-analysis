---
layout: page
title: LDA Theme analysis
---

* TOC
{:toc}

## Introduction
This is a presentation of two LDA theme analysis. The first one has been generated without an occurence filter and the second one with a filter. In our case, the first analysis tells us that the articles mostly deal with the epidemy or coronavirus in China, as expected.In the second analysis, the theme are better defined and gives us a better idea of the content of the articles besides the coronavirus epidemy. We must however keep in mind that the articles talks first about the theme extracted in the first one, especially the general extraction theme (0 in the theme selection). 

Readers are strongly encouraged to use a chinese-english dictionnary browser extension (such as [zhongwen](https://github.com/leezu/zhongwen)) if translation is needed. I also translated the [wordlists in french](https://github.com/Alqua/projet-analyse-Ncov/blob/master/ANALYSIS/DATAFRAMES/8subjects%2Bfr.csv).

The source code to generate both LDA analysis are [available on my GitHub](https://github.com/Alqua/projet-analyse-Ncov/tree/master/ANALYSIS/LDA). The whole process before that, [downloading the articles](https://github.com/Alqua/projet-analyse-Ncov/tree/master/ANALYSIS/DOWNLOAD%20ARTICLES%20with%20R) and [preparing them](https://github.com/Alqua/projet-analyse-Ncov/tree/master/ANALYSIS/CLEANING%20articles) for the analysis is also available.

## Understanding LDA representation
LDA analysis allows us to distributes the 4881 articles of the nCovMemory database into different themes. Each theme is represented with a wordlist, every word can appear into multiple lists. The proximity of the themes on the graph matters and the size too. Hovering on the words tells us in which theme that particular word is most influential. Other than that, the representations are quite easy to understand. For those wanting to know more about them see [Chuang et.al](http://vis.stanford.edu/files/2012-Termite-AVI.pdf) and [Sievert & Shirley](https://nlp.stanford.edu/events/illvi2014/papers/sievert-illvi2014.pdf) two accademic articles describing this process.


## First LDA analysis
without occurence filter (gensim filter extreme)
<iframe src="/website-nCovMemory-analysis/files/1LDA_output11s-0.html" height="870px" width="100%" style="border:none;"> </iframe>


## Second LDA analysis
With occurence filter (gensim filter extremes ->no_above= 0.26) 
<iframe src="/website-nCovMemory-analysis/files/3LDA_output8s-026.html" height="870px" width="100%" style="border:none;"> </iframe>
