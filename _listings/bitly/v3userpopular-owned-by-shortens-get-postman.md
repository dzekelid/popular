{
  "info": {
    "name": "Bitly User Metrics API User Popular Owned by Shortens",
    "_postman_id": "b9f631e0-f2d0-4cda-aa64-bdd57e67da4c",
    "description": "Returns the top links to your tracking domain (or domains) created by you or your subaccounts ordered by number of shortens.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "User",
      "item": [
        {
          "id": "58a92ef2-ee2e-4d65-be83-0351be4b380b",
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
              "id": "32007e76-98e8-49e4-920c-6e3d4f0e31f8"
            }
          ]
        },
        {
          "id": "0c806a6b-9b62-42b6-90ac-f3c52471d26a",
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
              "id": "c62a23b0-f9f3-49cf-9847-3c7aaf1299cf"
            }
          ]
        },
        {
          "id": "1a98d50e-f2f0-490b-b910-76fe5c2ee221",
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
              "id": "2d261d55-aa98-4ebb-a588-412115d26079"
            }
          ]
        },
        {
          "id": "5aac2414-266f-4374-9cd2-56365696c92b",
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
              "id": "12e19b1e-999d-4f5a-b002-adff810dac75"
            }
          ]
        },
        {
          "id": "656ec3bb-5a31-4d1d-a13a-48f032ae4699",
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
              "id": "fea71afb-cd2d-4612-8460-c9fe2d10ed7e"
            }
          ]
        },
        {
          "id": "8aaa7f59-f058-455e-abce-682988c0fa05",
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
              "id": "dc3f62d7-9862-4880-b747-3fb7adedcb14"
            }
          ]
        },
        {
          "id": "1f8f53d1-e945-4299-90e1-16e594e85522",
          "name": "userPopularOwnedByShortens",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/user/popular_owned_by_shortens?domain=%7B%7D&limit=%7B%7D&subaccount=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top links to your tracking domain (or domains) created by you or your subaccounts ordered by number of shortens."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c822bb9-9616-4f52-8897-4540040b7bab"
            }
          ]
        }
      ]
    }
  ]
}