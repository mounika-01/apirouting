Given `MyController.java` and `MyService.java` files, implement the respective classes in the files `MyController.java` and `MyService.java` for handling two APIs that return different strings.

Refer to the below table for paths and responses,

| Method | Path   | Description                                        |
| ------ | ------ | -------------------------------------------------- |
| GET    | /      | Will send the text <i>`Home Page`</i> as response  |
| GET    | /about | Will send the text <i>`About Page`</i> as response |


TEST CASE RESULTS
The Spring Boot application should consist of a controller class.
The GET request with path '/' should return a success status.
An HTTP GET request with path '/' should return the string 'Home Page' as a response.
The GET request with path '/about' should return a success status.
An HTTP GET request with path '/about' should return the string 'About Page' as a response.
