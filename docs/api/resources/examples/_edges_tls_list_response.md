<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-22T10:08:23Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_30E3SO36kt8Wu9jtjwAO8kXlbxN",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30E3SO36kt8Wu9jtjwAO8kXlbxN"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_30E3R0XuHOkTOXItFdCmcw5Wxpe",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_30E3R0XuHOkTOXItFdCmcw5Wxpe"
        },
        "enabled": true
      },
      "created_at": "2025-07-22T10:08:12Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_30E3R0GgOGvZ6T8TNnM4dMMgXH9",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30E3R0GgOGvZ6T8TNnM4dMMgXH9"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
