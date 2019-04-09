[![Build Status](https://travis-ci.org/SolaceSamples/solace-samples-java.svg?branch=master)](https://travis-ci.org/SolaceSamples/solace-samples-java)


## Build the Samples

Just clone and build. For example:

  1. clone this GitHub repository
  2. `./gradlew assemble`

## Running the Replay Sample

First start the QueueProducer to send a message to the queue. Then you can use the QueueConsumer sample to receive the messages from the queue. This will clear the queue. Get the messages to be replayed back by running QueueReplayConsumer

    ./build/staged/bin/queueProducer <host:port> <client-username>@<message-vpn> [client-password]
    ./build/staged/bin/queueConsumer <host:port> <client-username>@<message-vpn> [client-password]
    ./build/staged/bin/queueReplayConsumer <host:port> <client-username>@<message-vpn> [client-password]


## Resources

For more information try these resources:

- The Solace Developer Portal website at: http://dev.solace.com
- Get a better understanding of [Solace technology](http://dev.solace.com/tech/).
- Check out the [Solace blog](http://dev.solace.com/blog/) for other interesting discussions around Solace technology
- Ask the [Solace community.](http://dev.solace.com/community/)
