# reverseProxy_Go
In this article, we are going to learn about std library's in Go 'Reverse proxy' and how to use them as load balancer.

we have two instance service server running on two different ports ie ;9091 and 9092.

Our loadBalancer is running on port :9090, it randomnly selects the serving server.
