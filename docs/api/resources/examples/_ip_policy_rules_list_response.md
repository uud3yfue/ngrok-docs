<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"ip_policy_rules": [
		{
			"action": "allow",
			"cidr": "212.3.14.0/24",
			"created_at": "2024-10-10T08:19:45Z",
			"description": "nyc office",
			"id": "ipr_2nEq3ks4m2ol8vJwNYtMsvdO33e",
			"ip_policy": {
				"id": "ipp_2nEq3goXgOXIhPWC1Uv6mstCFV2",
				"uri": "https://api.ngrok.com/ip_policies/ipp_2nEq3goXgOXIhPWC1Uv6mstCFV2"
			},
			"uri": "https://api.ngrok.com/ip_policy_rules/ipr_2nEq3ks4m2ol8vJwNYtMsvdO33e"
		},
		{
			"action": "allow",
			"cidr": "2.2.2.2/32",
			"created_at": "2024-10-10T08:19:45Z",
			"description": "alan laptop",
			"id": "ipr_2nEq3kCVvwB8dfAX23mbldz7DKE",
			"ip_policy": {
				"id": "ipp_2nEq3goXgOXIhPWC1Uv6mstCFV2",
				"uri": "https://api.ngrok.com/ip_policies/ipp_2nEq3goXgOXIhPWC1Uv6mstCFV2"
			},
			"uri": "https://api.ngrok.com/ip_policy_rules/ipr_2nEq3kCVvwB8dfAX23mbldz7DKE"
		},
		{
			"action": "allow",
			"cidr": "132.2.19.0/24",
			"created_at": "2024-10-10T08:19:45Z",
			"description": "sf office",
			"id": "ipr_2nEq3iwPSISEX9HUPro0Fm47RzL",
			"ip_policy": {
				"id": "ipp_2nEq3goXgOXIhPWC1Uv6mstCFV2",
				"uri": "https://api.ngrok.com/ip_policies/ipp_2nEq3goXgOXIhPWC1Uv6mstCFV2"
			},
			"uri": "https://api.ngrok.com/ip_policy_rules/ipr_2nEq3iwPSISEX9HUPro0Fm47RzL"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/ip_policy_rules"
}
```
