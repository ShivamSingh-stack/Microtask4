# Documentation
# First MicroTask
#### API performs simple tasks of quering.

### Repo Link
    https://github.com/ShivamSingh-stack/microtask1

### Deta Link
    https://6mkk3y.deta.dev/api/get-all-products

### Clone the git repository
    git clone  https://github.com/ShivamSingh-stack/microtask1

### Navigation
    cd microtask1 

### Installation
    npm i

### Runserver
    npm start


### Endpoints
 Make a GET Request : To get details of all products.

    /api/get-all-products    




# Second MicroTask
The second microtask performs three actions:
Error handling (to handles server status),
Visitor counter(count the visitors),
and Authentication

#### Repo Link
    https://github.com/ShivamSingh-stack/microservicetask2
    
#### Clone the git repository
    git clone https://github.com/ShivamSingh-stack/microservicetask2

#### Navigation
    cd microservicetask2
    cd AuthAPI or cd ErrorHandler cd ViewCounter

#### Installation
    npm i

#### Runserver
    npm start


### ErrorHandling

GET Request:

    /api/error

### Authentication
#### Handles operations such as signup and login.
#### Sign-up(Returns token)

POST Request:

    /api/create-user


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| body | email | Required|
| body | password | Required|
| body | name | Required|


#### Log In(Returns token)

POST Request:

    /api/log-in


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| body | email | Required|
| body | password | Required|

### Visitor counter

#### It counts the number of visits in a particular endpoint.

GET Request:

    /api/get-views

# Third MicroTask
####  To create a location microservice that may use the user's latitude and longitude and provide the address, the html geolocation service is used. Latitude and longitude are also obtained using an address.

#### Repo Link
    https://github.com/ShivamSingh-stack/microtask3

#### Deta Link
    https://qm4erk.deta.dev/get-address


### API Refernce

#### Clone the git repository
    git clone  https://github.com/ShivamSingh-stack/microtask3

#### Navigation
    cd microtask3  

#### Installation
    npm i
    npm start


#### Endpoints
GET Request:

    /get-address
 
## Author
- [@ShivamSingh-stack](https://github.com/ShivamSingh-stack)
