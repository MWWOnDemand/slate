```text
HTTP/1.1 201 Created
Content-Type: application/vnd.api+json
ETag: W/"a3c86d6fc9e44e75887b996cafc57b37"
Cache-Control: max-age=0, private, must-revalidate
```

```json
{
  "data": {
    "id": "503678086298993748",
    "type": "webhooks",
    "links": {
      "self": "http://localhost:3000/api/webhooks/503678086298993748"
    },
    "attributes": {
      "created-at": "2016-04-09T22:38:50.426Z",
      "updated-at": "2016-04-09T22:38:50.426Z",
      "url": "http://localhost:3001/mwwondemand-order-notifications",
      "enabled": true,
      "received": true,
      "design-downloaded": false,
      "processed": true,
      "shipped": true,
      "cancelled": true,
      "printed": false,
      "pressed": false,
      "cut": false,
      "sewn": false,
      "turned": false,
      "packed": false
    },
    "relationships": {
      "user": {
        "links": {
          "self": "http://localhost:3000/api/webhooks/503678086298993748/relationships/user",
          "related": "http://localhost:3000/api/webhooks/503678086298993748/user"
        }
      }
    }
  }
}
```