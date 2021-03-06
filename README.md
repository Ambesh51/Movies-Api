# Movies-Api
#  👨🏼‍💻FUNCTIONS THAT CAN BE PERFORMED USING THIS API 
- ### REGISTER
- ### LOGIN
- ### ADD/CREATE A MOVIE
- ### RETRIEVE ALL MOVIES FROM DATABASE
  

##  🤷🏼‍♂️ WHERE TO USE WHICH API ?

##  👨🏻‍🏫 SIMPLE 

1. ### FOR SIGNUP:
    - #### API URL: 
        - #### LOCAL: [http://localhost:5000/api/users/signup](http://localhost:5000/api/users/signup)
  
    - #### METHOD: POST
  
    - #### REQUEST:
        ```
        content-type: application/json

        {  
          "name": "Himanshu Bhardwaj",
          "phoneNumber":"982964XXXX",
          "email": "bhardwajhimanshu2515@gmail.com",
          "password": "1234566788" 
        }
        ```
    - #### RESPONSE:
        ![Signup API Response](/imgs/signup.PNG)

2. ### FOR LOGIN:
    - #### API URL: 
        - #### LOCAL: [http://localhost:5000/api/users/login](http://localhost:5000/api/users/login)
  
    - #### METHOD: POST
  
    - #### REQUEST:
        ```
        content-type: application/json

        { 
            "email": "bhardwajhimanshu2515@gmail.com",
            "password": "1234566788"  
        }
        ```
    - #### RESPONSE:
        ![Login API Response](/imgs/login.PNG)

3. ### FOR ADDING NEW MOVIE TO DATABASE:
    - #### API URL: 
        - #### LOCAL: [http://localhost:5000/api/movies/create](http://localhost:5000/api/movies/create)
  
    - #### METHOD: POST
  
    - #### REQUEST:
        ```
        Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VySWQiOiI1ZjNmZWZhZDNiZWZiNzNjYzRjY2VhNDEiLCJlbWFpbCI6ImJoYXJkd2FqaGltYW5zaHUyNTE1QGdtYWlsLmNvbSIsImlhdCI6MTU5ODAyNTg0NCwiZXhwIjoxNTk4MDI5NDQ0fQ.dfKdh-qm56zd_XTpr7VScWl0aWlRxtoAZuOO7O9A_M4
        content-type: application/json

        { 
          "userId":"5f3fefad3befb73cc4ccea41",
          "name":"Harry Potter and the Order of the Phoenix",
          "img":"https://bit.ly/2IcnSwz",
          "summary":"Harry Potter and Dumbledore's warning about the return of Lord Voldemort is not heeded by the wizard authorities who, in turn, look to undermine Dumbledore's authority at Hogwarts and discredit Harry."
        }
        ```
    - #### RESPONSE:
        ![ADD MOVIE API Response](/imgs/movieAdd.PNG)


4. ### FOR GETTING ALL MOVIES FROM DATABASE:
    - #### API URL: 
        - #### LOCAL: [http://localhost:5000/api/movies/allMovies](http://localhost:5000/api/movies/allMovies)
  
    - #### METHOD: POST
  
    - #### REQUEST:
        ```
        Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VySWQiOiI1ZjNmZWZhZDNiZWZiNzNjYzRjY2VhNDEiLCJlbWFpbCI6ImJoYXJkd2FqaGltYW5zaHUyNTE1QGdtYWlsLmNvbSIsImlhdCI6MTU5ODAyNTg0NCwiZXhwIjoxNTk4MDI5NDQ0fQ.dfKdh-qm56zd_XTpr7VScWl0aWlRxtoAZuOO7O9A_M4

        ```
    - #### RESPONSE:
        ![GET ALL MOVIES API Response](/imgs/allMovies.PNG)