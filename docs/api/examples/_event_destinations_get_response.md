<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"created_at": "2024-10-28T15:37:47Z",
	"description": "kinesis dev stream 1 of 3",
	"format": "json",
	"id": "ed_2o4XYG8rgHZZe6UUZWOC7ieky5G",
	"metadata": "{\"environment\":\"dev\", \"stream\":1}",
	"target": {
		"azure_logs_ingestion": null,
		"cloudwatch_logs": null,
		"datadog": null,
		"firehose": null,
		"kinesis": {
			"auth": {
				"creds": null,
				"role": {
					"role_arn": "arn:aws:iam::123456789012:role/example"
				}
			},
			"stream_arn": "arn:ngrok-local:kinesis:us-east-2:123456789012:stream/mystream2"
		}
	},
	"uri": "https://api.ngrok.com/event_destinations/ed_2o4XYG8rgHZZe6UUZWOC7ieky5G"
}
```