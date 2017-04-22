### [&laquo; Home](index.md)

## Get All Products
This endpoint retrieves all products.
##### URL GET ALL PRODUCTS
`GET` `http://nusantara.detotty.com/index.php/api/products`

##### URL GET BY FILTER
`http://nusantara.detotty.com/index.php/api/products?filter[product_id]=1`
`http://nusantara.detotty.com/index.php/api/products?filter[category]=1&filter[sub_category]=5`

##### Example Request
````sh
curl "http://nusantara.detotty.com/index.php/api/products" -X "GET"

````

##### Example Response
Success response:
````json
{

    "status": true,
    "totalResults": 1,
    "data": [
        {
            "product_id": "14",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Bridal Gown ",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "4",
            "description": "<p><span style=\"text-align: justify;\">Lorem Ipsum&nbsp;is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages</span><br></p>",
            "sub_category": "34",
            "num_of_imgs": "1",
            "sale_price": "350.00",
            "purchase_price": "320.00",
            "shipping_cost": "9.99",
            "add_timestamp": "1472985919",
            "featured": "0",
            "tag": [
                "bride",
                "bridal dress"
            ],
            "status": "ok",
            "front_image": "0",
            "brand": "9",
            "current_stock": "0",
            "unit": "pc",
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "1",
            "background": null,
            "discount": "2",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": [
                "rgba(247,172,172,1)",
                "rgba(252,239,239,1)"
            ],
            "options": [
                {
                    "no": "0",
                    "title": "Size",
                    "name": "choice_0",
                    "type": "single_select",
                    "option": [
                        "46",
                        "50",
                        "54"
                    ]
                }
            ],
            "main_image": "0",
            "download": null,
            "download_name": null,
            "deal": null,
            "num_of_downloads": "0",
            "update_time": null,
            "requirements": null,
            "logo": null,
            "video": null,
            "last_viewed": null,
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/14"
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
        "product_ids": "product_ids not allowed using on filter"
    }

}
````
## Get Latest Products
This endpoint retrieves latest products.
##### URL GET THE LATEST PRODUCTS
`GET` `http://nusantara.detotty.com/index.php/api/products/latest`

##### Example Request
````sh
curl "http://nusantara.detotty.com/index.php/api/products/latest" -X "GET"

````

##### Example Response
Success response:
````json
{

    "status": true,
    "totalResults": 5,
    "data": [
        {
            "product_id": "100",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "3D Impact",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "13",
            "description": "<p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p><p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p>                                    ",
            "sub_category": "73",
            "num_of_imgs": "5",
            "sale_price": "20.00",
            "purchase_price": "19.00",
            "shipping_cost": "0",
            "add_timestamp": "1476002821",
            "featured": "ok",
            "tag": [
                "3d design",
                "design "
            ],
            "status": "ok",
            "front_image": null,
            "brand": null,
            "current_stock": "0",
            "unit": null,
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "3",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": null,
            "options": null,
            "main_image": "0",
            "download": "ok",
            "download_name": "100_c7e6cd571a7ca96492c3_3d design.zip",
            "deal": null,
            "num_of_downloads": "0",
            "update_time": "1476273286",
            "requirements": [
                {
                    "index": 0,
                    "field": "Color",
                    "desc": "<p>Multiple</p>"
                }
            ],
            "logo": "digital_logo_100.jpg",
            "video": [ ],
            "last_viewed": "1476381822",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/100"
        },
        {
            "product_id": "99",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Colored Solution",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "13",
            "description": "<p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p><p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p>                                                                        ",
            "sub_category": "75",
            "num_of_imgs": "3",
            "sale_price": "26.00",
            "purchase_price": "20.00",
            "shipping_cost": "0",
            "add_timestamp": "1476001190",
            "featured": "ok",
            "tag": [
                "printing solutioncolor",
                "color"
            ],
            "status": "ok",
            "front_image": null,
            "brand": null,
            "current_stock": "0",
            "unit": null,
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "2",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": null,
            "options": null,
            "main_image": "0",
            "download": "ok",
            "download_name": "99_c04a03c2506a4ba12d38_printing solution.zip",
            "deal": "ok",
            "num_of_downloads": "0",
            "update_time": "1476360456",
            "requirements": [
                {
                    "index": 0,
                    "field": "Package",
                    "desc": "<p>Full</p>"
                }
            ],
            "logo": "digital_logo_99.jpg",
            "video": [ ],
            "last_viewed": "1476001368",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/99"
        },
        {
            "product_id": "98",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Classified php script",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "12",
            "description": "                                                                                                                                                                <p>&nbsp;Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of \"de Finibus Bonorum et Malorum\" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, \"Lorem ipsum dolor sit amet..\", comes from a line in section 1.10.32</p><p>The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from \"de Finibus Bonorum et Malorum\" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.</p>                                                                                                                                                ",
            "sub_category": "66",
            "num_of_imgs": "3",
            "sale_price": "38.00",
            "purchase_price": "38.00",
            "shipping_cost": "0",
            "add_timestamp": "1475924525",
            "featured": "no",
            "tag": [
                "php",
                "classified "
            ],
            "status": "ok",
            "front_image": null,
            "brand": null,
            "current_stock": "0",
            "unit": null,
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "8",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": null,
            "options": null,
            "main_image": "0",
            "download": "ok",
            "download_name": "98_27cf69cb8ee8f1eaf47c_asdasdestghfjktgsseruyhxrityik.zip",
            "deal": null,
            "num_of_downloads": "0",
            "update_time": "1476352505",
            "requirements": [
                {
                    "index": 0,
                    "field": "php version",
                    "desc": "<p>php 5.0</p>"
                }
            ],
            "logo": "digital_logo_98.jpg",
            "video": [ ],
            "last_viewed": "1476350431",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/98"
        },
        {
            "product_id": "89",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Super Racing Bike",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "1",
            "description": "                                                                                                                                                                <p><span style=\"text-align: justify;\">Lorem Ipsum</span><span style=\"text-align: justify;\">&nbsp;</span><span style=\"text-align: justify;\">is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum</span><br></p>",
            "sub_category": "6",
            "num_of_imgs": "1",
            "sale_price": "45000.00",
            "purchase_price": "42000.00",
            "shipping_cost": "",
            "add_timestamp": "1474801360",
            "featured": "0",
            "tag": [
                "bike",
                "racing honda",
                "honda"
            ],
            "status": "ok",
            "front_image": "0",
            "brand": "52",
            "current_stock": "9",
            "unit": "Pc",
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "2",
            "background": null,
            "discount": "10",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": [
                "rgba(255,255,255,1)",
                "rgba(0,0,0,1)"
            ],
            "options": [ ],
            "main_image": "0",
            "download": null,
            "download_name": null,
            "deal": null,
            "num_of_downloads": "0",
            "update_time": null,
            "requirements": null,
            "logo": null,
            "video": null,
            "last_viewed": "1476269484",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/89"
        },
        {
            "product_id": "88",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Faster Racing Bike",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "1",
            "description": "<p><span style=\"text-align: justify;\">Lorem Ipsum</span><span style=\"text-align: justify;\">&nbsp;</span><span style=\"text-align: justify;\">is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum</span><br></p>",
            "sub_category": "6",
            "num_of_imgs": "1",
            "sale_price": "36000.00",
            "purchase_price": "33890.00",
            "shipping_cost": "1800",
            "add_timestamp": "1474800321",
            "featured": "no",
            "tag": [
                "racing bike",
                "honda",
                "bike"
            ],
            "status": "ok",
            "front_image": "0",
            "brand": "52",
            "current_stock": "24",
            "unit": "Pc",
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "2",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "5",
            "tax_type": "percent",
            "color": [
                "rgba(0,0,0,1)",
                "rgba(255,0,0,1)",
                "rgba(255,247,55,1)"
            ],
            "options": [ ],
            "main_image": "0",
            "download": null,
            "download_name": null,
            "deal": null,
            "num_of_downloads": "0",
            "update_time": null,
            "requirements": null,
            "logo": null,
            "video": null,
            "last_viewed": "1492804513",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/88"
        }
    ]

}
````

## Get Todays Deal
This endpoint retrieves todays deal products.
##### URL GET THE TODAYS DEAL PRODUCTS
`GET` `http://nusantara.detotty.com/index.php/api/products/todaysdeal`

##### Example Request
````sh
curl "http://nusantara.detotty.com/index.php/api/products/todaysdeal" -X "GET"

````

##### Example Response
Success response:
````json
{

    "status": true,
    "totalResults": 4,
    "data": [
        {
            "product_id": "99",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Colored Solution",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "13",
            "description": "<p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p><p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p>                                                                        ",
            "sub_category": "75",
            "num_of_imgs": "3",
            "sale_price": "26.00",
            "purchase_price": "20.00",
            "shipping_cost": "0",
            "add_timestamp": "1476001190",
            "featured": "ok",
            "tag": [
                "printing solutioncolor",
                "color"
            ],
            "status": "ok",
            "front_image": null,
            "brand": null,
            "current_stock": "0",
            "unit": null,
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "2",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": null,
            "options": null,
            "main_image": "0",
            "download": "ok",
            "download_name": "99_c04a03c2506a4ba12d38_printing solution.zip",
            "deal": "ok",
            "num_of_downloads": "0",
            "update_time": "1476360456",
            "requirements": [
                {
                    "index": 0,
                    "field": "Package",
                    "desc": "<p>Full</p>"
                }
            ],
            "logo": "digital_logo_99.jpg",
            "video": [ ],
            "last_viewed": "1476001368",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/99"
        },
        {
            "product_id": "82",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Gulfstream G550 Air Jet",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "1",
            "description": "<p><span style=\"text-align: justify;\">Lorem Ipsum</span><span style=\"text-align: justify;\">&nbsp;</span><span style=\"text-align: justify;\">is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum</span><br></p>",
            "sub_category": "63",
            "num_of_imgs": "1",
            "sale_price": "4800000.00",
            "purchase_price": "4467490.00",
            "shipping_cost": "145780",
            "add_timestamp": "1474792870",
            "featured": "0",
            "tag": [
                "private plane",
                "private jet",
                "private air"
            ],
            "status": "ok",
            "front_image": "0",
            "brand": "46",
            "current_stock": "8",
            "unit": "Pc",
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "2",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "25",
            "tax_type": "percent",
            "color": [
                "rgba(237,237,237,1)"
            ],
            "options": [ ],
            "main_image": "0",
            "download": null,
            "download_name": null,
            "deal": "ok",
            "num_of_downloads": "0",
            "update_time": null,
            "requirements": null,
            "logo": null,
            "video": null,
            "last_viewed": "1475880938",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/82"
        },
        {
            "product_id": "80",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Hughes UR-Path Helicopter",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "1",
            "description": "<p><span style=\"text-align: justify;\">Lorem Ipsum&nbsp;is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum</span><br></p>",
            "sub_category": "63",
            "num_of_imgs": "1",
            "sale_price": "775000.00",
            "purchase_price": "558900.00",
            "shipping_cost": "58900",
            "add_timestamp": "1474791921",
            "featured": "no",
            "tag": [
                "helicopter",
                "privet helicopter",
                "private jet"
            ],
            "status": "ok",
            "front_image": "0",
            "brand": "39",
            "current_stock": "10",
            "unit": "Pc",
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "1",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "19",
            "tax_type": "percent",
            "color": [
                "rgba(250,230,49,1)"
            ],
            "options": [ ],
            "main_image": "0",
            "download": null,
            "download_name": null,
            "deal": "ok",
            "num_of_downloads": "0",
            "update_time": null,
            "requirements": null,
            "logo": null,
            "video": null,
            "last_viewed": null,
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/80"
        },
        {
            "product_id": "78",
            "rating_num": "1",
            "rating_total": "5",
            "rating_user": [
                "3"
            ],
            "title": "Mercedes Benz SUV ",
            "added_by": {
                "type": "vendor",
                "id": "3"
            },
            "category": "1",
            "description": "<p><span id=\"docs-internal-guid-c79edabb-5c4c-3f82-8b4b-045482ca5abb\"><span [removed]=\"text-align: justify;\">Lorem Ipsum&nbsp;is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum</span><br></span></p>",
            "sub_category": "3",
            "num_of_imgs": "1",
            "sale_price": "140825.00",
            "purchase_price": "131772.00",
            "shipping_cost": "1072",
            "add_timestamp": "1474722247",
            "featured": "no",
            "tag": [
                "car",
                "super car",
                "luxury car"
            ],
            "status": "ok",
            "front_image": "0",
            "brand": "51",
            "current_stock": "19",
            "unit": "Pc",
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "3",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "25",
            "tax_type": "percent",
            "color": [
                "rgba(227,219,219,1)"
            ],
            "options": [ ],
            "main_image": "0",
            "download": null,
            "download_name": null,
            "deal": "ok",
            "num_of_downloads": "0",
            "update_time": null,
            "requirements": null,
            "logo": null,
            "video": null,
            "last_viewed": "1476005586",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/78"
        }
    ]

}
````

## Get featured
This endpoint retrieves featured products.
##### URL GET THE FEATURED PRODUCTS
`GET` `http://nusantara.detotty.com/index.php/api/products/featured`

##### Example Request
````sh
curl "http://nusantara.detotty.com/index.php/api/products/featured" -X "GET"

````

##### Example Response
Success response:
````json
{

    "status": true,
    "totalResults": 4,
    "data": [
        {
            "product_id": "100",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "3D Impact",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "13",
            "description": "<p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p><p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p>                                    ",
            "sub_category": "73",
            "num_of_imgs": "5",
            "sale_price": "20.00",
            "purchase_price": "19.00",
            "shipping_cost": "0",
            "add_timestamp": "1476002821",
            "featured": "ok",
            "tag": [
                "3d design",
                "design "
            ],
            "status": "ok",
            "front_image": null,
            "brand": null,
            "current_stock": "0",
            "unit": null,
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "3",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": null,
            "options": null,
            "main_image": "0",
            "download": "ok",
            "download_name": "100_c7e6cd571a7ca96492c3_3d design.zip",
            "deal": null,
            "num_of_downloads": "0",
            "update_time": "1476273286",
            "requirements": [
                {
                    "index": 0,
                    "field": "Color",
                    "desc": "<p>Multiple</p>"
                }
            ],
            "logo": "digital_logo_100.jpg",
            "video": [ ],
            "last_viewed": "1476381822",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/100"
        },
        {
            "product_id": "99",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Colored Solution",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "13",
            "description": "<p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p><p>Lorem Ipsum is simply dummy text of the printing and \r\ntypesetting industry. Lorem Ipsum has been the industry's standard dummy\r\n text ever since the 1500s, when an unknown printer took a galley of \r\ntype and scrambled it to make a type specimen book. It has survived not \r\nonly five centuries, but also the leap into electronic typesetting, \r\nremaining essentially unchanged. It was popularised in the 1960s with \r\nthe release of Letraset sheets containing Lorem Ipsum passages, and more\r\n recently with desktop publishing software like Aldus PageMaker \r\nincluding versions of Lorem Ipsum</p>                                                                        ",
            "sub_category": "75",
            "num_of_imgs": "3",
            "sale_price": "26.00",
            "purchase_price": "20.00",
            "shipping_cost": "0",
            "add_timestamp": "1476001190",
            "featured": "ok",
            "tag": [
                "printing solutioncolor",
                "color"
            ],
            "status": "ok",
            "front_image": null,
            "brand": null,
            "current_stock": "0",
            "unit": null,
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "2",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": null,
            "options": null,
            "main_image": "0",
            "download": "ok",
            "download_name": "99_c04a03c2506a4ba12d38_printing solution.zip",
            "deal": "ok",
            "num_of_downloads": "0",
            "update_time": "1476360456",
            "requirements": [
                {
                    "index": 0,
                    "field": "Package",
                    "desc": "<p>Full</p>"
                }
            ],
            "logo": "digital_logo_99.jpg",
            "video": [ ],
            "last_viewed": "1476001368",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/99"
        },
        {
            "product_id": "36",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Party Wear",
            "added_by": {
                "type": "vendor",
                "id": "1"
            },
            "category": "4",
            "description": "                                                                                                                                                                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages<br></p>",
            "sub_category": "8",
            "num_of_imgs": "1",
            "sale_price": "250.00",
            "purchase_price": "210.00",
            "shipping_cost": "",
            "add_timestamp": "1473078320",
            "featured": "ok",
            "tag": [
                "party dress",
                "dress"
            ],
            "status": "ok",
            "front_image": "0",
            "brand": "8",
            "current_stock": "0",
            "unit": "pc",
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "4",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": [
                "rgba(250,12,12,1)"
            ],
            "options": [
                {
                    "no": "0",
                    "title": "Size",
                    "name": "choice_0",
                    "type": "multi_select",
                    "option": [
                        "XXL",
                        "XL",
                        "L",
                        "M",
                        "S"
                    ]
                }
            ],
            "main_image": "0",
            "download": null,
            "download_name": null,
            "deal": null,
            "num_of_downloads": "0",
            "update_time": null,
            "requirements": null,
            "logo": null,
            "video": null,
            "last_viewed": "1476179405",
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/36"
        },
        {
            "product_id": "35",
            "rating_num": "0",
            "rating_total": "0",
            "rating_user": [ ],
            "title": "Formal Short Dress",
            "added_by": {
                "type": "admin",
                "id": "1"
            },
            "category": "4",
            "description": "<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages<br></p>",
            "sub_category": "35",
            "num_of_imgs": "1",
            "sale_price": "280.00",
            "purchase_price": "240.00",
            "shipping_cost": "",
            "add_timestamp": "1473077524",
            "featured": "ok",
            "tag": [
                "dress",
                "office dress"
            ],
            "status": "ok",
            "front_image": "0",
            "brand": "11",
            "current_stock": "0",
            "unit": "pc",
            "additional_fields": {
                "name": "null",
                "value": "null"
            },
            "number_of_view": "1",
            "background": null,
            "discount": "",
            "discount_type": "percent",
            "tax": "",
            "tax_type": "percent",
            "color": [
                "rgba(27,115,73,1)"
            ],
            "options": [
                {
                    "no": "1",
                    "title": "Size",
                    "name": "choice_1",
                    "type": "multi_select",
                    "option": [
                        "XXL",
                        "XL",
                        "L",
                        "M",
                        "S"
                    ]
                }
            ],
            "main_image": "0",
            "download": null,
            "download_name": null,
            "deal": null,
            "num_of_downloads": "0",
            "update_time": null,
            "requirements": null,
            "logo": null,
            "video": null,
            "last_viewed": null,
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/products/35"
        }
    ]

}
````