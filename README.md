# Chas Malmö Utvecklingsbyrå

## What this project is all about
`This project is based upon a request by a fictional company (WeatherTech Solutions AB) that requires us to develop a plattform that helps the companys clients to collect, store and analyze weather data in real time. We are required to develop a server component and a client application that is built in both C and C++, with the main focus on performance, safety and scaleability.`

## Project Goals:
`To develop a robust client-server-solution for weather data that also:`
* `Provides a centralized server that can handle multiple co-existing client requests.`
* `The server can connect to multiple external weather services simultaneously.`
* `Offers clients in both C and C++ which can collect, present and cache weather data.`
* `The documentation is made in a way that enables that the project can be handed over to the customer and they can provide further development internally in the future.`
* `The project should have an architecture that from the start is considering that the client made in C, later can be ported to an ESP32-device with a touch-screen.`


## Key Features:
### The server part:
* `Implemented in C.`
* `TCP-server that can handle multiple parallell client connections.`
* `Connects to several different weather API's for redundance.`
* `Supports HTTP GET/POST-requests. (REST-API's)`
* `Both questions and answers in JSON-format with weather data.`
* `Caches the response from external weather services to minimize API costs.`
* `Makes it simple to add future end points and external weather services.`

### The client part:
* `Two versions, one written in C and the other one written in C++.`
* `Functionality:`
    * `Connection to the server and requesting weather data.`
    * `Presenting data in the terminal with a clear structure.`
    * `Implementing caching in a local file system.`
* `Demands on portability:`
`The client in C have to be able to be ported to an ESP32 in a later stage. This means that design choices has to be taken with regards to resource limitations and compability.`

### Techincal Demands:
* `Clear and obvious documentation of the systems structure and usage.`
* `Basic input validation and error handling.`
* `The development will follow the SCRUM-model with sprints and regular reconciliations.`

## Deliverables:
* `A functional server application in C.`
* `A functional client application in C.`
* `A functional client application in C++.`
* `Documenation:`
    * `The systems architecture.`
    * `User instructions.`
    * `Instructions regarding further development.`
* `A simple test plan that verifies basic functionalities.`

## Time Frame:
* `Project start: Week 43`
* `Iterative development according to the SCRUM model (Customer is P.O).`
* `First functional prototype: week 44.`
* `End delivery including documenation: week 52 (2025-12-29 and 2025-12-30).`

## Primary Structure:
* `Core`
* `Client`
* `Server`
* `Shared` 

## Meet the 'CHAS Malmö Utvecklingsbyrå's members:
`All members sorted in alphabetical order.`
- [Emilio Ganibegovic](https://github.com/AlCapone1234) / [Emilios other account](https://github.com/samstalhandske/chas_malmo_weather/commits?author=pooppoop)
- [Henrik Westerlund](https://github.com/Henrik-Westerlund)
- [Isa Shipshani](https://github.com/isashiphotmailcom)
- [Lukas Städe](https://github.com/HoffaQt)
- [Pontus Rosenquist](https://github.com/pontusrosenquistgmailcom)
- [Pär Lundh](https://github.com/lundhpargmailcom)
- [Sam Stålhandske](https://github.com/samstalhandske)


## Donations
`Money for coffee is much appreciated. <3`
