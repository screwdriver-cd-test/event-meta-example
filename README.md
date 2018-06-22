# event-meta-example

Example of prepopulating Meta by configuring the payload of the `POST` request to `/v4/events`.

Example payload:

```
{
	"pipelineId": 1,
	"meta": {
		"foo": "bar",
		"one": 1
	},
	"startFrom": "~commit"
}
```

From the build:
```
meta get foo
bar

meta get one
1
```
