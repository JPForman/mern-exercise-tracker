# _Exercise Tracker - MERN Stack_

![routes](./public/trackerScreen.png)

#### _This is an application for tracking users and their exercises._

#### By _**Josh Forman**_

## Description

_This application allows the users full CRUD of exercises associated with a chosen user. This was built as a MERN Stack application._

_https://github.com/JPForman/mern-exercise-tracker.git_

## Setup/Installation Requirements

* _$ git clone https://github.com/JPForman/mern-exercise-tracker.git_

* _$ cd mern-exercise-tracker_

* _$ npm install_

* _$ npm run start (browser will open to localhost:3000)_  

* _change to directory mern-exercise-tracker/backend_  

* _$ nodemond server (server will open to localhost:5000)_  

## Routes

'/' -- View all logged exercises  
'/create' -- Create exercises  
'/user' -- Create User  
'/edit/:id' -- Edit Selected Exercise  
  


## Endpoints
### Exercises  
get http://localhost:5000/exercises  -- returns all exercise events  
get http://localhost:5000/exercises/:id -- return exercise by id  
delete http://localhost:5000/exercises/:id -- delete exercise by id  
post http://localhost:5000/exercises/add  -- add an exercise event  
post http://localhost:5000/exercises/update/:id  -- update an exercise event  

### Users  
get http://localhost:5000/users  -- returns all users  
get http://localhost:5000/users/add  -- add a user  


## Specs

* _The application allows the user to view, update, and create exercise events._
* _The application allows the user to create users._

## Known Bugs

_Readme Endpoints need updating_  
_Needs Styling_


## Support and contact details

_Any questions, comments or contributions please contact Josh Forman (cyborgforman@gmail.com)_

## Technologies Used

_React, MongoDB, Express, Node.js, Bootstrap, Axios_

## Resources  
 Special thanks to the tutorial at https://www.youtube.com/watch?v=7CqJlxBYj-M&t=618s

### License

*The MIT License


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.*

Copyright (c) 2020 **_Josh Forman_**