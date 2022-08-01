# AssetStoreApplication
Implementation of Rest apis like PUT, POST, GET, DELETE. 


After importing the project open POSTMAN-
Run this url in postman for signin > http://localhost:8080/api/auth/signin
Run this url in postman for signup > http://localhost:8080/api/auth/signup

Run http://localhost:8080/api/asset for get
Run http://localhost:8080/api/assets for post

Run http://localhost:8080/api/asset/id for get by id. (ID is 1001, 1002 for this case which is present in database)
.......


Reference for HTTP status codes...
Once we will get our data sucessfully we will get 200

When we are creating post, we are getting 202

If user is unauthorised we will get 401

If any user will try to create any post, we will get 403 
and so on.....
