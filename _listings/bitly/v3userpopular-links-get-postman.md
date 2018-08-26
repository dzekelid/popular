{
  "info": {
    "name": "Bitly User Metrics API User Popular Links",
    "_postman_id": "3af93411-56b2-48a2-8ab3-239ade1b4ed3",
    "description": "Returns the authenticated users most-clicked Bitlinks (ordered by number of clicks) in a given time period.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "e8ee34ac-2baf-4d01-a6a8-ca212fe89fcb",
          "name": "userClicks",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/user/clicks?format=%7B%7D&limit=%7B%7D&rollup=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the aggregate number of clicks on all of the authenticated users Bitlinks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff7687ba-5ed9-47db-a462-cec92654f345"
            }
          ]
        },
        {
          "id": "f243df25-8fa9-4811-a38a-ca0cc8bc1ad5",
          "name": "userCountries",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/user/countries?limit=%7B%7D&rollup=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns aggregate metrics about the countries referring click traffic to all of the authenticated users Bitlinks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "832dbea2-2c64-40d2-b205-98dcebe15aca"
            }
          ]
        },
        {
          "id": "738ae0e8-8567-4bf5-8f01-a247c3700faa",
          "name": "userPopularEarnedbyClicks",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/user/popular_earned_by_clicks?domain=%7B%7D&limit=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top links to your tracking domain (or domains) created by users not associated with your account, ordered by clicks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "141ff64f-3367-4802-84e8-eb46fe7e4118"
            }
          ]
        },
        {
          "id": "d8822902-a2b3-4ee2-86ca-e7a8f3efab00",
          "name": "userPopularEarnedByShortens",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/user/popular_earned_by_shortens?domain=%7B%7D&limit=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top links to your tracking domain (or domains) created by users not associated with your account, ordered by shortens."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9138fcd9-9d8f-4a62-8d0e-fbe9a14f9001"
            }
          ]
        },
        {
          "id": "ababd546-a921-4584-9d0b-13069074309a",
          "name": "userPopularLinks",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/user/popular_links?limit=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the authenticated users most-clicked Bitlinks (ordered by number of clicks) in a given time period."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7dc08ade-471f-4cc8-a524-6e25d8a18704"
            }
          ]
        }
      ]
    }
  ]
}