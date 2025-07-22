<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_30E3OzUVB31S2zsEdQGvqIyjy2a",
        "uri": "https://api.ngrok.com/tls_certificates/cert_30E3OzUVB31S2zsEdQGvqIyjy2a"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.59mfvkdoftzzbq5wu.local-ngrok-cname.com",
      "created_at": "2025-07-22T10:07:56Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30E3P2q6yEtWf0zoIAM2NI3pPBH",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30E3P2q6yEtWf0zoIAM2NI3pPBH"
    },
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
          "started_at": "2025-07-22T10:07:56Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.59mfvkdoftzzbq5wu.local-ngrok-cname.com",
      "created_at": "2025-07-22T10:07:56Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30E3Oye8J1HMorgzTjovUxEn2eJ",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30E3Oye8J1HMorgzTjovUxEn2eJ"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-07-22T10:07:26Z",
      "description": "Your dev domain",
      "domain": "halibut-balanced-snapper.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30E3LB4kEhSb0sxKesPTtByhX54",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30E3LB4kEhSb0sxKesPTtByhX54"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
