backup

<h1>Testing Project for **Todoist**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **app.todoist.com**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The following stories were created in Jira to describe the functional specifications of the Todoist testing project:

Story 1: Create a New Task

Title: As a user, I want to create a new task with or without a due date.
Description: Users should be able to create a task by entering a title, optionally adding a due date, and saving it.


Story 2: Mark a Task as Completed

Title: As a user, I want to mark a task as completed so that it moves to the "Completed Tasks" section.
Description: Users should be able to mark tasks as completed, removing them from the active list and moving them to "Completed Tasks."


Story 3: Set Recurring Tasks

Title: As a user, I want to set a task as recurring so that it reappears automatically at regular intervals.
Description: Users should be able to create a recurring task by setting its frequency (e.g., daily, weekly).

**inserati aici fie poza cu story-ul / story-urile daca aveti mai putine, dar daca aveti mai mult de doua recomand sa descarcati story-urile din jira si sa le incarcati ca fisier**

Here you can find the release that was created for this project:

**(inserati aici o poza cu release-ul pe care l-ati creat in jira. Atentie, release-ul nu va contine si teste, ci doar epic-uri, story-uri, task-uri, subtaskuri si bug-uri)**

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here **(inserati link catre documentul cu planul de testare)**

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager: John Smith</li> 
  <li>Product owner: Jane Doe</li>
  <li>Software developer: Mike Johnson</li>
  <li>QA Engineer: Cimpoca Bogdan</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

<li>-Stories were reviewed and approved.</li> 
<li>-Test environments were configured.</li> 
<li>-Necessary test data was prepared.</li> 

<h4> 1.1.3 Exit criteria defined </h4>

<li>-All planned test cases executed.</li> 
<li>-All critical bugs fixed and verified.</li> 
<li>-Test coverage of at least 90% achieved.</li> 

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

<li>Functional testing for task creation, completion, and recurrence.e</h4>
<li>UI testing on desktop and mobile browsers.e</h4>

<h5>Tests not in scope: </h5>

<li>Performance testing.</h4>
<li>Testing integrations with third-party apps.</h4>

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

Limited time for regression testing if bugs are detected late.

<h5> Product risks: </h5>

High-severity bugs in recurring tasks may affect task scheduling accuracy.

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

**(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)**

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>

1. Verify that a user can create a task with a valid title and future due date.
2. Verify that a task cannot be created with a due date in the past.
3. Verify that tasks can be created without a due date.
4. Verify that a created task is displayed in the correct project or "Inbox."
5. Verify that a user can mark a task as completed.
6. Verify that completed tasks appear in the "Completed Tasks" section.
7. Verify that completed tasks are removed from the active list.
8. Verify that users can set a recurring task with valid frequency options.
9. Verify that recurring tasks reappear in the active list after completion.
10. Verify that the recurrence settings for tasks are displayed correctly.


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**
