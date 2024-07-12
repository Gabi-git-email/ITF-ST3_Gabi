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

![image](https://github.com/Gabi-git-email/ITF-ST3_Gabi/assets/174444760/f3f5619b-46df-4637-8a0b-7e98fce5ddbc)


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
(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)

### 1.3 Test Analysis
The testing process will be executed based on the application requirements. 

The following test conditions were found:

![image](https://github.com/user-attachments/assets/7652bdfb-046d-4917-a1d0-9231b3de8cf6)


### 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here (inserati linkul catre fisierul cu testele, in format pdf, word sau csv)

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

(inserati lista de elemente care sunt evaluate in etapa de implementare)

### 1.6. Test Execution
Test cases are executed on the created test Cycle summary: (inserati aici numele cycle-ului pe care l-ati creat)

Bugs have been created based on the failed tests. The complete bug reports can be found here: (inserati aici fisierul cu bug-urile pe care le-ati identificat)

The following is a summary of the bugs that have been found (inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: (inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)

Test execution chart was generated and can be found below.

(inserati aici raportul de executie generat din jira din sectiunea de dashboards)

The final report shows that a number (inserati numarul de teste) tests have failed of a total of (inserati numarul de teste)

A number of (inserati numarul de bug-uri) total bugs were found, from which the priority is: (inserati numarul de bug-uri) are high and (inserati numarul de bug-uri) are medium.

(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)
