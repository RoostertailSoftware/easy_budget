# General Thoughts and Ideas

## Why?
Well, basically, I want to learn Rust.  

### In that, I was thinking of using:
1. Rust to be the API and serve up the UI.
2. I like Angular so, I am going to stick to that for the UI
3. I like mongo and so, I am going to use Mongo for the db.

That is the basics in 3 lines.

## What I am looking for

* I don't like other budgets -- they just don't do what I thought they should
* They tend to not allow the flexability I want

## What I want for the overall design

### Obvious things are 
* easy of use
* easy on the eyes
* some big buttons and not a lot of hidden things
* Not having to go down rabbit holes to see the data
* graphs to grasp harder to get ideas and see categories
* print some reports as needed

## Model
* I am going to start with some SysML and UML [(Star UML v4.x)](https://StarUML.io) to build the overall structure of how things will work.
    * I like to start with Use Cases -- which leads to ...
    * Requirements -- which leads to ...
    * Class Diagrams, Sequence Diagrams, Package Diagrams ... lots and lots of diagrams
    * bwahahahaha 
* I will use [Balsamiq wireframes](https://balsamiq.com/) to design the UI according to the Requirements

## Test
* Angular testing is rather a void for me. I hope to rectify that with this project
    * Use as many unit tests built into the system to test local functionality
    * Use a larger test app to test system system/integration level tests
* I plan to use [Postman](https://postman.com) to build unit and system tests for the API
    * First I will stub out the db so the api can be tested without having any db connection or db running   
* I Hope to learn how Rust tests can be completed and automated

Oh Yes, let me say automate testing as much as possible.  Writing the results to a log system.
