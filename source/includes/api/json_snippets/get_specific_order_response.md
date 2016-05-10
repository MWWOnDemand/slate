
```json
{
  "data": {
    "id": "001122334455667788",
    "type": "orders",
    "links": {
      "self": "https://api.mwwondemand.com/api/orders/001122334455667788"
    },
    "attributes": {
      "created-at": "2016-04-21T12:25:08.473Z",
      "updated-at": "2016-05-06T13:39:46.953Z",
      "state": "received",
      "state-events": [
        "invalidate_it",
        "process_it",
        "cancel_it"
      ],
      "billing-name": "MyStore",
      "billing-address": "111 Main St.",
      "billing-city": "AnyTown",
      "billing-state": "NC",
      "billing-country": "USA",
      "billing-postal-code": "",
      "billing-phone": "6468236220",
      "billing-email": "",
      "shipping-name": "MyWarehouse",
      "shipping-address": "999 Warehouse Road Doors 3-15",
      "shipping-city": "BOULDER",
      "shipping-state": "CO",
      "shipping-postal-code": "41048",
      "shipping-country": "US",
      "shipping-phone": "",
      "shipping-email": "",
      "shipping-method": "USPPLE",
      "vendor-po": "amflat-mww-10545-1374056_9-WHS-10545-1374056_142"
    },
    "relationships": {
      "line-items": {
        "links": {
          "self": "http://localhost:3000/api/orders/001122334455667788/relationships/line-items",
          "related": "http://localhost:3000/api/orders/001122334455667788/line-items"
        }
      },
      "line-item-views": {
        "links": {
          "self": "http://localhost:3000/api/orders/001122334455667788/relationships/line-item-views",
          "related": "http://localhost:3000/api/orders/001122334455667788/line-item-views"
        }
      },
      "user": {
        "links": {
          "self": "http://localhost:3000/api/orders/001122334455667788/relationships/user",
          "related": "http://localhost:3000/api/orders/001122334455667788/user"
        }
      }
    }
  }
}
```