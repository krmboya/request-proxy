# request-proxy
Proxy's http GET requests via nginx to other sites

Send a `GET` request with a header named `Upstream-URL`	whose value is the site
a request is being proxied to.

Example using curl:

`curl -H "Upstream-URL: http://www.nation.co.ke/latestrss.rss" my.proxy.site.com`

Replace `my.proxy.site.com` with the URL of the proxy server.

The initial plan was to implement the proxy using a python script running behind
a web server, but decided to keep things simple and do it in the webserver itself