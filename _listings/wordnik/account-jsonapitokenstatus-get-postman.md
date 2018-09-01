{
  "info": {
    "name": "Wordnik Returns usage statistics for the API account.",
    "_postman_id": "9ececa89-f46e-4e60-9ffb-2b60ebba6cc7",
    "description": "Returns usage statistics for the api account..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "df2b98df-ff42-4ff4-a120-22d91e689942",
          "name": "getApiTokenStatus",
          "request": {
            "url": "http://api.wordnik.com/v4/account.json/apiTokenStatus",
            "method": "GET",
            "header": [
              {
                "key": "api_key",
                "value": "{}",
                "description": "Wordnik authentication token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns usage statistics for the api account.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbad8e21-25ba-4675-9548-03443df38571"
            }
          ]
        }
      ]
    }
  ]
}