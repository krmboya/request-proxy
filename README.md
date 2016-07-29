# request-proxy
Proxy's http get requests to other sites

## Request

Send a get request with query parameter `url` set to the URL being retrieved

## Reponse

A JSON object with the following attributes:

`status` - the status code returned from the `url`

`headers` - the headers returned by url

`content` - body of the response returned from `url`
