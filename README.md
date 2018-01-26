# Fedora Docker Container for FISPACT-II
[![](https://img.shields.io/docker/pulls/fispact/fedora.svg?style=flat)](https://hub.docker.com/r/fispact/fedora) [![](https://img.shields.io/docker/build/fispact/fedora.svg?style=flat)](https://hub.docker.com/r/fispact/fedora) [![](https://images.microbadger.com/badges/license/fispact/fedora.svg)](https://microbadger.com/images/fispact/fedora)

This repository contains automated builds of Fedora images with the dependencies for [FISPACT-II](http://fispact.ukaea.uk).

For a complete list of Docker images for FISPACT-II, see the [FISPACT-II wiki](https://fispact.ukaea.uk/wiki/Docker_images).

Available on the Docker Hub as [fispact/fedora](https://hub.docker.com/r/fispact/fedora/).

### Images
The following images are included in this repository, tagged by their operating system version, compiler version and (for some systems) whether or not they include compressed nuclear data libraries for FISPACT-II:
- [![](https://images.microbadger.com/badges/image/fispact/fedora:27_gfortran_7.svg)](https://microbadger.com/images/fispact/fedora:27_gfortran_7) `27`, `gfortran-7`, [Dockerfile: *fispact/fedora:27_gfortran_7*](https://github.com/fispact/docker_fedora/blob/27_gfortran_7/Dockerfile)
- [![](https://images.microbadger.com/badges/image/fispact/fedora:26_gfortran_7.svg)](https://microbadger.com/images/fispact/fedora:26_gfortran_7) `26`, `gfortran-7`, [Dockerfile: *fispact/fedora:26_gfortran_7*](https://github.com/fispact/docker_fedora/blob/26_gfortran_7/Dockerfile)
- [![](https://images.microbadger.com/badges/image/fispact/fedora:26_gfortran_7_data.svg)](https://microbadger.com/images/fispact/fedora:26_gfortran_7_data) `26`, `gfortran-7`, `data`
