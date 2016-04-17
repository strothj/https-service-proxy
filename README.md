# https-service-proxy
`https-service-proxy` is a simple Go project which creates a HTTPS proxy for a service hosted on another machine.

https-service-proxy is composed of three components:

* `proxy-gencert` - Creates a certificate and key pair.
* `proxy-server` - Hosts a HTTPS server which proxies incoming requests to the service endpoint.
* `proxy-client` - Hosts a HTTPS server which proxies incoming requests to the `proxy-server`.

## Usage

### proxy-gencert
