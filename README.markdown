## About
A simple and extremely naive implementation of [Bayeux Publisher Subscriber](http://svn.cometd.com/trunk/bayeux/bayeux.html) protocol using [node.js](https://github.com/joyent/node)
and [socket.io](https://github.com/learnboost/socket.io-node) for learning purposes.

### What is Publisher-Subscriber pattern?
Publisher-subscriber, also known as pubsub, is a messaging pattern where a set of
clients listen to a set of channels. When the messages are sent (published) to a
specific channel, all the clients bound to that channel (subscribers) receive
such message.

### What is Bayeux Protocol?
Bayeux is a protocol specification of the pubsub pattern designed to work over
HTTP.
