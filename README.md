

## Table of contents 👀
* [General info](#general-info)
* [Technologies](#technologies)
* [Blog](#blog)
* [Setup](#setup)


### General info
TAPI or T-API is a Tea REST API made to show some love for the beverage. 

#### The TEA Object 🍵
| Properties | Description | Type  |
|:----------- |:---------------|:--------|
|name| the tea name | String| 
|image| an image url | String |
|description| the description | String | 
|keywords|words associated with the tea  |String | 
|origin|country where the tea is first made | String| 
|brew_time|time to brew in minutes | Number | 
|temperature|best temperature in Celsius to drink | Number | 
|comments|any comments posted about the tea |Array of String | 

#### Routes ⚡
| Routes | HTTP Methods| Description
|:------- |:---------------|:--------------
| /tea      | GET                  | Displays all tea
| /tea      | POST               | Creates a new tea
| /tea      | DELETE            | Deletes all tea
|/tea/:name| GET     | Displays a specific tea, given its name
|/tea/:name| POST  | Adds a comment to a specific tea, given its name
|/tea/:name| DELETE | Deletes a specific tea, given its name
	
### Technologies
Project is created with:
* Node version: 12.14.1
* Express version: 4.17.1
* Mongoose version: 5.9.25 
* Multer version: 1.4.2 
* MongoDB Atlas




### Setup
To run this project locally, clone repo and execute in command prompt:

```
$ cd tapi
$ npm install
$ npm start or node server.js
```


