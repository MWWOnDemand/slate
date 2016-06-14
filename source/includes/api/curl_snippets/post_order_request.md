```shell
curl -X "POST" "https://api.mwwondemand.com:443/api/orders" \
  -H "Accept: application/vnd.api+json; version=1" \
  -H "Authorization: auth-key=YOU_API_KEY" \
  -H "Content-Type: application/vnd.api+json" \
  -d $'{
  "data": {
    "type": "orders",
    "attributes": {
      "vendor-po": "dcbfdc59b8b51bbb530f0299b6db25c7",
      "shipping-method": "SAMPLE",
      "shipping-name": "Phillip J. Fry",
      "shipping-address": "123 Green St.\\nSuite 321",
      "shipping-city": "New New York",
      "shipping-state": "NY",
      "shipping-postal-code": "10012",
      "billing-name": "Hubert J. Farnsworth"
    }
  },
  "included": [
    {
      "type": "line-items",
      "attributes": {
        "line-number": 1,
        "quantity": 2,
        "description": "Awesome Item",
        "product-code": "293",
        "item-properties": {
          "comming": "soon"
        },
        "designs": [
          {
            "image_remote_url": "http://images.apple.com/v/home/cj/images/promos/ipad_pro_large.jpg"
          }
        ]
      }
    },
    {
      "type": "line-items",
      "attributes": {
        "line-number": 2,
        "quantity": 5,
        "description": "Sò fluffy!",
        "product-code": "294",
        "item-properties": {
          "comming": "soon"
        },
        "designs": [
          {
            "image_remote_url": "http://images.apple.com/v/home/cj/images/heros/iphone-6s-change_xlarge.jpg"
          }
        ]
      }
    },
    { 
      "type": "pack-list",
      "attributes": {
        "url": "https://images.YOURSTORAGELOCATION.com/packing_lists/123412341234.pdf"
        }
    }
  ]
}'
```
