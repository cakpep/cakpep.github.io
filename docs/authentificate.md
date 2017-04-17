### [&laquo; Home](README.md)

[Authentication for Bukalapak API](#authentication-for-bukalapak-api)
- [Authenticate](#authenticate)
    - [URL](#url)
    - [Parameters](#parameters)
    - [Example Request](#example-request)
    - [Example Response](#example-response)

## Authentication for Bukalapak API

### Authenticate
Return token to enable access for `required authentication's resources`
User Bukalapak `user` and `password` for server authentication.

+ Use `POST` http method.

##### URL
+ [https://api.bukalapak.com/v1/authenticate.json]()

##### Parameters
None

##### POST request data
None

##### Example Request
````sh
curl -u billy:Highs3creT https://api.bukalapak.com/v1/authenticate.json -X POST

````

##### Example Response
Success response:
````json
{
  "status":"OK",
  "user_id": "157324",
  "token": "U8Ch2LigkVhdI3XwYRA",
  "message":null
}
````

Failed response
````json
{
  "status":"ERROR",
  "user_id":"null",
  "message":"Invalid password"
}
````
## Commands

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md] [PlDb] |
| Github | [plugins/github/README.md] [PlGh] |
| Google Drive | [plugins/googledrive/README.md] [PlGd] |
| OneDrive | [plugins/onedrive/README.md] [PlOd] |
| Medium | [plugins/medium/README.md] [PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md] [PlGa] |