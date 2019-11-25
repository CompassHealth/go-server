# go-server
This is the Golang microservices common server start code. This handles graceful shutdowns. It also takes in a 
http.Handler function which works with a variety of routers, such as chi.Router to set up an array of handlers for
paths.
