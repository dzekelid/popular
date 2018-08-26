{
  "info": {
    "name": "Bitly User Metrics API User Popular Earned By Shortens",
    "_postman_id": "e785b4b1-af1f-4437-843a-39e38382e5a6",
    "description": "Returns the top links to your tracking domain (or domains) created by users not associated with your account, ordered by shortens.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "c1759e5b-ddb0-4138-822b-234fb8844e47",
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
              "id": "a527bbda-c6c5-4f5e-bc37-64ca3cd8a88d"
            }
          ]
        },
        {
          "id": "974bbaa7-3490-40c7-b19b-fd451d486a61",
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
              "id": "85840c35-c91b-4f32-bfeb-0c7a327d8305"
            }
          ]
        },
        {
          "id": "86479377-ddb4-4c5f-aca1-cbc9ca7f2385",
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
              "id": "7b1e104b-01e3-4028-af01-7dc8a4bed739"
            }
          ]
        },
        {
          "id": "1d50d8e9-8d78-4e34-a3c4-20ce3ec7771c",
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
              "id": "3191a291-fe39-4398-91cf-71706705a773"
            }
          ]
        }
      ]
    }
  ]
}