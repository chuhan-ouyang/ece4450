Application
* File Transport
* VoIP
* Interactive Games
* Email

Throughput
* Elastic
* Audio: 4kbps - 1Mbps

Delay Sensitivity
* <= 100ms

Trnasport Protocols
* VoIP, UDP always
* Email, TCP
* Variations in QoS parameters are dealt with at the transport layer

Addressing
* Take place more down than the application layer
* Port number map to the processes, occuring at the transport layer
* IP Addresses point to a host, that can be running many processors (network layer)


HTTP
* Hypertext Transfer Protocol
* Client server model

Connections
* Persistent
* Non-Persistent
  * HTTP is one way communication
  * The underlying TCP connection can be closed after one transaction
  * Close after Tx, Rx
* Persistent
  * Keep the connection open until all transactions are finished
* Stateless
  * The server does not remember anything about your request
    * Enhances security (no stealing information)
    * Greatly simplifies the server architecture, support more simultaneous transactions
  * Benefit of retaining information: remember information about a user to better target ads
    * Use cookies: maintain states
    * There are more ways to retain states beyond cookies

Content Distribution Network
* Specific server (dominating computer traffic)
* Edge server, caching
* CDNs are used by media and retain companies and video streaming companies
* Dominates the bandwidth on internet
* Total internet traffic
  * Downstream = internet to device, upstream = device to internet
  * Video streaming: downstream - 48%, upstream - 20%
  * Social media: downstream - 20%, upstream - 16%
  * Web traffic: downstream - 31%, upstream - 23%


Content Distribution on Edge Servers

File Transfer Protocol
* RFC: Request for comment
    * Before TCP/IP
* Client-Server architecture
* FTP is stateful
  * Eg. Large file, don't want to reset connection when there are glitches in file transfer
* All transport have associated port number/process

Peer to Peer Communication
* No Servers, no infrastructure
* Usecases
  * Sony vs. Universal Studios

Peer to Peer Distribution
* Scalability: Self-Scaling
* P2p is much more efficient for passing large amount of data to a lot of servers
* However, client-server is still used for CDN
