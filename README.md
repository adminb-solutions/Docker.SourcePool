# Liquidsoap and Openresty

Builds a docker image with [Liquidsoap](http://liquidsoap.info/) and [Openresty](https://openresty.org/en/). It allows you to create scripts in Openresty that could react to incoming requests and start up Liquidsoap.

## Usage

Openresty is exposed on port 8080. You should copy your custom nginx.conf configuration to the standard location `/etc/nginx.conf`.
