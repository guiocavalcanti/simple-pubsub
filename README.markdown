## About and FAQ
simple-pubsub is a implementation of [[Bayeux Publisher Subscriber | http://svn.cometd.com/trunk/bayeux/bayeux.html ]] protocol using node.js
and socket.io developed for learning purposes.

### What is Publisher-Subscriber protocol?
Publisher-subscriber, also known as pubsub, is a message protocol where a set of
clients listen to a set of channels. When the messages are sent to a specific 
channel all the clients bound to that channel receive such message.
