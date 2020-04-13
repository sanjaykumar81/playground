
## Difference between layer 4 and layer 7 load balencers: 

- Layer 4 LB
  - Work on the Layer 3 and 4 of the OSI network model
  - Layer 4 load balancers simply forward network packets to and from the upstream server without inspecting the content of the packets. 
  - Layer 4 load balancers make their routing decisions based on address information extracted from the first few packets in the TCP stream, and do not inspect packet content.
  - Read request packet-by-packet basis and uses NAT for forwording the request and response  
  - A Layer 4 load balancer is often a dedicated hardware device supplied by a vendor and runs proprietary load-balancing software, and the NAT operations might be performed by specialized chips rather than in software.
  Fast and Secure


- Hypertext Transfer Protocol (HTTP) layer 7 LB
  - Layer 7 load balancers base their routing decisions on various characteristics of the HTTP header and on the actual contents of the message 
  - Layer 7 load balancing proxies can read requests and responses in their entirety. 
  - It then makes a new TCP connection to the selected upstream server (or reuses an existing one, by means of HTTP keepalives) and writes the request to the server.


## Difference between layer 4 and layer 7 load balencers another view

- Operate on different level on OSI model of networking layers
- Layer 4 loadbalencer operate on layer 3 and layer4 of the OSI model dealing with IP and TCP. While Layer 7 loadbalancers operate on Layer 7 dealing with HTTP protocal.
- Layer 4 loadbalancer forward the request to destination server and forward back the response from server to client. Forward not create new request. Layer 7 loadbalancer inplace of forwarding the request makes a new request on behalf of the client to the server. A new request is created. 
- Layer 4 load balancer read request packet-by-packet basis, do not inspect packet content and uses NAT for forwording the request and response, while Layer 7 load balancing proxies can read requests and responses in their entirety and  based on the content can then make the decision of redirecting the request. 
- Layer 4 load balancer are dumb and layer 7 are smart in above context. 
- Usually layer 4 loadbalancer  are fast and secure as they don't read the whole reqeust and its content. Layer 7 load balancing is more CPU‑intensive than packet‑based Layer 4 load balancing.

## Also refer below links for more detail:

- https://www.nginx.com/resources/glossary/layer-4-load-balancing/

- https://freeloadbalancer.com/load-balancing-layer-4-and-layer-7/

