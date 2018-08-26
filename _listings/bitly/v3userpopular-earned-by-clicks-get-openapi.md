---
swagger: "2.0"
x-collection-name: Bitly
x-complete: 0
info:
  title: Bitly User Metrics API User Popular Earned By Clicks
  description: Returns the top links to your tracking domain (or domains) created
    by users not associated with your account, ordered by clicks.
  termsOfService: http://dev.bitly.com/best_practices.html
  version: v3
host: api-ssl.bitly.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/user/popular_earned_by_clicks:
    get:
      summary: User Popular Earned By Clicks
      description: Returns the top links to your tracking domain (or domains) created
        by users not associated with your account, ordered by clicks.
      operationId: userPopularEarnedbyClicks
      x-api-path-slug: v3userpopular-earned-by-clicks-get
      parameters:
      - in: query
        name: domain
        description: a tracking domain as returned from /v3/user/tracking_domain_list
      - in: query
        name: limit
        description: "1"
      - in: query
        name: timezone
        description: an integer hour offset from UTC (-14
      - in: query
        name: unit
        description: hour | day | week | month default:day
      - in: query
        name: units
        description: an integer representing the time units to query data for
      - in: query
        name: unit_reference_ts
        description: an epoch timestamp, indicating the most recent time for which
          to pull metrics
      responses:
        200:
          description: OK
      tags:
      - User
      - Popular
      - Earned
      - Clicks
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---