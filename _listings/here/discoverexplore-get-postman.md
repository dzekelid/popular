{
  "info": {
    "name": "HERE Places API Explore Popular Places",
    "_postman_id": "5bdff3ee-106d-4f06-ad2e-10f4840f944e",
    "description": "*Request a list of popular places around a location*\n\nThe `explore` location context can either be an explicitly given location using the `at` parameter, or implicitly defined by a user's current position or the currently visible map.\n\n\n\n* **at**  `latlng`\n \\- Location of the central point for the places search.    e.g. `52.515,13.377`\n\n* **app_id**  `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.\n\n* **app_code**  `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.\n\n* **Accept**  `header`\n\n  Format to request from the server",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Explore",
      "item": [
        {
          "id": "dae6bc81-35c6-4cd0-99f1-e5ea852c6438",
          "name": "DiscoverExploreGet5",
          "request": {
            "url": "http://places.demo.api.here.com/places/v1/discover/explore?app_code=%7B%7D&app_id=%7B%7D&at=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "*Request a list of popular places around a location*\n\nThe `explore` location context can either be an explicitly given location using the `at` parameter, or implicitly defined by a user's current position or the currently visible map.\n\n\n\n* **at**  `latlng`\n \\- Location of the central point for the places search.    e.g. `52.515,13.377`\n\n* **app_id**  `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.\n\n* **app_code**  `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.\n\n* **Accept**  `header`\n\n  Format to request from the server"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d68e7e3-2d4f-4aa0-a4cf-5e0258b3a073"
            }
          ]
        }
      ]
    }
  ]
}