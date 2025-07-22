<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-22T10:08:17Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_30E3R0grIw8XxBTsRqEEUMrP70z",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30E3R0grIw8XxBTsRqEEUMrP70z"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30E3Re9JvAMRnlBhkJqkk5kLYMr",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-22T10:08:17Z",
      "uri": "https://api.ngrok.com/endpoints/ep_30E3Re9JvAMRnlBhkJqkk5kLYMr",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-22T10:08:15Z",
      "hostport": "07dd8c5a32ba.ngrok.paid:443",
      "id": "ep_30E3RPaW6qtF11OZdjNC2QwSexX",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_30E3KoU8eDw4TXLdr3PmCq62Eoo",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://07dd8c5a32ba.ngrok.paid",
      "tunnel": {
        "id": "tn_30E3RPaW6qtF11OZdjNC2QwSexX",
        "uri": "https://api.ngrok.com/tunnels/tn_30E3RPaW6qtF11OZdjNC2QwSexX"
      },
      "tunnel_session": {
        "id": "ts_30E3RPoCyxOqtTpTMmmN2q3135v",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_30E3RPoCyxOqtTpTMmmN2q3135v"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-22T10:08:15Z",
      "upstream_url": "http://localhost:80",
      "url": "https://07dd8c5a32ba.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-22T10:08:12Z",
      "domain": {
        "id": "rd_30E3R0grIw8XxBTsRqEEUMrP70z",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30E3R0grIw8XxBTsRqEEUMrP70z"
      },
      "edge": {
        "id": "edgtls_30E3R0GgOGvZ6T8TNnM4dMMgXH9",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_30E3R0GgOGvZ6T8TNnM4dMMgXH9"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30E3R08xzupmPy37H0SnaEc21Bb",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-22T10:08:12Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
