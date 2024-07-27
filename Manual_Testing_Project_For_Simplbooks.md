Testing Project for Simplbooks

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: Simplbooks

Tools used: Jira, Zephyr Squad.


Functional specifications:
The below stories were created in Jira and describe the functional specifications of the Partners and Wages Section, for which the final project is performed upon.

![image](https://github.com/user-attachments/assets/b62cf6e7-0e82-4cde-8c51-8cdc3ea23406)

Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/dfe806eb-a228-41dc-b638-587b2ecabf37)

Testing process
The test process was performed based on the standard test process as described below.

1.1 Test planning
The Test Plan is designed to describe all details of testing for Partners and Wages section of the SimplBooks application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)

1.1.1. Roles asigned to the project and persons allocated
Project manager - Denisa Cetatean
Product owner - Andrei Rus
Software developer - Ana Maria
QA Engineer - Ilinca Ilie
Tester - Camelia Cetatean

1.1.2 Entry criteria defined
Availability of Functional Specifications: detailed functional specifications or required documentation are available
Availability of Test Resources: sufficient testing resources (personnel, time, and budget) are allocated
Test Plan Approval from relevant stakeholders, including project managers, business analysts & quality assurance leads
Smoke test passed

1.1.3 Exit criteria defined
Test coverage - 90% of key user scenarios are tested 
Defect Closure rate - All critical functionalities and high priority/severity cases have Closed status
Risk mitigation - All project risks and product risks are identified and resolved
Documentation complete - All test cases are up-to-date and the Test Summary Report  was sent to the stakeholders
User acceptance - Regression Testing and Acceptance testing  is finalized and management approval is obtained

1.1.4 Test scope
Tests in scope:
Negative and Positive Testing on both Chrome & Mozilla and on the following devices: Layout desktop & iphone 14 pro max
Non functional testing: volume testing and usability testing

Tests not in scope:
Blackblox testing, Whitebox Testing, Portability testing

1.1.5 Risks detected
Project risks:
Resource Constraints: Deadline is not met or budget not sufficient 
Change Management: resistance to change from stakeholders
User Data (banking related data, invoices, purchases etc) might be impacted with update tests

Product risks:
Data Security Breaches: Risk of unauthorized access, data breaches, or security vulnerabilities that could compromise sensitive financial or personal information stored in the app
Compatibility Issues: different operating systems, browsers, or devices affecting the app's usability and accessibility

1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

1.2 Test Monitoring and Control
![image](https://github.com/user-attachments/assets/f2155237-f797-4e97-b65e-eafbdab15db1)


1.3 Test Analysis
The testing process will be executed based on the application requirements. 
The following test conditions were found:

![image](https://github.com/user-attachments/assets/472cb95d-6c38-4607-85ae-55dd3139c2af)
![image](https://github.com/user-attachments/assets/3c22158e-40b3-4133-86bd-7a8c1a01d57f)
![image](https://github.com/user-attachments/assets/2ee6ecd2-e2e7-47a9-8ca9-3347deea2499)

1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here https://itfclasses.atlassian.net/projects/CAM?selectedItem=com.thed.zephyr.je__cycle-summary

1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:
all the test data is available and reviewed (test data= email & password credentials, different types of currencies, different types of credit cards)
All permissions and GDPR approvals for personal data received 
Execution of smoke testing is the top priority
Non-functional performance testing should be completed for purposes of reliability testing and volume testing
Non-functional tests should also include usability and security testing
Starting with the Partners Section, we should check whether users are able to add or search for entries of clients and suppliers in the corresponding subsection, to import or export lists and to add invoices for those clients. 
Moving on to the Delivery addresses Tab, users should be able to add and search for entries of addresses for each of their clients 
Furthermore, in the Wages section and then Employees sub section, users should be able to add and/or search for entries of employees, import or export lists with them
Whereas, in the Salaries subsection, users can add salaries for either one individual employee or for multiple ones

1.6. Test Execution
Test cases are executed on the created test Cycle summary: Simplbooks - Verifying Wages Section, Verifying Partners Section and Login Verification.

The following is a summary of the bugs that have been found:
GUI Design error in Clients and Suppliers Page as seen through an Iphone 14 Pro Max (high severity, high priority)
Client page not corresponding to documentation (high priority, medium severity)
Error at login with empty fields (high severity, high priority)
Infinite number of characthers accepted in input fields (medium priority, medium severity)
Error not displayed for negative inputs in Employees First Name Field in Main Details section (high priority, medium severity)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
The traceability matrix was generated and can be found here: (inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)

Test execution chart was generated and can be found below.
![image](https://github.com/user-attachments/assets/1065a671-e0b4-467a-9d66-881e8ef1f20a)

The final report shows  a number of 11 tests written and executed, out of which 3 failed. 
A number of 5 total bugs were found, from which the priority is medium.
