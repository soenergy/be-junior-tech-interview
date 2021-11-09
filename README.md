# be-junior-tech-interview 
This exercise is to see how you go about executing a relatively simple set of use cases 
in which you need to create a Ktor based Kotlin microservice that utilise an external API 
in order to expose a simple RESTful JSON API.    

## Setup
- clone this git repository as this will form the base of your service
    - **you do not need to fork this repository**
    - **PR's will not be accepted on this repository**

## Exercise Detail
- you will need to create the following fully functional RESTful endpoints:
    - get a beer for a given ID
    - get ALL beers (no pagination is explicitly required)
    - search all beers for a given name
    
- The external API used as a source of data: 
    - [The Punk API](https://punkapi.com/documentation/v2) (requires no authentication)

- In order to accomplish this task you must
    - ingest data from the data-source listed

- you are free to add any libraries you like to compliment the current project setup in order to complete the task at hand

- the JSON definition of a beer that your service should be using for the various endpoints you are exposing 
  [can be found within the resources](https://github.com/soenergy/be-junior-tech-interview/blob/main/resources/beer-example/beer-example.json)  

## Notes

- The intention is for this test to take you no more than around ±3 hours or so depending on 
  your familiarity with the Kotlin language and/or the tool
  
- Please structure your commits!
    - remember that the idea here is for us to be able to see how you go about tackling the problem, and a 
      commit that does one action is easier to follow than a commit that contains several actions. 

- Your resulting project is going to be judged largely on the following merits:
    - the design of the external facing API your service is exposing 
    - the design of your internal system architecture  
        - clean architectural principles
        - how you go about modeling the data that you consume vs the data you expose and mapping  
    - testing!
        - how testable your service is 
        - where you focus your testing efforts
        
- your service implementation will form the basis of our final stage interview

- if you feel more comfortable with another programming language it's not ideal, but it will be accepted too

- should you have any questions, please don't hesitate to get in touch with us

## Delivering your finished project
- zip up your entire local git project
- send us the zipped-up git project
