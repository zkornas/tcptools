# tcptools
INFO 314 TCP / IP Tools

This assignment helps us develop an understanding of networking tools

1. Ping
- What was the min/avg/max/stddev for each site?

|      Website      |    min   |    avg   |    max   | Std Dev  |
|-------------------|----------|----------|----------|----------|
|   www.amazon.com  | 1.139 ms | 1.176 ms | 1.223 ms | 0.034 ms |
|   www.google.com  | 1.093 ms | 1.168 ms | 1.230 ms | 0.042 ms |
| www.microsoft.com | 1.018 ms | 1.141 ms | 1.234 ms | 0.076 ms |

- Was there any packet loss on any of the pings?
  - There was 0% packet loss when pinging each website.
  
- Did the IP address change for a given website between pings?
  - No, the IP address did not change between pings for each website.
  
  
2. Traceroute
- What was the target server's IP address and number of hops?
  
|      Website      |    Target IP   | Hops |
|-------------------|----------------|------|
|   www.amazon.com  | 18.172.169.208 |  64  |
|   www.google.com  | 142.250.217.68 |  10  |
| www.microsoft.com | 23.251.48.212  |  64  |

- Can you identify your ISP from the intermediate server DNS names?
  - Yes, I believe that my ISP is infra.washington.edu based on the intermediate server DNS names.

3. Using "ngrok"
- [link](ngrok.png)
