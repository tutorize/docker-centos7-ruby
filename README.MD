# Docker image based on CentOS 7 with ruby 2.3.3 / 2.3.4

## Description
This repository contains dockerfiles for building an image based on `centos/centos7` with ruby 2.3.3 / 2.3.4 included. 
Parts of the configuration are based on the official ruby images using `debian:jessie`. 

## Usage
In your `Dockerfile`: 

```
FROM tutorize/centos7-ruby:ruby-2.3.3
# or
FROM tutorize/centos7-ruby:ruby-2.3.4

# you stuff
```
