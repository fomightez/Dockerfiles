# Dockerfiles


*(At first I thought the automated build settings at Docker Hub is based on a repo having a single Dockerfile, and so I thought I needed a separate repo for each. But [this repo](https://github.com/27Bslash6/docker) seems to suggest otherwise, and you can see the resulting builds [here[(https://hub.docker.com/u/funkygibbon/). Now I wish I didn't remove my recent sub-directory. Although if build a bunch together, might sometime encounter Docker Hub's restrictions on how long a build of a repo can be limited to? see [here](http://stackoverflow.com/questions/34440753/docker-hub-timeout-in-automated-build/34588866#34588866) and [here](http://stackoverflow.com/questions/36948145/chain-automated-builds-in-the-same-docker-hub-repository) for the limits info.)*  

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
