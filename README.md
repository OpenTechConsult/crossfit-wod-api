# CROSSFIT WOD API 

We'll be building a REST API for Crossfit Training Application. Crossfit is a fitness method and competitive sport that combines high-intensity workout with elements from several sports.

In our application, we'd like to create, read, update, and delete WODs. This will help users (gym owners) come up with workout plans and maintain their own workout inside a single application. On top of that, they also can add some important training tips for each workout.

We will design and implement an API for that application.

## Architecture

We'll be using Express.js for building our API. We'll stick to **3 Layer Architecture**

       REQUEST                  RESPONSE
         |                        |
         |                        |
    -----------------------------------
    |             Router              |
    -----------------------------------
           |                      |
    -----------------------------------
    |             Controller          |
    -----------------------------------
          |                     |
    -----------------------------------
    |             Service             |
    -----------------------------------
          |                     |
    -----------------------------------
    |             Database            |
    -----------------------------------