# SDP-3 Game

- First go to Spring Initializer and download the required stuff and dependendcies
- Change the pom.xml file with the other one
- Inside the folder use `mvn clean install`
- Then after it run `mvn springboot:run`
- In application.properties paste the required information
- Create the necessary folders in main/java/com/name/ecom_app  - controller, dto, entity, repository, service
    - Under entity create a new file called `User.java` and add the relevant code there
        - Add the User class and the getters and setters for the data using *Source Action* -> *Generate Getters and Setters* -> *Select All and OK*
    - Under repository create a new file called `UserRepository.java` and import the required packages and stuff
    - Under controller create a new file called `UesrController.java` and import the required packages
    - Under service create a new file called `UserService.java` and add the necessary code
- Install the extension ThunderClient
    - Click on new request and in the url we can go the `UserController.java` and find the required url in there, like /user/addUser etc.
    - Use POST `user/addUser` to add user and put the data in the JSON format in the option
    - To retrieve the users use GET `user/getAll` and we will get all the data in it
- GO to render and deploy there choose the repo and deploy