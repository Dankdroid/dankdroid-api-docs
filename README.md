# Dankdroid API
A full documentation of the API is available at https://dankdroid.github.io/dankdroid-api-docs/

## How do I authenticate?
We use the `API-Key` header for authorization.
Example with cURL:
```curl -H "API-Key: your-long-api-key-here" -X GET https://api.dankdroid.xyz/{version}/{request_uri}```
