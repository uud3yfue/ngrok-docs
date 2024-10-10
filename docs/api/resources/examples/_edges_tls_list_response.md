<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-10-10T08:19:50Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2nEq4JqFo7l6MFDqjWVa47cR2h4",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2nEq4JqFo7l6MFDqjWVa47cR2h4"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2nEq2tNTxQUPeUfZ09lSTR2U5tK",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2nEq2tNTxQUPeUfZ09lSTR2U5tK"
				},
				"enabled": true
			},
			"created_at": "2024-10-10T08:19:38Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2nEq2vOF6Fy69xHVleSNNrgpiGH",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2nEq2vOF6Fy69xHVleSNNrgpiGH"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
