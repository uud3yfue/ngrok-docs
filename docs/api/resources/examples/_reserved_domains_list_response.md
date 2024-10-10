<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
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
					"started_at": "2024-10-10T08:19:23Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.2dvngwbkjp4lhtghx.local-ngrok-cname.com",
			"created_at": "2024-10-10T08:19:22Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2nEq10jlWT4asBjyhbFBV0EzKL2",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2nEq10jlWT4asBjyhbFBV0EzKL2"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2nEq0seET1E6L7GEfHRjFEq9lbL",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2nEq0seET1E6L7GEfHRjFEq9lbL"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.2dvngwbkjp4lhtghx.local-ngrok-cname.com",
			"created_at": "2024-10-10T08:19:22Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2nEq0tEjTi13rv6yYNQOkhbgf1Q",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2nEq0tEjTi13rv6yYNQOkhbgf1Q"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
