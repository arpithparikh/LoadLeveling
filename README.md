Load balancing refers to efficiently distributing incoming network traffic across a group of backend servers, also known as a server farm or server pool.
Let’s say in the banking system, to simulate the process of n tasks require set of m servers. Each requests are put on queue if the load is more than expected. There is s queue chosen at random. 
Let’s say, there are 25 request needs to serve using 2 servers, but each server only simulate 10 requests at time. So for another 5 requests needs to wait until the two servers are processed the 20 requests first. So, once the server would available to serve the request, during that time, server would handle another 5 requests.

