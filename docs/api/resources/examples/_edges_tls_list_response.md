<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-08-27T10:08:18Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_31rjtK2667eDraoqyoq4MsEjtYo",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31rjtK2667eDraoqyoq4MsEjtYo"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_31rjrwA9ciKOgz8lM43ccU1rFFH",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_31rjrwA9ciKOgz8lM43ccU1rFFH"
        },
        "enabled": true
      },
      "created_at": "2025-08-27T10:08:07Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_31rjrsCSSQv0PPa0uedj17Hdygn",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31rjrsCSSQv0PPa0uedj17Hdygn"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
