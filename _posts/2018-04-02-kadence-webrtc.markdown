---
layout: post
title:  "Kadence-webrtc"
date:   2018-05-01 12:40:00 -0500
categories: kadence kademlia webrtc
---
This is what happens when you're tasked with merging two emerging techs:
1. Kademlia and distributed Databases - [Paper][kademlia-paper]
2. webrtc - [homepage][webrtc-home]

In short, kademlia is the distributed hash table protocol many decentralized peer-to-peer networks utilize to organize data. Ever used torrents? Webrtc is an up-and-coming open-source project that allows direct browser-to-browser communication without needing to go through a server.

For this current project, I'm using a github-famous repo, [kadence][kadence-github] and creating a webrtc transport-plugin that will allow this project to run a network on-top of browser connections. This is the current [progress][repo-home]. The readme is intended as thorough as possible with comments prefacing every function.

For a report on the current progress of the project, [click here][kadence-webrtc-paper].

As it stands, we were able to build a simple react demo (not yet deployable as kadence and kadence-webrtc is built in es6, not es5) that emulates a twitter message board with searching of posts by words.


[repo-home]: https://github.com/DRC9702/kadence-webrtc
[kademlia-paper]: https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf
[webrtc-home]: https://webrtc.org/
[kadence-github]: https://kadence.github.io/
[kadence-webrtc-paper]:{{ drc9702.github.io }}/download/backend-common-green.pdf
