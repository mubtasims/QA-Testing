# QA-Testing

# QA Purpose:

Our purpose was to prevent mistakes and defects in both developing and production ready codes in order to prevent and avoid post production bugs and errors.


# Tools we used:
Unittest

PyTest

Postman

Jenkins

We started with Waterfall methodology but switched to Agile methodology.

# Strategies: 
For test routing: writing of pytest cases and later use of Postman

For functions: Postman with database testing

For AWS: We created 

For APIs: Postman to make sure it can connect to the APIs that need testing


The testing procedures were to test the routes, APIs, AWS, functions, databases (via Postman)



# Why we tested them in that way?:
Why did we test routing? To ensure that each route returned an “OK” (200) message

Why did we test the functions? To ensure that the system is ready for functional use, this means that all the functions are carrying out their task.

Why did we test the AWS part? Because our database lies in the AWS (DynamoDB) and without testing our database, we wouldn’t be able to store any of our user’s or company’s information in the website.

Why did we test APIs? We test the API to ensure that there isn’t any error that would disrupt deployment or services offered by the app.

Postman and Pytest were the most user-friendly testing programs/libraries that seemed fit for us in QA to use. It helped us to learn proper testing techniques.


# Unittest: (Scrapped in favor of pytest)

Why was it scrapped? It was unmanageable to use, and involved the creation of new classes, whereas Pytest involved creating methods that can easily be inserted into an existing python file.


# PyTest: Used to initially test the routes for each service (Events, Users, etc.)


Why did we use Pytest: The idioms that pytest first introduced brought a change in the Python community because they made it possible for test suites to be written in a very compact style, or at least far more compact than was ever possible before. Pytest basically introduced the concept that Python tests should be plain Python functions instead of forcing developers to include their tests inside large test classes.


# Postman: Used to test routes and database functionality

Why did we use Postman: Postman is a great tool when trying to dissect RESTful APIs made by others or test ones you have made yourself. It offers a sleek user interface with which to make HTML requests, without the hassle of writing a bunch of code just to test an API's functionality.

# Jenkins: Creating Pipelines 

To automate the testing of code whenever it's pushed. We connected the pipeline to each individual github repository. 
