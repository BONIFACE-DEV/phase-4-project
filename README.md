# TheOrchid

**TheOrchid** is an online flowers museum. The Orchid is a museum dedicated to the preservation, education, and appreciation of flowers.
It is a place where you can learn about the history of flowers and their beauty from thousands of years past to present. We tell stories about how flowers have changed over time and how they influence our lives today. It is a space to learn more on which flower is suitable for your home botanical garden.



### Setup
    Fork and clone this repository  
    bundle install to install backend dependencies
    npm install --prefix client  to install front end dependencies
    Run __"npm install react-router-dom@6.4.3"__ to install a compatible version of react-router-dom.
    Run rails db:migrate to do the migrations
    Run rails db:seed to do the seedings
    rails s   to start the rails server
    npm start --prefix client to start front end application


### Technologies used 
1. React JS - Front-end
2. CSS - Front-end styling
3. Ruby on rails for the server


### ERD diagram
![ERD DIAGRAM](/ERD.png)

### Endpoints

GET /flowers
GET /flowers/id

POST /reviews

DELETE/review/id
 
### AUTHOR
[Boniface korir] https://github.com/BONIFACE-DEV

### License info
Copyright (c) 2022 korir boniface Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.