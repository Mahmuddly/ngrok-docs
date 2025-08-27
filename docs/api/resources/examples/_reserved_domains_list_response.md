<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_31rjpxdsNBMoqUOJhHWL5f56hEO",
        "uri": "https://api.ngrok.com/tls_certificates/cert_31rjpxdsNBMoqUOJhHWL5f56hEO"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.3ubt55521ikhv7fvl.local-ngrok-cname.com",
      "created_at": "2025-08-27T10:07:51Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31rjpyQ732RUXHJfI2T5DtDtyQX",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31rjpyQ732RUXHJfI2T5DtDtyQX"
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
          "started_at": "2025-08-27T10:07:51Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.3ubt55521ikhv7fvl.local-ngrok-cname.com",
      "created_at": "2025-08-27T10:07:51Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31rjpygn5MDR1cA61gqxl7Rm6K3",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31rjpygn5MDR1cA61gqxl7Rm6K3"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-08-27T10:07:20Z",
      "description": "Your dev domain",
      "domain": "gently-leading-parrot.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31rjlyYmCvs1Eg8TL2dcIXEpUkB",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31rjlyYmCvs1Eg8TL2dcIXEpUkB"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
