```shell
curl -X PATCH http://localhost:3000/api/webhooks/503678086298993748 \
  -d '{
    "data": {
      "id": "503678086298993748",
      "type": "webhooks",
      "attributes": {
        "url": "http://localhost:3001/mwwondemand-order-notifications",
        "printed": true,
        "pressed": true,
        "cut": true,
        "sewn": true,
        "turned": true,
        "packed": true
      }
    }
  }' \
  -H "Content-Type: application/vnd.api+json" \
  -H "Accept: application/vnd.api+json; version=2" \
  -H "Authorization: YOUR_API_KEY"
```