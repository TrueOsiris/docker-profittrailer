ProfitTrailer for Docker
------------------------

[![Docker Pulls](https://img.shields.io/docker/pulls/trueosiris/profittrailer.svg)](https://hub.docker.com/r/trueosiris/profittrailer/) [![Docker Stars](https://img.shields.io/docker/stars/trueosiris/profittrailer.svg)](https://hub.docker.com/r/trueosiris/profittrailer/) [![Docker Automated buil](https://img.shields.io/docker/automated/trueosiris/profittrailer.svg)](https://hub.docker.com/r/trueosiris/profittrailer/) [![Docker Build Statu](https://img.shields.io/docker/build/trueosiris/profittrailer.svg)](https://hub.docker.com/r/trueosiris/profittrailer/) ![GitHub last commit](https://img.shields.io/github/last-commit/trueosiris/docker-profittrailer.svg)

Current profittrailer version: v2.2.12

**ProfitTrailer** is a smart crypto currency trading bot. It gives you the ability to trade using different exchanges in a fast and simple way.
For easier deployment, I set up a *Docker Container*.

For more information about ProfitTrailer :

 - Official website : https://profittrailer.com
 - Wiki : https://wiki.profittrailer.io
 - Github : https://github.com/taniman/profit-trailer

Usage
-----

Start a new container with a volume for your config files

    docker run -d -v "$( pwd )/mybot:/app/ProfitTrailer" trueosiris/profittrailer

Credit
------

Based on the work of Beemster, go check it out here
https://github.com/beemster/profittrailer \
Forked from 
https://github.com/rafffael/profit-trailer/ \
No credit goes to myself.
