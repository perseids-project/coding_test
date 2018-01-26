Perseids Coding Test
===================

Thank you for taking the time to do our technical test. There are two tasks to choose from:

1. Create a small client application for the Perseids Collections Service using the RDA Collections API
2. Analyze the interactions between the Arethusa Treebank Editor and the backend services which feed it

You can choose whichever of these tasks you prefer. Recommended time for either is under an hour. The API client application task may take longer depending upon skills and experience.


Option 1: Client Application Task
=================================

The Perseids Collection Service is available at [http://collections.perseids.org](http://collections.perseids.org).  This service implements the [RDA Collections API Specification](https://github.com/RDACollectionsWG/specification). The base page for the service at http://collections.perseids.org will give you a user-friendly view of the API documentation, including the ability to test out sample calls and see a curl command which shows you the exact syntax of a request.

Write a small client application, in the language of your choice, which interacts with the service to retrieve and display the properties of a single member item of a single collection.

The application should fulfill the following *User Story*:

As a user running the application I want to see the description of the collection with the id *org.perseids/Topic/TreebankCiteIdentifier/urn:cts:latinLit:phi0690.phi003.perseus-lat2* and the date it was created. I would also like to see the list of member items of this collection including their ids, locations and the date they were added to the collection.

It is your choice whether or not to include unit tests in your code, but if you don't you should at a minimum provide a a description of what you think *should* be included in unit tests.

You can use whatever programming language you prefer for the client application. 

Provide the final code in a zip file. The zip file should include:

1. a README.MD which provides all the necesary information on how to compile and run the application.
2. all code
3. a markdown file named ANSWERS.md which includes answers to the following questions:
   1. How long did you spend on the task? What would you add if you had more time?
   2. What questions do you have about the Collections Service API or the data it serves?
   3. Explain your choice of programming language for the test.
   4. If you did not include tests in your code, what tests do you think you should write?






