
# VKApiMethods

A description of this package.
=======
## Package VKApiMethods designed to get the absolute URL for a request to VKApi

***Usage***
```
let token  = "Your VKApi authorization token" //String
let userId = "ID of the user for whom the request is being made" //String

let url = VKApiMethods.getUserInfo( token: token, userId: userId ).absoluteURL
```
***.absoluteURL*** _Optional type returns URL or nil_
