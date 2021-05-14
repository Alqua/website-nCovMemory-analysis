---
layout: page
title: LDA Theme analysis
---

* TOC
{:toc}

## Introduction
This is a presentation of two LDA theme analysis. The first one has been generated without an occurence filter and the second one with a filter. In the second analysis, the theme are better defined but we must keep in mind that the articles talks first about the theme extracted in the first one, especially the general extraction theme (0 in the theme selection). In our case, the first analysis tells us that the articles mostly deal with the epidemy or coronavirus in China, as expected.

Readers are strongly encouraged to use a chinese-english dictionnary browser extension (such as perapera) if translation is needed.

The source code to generate both LDA analysis are available on my GitHub.

## First LDA analysis
without occurence filter (gensim filter extreme)
<iframe src="website-nCovMemory-analysis/files/1LDA_output11s-0.html" height="870px" width="100%" style="border:none;"> </iframe>


## Second LDA analysis
With occurence filter (gensim filter extremes ->no_above= 0.26) 
<iframe src="website-nCovMemory-analysis/files/3LDA_output8s-026.html" height="870px" width="100%" style="border:none;"> </iframe>
