
```json
  {
    "data": {
      "id": "480226771879331308",
      "type": "orders",
      "links": {
        "self": "https://api.mwwondemand.com/api/orders/480226771879331308"
      },
      "attributes": {
        "created-at": "2016-03-08T14:05:15.978Z",
        "updated-at": "2016-03-08T14:05:15.978Z",
        "state": "received",
        "state-events": [ "invalidate_it", "process_it", "cancel_it"],
        "billing-name": "Phillip J. Fry",
        "billing-address": "123 Green St.\nSuite 321",
        "billing-city": "New New York",
        "billing-state": "CA",
        "billing-country": null,
        "billing-postal-code": "10012",
        "billing-phone": null,
        "billing-email": null,
        "shipping-name": null,
        "shipping-address": "123 Green St.\nSuite 321",
        "shipping-city": "New New York",
        "shipping-state": "CA",
        "shipping-postal-code": "10012",
        "shipping-country": null,
        "shipping-phone": null,
        "shipping-email": null,
        "shipping-method": "321",
        "vendor-po": "1234567890"
      },
      "relationships": {
        "line-items": {
          "links": {
            "self": "https://api.mwwondemand.com/api/orders/480226771879331308/relationships/line-items",
            "related":"https://api.mwwondemand.com/api/orders/480226771879331308/line-items"
          }
        },
        "line-item-views": {
          "links": {
            "self": "https://api.mwwondemand.com/api/orders/525951654449644579/relationships/line-item-views",
            "related": "https://api.mwwondemand.com/api/orders/525951654449644579/line-item-views"
          }
        },
        "user": {
          "links": {
            "self": "https://api.mwwondemand.com/api/orders/480226771879331308/relationships/user",
            "related":"https://api.mwwondemand.com/api/orders/480226771879331308/user"
          }
        }
      }
    }
  }
```
