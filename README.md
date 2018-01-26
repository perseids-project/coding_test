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

The application should fulfill the following __User Story__:

As a user running the application I want to see the description of the collection with the id __org.perseids/Topic/TreebankCiteIdentifier/urn:cts:latinLit:phi0690.phi003.perseus-lat2__ and the date it was created. I would also like to see the list of member items of this collection including their ids, locations and the date they were added to the collection.

It is your choice whether or not to include unit tests in your code, but if you don't you should at a minimum provide a a description of what you think *should* be included in unit tests.

You can use whatever programming language you prefer for the client application. 

Provide the final code in a zip file. The zip file should include:

1. a README.MD which provides all the necesary information on how to compile and run the application.
2. all code
3. a markdown file named ANSWERS.md which includes answers to the following questions:
   1. How long did you spend on the task? 
   2. What would you do differently if this was going to serve as the basis for an application that was really going to be a deployed part of the Perseids infrastructure?
   3. What questions do you have about the Collections Service API or the data it serves?
   4. Explain your choice of programming language for the test.
   5. If you did not include tests in your code, what tests do you think you should write?
   
Option 2: Analyze interactions between Arethusa and Back-end services
=====================================================================

The purpose of this task is to analyze the interactions between the javascript application Arethusa and the back-end services which feed data to it.

Access read-only views of two different documents in Arethusa at the following URLS:

Document 1: http://www.perseids.org/tools/arethusa/app/#/jmh?collid=lattb&objid=4361&doc=lattb.4361.1

Document 2: http://www.perseids.org/tools/arethusa/app/#/perseids?chunk=1&doc=27598

Provide the answers to the following questions (markdown preferred, but text, doc, or PDF also fine).

1. What are the base addresses of the services from which the Arethusa application is retrieving data?
2. What services are unique to retrieval of the above 2 documents?
3. When retreiving Document 2, which service requestdo you think results in the user warning about not being logged in?
4. When retrieving Document 1, which service request results in the text "Caes. Gall. 1.1" being present in the Arethusa interface?
5. For each Document, which request produces the data that appears in the Greek and Latin syntax diagrams (the words which appear in a hierarchical tree)
6. Bonus: for each Document, which request could be responsible for providing the data which drives the colors used for the words that appear in the Greek and Latin syntax diagrams?
7. After answering the above, what questions do you have about the Arethusa application design or the underlying services?






   






