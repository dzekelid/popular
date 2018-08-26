{
  "info": {
    "name": "Bitly Organization Metric API Organization Popular Links",
    "_postman_id": "f36c908e-9d42-441e-96de-81779aeefc0f",
    "description": "Returns the top links shared by you or your audience, ordered by clicks",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Organization",
      "item": [
        {
          "id": "2aafe320-d380-443d-9851-e9b3b87876b2",
          "name": "organizationBrandMessages",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/organization/brand_messages?domain=%7B%7D&limit=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top Bitlinks created by you with traffic, that did not also have non-organization traffic in the same time period, ordered by clicks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "607d9c50-572f-4181-82da-ae115550d08b"
            }
          ]
        },
        {
          "id": "863ad3b4-7d5d-49f4-a097-bd5b456a2a5f",
          "name": "organizationClicks",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/organization/clicks?domain=%7B%7D&limit=%7B%7D&login=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the number of clicks on Bitlinks created by your organization or by other Bitly users that point to your domains."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86b64504-9264-48e2-982e-5179e75c3e12"
            }
          ]
        },
        {
          "id": "baf3863f-1228-4758-94fc-2b8b95ebbb72",
          "name": "organizationIntersectingLinks",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/organization/intersecting_links?domain=%7B%7D&limit=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top links shared by both your audience and by your account, ordered by clicks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b09a46ab-9277-466e-b3be-89b3f9fce8c9"
            }
          ]
        },
        {
          "id": "2ea9d0e1-1e41-410b-bb53-592f990548af",
          "name": "organizationLeaderBoard",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/organization/leaderboard?domain=%7B%7D&limit=%7B%7D&orderby=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top-performing organization members ordered by clicks or shortens."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "004e0771-8c80-456a-9d94-73ac21c21e8a"
            }
          ]
        },
        {
          "id": "fb1cf37d-8cfe-4312-8a5e-bc85922a8dff",
          "name": "organizationMissedOpportunities",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/organization/missed_opportunities?an epoch timestamp, indicating the most recent time for which to pull metrics. default:now=%7B%7D&domain=%7B%7D&limit=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top links shared by your audience, but not by you, ordered by clicks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53c0762f-2161-45f4-987b-613fbe446b17"
            }
          ]
        },
        {
          "id": "8322c02b-456b-4a87-b95e-66aeedab4bd0",
          "name": "organizationPopularLinks",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/organization/popular_links?domain=%7B%7D&limit=%7B%7D&timezone=%7B%7D&unit=%7B%7D&units=%7B%7D&unit_reference_ts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the top links shared by you or your audience, ordered by clicks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4f762ec8-0130-4623-aa6f-287d215369bc"
            }
          ]
        }
      ]
    }
  ]
}