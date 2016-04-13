```shell
curl -i -X POST http://localhost:3000/api/webhooks \
  -d '{
    "data": {
      "type": "webhooks",
      "attributes": {
        "url": "http://localhost:3001/mwwondemand-order-notifications"
      }
    }
  }' \
  -H "Content-Type: application/vnd.api+json" \
  -H "Accept: application/vnd.api+json; version=2" \
  -H "Authorization: YOUR_API_KEY"
```