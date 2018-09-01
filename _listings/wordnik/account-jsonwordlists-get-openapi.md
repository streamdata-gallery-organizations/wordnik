---
swagger: "2.0"
x-collection-name: Wordnik
x-complete: 0
info:
  title: Wordnik Fetches WordList objects for the logged-in user.
  description: Fetches wordlist objects for the logged-in user..
  version: "4.0"
host: api.wordnik.com
basePath: /v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account.json/apiTokenStatus:
    get:
      summary: Returns usage statistics for the API account.
      description: Returns usage statistics for the api account..
      operationId: getApiTokenStatus
      x-api-path-slug: account-jsonapitokenstatus-get
      parameters:
      - in: header
        name: api_key
        description: Wordnik authentication token
      responses:
        200:
          description: OK
      tags:
      - Account
      - ApiTokenStatus
  /account.json/authenticate/{username}:
    get:
      summary: Authenticates a User
      description: Authenticates a user.
      operationId: authenticate
      x-api-path-slug: account-jsonauthenticateusername-get
      parameters:
      - in: query
        name: password
        description: The users password
      - in: path
        name: username
        description: A confirmed Wordnik username
      responses:
        200:
          description: OK
      tags:
      - Account
      - Authenticate
      - Username
    post:
      summary: Authenticates a user
      description: Authenticates a user.
      operationId: authenticatePost
      x-api-path-slug: account-jsonauthenticateusername-post
      parameters:
      - in: body
        name: body
        description: The users password
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: username
        description: A confirmed Wordnik username
      responses:
        200:
          description: OK
      tags:
      - Account
      - Authenticate
      - Username
  /account.json/user:
    get:
      summary: Returns the logged-in User
      description: Requires a valid auth_token to be set.
      operationId: getLoggedInUser
      x-api-path-slug: account-jsonuser-get
      parameters:
      - in: header
        name: auth_token
        description: The auth token of the logged-in user, obtained by calling /account
      responses:
        200:
          description: OK
      tags:
      - Account
      - User
  /account.json/wordLists:
    get:
      summary: Fetches WordList objects for the logged-in user.
      description: Fetches wordlist objects for the logged-in user..
      operationId: getWordListsForLoggedInUser
      x-api-path-slug: account-jsonwordlists-get
      parameters:
      - in: header
        name: auth_token
        description: auth_token of logged-in user
      - in: query
        name: limit
        description: Maximum number of results to return
      - in: query
        name: skip
        description: Results to skip
      responses:
        200:
          description: OK
      tags:
      - Account
      - Words
      - Lists
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