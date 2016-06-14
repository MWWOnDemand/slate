```json
{
  "data": [
    {
      "id": "001122334455667788",
      "type": "orders",
      "links": {
        "self": "https://api.mwwondemand.com/api/orders/001122334455667788"
      },
      "attributes": {
        "created-at": "2016-05-04T14:56:10.210Z",
        "updated-at": "2016-05-06T13:39:46.866Z",
        "state": "received",
        "state-events": [
          "invalidate_it",
          "process_it",
          "cancel_it"
        ],
        "billing-name": "ART BY HILLARY",
        "billing-address": "",
        "billing-city": "MEMPHIS",
        "billing-state": "GA",
        "billing-country": "USA",
        "billing-postal-code": "32333",
        "billing-phone": "8005551212",
        "billing-email": "",
        "shipping-name": "Hillary Sanders",
        "shipping-address": "1800 RASBERRY AVE APT 2415\nApartment 2415",
        "shipping-city": "MIAMI BEACH",
        "shipping-state": "TN",
        "shipping-postal-code": "33139",
        "shipping-country": "US",
        "shipping-phone": null,
        "shipping-email": "",
        "shipping-method": "USPPLE",
        "vendor-po": "ANN023"
      },
      "relationships": {
        "line-items": {
          "links": {
            "self": "https://api.mwwondemand.com/api/orders/001122334455667788/relationships/line-items",
            "related": "https://api.mwwondemand.com/api/orders/001122334455667788/line-items"
          }
        },
        "line-item-views": {
          "links": {
            "self": "https://api.mwwondemand.com/api/orders/001122334455667788/relationships/line-item-views",
            "related": "https://api.mwwondemand.com/api/orders/001122334455667788/line-item-views"
          }
        },
        "user": {
          "links": {
            "self": "https://api.mwwondemand.com/api/orders/001122334455667788/relationships/user",
            "related": "https://api.mwwondemand.com/api/orders/001122334455667788/user"
          }
        }
      }
    },
    {
      "id": "522975713377125913",
      "type": "orders",
```
...