# msd-2022-spring-cs477-homework4
# Lab 4

1. Create a http server which is listen to 3000 port using Express
   1. npm init
   2. npm install express
2. Create the route of “/” which returns 'Hello World' using http GET. For example, sending a GET request http://localhost:3000, the result is "Hello World"
3. Create the route which returns a specific user. For example, sending a GET request http://localhost:3000/users/thao, the response is {first_name: 'thao', last_name: 'vu'}
4. Create the route which returns a specific user. For example, sending a GET request http://localhost:3000/users?name=thao, the response is {first_name: 'thao', last_name: 'vu'}
5. Create a middleware to make sure the length of the first name should not exeed 16
6. Save all data to a JSON file and load data when starting the app
7. Create the route which add a new user. For example, sending a POST request http://localhost:3000/users/add with the body is {first_name: 'thao', last_name: 'vu'}, the response will be {first_name: 'thao', last_name: 'vu'}.
8. Provide your own error handling




