### [&laquo; Home](index.md)

## Get User profile
This endpoint retrieves specific user profile.
##### URL
`GET` `http://nusantara.detotty.com/index.php/api/users/(:user_id)`

##### URL GET BY ID
`http://nusantara.detotty.com/index.php/api/users/7`

##### Example Request
````sh
curl "http://nusantara.detotty.com/index.php/api/users/7" -X "GET"

````
##### Example Response
Success response:
````json
{

    "status": true,
    "totalResults": 1,
    "data": [
        {
            "user_id": "1",
            "username": "rorurehy",
            "surname": "Fleming",
            "email": "miromumyp@yahoo.com",
            "phone": "+532-55-5730682",
            "address1": "Fuga Enim necessitatibus proident omnis quis aut voluptatibus iste dolore quis neque adipisicing ut",
            "address2": "Et ea vitae porro error labore impedit autem voluptates vel voluptas dolores mollitia",
            "city": "Voluptatem totam sit in fugiat delectus illo aliquam culpa dolor",
            "zip": "88604",
            "langlat": "",
            "fb_id": null,
            "g_id": null,
            "g_photo": null,
            "creation_date": "1474453509",
            "google_plus": null,
            "skype": null,
            "facebook": null,
            "wishlist": [ ],
            "last_login": "1492833461",
            "user_type": "default",
            "user_type_till": null,
            "left_product_type": [ ],
            "downloads": [ ],
            "country": null,
            "state": null,
            "totalPurchase": 10,
            "wishedProducts": 10,
            "last7Days": 10,
            "last30Days": 10,
            "orderHistory": [ ]
        }
    ]

}
````

User not found response
````json
{

    "status": true,
    "totalResults": 0,
    "data": [ ]

}
````