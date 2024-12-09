<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-09T13:06:29Z",
			"hostport": "c6b6a2c6c73f.ngrok.paid:443",
			"id": "ep_2pysL3Csu483xRcAkfTmjWR9yvJ",
			"name": "command_line",
			"principal": {
				"id": "usr_2pysIQq5pUKhxteEkgA3NuNdX3K",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://c6b6a2c6c73f.ngrok.paid",
			"tunnel": {
				"id": "tn_2pysL3Csu483xRcAkfTmjWR9yvJ",
				"uri": "https://api.ngrok.com/tunnels/tn_2pysL3Csu483xRcAkfTmjWR9yvJ"
			},
			"tunnel_session": {
				"id": "ts_2pysL0WaFCuHw6IZiiXw2FlYkxy",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2pysL0WaFCuHw6IZiiXw2FlYkxy"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-09T13:06:29Z",
			"upstream_url": "http://localhost:80",
			"url": "https://c6b6a2c6c73f.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-09T13:06:26Z",
			"domain": {
				"id": "rd_2pysKau4aDzUFNlNX3B809dti6r",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2pysKau4aDzUFNlNX3B809dti6r"
			},
			"edge": {
				"id": "edgtls_2pysKbxoCkgqmPfLu2O1J39OvRL",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2pysKbxoCkgqmPfLu2O1J39OvRL"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2pysKeDyDF05YJgssNeTLnuxAE6",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-09T13:06:26Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
