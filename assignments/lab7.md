# Lab 7

## Goals

* Configure docker images with *docker-compose*
* Setup *node-exporter* on 2 docker images
* Setup *prometheus* on 1 docker image
* Setup *grafana*

## Details

Configure at least 2 docker images to have *node-exporter*, using *docker-compose* link the containers with one running *prometheus* to get the data from the *node-exporter* containers when running.

## Grafana

Setup *grafana* preferably on it's own container to pull data from the *prometheus* container. Microservices by convention are 1 service per container; however, integrating monitoring like *prometheus* and *grafana* is kind of an added layer.

## Answer Questions about Prometheus/Grafana

Answer the following questions on Canvas.

1. What is *prometheus*?
2. What is *grafana*?
3. Why might you want to use *prometheus*?
4. When do such tools really become useful?
5. When might you want to use them personally?

## Submitting Assignment

Commit to the *assignment7* branch of your CSCI345 organization repo with the following:

* Dockerfiles
* docker-compose.yml
* Any other files needed

Verify that you can see your files on GitHub for the repo under the *assignment7* branch. Also make sure your branch is named correctly or it will not be pulled for grading.

Also don't forget to answer the questions on Canvas or you won't be graded as well.


## Resources

1. https://prometheus.io/
2. https://linuxhint.com/install_prometheus_ubuntu/
3. https://prometheus.io/docs/visualization/grafana/
