```text
HTTP/1.1 200 OK
Content-Type: application/vnd.api+json
ETag: W/"79fb5347c319c693f6d89ca82dc43e78"
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
      "updated-at": "2016-04-09T23:35:18.364Z",
      "url": "http://localhost:3001/mwwondemand-order-notifications",
      "enabled": true,
      "received": true,
      "design-downloaded": false,
      "processed": true,
      "shipped": true,
      "cancelled": true,
      "printed": true,
      "pressed": true,
      "cut": true,
      "sewn": true,
      "turned": true,
      "packed": true
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