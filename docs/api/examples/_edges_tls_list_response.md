<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-09T13:06:37Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2pysM3rMyxZHdSCZk10xTJVFUSz",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pysM3rMyxZHdSCZk10xTJVFUSz"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2pysKfL8fvQ0Q2aSd67W4MPWx5P",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2pysKfL8fvQ0Q2aSd67W4MPWx5P"
				},
				"enabled": true
			},
			"created_at": "2024-12-09T13:06:26Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2pysKbxoCkgqmPfLu2O1J39OvRL",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pysKbxoCkgqmPfLu2O1J39OvRL"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
