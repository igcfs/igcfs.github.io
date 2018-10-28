---
layout: page
title: About
permalink: /about/
---

# About

IGCFS project provides and develops open tools for storage, processing and analytics of gliding IGC track files. 

The project consists of three high-level modules:
* IGCFS Filesystem: provides the core, IGC file-centric distributed p2p filesystem,
* IGCFS Logbook: a flight log book, that is a simple view over the IGC filesystem for pilots,
* IGCFS Analytics: analysis tools to provide analytics and visualization of the flight data from the IGC filesystem.

# IGCFS filesystem

IGCFS filesystem is a peer-to-peer distributed filesystem specifically designed for storing and retrieving IGC files. It has been inspired and build on the [IPFS project][ipfs-project], in particular, the current implementation uses [IPFS Go][ipfs-go-ipfs] implementation. 

The project is in research and development stage. 


# IGCFS-Logbook

The Logbook is the web-based front-end to the IGC filesystem. User can upload and browse individual tracks. Users can search for the IGC files with their name in them, to claim their flights, visualize them, and so on. 

There is a prototype proof-of-concept system that uses local storage for now, to allow work on visualization and analytics to continue in parallel to the core developments of IGCFS filesystem.


# IGCFS-Analytics

Coming soon...



# License 

All the tools are open sourced under MIT license. 
See LICENSE file for details. See AUTHORS file for the list of contributors.


# Resources

You can find the [main igcfs project source code at GitHub](https://github.com/igcfs/igcfs)

All hosted dependencies can be found under [IGCFS project]



[igcfs-project]: http://igcfs.org
[ipfs-project]: http://ipfs.org
[ipfs-go-ipfs]: https://github.com/ipfs/go-ipfs
