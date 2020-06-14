Provisioning a new site
=======================

## Required packages;

* nginx
* python3
* virtualenv + pip
* git

eg, on Ubuntu:
    sudo add-apt-repository ppa:fkrull/deadsnakes
    sudo apt-get install nginx git python36 python3.6-env


## Nginx Virtual Host config

* see gunicorn-systemd.template.service
* replace SITENAME with, eg, staging.my-domain.com

## Folder structure:

/home/username
|-- sites
    |-- SITENAME
        |-- database
        |-- source
        |-- virtualenv
        |-- static