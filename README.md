# krakend-pubsub
a pubsub backend for the KrakenD framework

## Backends

- Kafka

## Configuration

Just add the extra config at your backend:

```
"github.com/devopsfaith/krakend-pubsub/subscriber": {
	"subscription_url": "my_topic",
	"group_id": "group_id",
	"addresses": "host1:port1, host2:port"
}
```
```
"github.com/devopsfaith/krakend-pubsub/publisher": {
	"topic_url": "my_topic",
	"addresses": "host1:port1, host2:port"
}
```
