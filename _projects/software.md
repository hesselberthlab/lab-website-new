---
layout: page
title: Software development
description: 
importance: 3
category: research
---

We develop software packages and provide complete analysis workflows for our
studies. The complete collection of software packages are available on the [RBI
Github page](https://github.com/rnabioco).

Our public data sets are available at the [NCBI Gene Expression
Omnibus](https://www.ncbi.nlm.nih.gov/geo/browse/?view=series&submitter=2717).

## raer

<img style="float: right; max-width: 100px" src="/assets/img/hex/raer.png">

[`raer`](https://github.com/rnabioco/raer) facilitates analysis of RNA adenosine
editing in the Bioconductor ecosystem, enabling rigorous identification of
editing events from both bulk and single-cell mRNA sequencing experiments.

<br>

## djvdj

<img style="float: right; max-width: 100px" src="/assets/img/hex/djvdj.png">

[`djvdj`](https://github.com/rnabioco/djvdj) provides a range of tools to
analyze and manipulate single cell V(D)J sequencing data, with a particular
focus on a facile user experience, providing publication-quality plots exploring
the VDJ repertoire and associated gene expression patterns.

<br>

## clustifyr

[`clustifyr`](https://github.com/rnabioco/clustifyr) classifies cells and
clusters in single-cell RNA sequencing experiments using reference bulk RNA-seq
data sets, sorted microarray expression data, single-cell gene signatures, or
lists of marker genes.

<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[pmid=32765839]* %}
</div>

## valr

[`valr`](https://github.com/rnabioco/valr) provides tools to read and manipulate
genome intervals and signals, similar to the BEDtools suite. valr enables
analysis in the R/RStudio environment, leveraging modern R tools in the
tidyverse for a terse, expressive syntax.

<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[pmid=28751969]* %}
</div>