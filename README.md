# reverseProxy_Go // or Loadbalancer
In this article, we are going to learn about std library's in Go 'Reverse proxy' and how to use them as load balancer.

we have two instance service server running on two different ports ie ;9091 and 9092.

Our loadBalancer is running on port :9090, it randomnly selects the serving server.

To run this setup :

1) go run main.go
2) go run port9091.go 9091
3) go run port9092.go 9092
4) for testing either use curl command or use browser
   curl http://localhost:9090 
   or
   else in browser hit below url :
   http://localhost:9090
