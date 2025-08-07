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
          "started_at": "2025-08-07T10:08:24Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.31ubcm4fcs1xcb6ej.local-ngrok-cname.com",
      "created_at": "2025-08-07T10:08:24Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30xFR2WownvoDftrCrUoY6RCXHh",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30xFR2WownvoDftrCrUoY6RCXHh"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_30xFQz4A9DK7J4qxyFLOy0hFIwn",
        "uri": "https://api.ngrok.com/tls_certificates/cert_30xFQz4A9DK7J4qxyFLOy0hFIwn"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.31ubcm4fcs1xcb6ej.local-ngrok-cname.com",
      "created_at": "2025-08-07T10:08:24Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30xFR0QPSxe2NJljHeyTL35EpDI",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30xFR0QPSxe2NJljHeyTL35EpDI"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-08-07T10:07:53Z",
      "description": "Your dev domain",
      "domain": "heartily-clever-stud.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30xFN6bT9cPfYT1efe8nNtD03Cf",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30xFN6bT9cPfYT1efe8nNtD03Cf"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
