{
  "info": {
    "name": "Bitly User Metrics API User Popular Owned By Clicks",
    "_postman_id": "085df904-c7b4-4c36-8687-adcd1a535bf2",
    "description": "Returns the top links to your tracking domain (or domains) created by you or your subaccounts ordered by clicks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "12d1a5be-b553-4376-931f-c84a620aca2d",
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
              "id": "b9e17c06-c8b1-4e96-b5ae-89f1bd12ef7a"
            }
          ]
        },
        {
          "id": "9da7afd3-d924-454d-8b13-4ec3beedaeb1",
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
              "id": "20e344cc-0c05-4a8b-a98f-5f0e851c9c02"
            }
          ]
        },
        {
          "id": "fdac4eb3-a3d5-4f6a-a2c3-47788472dafd",
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
              "id": "4eb414a2-0b06-49cc-b2b9-f238803b127c"
            }
          ]
        },
        {
          "id": "02f52bf8-36ea-483a-80d8-1a3e2015d3ac",
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
              "id": "3c697d2c-bec8-41e4-98e8-1e70acdb03fa"
            }
          ]
        },
        {
          "id": "fffa17fd-6713-4b69-90de-bd8353d1e76c",
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
              "id": "68270935-c9ae-479f-84a8-7fc31db29dce"
            }
          ]
        },
        {
          "id": "fb99223d-45e1-4855-9004-0dd8f57792e2",
          "name": "userPopularOwnedByClicks",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/user/popular_owned_by_clicks?domain=%7B%7D&limit=%7B%7D&subaccount=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top links to your tracking domain (or domains) created by you or your subaccounts ordered by clicks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4dc82db6-a4ec-4a8d-8ed6-c5925d5e0ed7"
            }
          ]
        }
      ]
    }
  ]
}