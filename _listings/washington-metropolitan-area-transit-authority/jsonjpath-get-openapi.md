---
swagger: "2.0"
x-collection-name: Washington Metropolitan Area Transit Authority
x-complete: 0
info:
  title: WMATA Rail Station Information JSON - Path Between Stations
  description: "Description\r\n\r\nReturns a set of ordered stations and distances
    between two stations on the\r\nsame line.\r\n\r\nNote that this method is not
    suitable on its own as a pathfinding solution\r\nbetween stations.\r\n\r\nResponse
    Elements\r\n\r\n\r\n\r\n\r\nElement\r\n\r\nDescription\r\n\r\n\r\n\r\n\r\n\r\nPath\r\n\r\n\r\nArray
    containing path details (MetroPathItem)\r\n\r\n\r\n\r\n\r\n\r\n\r\nMetroPathItem\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nDistanceToPrev\r\n\r\nDistance
    in feet to the previous station in the list.\r\n\r\n\r\n\r\nLineCode\r\n\r\nTwo-letter
    abbreviation for the line (e.g.: RD, BL, YL, OR, GR,\r\nor SV) this station's
    platform is on.\r\n\r\n\r\n\r\nSeqNum\r\n\r\nOrdered sequence number.\r\n\r\n\r\n\r\nStationCode\r\n\r\nStation
    code for this station. Use this value in other\r\nrail-related APIs to retrieve
    data about a station.\r\n\r\n\r\n\r\nStationName\r\n\r\nFull name for this station,
    as shown on the WMATA website."
  version: 1.0.0
host: api.wmata.com
basePath: /Rail.svc
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /json/jPath:
    get:
      summary: JSON - Path Between Stations
      description: "Description\r\n\r\nReturns a set of ordered stations and distances
        between two stations on the\r\nsame line.\r\n\r\nNote that this method is
        not suitable on its own as a pathfinding solution\r\nbetween stations.\r\n\r\nResponse
        Elements\r\n\r\n\r\n\r\n\r\nElement\r\n\r\nDescription\r\n\r\n\r\n\r\n\r\n\r\nPath\r\n\r\n\r\nArray
        containing path details (MetroPathItem)\r\n\r\n\r\n\r\n\r\n\r\n\r\nMetroPathItem\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nDistanceToPrev\r\n\r\nDistance
        in feet to the previous station in the list.\r\n\r\n\r\n\r\nLineCode\r\n\r\nTwo-letter
        abbreviation for the line (e.g.: RD, BL, YL, OR, GR,\r\nor SV) this station's
        platform is on.\r\n\r\n\r\n\r\nSeqNum\r\n\r\nOrdered sequence number.\r\n\r\n\r\n\r\nStationCode\r\n\r\nStation
        code for this station. Use this value in other\r\nrail-related APIs to retrieve
        data about a station.\r\n\r\n\r\n\r\nStationName\r\n\r\nFull name for this
        station, as shown on the WMATA website."
      operationId: getJsonJpath
      x-api-path-slug: jsonjpath-get
      parameters:
      - in: query
        name: FromStationCode
        description: Station code for the origin station
      - in: query
        name: ToStationCode
        description: Station code for the destination station
      responses:
        200:
          description: OK
      tags:
      - Transit
      - Paths
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