# blog-raster-service

the repository of the blog create a raster service tutorial

| | |
|---|---|
| Language | Python |
| Last active | 2016-12-15 |
| Original location | `github.com/noypimaps/blog-raster-service` (removed from the organization) |
| Imported | Full git history, under `blog-raster-service/` in this archive |

---

## Original README

## Sample Raster Service Setup Guide

The following application setup guide has only been tested on Ubuntu 16.04 LTS. 

#### Service dependencies

- Virtualenv
- Flask
- Numpy
- GDAL

#### Installation Steps
1. Installing system dependencies: `sudo apt-get install -y python-pip python-psycopg2 python-dev libpq-dev libgdal-dev libgdal1i gdal-bin virtualenv`

2. Check the installed gdal version: `gdalinfo --version`

3. Create a python virtual environment: `virtualenv env`

4. Installing python dependencies in virtual environment:
    
        source env/bin/activate
        pip install numpy flask
        pip install pygdal

Finally, we have installed the necessary libraries to build our service. On the next post, we will be covering the API development of our service.
