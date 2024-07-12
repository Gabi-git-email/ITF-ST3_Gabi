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

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)

#### 1.1.1. Roles asigned to the project and persons allocated
<table>
<tr><td>Project manager -</td></tr> 
<tr><td>Product owner   -</td></tr>
<tr><td>Software developer -</td></tr>
<tr><td>QA Engineer - Salca Gabriel</td></tr>
</table>

#### 1.1.2 Entry criteria defined
Entry Criteria: Specify conditions that must be met before testing begins, such as environment setup and data availability, business requirements are completed by the analysis team and are delivered to the appropriate testing team for evaluation;

#### 1.1.3 Exit criteria defined
Exit Criteria: Define the conditions required to conclude testing, such as completion of all test cases and resolution of critical defects, 90%  or more of the tests are passed, no critical issues have status open, all detected errors have been reported and closed;

#### 1.1.4 Test scope
The functionalities in scope for testing include:

Account Registration/Login: Ensure secure and smooth user authentication;

Wallet Management: Verify cryptocurrency storage and transfer 
functionalities;

Fiat-to-Crypto and Crypto-to-Crypto Exchange: Test exchange processes for accuracy and reliability;

NFT send and receive : Test if the function is implemented for with accuracy and reliability;

Messenger for application: so that user can chat in the ecosystem ;

Security Features: Assess biometric and PIN authentication for user security;

User Experience (UX) and User Interface (UI): Evaluate the application’s usability and design.


##### Tests not in scope:

We are not going to cover during the testing process any techniques related to whitebox testing.

#### 1.1.5 Risks detected
Project risks:
- displaying the data correctly.
- avoiding errors in the process of completing transaction data.

#### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control
The moust important reason for monitoring and control, is visibility and transparency of the project and issue tracking management, with can be view in the below picture.

![image](https://github.com/user-attachments/assets/ff39b7d3-d936-4fb0-a5fe-f453bf38e069)

### 1.3 Test Analysis
The testing process will be executed based on the application requirements. 

The following test conditions were found:

![image](https://github.com/user-attachments/assets/7652bdfb-046d-4917-a1d0-9231b3de8cf6)


### 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/Gabi-git-email/ITF-ST3_Gabi/blob/main/Jira_stories.doc)

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

- Test Data Preparation: Generate and validate test data.
- Environment Setup: Ensure the test environment mimics the production setup to identify potential deployment issues early.


### 1.6. Test Execution
Test cases are executed on the created test Cycle summary: Wallet and Insider(News)

Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/Gabi-git-email/ITF-ST3_Gabi/blob/main/Jira_Bugs.doc)

The following is a summary of the bugs that have been found 

![image](https://github.com/user-attachments/assets/b36d5abb-a288-4197-a2f1-0b5a5d33c0a4)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 

![image](https://github.com/user-attachments/assets/d0743271-7d54-40b6-aaaa-44ea2488a34e)


Test execution chart was generated and can be found below.

![image](https://github.com/user-attachments/assets/fd7c6c10-23c4-4597-9d7a-b4034e0cc802)

The final report shows that a number 10 tests have failed of a total of 1.

A number of 2 total bugs were found, from which the priority is: 2 are high.

The objective of this test is to ensure there are no bugs in the aplication and ensure the quality of the product. For the test scope a percentage of 80% was coverd, and all reported bugs where fix.
