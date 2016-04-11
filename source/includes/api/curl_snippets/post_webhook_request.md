```shell
curl http://localhost:3000/api/orders \
  -d '{
    "data": {
      "type": "webhooks",
      "attributes": {
        "url": "http://localhost:3001/mwwondemand-order-notifications"
      }
    }
  }' \
  -X POST \
  -H "Content-Type: application/vnd.api+json" \
  -H "Accept: application/vnd.api+json; version=2" \
  -H "api-key: YOUR_API_KEY"
```