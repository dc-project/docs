# Dc 系列项目

## dc-ctl 
包管理工具，可以通过dc-ctl 安装相关软件包,支持Debian及其衍生版，Centos7

## dc-proxy
定制化的web服务器，Caddy和Nginx

## dc-web
提供安装脚本及其他服务

## dc-pkg
提供安装脚本模版

## dc-dash
向psdash致敬的定制版,提供各项服务数据的可视化操作

## dc-test
主要用于测试的镜像服务

## core-image
上述服务可能用到的基础镜像

# Todo

## dc-ctl 安装基础服务
dc-ctl install dc-dash 
dc-ctl install dc-proxy
dc-ctl install dc-web

## 安装相关服务(dc-web,dc-pkg)
dc-ctl web list (列出服务)
dc-ctl web install etcd
dc-ctl web install calico-node
dc-ctl web install docker
dc-ctl web install k8s

## dc-proxy 
apt/yum/pypi：提供相关包





