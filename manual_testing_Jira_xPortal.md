# Testing Project for xPortal
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

**Application under test:** xPortal.com

Tools used: Jira, Zephyr Squad.

### 1.Functional specifications:
The below storys [here](https://github.com/Gabi-git-email/ITF-ST3_Gabi/blob/main/Jira_stories.doc) was created in Jira and describes the functional specifications of the Wallet module, for which the final project is performed upon.

You can find a example of one of the stories that were created in the picture below:

![image](https://github.com/Gabi-git-email/ITF-ST3_Gabi/assets/174444760/51fbc529-57d2-477f-8f9d-1c46d1dda648)


## Release

Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/e48ba544-d3a7-429f-bedb-bdb2441b6422)


## 2.Testing process
The test process was performed based on the standard test process as described below.

### 1.1 Test planning
The Test Plan is designed to describe all details of testing for all the modules from the xPortal app.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.
The test plan that was created for this project can be found [here](https://github.com/Gabi-git-email/ITF-ST3_Gabi/blob/main/Jira_TestPlan.doc)

#### 1.1.1. Roles asigned to the project and persons allocated
<table>
<tr><td>Project manager - Mihai George </td></tr> 
<tr><td>Product owner   - Alexandru Popescu </td></tr>
<tr><td>Software developer - Traian Popescu </td></tr>
<tr><td>QA Engineer - Salca Gabriel</td></tr>
</table>

#### 1.1.2 Entry criteria defined
Entry Criteria: Specify conditions that must be met before testing begins, such as environment setup and data availability, business requirements are completed by the analysis team and are delivered to the appropriate testing team for evaluation;
- Ensure that all business requirements for the 'Wallet' are tested.
- Test environment setup: test environment includes integration with xPortal and at least one third-party exchange, ensuring complete end-to-end testing of functionalities.

#### 1.1.3 Exit criteria defined
Exit Criteria: Define the conditions required to conclude testing, such as completion of all test cases and resolution of critical defects, 90%  or more of the tests are passed, no critical issues have status open, all detected errors have been reported and closed.

- Verify that all critical defects related to the 'Wallet and Insider(News)' are resolved and validated, with no open critical issues remaining.
- Confirm that the app can handle at least 5.000 simultaneous users during peak load without performance degradation, and passes all security vulnerability tests.
- Aplication is easy to navigate for new crypto users.

#### 1.1.4 Test scope
- The functionalities in scope for testing include:

- Account Registration/Login: Ensure secure and smooth user authentication;

- Wallet Management: Verify cryptocurrency storage and transfer 
functionalities;

- Fiat-to-Crypto and Crypto-to-Crypto Exchange: Test exchange processes for accuracy and reliability;

- NFT send and receive : Test if the function is implemented for with accuracy and reliability;

- Messenger for application: so that user can chat in the ecosystem ;

- Security Features: Assess biometric and PIN authentication for user security;

- User Experience (UX) and User Interface (UI): Evaluate the application’s usability and design.


##### Tests not in scope:

We are not going to cover during the testing process any techniques related to whitebox testing.

#### 1.1.5 Risks detected
Project risks:
- exceeding the budget, time delays and changes in requirements;
- supplier dependency risks for mentaning the servers running;
- problems integrating with old systems or platforms.

#### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control
The most important reason for monitoring and control, is visibility and transparency of the project and issue tracking management, with can be view in the below picture.

![image](https://github.com/user-attachments/assets/3d65e39c-294c-483c-a2c6-476699f60a10)


### 1.3 Test Analysis
The testing process will be executed based on the application requirements. 

The following test conditions were found:

![image](https://github.com/user-attachments/assets/dec1a285-8a85-4bae-8bce-6597d4d7116f)


### 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/Gabi-git-email/ITF-ST3_Gabi/blob/main/Jira_stories.doc)

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

- Test data preparation: Generate and validate test data.
- Environment setup: Ensure the test environment mimics the production setup to identify potential deployment issues early.


### 1.6. Test Execution
Test cases are executed on the created test Cycle summary: Wallet and Insider(News)

Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/Gabi-git-email/ITF-ST3_Gabi/blob/main/Jira_Bugs.doc)

The following is a summary of the bugs that have been found 

![image](https://github.com/user-attachments/assets/b36d5abb-a288-4197-a2f1-0b5a5d33c0a4)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Exit criteria 
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.

The traceability matrix was generated and can be found here: 

![image](https://github.com/user-attachments/assets/d50f332e-21e4-4040-beb1-269f40b808da)


- Requirements ST3GS-12 and ST3GS-7 have associated tests and executions, these requirements have been addressed and tested within the project.
- Requirements ST3GS-11, ST3GS-10, ST3GS-9, and ST3GS-8 have no associated tests or executions, which may indicate that these requirements have not yet been implemented or tested.
- The ST3GS-7 requirement has identified defects that require remedial action before it can be considered fully implemented.

Test execution chart was generated and can be found below.

![image](https://github.com/user-attachments/assets/fd7c6c10-23c4-4597-9d7a-b4034e0cc802)

The final report shows that a number 13 tests have failed of a total of 1.

A number of 2 total bugs were found, from which the priority is: 2 are highest.

The objective of this test is to ensure there are no bugs in the aplication and ensure the quality of the product. For the test scope a percentage of 80% was coverd, and all reported bugs where fix.
