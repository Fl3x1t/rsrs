# rsrs
Really Simple Registry Server

The RSRS is a development tool which makes it easy to manage network configurations in a distributed system. Therefore each application shall register to the Registry Server. So the applications themselves only need to know the place of the Registry Server and the alias of the applications they work with.

Roadmap:
Version 0.1
-----------
Implementation of a simple socket based server
Integration of the RSRS data model Version 1.0
Integration of the RSRS protocol Version 1.0

Version 0.2
-----------
Implementation of RESTful interface for RSRS
Integration of a Web Interface for RSRS

Version 0.3
-----------
Implementation of a optional heartbeat functionality
Implementation of a monitoring port for heartbeat functionality

To be continued


This application should only be used for development and local area network. It does not take care about security or stability needed for enterprise networks.
