# E-CommerceBackEnd
The challenge is to build the back end for an e-commerce site.

## Table Of Content
* [General Info](#general-info)
* [User Story](#userstory)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)

## General Info
With use of sequelize, task was to build E-commerce Backend application using Express.js, sequelize, mysql. 


## Demonstration Video

https://watch.screencastify.com/v/eGffcNdHgH6yfHFjxsMI

## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Installation
To get started clone this repository using
<br>
```terminal
git clone https://github.com/Aecop/E-CommerceBackEnd.git
```

Then, 
```terminal
npm install
``` 

Open up MySQL shell and input
```terminal
source db/schema.sql
```
and
```terminal
use ecommerce_db
```
Then quit MySQL shell and input the following in your terminal
```terminal
npm run seed
```
to start running application simply input
```terminal
node server.js
```

## Usage
The application is used to GET data for each route(categories, products, or tags) as well as create, update, and delete data in those routes.

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br>
This repository is licensed under the MIT license.
