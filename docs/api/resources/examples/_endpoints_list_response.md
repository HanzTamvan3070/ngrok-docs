<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-07T10:08:45Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_30xFSvcBWak5UeJUlYueVPvtpdg",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30xFSvcBWak5UeJUlYueVPvtpdg"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30xFTelj5deDgVSAB50KNrXuGLp",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-08-07T10:08:45Z",
      "uri": "https://api.ngrok.com/endpoints/ep_30xFTelj5deDgVSAB50KNrXuGLp",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-07T10:08:43Z",
      "hostport": "0d4a3b007044.ngrok.paid:443",
      "id": "ep_30xFTOUe4rPQJlZrZT4mjn2xJaU",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_30xFMmTBWV01Y63HgXCCpaNceI1",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://0d4a3b007044.ngrok.paid",
      "tunnel": {
        "id": "tn_30xFTOUe4rPQJlZrZT4mjn2xJaU",
        "uri": "https://api.ngrok.com/tunnels/tn_30xFTOUe4rPQJlZrZT4mjn2xJaU"
      },
      "tunnel_session": {
        "id": "ts_30xFTNONEEWkugKZgpjlhT5bxEz",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_30xFTNONEEWkugKZgpjlhT5bxEz"
      },
      "type": "ephemeral",
      "updated_at": "2025-08-07T10:08:43Z",
      "upstream_url": "http://localhost:80",
      "url": "https://0d4a3b007044.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-07T10:08:40Z",
      "domain": {
        "id": "rd_30xFSvcBWak5UeJUlYueVPvtpdg",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30xFSvcBWak5UeJUlYueVPvtpdg"
      },
      "edge": {
        "id": "edgtls_30xFT37uPf73CxOLSd50ic3A6vR",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_30xFT37uPf73CxOLSd50ic3A6vR"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30xFSweilYHKWJOVJIGJRll4bhd",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-08-07T10:08:40Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
