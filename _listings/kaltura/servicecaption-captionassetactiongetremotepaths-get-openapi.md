---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Caption Captionasset Action Getremotepaths
  description: Get remote storage existing paths for the asset
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/attachment_attachmentasset/action/getRemotePaths:
    get:
      summary: Get Service Attachment Attachmentasset Action Getremotepaths
      description: Get remote storage existing paths for the asset
      operationId: attachmentAsset.getRemotePaths
      x-api-path-slug: serviceattachment-attachmentassetactiongetremotepaths-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Attachment
      - Attachmentasset
      - Action
      - GetRemotePaths
  /service/baseentry/action/getRemotePaths:
    get:
      summary: Get Service Baseentry Action Getremotepaths
      description: Get remote storage existing paths for the asset.
      operationId: baseEntry.getRemotePaths
      x-api-path-slug: servicebaseentryactiongetremotepaths-get
      parameters:
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Baseentry
      - Action
      - GetRemotePaths
  /service/caption_captionasset/action/getRemotePaths:
    get:
      summary: Get Service Caption Captionasset Action Getremotepaths
      description: Get remote storage existing paths for the asset
      operationId: captionAsset.getRemotePaths
      x-api-path-slug: servicecaption-captionassetactiongetremotepaths-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - GetRemotePaths
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