# Online Marketplace (Beta)
## Description
This application serves as a online web-based market platform that allows anyone to buy and sell products from various categories. The idea of this is inspired from Amazon. This whole app will be designed as a microservice rather than a monolith system

This app was developed as base foundation for all my projects. I have always been interested in how marketplaces work, as well as how their internals run and work. This app will allow me to exhibit my system design skills as well as my knowledge of Agile Methdologies and working in a Scrum environment. I will follow the Agile Software Development Life Cycle which which includes:
* FDD - Freature Driven Development
* XP - Extereme Programming
* DSDM - Dynamic Systems Development Method
* Scrum/Kanban Log (have to see which is better)

## Key Features
* Create an account
    * Users will be able to create an account with information such as username, password, details, etc.
    * All this information will be stored in a database. In order for other microservices to get access to a person's info, they must pass in their unique ID into a REST Api which will return the desired info (have to look into this)
 * Browse for items
     * Allows any user to search and browse for any item without needing an account to log into 
     * Brows for items will be its own microservice
* Recommended/History Purchases
    * Going to be its own microservie. Recommended and showing items based on what you viewed in the past or purchased in the past
* Payment
    * No clue if I am going to add this since I just won't use it. Most likely will be bottom of TO-DO list
* Place an order
    * Ofc gonna be its own microservice. Allows user to place an order for the item if it is in stock and they have sufficient funds
* Refund an item
    * If item is refundable (a month from purchase date), refund it. This will be its own microservice
* Item view
    * The concept of viewing an item will most likely be based on Object Oriented principles and design. This will not be its own microservice 
