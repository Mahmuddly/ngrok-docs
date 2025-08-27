<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-27T10:08:12Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_31rjrvwgfrMQw6ldKv7EzXwhTA5",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31rjrvwgfrMQw6ldKv7EzXwhTA5"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31rjsbc3aycPSFeO5sWD32iMlbI",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-08-27T10:08:12Z",
      "uri": "https://api.ngrok.com/endpoints/ep_31rjsbc3aycPSFeO5sWD32iMlbI",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-27T10:08:10Z",
      "hostport": "d46657d85ffe.ngrok.paid:443",
      "id": "ep_31rjsKHZgxMlBbrJFk504cV4TEh",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_31rjlksGspvxJ1GTwt8vBKK9zSh",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://d46657d85ffe.ngrok.paid",
      "tunnel": {
        "id": "tn_31rjsKHZgxMlBbrJFk504cV4TEh",
        "uri": "https://api.ngrok.com/tunnels/tn_31rjsKHZgxMlBbrJFk504cV4TEh"
      },
      "tunnel_session": {
        "id": "ts_31rjsJEfVguv8WXclOEPhAvWsBT",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_31rjsJEfVguv8WXclOEPhAvWsBT"
      },
      "type": "ephemeral",
      "updated_at": "2025-08-27T10:08:10Z",
      "upstream_url": "http://localhost:80",
      "url": "https://d46657d85ffe.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-27T10:08:07Z",
      "domain": {
        "id": "rd_31rjrvwgfrMQw6ldKv7EzXwhTA5",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31rjrvwgfrMQw6ldKv7EzXwhTA5"
      },
      "edge": {
        "id": "edgtls_31rjrsCSSQv0PPa0uedj17Hdygn",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_31rjrsCSSQv0PPa0uedj17Hdygn"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31rjryphZP5Xat1LvsQyEIGO0kB",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-08-27T10:08:07Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
