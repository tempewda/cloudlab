```
import requests

url = ""
key = ""

headers = {
    "Authorization": f"Bearer {key}",
    "Content-Type": "application/json"
}

data = {
    "input_data": {
        "columns": [
            "age","sex","cp","trestbps","chol",
            "fbs","restecg","thalach","exang",
            "oldpeak","slope","ca","thal"
        ],
        "data": [[
            63,1,3,145,233,
            1,0,150,0,
            2.3,0,0,1
        ]]
    }
}

response = requests.post(url, json=data, headers=headers)
print(response.text)
```

