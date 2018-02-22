# Symfony-4-Docker

Project  is based on [richarvey/nginx-php-fpm](https://github.com/richarvey/nginx-php-fpm) and [symfony/skeleton](https://github.com/symfony/skeleton).

## Overview

**s4d** is for easy deployment of **Symphony 4** using **Docker**. 


> **Attention!** s4d was not created for development. You should use built-in PHP web server on your local machine.

> **Attention!** s4d does not include database server. You have to deploy it additionally.

## Usage

+ Clone repository: `git clone git@github.com:TheNovel/symfony4docker.git`
+ Put your **Symphony 4** app in `app` folder
+ Build container: `docker build -t your-name/your-project.`

## Documentation

Main part of  [richarvey/nginx-php-fpm](https://github.com/richarvey/nginx-php-fpm) documentation is appropriate for **s4d**. But some parts are inconsistent:
+ **s4d** does not support work with code from GitHub, because it should be used only as app skeleton; 

## Roadmap
+ add autogeneretaion and prolongation of Lets Encrypt certificates;
+ delete from repository all mentions of inside container work with GitHub;
+ clear all branches of other versions of original product from repository;
+ describe different scenarios of s4d usage in documentation.
