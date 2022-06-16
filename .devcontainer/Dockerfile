FROM rocker/rstudio:3.6.3-ubuntu18.04


RUN apt-get update \
    && apt-get install -y --no-install-recommends \
    libxml2-dev libz-dev tzdata cmake vim git # add any additional libraries you need

CMD ["/init"]