# How Torrent works

---

| Question   | Answer                                                            |
| ---------- | ----------------------------------------------------------------- |
| Writer     | Abhinav Kumar - Msc II year                                  |
| Editor     | Diksha Gupta                                                      |
| Status     | Edited                                                |
| Plagiarism | None 100% Unique                                                  |

---
At one point or another, we have shared software or everyone's favourite these days, web series, with someone. Most of these, we download using "torrents". Uncountable files readily available for free download. But, where does this data come from and how do the services that we use torrent have it all?

The story of torrent is based on the robustness of the peer to peer(P2P) networks. In P2P networks there is no concept of server and client. No node on the network is entirely designated to serve and no node just downloads. Both of these functionalities are performed by each node that exists on the network. Files on the network are broken down into pieces which are then hosted by multiple nodes. These nodes have downloaded file pieces already with no regards to their point of origin. One might come from a node that exists on your own LAN or even from a different continent. Torent Client, a software/ application which can upload, download and locate pieces, then compiless the downloaded pieces natively on the device that you are downloading to. BitTorrent and μtorrent are two famous torrent clients.

Creating nodes is not a major task in itself, the problem lies in finding ways to keep track of files or as we now know, pieces of files. During the infancy of P2P systems, the reliance was on a tracking server which had only one purpose - to keep track of nodes on the network and the files that they hosted using their public IP address. Unfortunately, such systems are bound to fail. The dependency on the tracking server gradually becomes costly. Individual nodes can come and go without affecting the network throughput but if the tracking server goes down, the whole system goes down. To remedy the deficiencies caused by this design, BitTorrent architecture and protocol got introduced. It consists of an application layer protocol which provides an efficient algorithm for decision-making. Both the elements - the peers to upload to, and the pieces of a file that should be downloaded first are decided by this algorithm. It works on a hybrid network using both client server and peer to peer network. The tracking server here is based on distributed computing. Choke algorithm is used which distinctly maintains state of uploaders and downloaders. This is determined in different intervals of time to keep record on their contribution, so that new nodes will be able to locate the resources on the network in an effective manner. It also penalizes the nodes that rarely host resources on the network, thus keeping the functioning of the network streamlined.


Torrent is one of the most robust and largest peer to peer network on this planet, and it is estimated that half of the world’s internet traffic is torrent!



