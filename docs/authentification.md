### [&laquo; Home](index.md)

## Authentication for Nusantara MALL API
This endpoint for user authentifacation.
##### URL
`POST` `http://nusantara.detotty.com/index.php/api/auth`

##### Parameters
| Parameter name | Required | Value |
| ------ | ------ | ------ |
| username | true | username or email |
| password | true | user password |

##### Example Request
````sh
curl "http://nusantara.detotty.com/index.php/api/auth" -H "Content-Type: application/x-www-form-urlencoded" -d "username=cakpep&password=cakpep"  -X "POST"

````

##### Example Response
Success response:
````json
{
    "status": true,
    "totalResults": 1,
    "data": [{
        "user_id": "9",
        "username": "cakpep",
        "surname": "cacaca",
        "email": "cakpepp@gmail.com",
        "phone": "89898",
        "address1": "jl kita masih panjang",
        "address2": "",
        "city": "Yogyakarta",
        "zip": "2113",
        "langlat": "",
        "fb_id": null,
        "g_id": null,
        "g_photo": null,
        "creation_date": "1492801582",
        "google_plus": null,
        "skype": null,
        "facebook": null,
        "wishlist": "[\"89\",\"88\"]",
        "last_login": "1492832642",
        "user_type": "default",
        "user_type_till": null,
        "left_product_type": "[]",
        "downloads": "[]",
        "country": "US",
        "state": ""
    }]
}
````

Failed response
````json
{
    "status": false,
    "message": "Required username (Email or name value)"
}
````