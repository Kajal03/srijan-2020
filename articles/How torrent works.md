# How torrent works

---

| Question   | Answer                                                            |
| ---------- | ----------------------------------------------------------------- |
| Writer     | How torrent works - Msc II year                                      |
| Editor     | Diksha Gupta                                                       |
| Status     | Edited                                                                |
| Plagiarism | None 100% Unique                                                  |

---
We all have seen or shared some pirated software or web series from someone, well sharing such pieces of data is illegal and hosting such files will certainly end up something against you but from where this kind of data comes from? Most of it comes from torrent where someone magically uploads these files and allows us to experience everything for free!

The story of torrent is based on the robustness of the peer to peer networks in a nutshell. In peer to peer or P2P networks there is no concept of server or client, no node on the network entirely designated to serve and no node is designed to just download something but the very node has same functionality to upload as well.Each file gets broken down into pieces which are then hosted by nodes that already downloaded those pieces of files, the network does not really care from where those pieces come from. One might come from a node on your LAN or from a different continent. Those pieces are then compiled natively on the device you are downloading by something called torrent client, it’s basically a software or application which can upload, download, locate pieces and help locate pieces, example of torrent are BitTorrent and μ torrent.

Defining or perhaps creating such nodes is a piece of cake but the main problem lies in how to keep track of files or I should say pieces of files. In infant state of P2P systems they relied on a tracking server which had only one purpose- to keep track of files on the network and nodes hosting those files through their public IP, but such systems are prone on too much reliance on tracking server where individual nodes can come and go without affecting the network throughput or reliability but if the tracking server goes down, the whole system goes down. So, after some failures BitTorrent architecture and protocol got introduced, it consists of an application layer protocol which provides an efficient algorithm that decide which peers to upload to and which pieces of the file to download first on a hybrid network using both client server and peer to peer network, centralized part being tracked server which is based on distributed computing. Choke algorithm is used which distinctly maintains records of uploaders and downloader which is called a different interval of time to keep record and creates the entry accordingly, and these network protocols are used on predefined ports.

In conclusion using such networks are not illegal promoting piracy is not legal, it is one of the most robust and largest peer two peer networks on this planet, and it is estimated that half of world’s internet traffic is torrent!



