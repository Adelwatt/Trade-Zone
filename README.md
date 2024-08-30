# Trade-Zone

Trade-Zone is a system that enables a trading infrastructure between sellers and buyers. The system is complex
From a collection of stores. A store contains identifying details and product inventory, where each product has different characteristics. Users
visit the market for buying, selling, and management purposes. System users play roles
Different in the system: sellers, buyers and managers.

## Installation And Running

To install and run the project, please follow these steps:

1. Clone the repository: https://github.com/Adelwatt/Trade-Zone.git
2. Install the Spting Boot packages.
3. Run the project by running the SpringbootHtmlApplication class in Intellij and opening http://localhost:8080/ in WEB.

## Understanding Load Files

The system Loads data from the files :

 init_1.json

 init_2.json

 init_3.json

 Each file above contains specific data, for Example:

  after loading init_1 file, the system will include the registered users u1,u2 and u3 , store s1 that owned by u1,u2 and u3.

## Testing the system

The project can be tested by running test package that contains two kinds of testing:

1. Unit tests : Unit tests are a type of software testing where individual units or components of a system are tested in isolation to ensure their functionality. They help identify bugs, validate code changes, and enhance the overall quality and reliability of software.

2. Acceptance tests : 
Acceptance tests, also known as user acceptance tests or UAT, are conducted to determine whether a system meets the requirements and expectations of its end users or stakeholders. These tests are typically performed towards the end of the development cycle and focus on evaluating the system's overall usability, functionality, and compliance with the desired specifications. Acceptance tests aim to ensure that the software is ready for deployment and can be effectively used by its intended audience.

3. DataBase tests: testing the system with a connection to the data base, it focuses on each senario that could happen in the system and checks the affectivness of the data base and how the hole system interacts with it. 

