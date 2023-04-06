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
|   www.amazon.com  | 18.172.169.208 |  14  |
|   www.google.com  | 142.250.217.68 |  10  |
| www.microsoft.com | 23.251.48.212  |   8  |

- Can you identify your ISP from the intermediate server DNS names?
  - Yes, I believe that my ISP is infra.washington.edu based on the intermediate server DNS names.

- Can you identify the "class" of IP addressfor each major step in the trip?

  - Amazon 

| Hop |    IP Address   |  Class  |
|-----|-----------------|---------|
|  1  |    10.18.0.2    | Class A |
|  2  |   10.132.5.73   | Class A |
|  3  |   10.132.5.75   | Class A |
|  4  |  10.132.255.21  | Class A |
|  5  |  10.132.255.22  | Class A |
|  6  | 209.124.190.134 | Class C |
|  7  | 209.124.181.245 | Class C |
|  8  |     TIMED OUT   |   N/A   |
|  9  |     TIMED OUT   |   N/A   |
| 10  |     TIMED OUT   |   N/A   |
| 11  |     TIMED OUT   |   N/A   |
| 12  |     TIMED OUT   |   N/A   |
| 13  |   15.230.247.0  | Class A |
| 14  |  18.172.169.208 | Class A |

- Google

| Hop |    IP Address   |  Class  |
|-----|-----------------|---------|
|  1  |    10.18.0.2    | Class A |
|  2  |   10.132.5.73   | Class A |
|  3  |   10.132.5.75   | Class A |
|  4  |  10.132.255.21  | Class A |
|  5  |  10.132.255.22  | Class A |
|  6  | 209.124.190.134 | Class C |
|  7  |  74.125.51.244  | Class A |
|  8  |  142.251.70.101 | Class B |
|  9  |  142.251.55.199 | Class B |
| 10  |  142.250.217.68 | Class B |

- Microsoft

| Hop |    IP Address   |  Class  |
|-----|-----------------|---------|
|  1  |    10.18.0.2    | Class A |
|  2  |   10.132.5.73   | Class A |
|  3  |   10.132.5.75   | Class A |
|  4  |  10.132.255.21  | Class A |
|  5  |  10.132.255.22  | Class A |
|  6  | 209.124.188.134 | Class C |
|  7  |  209.81.80.168  | Class C |
|  8  |     TIMED OUT   |   N/A   |
|  9  |     TIMED OUT   |   N/A   |
| 10  |     TIMED OUT   |   N/A   |
| 11  |  23.216.81.152  | Class A |





3. Using "ngrok"
- [I was able to successfully use ngrok to host a website :D](ngrok.png)

4. Using packet-capture tools
- [I was able to successfully use Wireshark to see the DHCP traffic :D](DHCP.png)

5. Spy on your opponents
-

6. Insecure web server
- [I was successfully able to see my email and secret password when logging into an insecure site :O](insecure_site.png)
