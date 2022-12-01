
Fork of [`thomseddon/traefik-forward-auth`](https://github.com/thomseddon/traefik-forward-auth) which is a "minimal forward authentication service that provides Google oauth based login and authentication for the [traefik](https://github.com/containous/traefik) reverse proxy/load balancer."

Extended to provide username and user id of the google provider in the cookie and forwarded headers. This is useful for applications that need to know the user id of the logged in user since the email address is mutable. User id is always unique and does not change even if the email address changes.