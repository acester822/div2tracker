## Usage/Examples

```javascript

 - POST: http://localhost:105/api/query-data

{
  "status": true,
  "message": [
    {
      "endpoint": "/api/query-data",
      "platforms": [
        "xbox",
        "psn",
        "uplay"
      ],
      "method": "POST",
      "required": [
        {
          "api_key": "JaRyk3ys4fVZrwHzMAba",
          "username": "Adrenaline23",
          "platform": "uplay"
        }
      ]
    },
    {
      "endpoint": "/api/help",
      "method": "GET"
    },
    {
      "endpoint": "/api/",
      "method": "GET"
    }
  ]
}
