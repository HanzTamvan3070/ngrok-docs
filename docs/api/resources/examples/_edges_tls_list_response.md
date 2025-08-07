<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-08-07T10:08:51Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_30xFUQFrl9G3baQNoEPNT14yfgw",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30xFUQFrl9G3baQNoEPNT14yfgw"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_30xFT2GC5qywD1u5tnEOaHFWscl",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_30xFT2GC5qywD1u5tnEOaHFWscl"
        },
        "enabled": true
      },
      "created_at": "2025-08-07T10:08:40Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_30xFT37uPf73CxOLSd50ic3A6vR",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30xFT37uPf73CxOLSd50ic3A6vR"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
