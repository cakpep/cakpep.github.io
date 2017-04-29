### [&laquo; Home](index.md)

## Get User profile
This endpoint retrieves specific user profile.
##### URL
`GET` `http://nusantara-mall.org/index.php/api/users/(:user_id)`

##### URL GET BY ID
`http://nusantara-mall.org/index.php/api/users/9`

##### Example Request
````sh
curl "http://nusantara-mall.org/index.php/api/users/9" -X "GET"

````
##### Example Response
Success response:
````json
{

    "status": true,
    "totalResults": 1,
    "data": [
        {
            "user_id": "9",
            "username": "De",
            "surname": "Totty",
            "email": "detotty@gmail.com",
            "phone": "+628988448846",
            "address1": "Jl Raya janti no 240",
            "address2": "Tegalpasar, Banguntapan",
            "city": "Bantul",
            "zip": "55198",
            "langlat": "(-7.798602099999999, 110.40890149999996)",
            "fb_id": null,
            "g_id": null,
            "g_photo": null,
            "creation_date": "2017-04-06",
            "google_plus": null,
            "skype": null,
            "facebook": null,
            "wishlist": [
                "4",
                "22",
                "21"
            ],
            "last_login": "2017-04-29",
            "user_type": "default",
            "user_type_till": null,
            "left_product_type": [ ],
            "downloads": [ ],
            "country": "Indonesia",
            "state": "Ponorogo",
            "currency": "Rp",
            "totalPurchase": "0.00",
            "last7Days": "0.00",
            "last30Days": "0.00",
            "orderHistory": [
                {
                    "sale_id": "1",
                    "sale_code": "2017041",
                    "buyer": "9",
                    "product_details": {
                        "3c59dc048e8850243be8079a5c74d079": {
                            "id": "21",
                            "qty": 12,
                            "option": "{\"color\":{\"title\":\"Color\",\"value\":\"rgba(204,204,204,1)\"}}",
                            "price": 300000,
                            "name": "Souvenir A001",
                            "shipping": "15000",
                            "tax": 0,
                            "image": "http://localhost/nusantara_mall_web/uploads/product_image/product_21_1_thumb.jpg",
                            "coupon": "",
                            "rowid": "3c59dc048e8850243be8079a5c74d079",
                            "subtotal": 3600000
                        }
                    },
                    "shipping_address": {
                        "firstname": "De",
                        "lastname": "Totty",
                        "address1": "Jl Raya janti no 240",
                        "address2": "Tegalpasar, Banguntapan",
                        "zip": "55198",
                        "email": "detotty@gmail.com",
                        "phone": "+628988448846",
                        "langlat": "(-7.798602099999999, 110.40890149999996)",
                        "payment_type": "cash_on_delivery"
                    },
                    "vat": "0",
                    "vat_percent": "",
                    "shipping": "180000",
                    "payment_type": "cash_on_delivery",
                    "payment_status": [
                        {
                            "admin": "",
                            "status": "due"
                        }
                    ],
                    "payment_details": "",
                    "payment_timestamp": null,
                    "grand_total": "3780000",
                    "sale_datetime": "1492944526",
                    "delivary_datetime": "",
                    "delivery_status": [
                        {
                            "admin": "",
                            "status": "pending",
                            "delivery_time": ""
                        }
                    ],
                    "viewed": "ok"
                }
            ],
            "image": {
                "original": "http://localhost/siteproject/nusantara-mall-web-app/uploads/user_image/user_9.jpg?t=1493453108",
                "thumb": "http://localhost/siteproject/nusantara-mall-web-app/uploads/user_image/user_9_thumb.jpg?t=1493453108"
            }
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
## PUT Update User profile
This endpoint retrieves specific user profile.
##### URL
`PUT` `http://nusantara-mall.org/index.php/api/users/(:user_id)`

##### Parameters
| Parameter name | Required |
| ------ | ------ |
| username | false |
| surname | false |
| email | false |
| phone | false |
| address1 | false |
| address2 | false |
| city | false |
| zip | false |
| langlat | false |
| fb_id | false |
| g_id | false |
| g_photo | false |
| creation_date | false |
| google_plus | false |
| skype | false |
| facebook | false |
| wishlist | false |
| last_login | false |
| user_type | false |
| user_type_till | false |
| left_product_type | false |
| downloads | false |
| country | false |
| state | false |

##### Example Request
````sh
curl "http://nusantara-mall.org/index.php/api/users/9" -H "Content-Type: application/x-www-form-urlencoded" -d "state=Sleman&city=Yogyakarta"  -X "PUT"

````
##### Example Response
Success response:
````json
{

    "status": true,
    "totalResults": 1,
    "data": [
        {
            "user_id": "9",
            "username": "De",
            "surname": "Totty",
            "email": "detotty@gmail.com",
            "phone": "+628988448846",
            "address1": "Jl Raya janti no 240",
            "address2": "Tegalpasar, Banguntapan",
            "city": "Yogyakarta",
            "zip": "55198",
            "langlat": "(-7.798602099999999, 110.40890149999996)",
            "fb_id": null,
            "g_id": null,
            "g_photo": null,
            "creation_date": "2017-04-06",
            "google_plus": null,
            "skype": null,
            "facebook": null,
            "wishlist": [
                "4",
                "22",
                "21"
            ],
            "last_login": "2017-04-29",
            "user_type": "default",
            "user_type_till": null,
            "left_product_type": [ ],
            "downloads": [ ],
            "country": "Indonesia",
            "state": "Sleman",
            "currency": "Rp",
            "totalPurchase": "0.00",
            "last7Days": "0.00",
            "last30Days": "0.00",
            "orderHistory": [
                {
                    "sale_id": "1",
                    "sale_code": "2017041",
                    "buyer": "9",
                    "product_details": {
                        "3c59dc048e8850243be8079a5c74d079": {
                            "id": "21",
                            "qty": 12,
                            "option": "{\"color\":{\"title\":\"Color\",\"value\":\"rgba(204,204,204,1)\"}}",
                            "price": 300000,
                            "name": "Souvenir A001",
                            "shipping": "15000",
                            "tax": 0,
                            "image": "http://localhost/nusantara_mall_web/uploads/product_image/product_21_1_thumb.jpg",
                            "coupon": "",
                            "rowid": "3c59dc048e8850243be8079a5c74d079",
                            "subtotal": 3600000
                        }
                    },
                    "shipping_address": {
                        "firstname": "De",
                        "lastname": "Totty",
                        "address1": "Jl Raya janti no 240",
                        "address2": "Tegalpasar, Banguntapan",
                        "zip": "55198",
                        "email": "detotty@gmail.com",
                        "phone": "+628988448846",
                        "langlat": "(-7.798602099999999, 110.40890149999996)",
                        "payment_type": "cash_on_delivery"
                    },
                    "vat": "0",
                    "vat_percent": "",
                    "shipping": "180000",
                    "payment_type": "cash_on_delivery",
                    "payment_status": [
                        {
                            "admin": "",
                            "status": "due"
                        }
                    ],
                    "payment_details": "",
                    "payment_timestamp": null,
                    "grand_total": "3780000",
                    "sale_datetime": "1492944526",
                    "delivary_datetime": "",
                    "delivery_status": [
                        {
                            "admin": "",
                            "status": "pending",
                            "delivery_time": ""
                        }
                    ],
                    "viewed": "ok"
                }
            ],
            "image": {
                "original": "http://localhost/siteproject/nusantara-mall-web-app/uploads/user_image/user_9.jpg?t=1493453108",
                "thumb": "http://localhost/siteproject/nusantara-mall-web-app/uploads/user_image/user_9_thumb.jpg?t=1493453108"
            }
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

## PUT Update Password User
This endpoint update specific user password.
##### URL
`PUT` `http://nusantara-mall.org/index.php/api/users/password/(:user_id)`

##### Example Request
````sh
curl "http://nusantara-mall.org/index.php/api/users/password/9" -H "Content-Type: application/x-www-form-urlencoded" -d "oldPassword=12345&newPassword=abc&confirmNewPassword=abc"  -X "PUT"

````
##### Example Response
Success response:
````json
{
    "status": true,
    "totalResults": 1,
    "data": {
        "message": "ok"
    }
}
````

parameter not allowed
````json
{
    "status": false,
    "message": "state Param not allowed"
}
````

Passwords Did Not Match!
````json
{
    "status": false,
    "message": "Passwords Did Not Match!"
}
````