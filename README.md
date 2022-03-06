# krakend-pubsub
a pubsub backend for the KrakenD framework

## Backends

- Kafka

## Configuration

set the environment variable KAFKA_BROKERS="host1:port1, host2:port" and add the extra config at your backend:

```
"github.com/devopsfaith/krakend-pubsub/subscriber": {
	"subscription_url": "my_topic",
	"group_id": "group_id"
}
```
```
"github.com/devopsfaith/krakend-pubsub/publisher": {
	"topic_url": "my_topic"
}
```
