### [&laquo; Home](index.md)

## Get All Categories
This endpoint retrieves all categories.
##### URL
`GET` `http://nusantara-mall.org/index.php/api/categories`

##### URL GET BY FILTER
`http://nusantara-mall.org/index.php/api/categories?filter[category_id]=1`

##### Example Request
````sh
curl "http://nusantara-mall.org/index.php/api/categories" -X "GET"

````
##### Example Response
Success response:
````json
{

    "status": true,
    "totalResults": 1,
    "data": [
        {
            "category_id": "1",
            "category_name": "Automobile",
            "description": null,
            "digital": null,
            "banner": "category_1.jpg",
            "data_brands": [
                [
                    "41",
                    "Chevrolet"
                ],
                [
                    "40",
                    "Ford"
                ],
                [
                    "39",
                    "Nissan"
                ],
                [
                    "38",
                    "Audi"
                ],
                [
                    "44",
                    "Hyundai"
                ],
                [
                    "45",
                    "BMW"
                ],
                [
                    "46",
                    "Marcedes-Benz"
                ],
                [
                    "47",
                    "Mitsubishi"
                ],
                [
                    "51",
                    "Toyota"
                ],
                [
                    "52",
                    "Honda"
                ],
                [
                    "54",
                    "Volvo"
                ],
                [
                    "50",
                    "Lamborghini"
                ],
                [
                    "55",
                    "Porsche"
                ],
                [
                    "48",
                    "Suzuki"
                ],
                [
                    "56",
                    "Dunlop"
                ],
                [
                    "57",
                    "Yamaha"
                ]
            ],
            "data_vendors": [
                [
                    "3",
                    "Tom"
                ]
            ],
            "data_subdets": [
                {
                    "sub_id": "1",
                    "sub_name": "Car",
                    "min": 0,
                    "max": 0,
                    "brands": [
                        [
                            "41",
                            "Chevrolet"
                        ],
                        [
                            "40",
                            "Ford"
                        ],
                        [
                            "39",
                            "Nissan"
                        ],
                        [
                            "38",
                            "Audi"
                        ],
                        [
                            "44",
                            "Hyundai"
                        ],
                        [
                            "45",
                            "BMW"
                        ],
                        [
                            "46",
                            "Marcedes-Benz"
                        ],
                        [
                            "47",
                            "Mitsubishi"
                        ],
                        [
                            "51",
                            "Toyota"
                        ],
                        [
                            "52",
                            "Honda"
                        ],
                        [
                            "54",
                            "Volvo"
                        ]
                    ]
                },
                {
                    "sub_id": "2",
                    "sub_name": "Racing Car",
                    "min": 0,
                    "max": 0,
                    "brands": [
                        [
                            "41",
                            "Chevrolet"
                        ],
                        [
                            "40",
                            "Ford"
                        ],
                        [
                            "39",
                            "Nissan"
                        ],
                        [
                            "38",
                            "Audi"
                        ],
                        [
                            "45",
                            "BMW"
                        ],
                        [
                            "46",
                            "Marcedes-Benz"
                        ],
                        [
                            "47",
                            "Mitsubishi"
                        ],
                        [
                            "50",
                            "Lamborghini"
                        ],
                        [
                            "51",
                            "Toyota"
                        ],
                        [
                            "52",
                            "Honda"
                        ],
                        [
                            "54",
                            "Volvo"
                        ],
                        [
                            "55",
                            "Porsche"
                        ]
                    ]
                },
                {
                    "sub_id": "3",
                    "sub_name": "Luxury SUV",
                    "min": 46545,
                    "max": 140825,
                    "brands": [
                        [
                            "41",
                            "Chevrolet"
                        ],
                        [
                            "40",
                            "Ford"
                        ],
                        [
                            "39",
                            "Nissan"
                        ],
                        [
                            "45",
                            "BMW"
                        ],
                        [
                            "47",
                            "Mitsubishi"
                        ],
                        [
                            "51",
                            "Toyota"
                        ],
                        [
                            "54",
                            "Volvo"
                        ]
                    ]
                },
                {
                    "sub_id": "5",
                    "sub_name": "Chopper Bike",
                    "min": 13150,
                    "max": 79560,
                    "brands": [
                        [
                            "39",
                            "Nissan"
                        ],
                        [
                            "45",
                            "BMW"
                        ],
                        [
                            "48",
                            "Suzuki"
                        ],
                        [
                            "52",
                            "Honda"
                        ],
                        [
                            "56",
                            "Dunlop"
                        ],
                        [
                            "57",
                            "Yamaha"
                        ]
                    ]
                },
                {
                    "sub_id": "6",
                    "sub_name": "Racing Bike",
                    "min": 36000,
                    "max": 48000,
                    "brands": [
                        [
                            "45",
                            "BMW"
                        ],
                        [
                            "52",
                            "Honda"
                        ],
                        [
                            "57",
                            "Yamaha"
                        ]
                    ]
                },
                {
                    "sub_id": "63",
                    "sub_name": "Private Air",
                    "min": 775000,
                    "max": 4800000,
                    "brands": [
                        [
                            "40",
                            "Ford"
                        ],
                        [
                            "39",
                            "Nissan"
                        ],
                        [
                            "38",
                            "Audi"
                        ],
                        [
                            "46",
                            "Marcedes-Benz"
                        ],
                        [
                            "47",
                            "Mitsubishi"
                        ],
                        [
                            "55",
                            "Porsche"
                        ]
                    ]
                }
            ],
            "url_detail": "http://localhost/siteproject/nusantara_mall/index.php/api/categories/1",
            "url_product_lists": "http://localhost/siteproject/nusantara_mall/index.php/api/categories/products/1"
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
        "category_ids": "category_ids not allowed using on filter"
    }

}
````