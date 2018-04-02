---
layout: post
title:  "Kadence-webrtc"
date:   2018-04-02 12:40:00 -0500
categories: kadence kademlia webrtc
---
This is what happens when you're tasked with merging two emerging techs:
1. Kademlia and distributed Databases - [Paper][kademlia-paper]
2. webrtc - [homepage][webrtc-home]

In short, kademlia is the distributed hash table protocol many decentralized peer-to-peer networks utilize to organize data. Ever used torrents? Webrtc is an up-and-coming open-source project that allows direct browser-to-browser communication without needing to go through a server.

For this current project, I'm using a github-famous repo, [kadence][kadence-github] and creating my own webrtc transport-plugin that will allow this project to run a network on-top of browser connections. This is the current [progress][repo-home].


[repo-home]: https://github.com/DRC9702/kadence-webrtc
[kademlia-paper]: https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf
[webrtc-home]: https://webrtc.org/
[kadence-github]: https://kadence.github.io/
