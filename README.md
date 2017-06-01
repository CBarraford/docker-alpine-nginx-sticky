docker-alpine-nginx-sticky
============================

This is based on
https://github.com/nginxinc/docker-nginx/tree/014e624239987a0a46bee5b44088a8c5150bf0bb/stable/alpine.
The main difference is sticky module is included in the compilation of nginx. 

Copy or mount any nginx configuration files into `/etc/nginx/conf.d` and they should
get loaded.
