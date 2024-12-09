<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2pysIavoINWjasEOzShw4ukoPCh",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2pysIavoINWjasEOzShw4ukoPCh"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.5hrlfzkven1lyksta.local-ngrok-cname.com",
			"created_at": "2024-12-09T13:06:10Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2pysIZm1fyPerMuLawu8LRUNcLD",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2pysIZm1fyPerMuLawu8LRUNcLD"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2024-12-09T13:06:10Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.5hrlfzkven1lyksta.local-ngrok-cname.com",
			"created_at": "2024-12-09T13:06:10Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2pysIeeN27SUdpMBy5iyca8j3xB",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2pysIeeN27SUdpMBy5iyca8j3xB"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
