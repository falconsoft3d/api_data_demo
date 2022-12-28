# Api Data Demo

```
import requests

url = "https://raw.githubusercontent.com/falconsoft3d/api_data_demo/main/product_data.json"

payload={}
headers = {}

response = requests.request("GET", url, headers=headers, data=payload)

print(response.text)
```
