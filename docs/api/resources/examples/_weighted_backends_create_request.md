<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"backends":{"bkdhr_30xFTpMMWrmw0C6VCFvRbK4wWNB":0,"bkdhr_30xFTsvMptAPIs5OgeGXEV5td0Q":1},"description":"acme weighted","metadata":"{\"environment\": \"staging\"}"}' \
https://api.ngrok.com/backends/weighted
```
