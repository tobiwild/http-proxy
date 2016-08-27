# HTTP proxy

A basic HTTP proxy implemented with [goproxy](https://github.com/elazarl/goproxy)

## Usage

    docker run \
        -p 8080:8080 \
        --link some-http-container:some-host-name \
        tobiwild/http-proxy -v
