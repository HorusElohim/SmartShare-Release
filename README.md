# SmartShare Alpha V1.1

![SmartShare-Logo](https://user-images.githubusercontent.com/74312168/120508419-fcac7180-c3c7-11eb-9c04-24f5f425b500.png)

SmartShare is a peer2peer full Torrent client based on libtorrent.
The main aim behied is to made accesible sharing huge files to everyone without passing by any third party application. 

The creation of .smartshare is easy and make possible to only the receiver of this file to start downloading from the creator.
It use behiend the Kademlia network.

### Libtorrent 
libtorrent is a feature complete C++ bittorrent implementation focusing on efficiency and scalability. It runs on embedded devices as well as desktops. It boasts a well documented library interface that is easy to use. It comes with a simple bittorrent client demonstrating the use of the library.

screenshot of libtorrent's client_test
The main goals of libtorrent are:

to be CPU efficient
to be memory efficient
to be very easy to use

[Libtorrent](https://www.libtorrent.org/)


### Kademlia 
Kademlia is a distributed hash table for decentralized peer-to-peer computer networks designed by Petar Maymounkov and David Mazières in 2002.[1][2] It specifies the structure of the network and the exchange of information through node lookups. Kademlia nodes communicate among themselves using UDP. A virtual or overlay network is formed by the participant nodes. Each node is identified by a number or node ID. The node ID serves not only as identification, but the Kademlia algorithm uses the node ID to locate values (usually file hashes or keywords). In fact, the node ID provides a direct map to file hashes and that node stores information on where to obtain the file or resource.

When searching for some value, the algorithm needs to know the associated key and explores the network in several steps. Each step will find nodes that are closer to the key until the contacted node returns the value or no more closer nodes are found. This is very efficient: like many other DHTs, Kademlia contacts only {\displaystyle O(\log(n))}O(\log(n)) nodes during the search out of a total of {\displaystyle n}n nodes in the system.

Further advantages are found particularly in the decentralized structure, which increases the resistance against a denial-of-service attack. Even if a whole set of nodes is flooded, this will have limited effect on network availability, since the network will recover itself by knitting the network around these "holes".

[Kademlia](https://en.wikipedia.org/wiki/Kademlia)



## How to install SmartShare 
https://user-images.githubusercontent.com/74312168/120505780-97578100-c3c5-11eb-93fa-16a7178787fe.mp4


## How to download a Torrent or a .smartshare file 
https://user-images.githubusercontent.com/74312168/120506053-dbe31c80-c3c5-11eb-98f5-78fb24e656d3.mp4


## Hot to set your IP needed to add the DHT node ip in generated .smartshare file. 
https://user-images.githubusercontent.com/74312168/120506508-46945800-c3c6-11eb-8243-d4cc2fb0be4e.mp4


## How to create a .smartshare file and then start sharing it 
https://user-images.githubusercontent.com/74312168/120506676-72174280-c3c6-11eb-9ef0-a9a964515a99.mp4








