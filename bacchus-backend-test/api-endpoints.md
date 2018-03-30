# Title

API Endpoints

## About

- Creation: 2018-03-30
- Created by: Marc Friedrich
- Maintained by: Marc Friedrich

___

# Index

# Content

## API Protocol

### API Endpoint Structure 

To be decided.

Propositions:

### API Response Structure

The backend response will always be sent using JSON. The top hierarchy level will also always contain the request parameters. The response follows the following format:

```json
{
  "response_status": "(1)", 
  "param1": "(2)",
  "paramN": "valueN",
  "response_message": [
    "key1": "val1"
  ]
}
```

## /api

### /api/get/city_bars

https://beercules-test-api.herokuapp.com/api/get/city_bars?lat=48.2109657&lon=9.0246603

Requires the following GET parameters:

- lat: Latitude
- lon: Longitude

Example HTTP request:

```
https://beercules-test-api.herokuapp.com/api/get/city_bars?lat=48.2109657&lon=9.0246603
```

Example JSON response
