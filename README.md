# Invalid-CORS-request

![image](https://user-images.githubusercontent.com/2658837/97627771-111b2c80-19e9-11eb-8dad-b17ca7b4deb0.png)

This kind of error description can be seen in Network headers in browser inspect.


Make sure your cross origin in the server code is not specific to port, Instead change it to @CrossOrigin(Origins="*") in the controller class to accept requests from every port. 
