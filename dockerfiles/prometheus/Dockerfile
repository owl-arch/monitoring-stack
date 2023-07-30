
# Inspiração
#   https://prometheus.io/docs/introduction/first_steps/
#
# Linux Alpine versão última
FROM alpine as base

LABEL maintainer="marcos.antonio.carvalho@gmail.com"
LABEL version="1.0"

ENV prometheus_version 0.x.x

# Atualiza o sistema
RUN apk update && apk upgrade  

##---------------------------##
##  2a fase - REQUERIMENTOS  ##
##  COMPILAÇÃO E CONSTRUÇÃO  ##
##---------------------------##
FROM base as builder
RUN apk add  prometheus 
