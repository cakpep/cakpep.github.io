### [&laquo; Home](index.md)

## Get All Brands
This endpoint retrieves all brands.
##### URL
`GET` `http://nusantara.detotty.com/index.php/api/brands`

##### URL GET BY FILTER
`http://nusantara.detotty.com/index.php/api/brands?filter[brand_id]=7`

##### Example Request
````sh
curl "http://nusantara.detotty.com/index.php/api/brands" -X "GET"

````
##### Example Response
Success response:
````json
{

    "status": true,
    "totalResults": 1,
    "data": [
        {
            "brand_id": "7",
            "name": "Tanishq",
            "description": null,
            "logo": "brand_7.jpg"
        }
    ]

}
````

Failed response
````json
{
    "status": false,
    "message": "data is not found"
}
````
````json
{

    "status": false,
    "message": {
        "brand_ids": "brand_ids not allowed using on filter"
    }

}
````