```python
# Install the Python Requests library:
# `pip install requests`

import requests


def send_request():
    # Get Line Items By Order
    # GET http://localhost:3000/api/orders/647372455787562562/line-items

    try:
        response = requests.get(
            url="http://localhost:3000/api/orders//line-items",
            headers={
                "Authorization": "auth-key=YOUR_API_KEY",
                "Accept": "application/vnd.api+json; version=1",
            },
        )
        print('Response HTTP Status Code: {status_code}'.format(
            status_code=response.status_code))
        print('Response HTTP Response Body: {content}'.format(
            content=response.content))
    except requests.exceptions.RequestException:
        print('HTTP Request failed')
```