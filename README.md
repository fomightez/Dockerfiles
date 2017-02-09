# Dockerfiles


*(I may be wrong, but it seems the automated build settings at Docker Hub is based on a repo having a single Dockerfile, and so I think I need a separate repo for each. Unsure but I am going to keep my eyes open for examples where it isn't so. Plus even if could have multiple Dockerfiles, I didn't even think that Docker Hub might place restrictions on how long a build of a repo could be limited to but looks kike that is so, see [here](http://stackoverflow.com/questions/34440753/docker-hub-timeout-in-automated-build/34588866#34588866) and [here](http://stackoverflow.com/questions/36948145/chain-automated-builds-in-the-same-docker-hub-repository).)*  
I want to easily track my Docker efforts, and so I made this markdown file to do this.


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
