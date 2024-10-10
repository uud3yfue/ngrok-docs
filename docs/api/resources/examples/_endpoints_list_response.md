<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-10-10T08:19:42Z",
			"hostport": "9d25ed1a8fb9.ngrok.paid:443",
			"id": "ep_2nEq3PtmrnzFfjddeeOCi2k6Rxx",
			"principal_id": {
				"id": "usr_2nEq0rygqR4qkCcON4XJMUR4PUE",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://9d25ed1a8fb9.ngrok.paid",
			"tunnel": {
				"id": "tn_2nEq3PtmrnzFfjddeeOCi2k6Rxx",
				"uri": "https://api.ngrok.com/tunnels/tn_2nEq3PtmrnzFfjddeeOCi2k6Rxx"
			},
			"tunnel_session": {
				"id": "ts_2nEq3O3AqyCDrx0W71jn2uzBOAw",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2nEq3O3AqyCDrx0W71jn2uzBOAw"
			},
			"type": "ephemeral",
			"updated_at": "2024-10-10T08:19:42Z",
			"upstream_url": "http://localhost:80",
			"url": "https://9d25ed1a8fb9.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-10-10T08:19:39Z",
			"domain": {
				"id": "rd_2nEq2ozYH1C6gg3GwStZJeIh7GB",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2nEq2ozYH1C6gg3GwStZJeIh7GB"
			},
			"edge": {
				"id": "edgtls_2nEq2vOF6Fy69xHVleSNNrgpiGH",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2nEq2vOF6Fy69xHVleSNNrgpiGH"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2nEq30umDajhFJK8WLOYV3wt2Dw",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-10-10T08:19:39Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
