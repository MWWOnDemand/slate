```shell
curl https://api.mwwondemand.com/api/orders \
  -d '{
    "data": {
      "type": "orders",
      "attributes": {
        "vendor-order-id": "cds-0001",
        "po": "123",
        "shipping-method": "321",
        "shipping-name": "Phillip J. Fry",
        "shipping-address1": "123 Green St.\nSuite 321",
        "shipping-city": "New New York",
        "shipping-state": "CA",
        "shipping-postal-code": "10012"
      }
    },
    "included": [
      {
        "type": "line-items",
        "attributes": {
          "line-number": 1,
          "quantity": 2,
          "description": "Warm Blanket!",
          "product-code": "294",
          "item-properties": {
            "thread-color": "green",
            "blah": "blah 2"
          },
          "path-to-image": "http://images.apple.com/v/home/cj/images/promos/ipad_pro_large.jpg"
        }
      },
      {
        "type": "line-items",
        "attributes": {
          "line-number": 2,
          "quantity": 5,
          "description": "Super Soft Pillow!",
          "product-code": "1029",
          "item-properties": {
            "thread-color": "blue",
            "blah": "blah 3"
          },
          "path-to-image": "http://images.apple.com/v/home/cj/images/heros/iphone-6s-change_xlarge.jpg"
        }
      }
    ]
  }' \
  -X POST \
  -H "Content-Type: application/vnd.api+json" \
  -H "Accept: application/vnd.api+json; version=1" \
  -H "Authorization: auth-key=YOUR_API_KEY"
```
