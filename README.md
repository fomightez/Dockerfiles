# Dockerfiles


*(At first I thought the automated build settings at Docker Hub is based on a repo having a single Dockerfile, and so I thought I needed a separate repo for each. But [this repo](https://github.com/27Bslash6/docker) and [this one](https://github.com/andrejsavikin/Dockerfiles) indicate otherwise, and you can see the resulting builds [here](https://hub.docker.com/u/funkygibbon/) and [here](https://hub.docker.com/r/andrejsavikin/ubuntu-openjdk-8-jre/), respectively. Now I sort of wish I didn't remove my recent sub-directory hierarchy. Although if build a bunch together, might sometime encounter Docker Hub's restrictions on how long a build of a repo can be limited to? see [here](http://stackoverflow.com/questions/34440753/docker-hub-timeout-in-automated-build/34588866#34588866) and [here](http://stackoverflow.com/questions/36948145/chain-automated-builds-in-the-same-docker-hub-repository) for the limits info.)*  

I want to easily track my Docker efforts, but for now have separate repos for those efforts, and so I made this markdown file to do this.


----
Dockerfiles for Docker images that connect to Mac Desktop
=========================================================

Dockerfiles for Docker images that make containers (generally linux-based) that when run, can display to the screen of a properly set up Mac OSX system.


Associated Docker hub images and github repos
------------------------

Chromium:  
[![](https://images.microbadger.com/badges/image/fomightez/chromium.svg)](https://microbadger.com/images/fomightez/chromium "Get your own image badge on microbadger.com")  
https://hub.docker.com/r/fomightez/chromium/

https://github.com/fomightez/docker-mac-linuxchromium

----


----
Dockerfiles for Bioinformatics Docker images
============================================

Dockerfiles for Docker images that make containers (generally linux-based) that aid in performing and documenting replicable (maybe even repeoducible bioinformatics efforts


Associated Docker hub images and github repos
------------------------

rnaseq_wang:  
[![](https://images.microbadger.com/badges/image/fomightez/rnaseqwang.svg)](https://microbadger.com/images/fomightez/rnaseqwang "Get your own image badge on microbadger.com")  

Complete container for all command line processing as directed in  
Using RNA-seq for Analysis of Differential Gene Expression in Fungal Species.
Wang C, Schröder MS, Hammel S, Butler G.
Methods Mol Biol. 2016;1361:1-40. doi: 10.1007/978-1-4939-3079-1_1. PMID: [26483013](https://www.ncbi.nlm.nih.gov/pubmed/26483013)

https://hub.docker.com/r/fomightez/rnaseqwang/

https://github.com/fomightez/rnaseq_wang

----

cufflinks_docker:  
[![](https://images.microbadger.com/badges/image/fomightez/rnaseqcufflinks.svg)](https://microbadger.com/images/fomightez/rnaseqcufflinks "Get your own image badge on microbadger.com")

Docker container for Cufflinks for Transcriptome assembly and differential expression analysis for RNA-Seq

https://hub.docker.com/r/fomightez/rnaseqcufflinks/

https://github.com/fomightez/cufflinks_docker

----
