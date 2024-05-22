# Restful Products_OAS API - API Catalog CLI

## Note: this is a API Catalog CLI documentation

The purpose of this api is to return all products. this is sample API Catalog CLI Demo.

**URL** : `/api/products`

**Query Parameters** : NO 

**Resources** : `get products, post products`

**Method** : `GET,POST` 

**Auth Required** : YES 

**Data** : `{}` 


## Success Response


**Code** : `200 OK`

**Content example** 

```json
[
 {
    "id": "112342!!!!!!",
    "title": "The Black T-Shirt",
    "price": "100 USD",
    "availability": "inStock"
  },
  {
    "id": "352347!!!!!",
    "title": "The Black designed cap",
    "price": "50 USD",
    "availability": "inStock"
  },
  {
    "id": "917332!!!!!!",
    "title": "Sports shoes",
    "price": "200 USD",
    "availability": "out of stock"
  }
]
```





