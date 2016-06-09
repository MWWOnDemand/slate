```json
{
  "data": {
    "attributes": {
      "billing-address": "123 Green St.\nSuite 321",
      "billing-city": "New New York",
      "billing-country": null,
      "billing-email": null,
      "billing-name": "Hubert J. Farnsworth",
      "billing-phone": null,
      "billing-postal-code": "10012",
      "billing-state": "NY",
      "created-at": "2016-05-20T13:13:29.485Z",
      "shipping-address": "123 Green St.\nSuite 321",
      "shipping-city": "New New York",
      "shipping-country": null,
      "shipping-email": null,
      "shipping-method": "SAMPLE",
      "shipping-name": "Phillip J. Fry",
      "shipping-phone": null,
      "shipping-postal-code": "10012",
      "shipping-state": "NY",
      "state": "received",
      "state-events": [
        "invalidate_it",
        "process_it",
        "cancel_it"
      ],
      "updated-at": "2016-05-20T13:13:29.485Z",
      "vendor-po": "dcbfdc59b8b51bbb530f0299b6db25c7"
    },
    "id": "533109340861629455",
    "links": {
      "self": "https://api.mwwondemand.com/api/orders/533109340861629455"
    },
    "relationships": {
      "line-item-views": {
        "links": {
          "related": "https://api.mwwondemand.com/api/orders/533109340861629455/line-item-views",
          "self": "https://api.mwwondemand.com/api/orders/533109340861629455/relationships/line-item-views"
        }
      },
      "line-items": {
        "links": {
          "related": "https://api.mwwondemand.com/api/orders/533109340861629455/line-items",
          "self": "https://api.mwwondemand.com/api/orders/533109340861629455/relationships/line-items"
        }
      },
      "user": {
        "links": {
          "related": "https://api.mwwondemand.com/api/orders/533109340861629455/user",
          "self": "https://api.mwwondemand.com/api/orders/533109340861629455/relationships/user"
        }
      },
      "pack-list": {
        "links": {
          "self": "https://api.mwwondemand.com/api/orders/533109340861629455/relationships/pack-list",
          "related": "https://api.mwwondemand.com/api/orders/533109340861629455/pack-list"
        }
      }
    },
    "type": "orders"
  }
}
```