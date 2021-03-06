Node-RED Nodes for IBM Bluemix
==============================

A collection of nodes to be used with Node-RED in [IBM Bluemix](http://bluemix.net/).

# Nodes

The current release contains the following nodes:

- TCP
    - Provides TCP input and output clients
    - Connects to remote TCP port and replies to messages from an input client
- UDP
    - Sends a message to the designated UDP host and port
- MQ Light
    - Provides MQ Light receive and send clients
    - Publishes and subscribes to chosen topics
- MongoDB
    - Perform save, insert, update or remove operations
    - Perform find, count and aggregate operations
- Twilio
    - Sends an SMS message using the Twilio service
- Weather
    - Access historical and real-time weather data from The Weather Company

Prior to version 1.0.1, this module also included nodes for the IBM Watson and Alchemy
services. They have now been moved to [node-red-node-watson](http://flows.nodered.org/node/node-red-node-watson).

### Contributing

For simple typos and single line fixes please just raise an issue pointing out
our mistakes. If you need to raise a pull request please read our
[contribution guidelines](https://github.com/node-red/node-red/blob/master/CONTRIBUTING.md)
before doing so.

### Copyright and license

Copyright 2014, 2016 IBM Corp. under [the Apache 2.0 license](LICENSE).
