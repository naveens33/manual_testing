## Software Testing 
The process or method of finding error/s in a software application or program so that the application functions according to the end user's requirement is called software testing.

## Who does testing?
In organization everyone has the responsibilities to evaluate the developed software in the context of the given requirements. Following professionals are involved in testing of a system within their respective responsibilities:
* Software Tester
* Software Developer
* Project Lead/Manager
* End User 

## When to Start Testing?
1. Early start to testing reduces the cost, time to rework and error free software that is delivered to the client. 
2. In Software Development Life Cycle (SDLC) testing can be started from the Requirements Gathering phase and lasts till the deployment of the software. 
3. Also software testing depends on the development model that is being used.
 
	* For example in Water fall model formal testing is conducted in the Testing phase, but in agile model, testing is performed for every new update is made to the code and feeding back directly to the developers

## When to Stop Testing?
Following
are the aspects which should be considered to stop the testing:

1. Testing Deadlines.
2. Completion of test case execution.
3. Completion of Functional and code coverage to a certain point.
4. Bug rate falls below a certain level and no high priority bugs are identified.
Management decision.

## What Are the Pros and Cons of Manual Testing?
Pros
* If you’re using black box testing, you don’t need programming knowledge
* It’s ideal for test dynamically changing graphic user interface (GUI) designs
* It’s easy for new testers to learn
* It lets the tester interact with the apps as a real user, to spot usability and user interface issues
* The software ends up one hundred percent bug-free
* It’s cost-effective in the long run because it catches errors and issues that would otherwise appear in the finished product, requiring resolutions such as releasing patches or new versions, perhaps even an outright recall

Cons
* It uses a comparatively large number of human resources
* It’s costly in the short run. Ideally, though, the business is investing significant funds at the start to head off more prominent and more expensive headaches after the product is released
* It is very time-consuming
* The tester develops test cases based on their skills and previous experiences. There is no proof that they have covered all functions.
* Testers cannot use a given test case again. Testers need to develop separate test cases for each new application
* It does not cover all aspects of testing.

##  Advantages of Automated testing. 
The following are some major advantages of automated testing - 

* Automated test execution is quick and saves a significant amount of time.
* Human mistakes are eliminated during testing when test scripts are carefully prepared.
* CI tools like Jenkins, which may also be set to distribute daily test results to key stakeholders, can be used to schedule test execution for a nightly run.
* Automation testing uses a lot less resources. Test execution requires nearly no time from QAs once the tests have been automated. QA bandwidth can be used for other exploratory work.

## Difference between Verification & Validation
|Verification|Validation|
| :------- | :---- |
|Verification is the process of evaluating the artifacts of software development in order to ensure that the product being developed will comply to the standards|Validation is the process of validating that the developed software product confirms to the specified business requirements|
|It is a static testing analysing the documents and not the actual end product|It involves dynamic testing of a software product by running it|
|Answers the question – “Are we building the product right?”|Answers the question – “Are we building the right product?”|
|It involves activities like document review, test case review, walk-throughs, inspection etc.|It involves activities like functional testing|

## Testing principles
1. Testing shows the presence of defects, not their absence
2. Exhaustive testing is impossible
3. Early testing saves time and money
4. Defects cluster together
5. Beware of the pesticide paradox
6. Testing is context dependent
7. Absence-of-errors is a fallacy

## Fundamental test process/Software Testing Life Cycle(STLC)
1. Planning and Control
2. Analysis and Design
3. Implementation and Execution
4. Evaluating exit criteria and Reporting
5. Test Closure activities

## Roles and Responsibilities of a Software Tester
* Test lead/manager
	* Defining the testing activities for subordinates – testers or test engineers.
	* All responsibilities of test planning.
	* To check if the team has all the necessary resources to execute the testing activities.
	* To check if testing is going hand in hand with the software development in all phases.
	* Prepare the status report of testing activities.
	* Required Interactions with customers.
	* Updating project manager regularly about the progress of testing activities.
* Test engineers/QA testers
	* To read all the documents and understand what needs to be tested.
	* Based on the information procured in the above step decide how it is to be tested.
	* Inform the test lead about what all resources will be required for software testing.
	* Develop test cases and prioritize testing activities.
	* Execute all the test case and report defects, define severity and priority for each defect.
	* Carry out regression testing every time when changes are made to the code to fix defects.
	
## Software Development Life Cycle (SDLC)
A system development life cycle or SDLC is essentially a project management model. It defines different stages that are necessary to bring a project from its initial idea or conception all the way to deployment and later maintenance. 

‍Stages of the System Development Life Cycle

* Planning
* Requirement Analysis
* Design
* Implementation
* Testing
* Maintenance

## Popular SDLC models

* Waterfall
* V-Model
* Iterative Model
* Agile Model

## Waterfall model
Waterfall model referred to as a linear-sequential life cycle model.  It is very simple to understand and use.  In a waterfall model, each phase must be completed fully before the next phase can begin. This type of software development model is basically used for the project which is small and there are no uncertain requirements.

Advantanges:
* This model is simple and easy to understand and use
* It is easy to manage due to the rigidity of the model – each phase has specific deliverables and a review process
* In this model phases are processed and completed one at a time. Phases do not overlap
* Waterfall model works well for smaller projects where requirements are clearly defined and very well understood

Disadvantages:
* Once an application is in the testing stage, it is very difficult to go back and change something that was not well-thought out in the concept stage
* No working software is produced until late during the life cycle
*High amounts of risk and uncertainty
* Not a good model for complex and object-oriented projects
* Poor model for long and ongoing projects
* Not suitable for the projects where requirements are at a moderate to high risk of changing

## V-Model
V- model means Verification and Validation model. Just like the waterfall model, the V-Shaped life cycle is a sequential path of execution of processes. Each phase must be completed before the next phase begins.

Advantages:
* Simple and easy to use
* Testing activities like planning, test designing happens well before coding. This saves a lot of time. Hence higher chance of success over the waterfall model
* Proactive defect tracking – that is defects are found at early stage
* Avoids the downward flow of the defects
* Works well for small projects where requirements are easily understood

Disadvantages:
* Very rigid and least flexible
* Software is developed during the implementation phase, so no early prototypes of the software are produced
* If any changes happen in midway, then the test documents along with requirement documents has to be updated

## Iterative Model
The iterative model is a way of software development that works in small steps for the development of the software. It was developed by a group of software developers for better ways of developing one. It is an easy way to craft requirements into a software solution. This works in iterations as large tasks are divided into small steps and easy step is developed in iterations to achieve a final solution. 

Advantages:

* Easy debugging of errors
* More flexible way of creating software

Disadvantages:

* Requires good planning for deciding iterations
* Needs well-defined modules to work on

## Agile Methodology
The Agile methodology is a way to manage a project by breaking it up into several phases. It involves constant collaboration with stakeholders and continuous improvement at every stage. Once the work begins, teams cycle through a process of planning, executing, and evaluating.

Advantages:
* Continuous customer feedback
* The ability to adapt 
* Faster delivery
* Lower project risk
* Ongoing innovation

## Testing Levels 

* Unit/Component testing
* Integration testing
* System testing
* Acceptance testing 

## Unit testing:
A Unit is a smallest testable portion of system or application which can be compiled, liked, loaded, and executed. This kind of testing helps to test each module separately.

The aim is to test each part of the software by separating it. It checks that component are fulfilling functionalities or not. This kind of testing is performed by developers.

## Integration testing:
Integration means combining. For Example, In this testing phase, different software modules are combined and tested as a group to make sure that integrated system is ready for system testing.

Integrating testing checks the data flow from one module to other modules. This kind of testing is performed by testers.

## System Testing
System testing is performed on a complete, integrated system. It allows checking system’s compliance as per the requirements. It tests the overall interaction of components. It involves load, performance, reliability and security testing.

System testing most often the final test to verify that the system meets the specification. It evaluates both functional and non-functional need for the testing.

## Acceptance testing:
Acceptance testing is a test conducted to find if the requirements of a specification or contract are met as per its delivery. Acceptance testing is basically done by the user or customer. However, other stockholders can be involved in this process.

## Types of Software Testing

1. Functional Testing
Functional testing involves the testing of the functional aspects of a software application. When you’re performing functional tests, you have to test each and every functionality. You need to see whether you’re getting the desired results or not.

There are several types of functional testing, such as:

* Unit testing
* Integration testing
* End-to-end testing
* Smoke testing
* Sanity testing
* Regression testing
* Acceptance testing
* White box testing
* Black box testing
* Interface testing

Functional tests are performed both manually and using automation tools. For this kind of testing, manual testing is easy, but you should use tools when necessary.

2. Non-functional Testing
Non-functional testing is the testing of non-functional aspects of an application, such as performance, reliability, usability, security, and so on. Non-functional tests are performed after the functional tests.

With non-functional testing, you can improve your software’s quality to a great extent. Functional tests also improve the quality, but with non-functional tests, you have the opportunity to make your software even better. Non-functional testing allows you to polish the software. This kind of testing is not about whether the software works or not. Rather, it’s about how well the software runs, and many other things.

Non-functional tests are not generally run manually. In fact, it’s difficult to perform this kind of tests manually. So these tests are usually executed using tools.

There are several types of non-functional testing, such as:

* Performance testing
* Security testing
* Load testing
* Failover testing
* Compatibility testing
* Usability testing
* Scalability testing
* Volume testing
* Stress testing
* Maintainability testing
* Compliance testing
* Efficiency testing
* Reliability testing
* Endurance testing
* Disaster recovery testing
* Localization testing
* Internationalization testing

## Test design techniques
* Equivalent Class Partitioning
* Boundary Value Analysis
* State Transition
* Use Case Testing 
* Error Guessing

## Equivalent Class Partitioning

This testing involved testing only for one condition for every partition classes which is created. The reason for this is that we consider that all conditions in one partition should be treated the same by the software. This is because we have an assumption that if one condition works for the partition, it will work for other conditions as well. This leaves us with saving our efforts in the testing. If a particular condition does not work, then it can be concluded that the other conditions will also not work and there is no point left in testing the other conditions in that partition. The partitions which are created can be created for valid data i.e for the values which can be accepted and also for invalid data which means values which are to be rejected. One representative value is chosen in the partition and it covers all the items in the same partition that can be considered. A set of data is to be chosen which can act as input condition. The result when the program is executed can classify as a set of equivalent data for that entire partition.

Example:

Assume, we have to test a field which accepts Age 18 – 58

Valid Input: 18 – 58

Invalid Input: less than or equal to 17 (<=17), greater than or equal to 59 (>=59)

Valid Class: 18 – 58 = Pick any one input test data from 18 – 58

Invalid Class 1: <=17 = Pick any one input test data less than or equal to 17

Invalid Class 2: >=59 = Pick any one input test data greater than or equal to 59

![alt text](/equivalentclasspartitioning.png)


## Boundary Value Analysis 

The boundary value analysis is similar to the previous technique. Some may even say it is based on the equivalent class partitioning. So what makes the boundary value analysis different? We still group data in equivalent classes but don’t test values from a particular class only. Instead, we check boundary values, those that are at the ‘borders’ of the classes. The same logic works perfectly for integration testing. We check smaller elements during unit testing, and on the next level, the errors are likely to pop up at the unit junctions.

Let’s take the previous scenario. We have the same data but a different approach to using it. Assuming that errors are the most likely to occur at the boundaries, we test only the ‘boundary’ numbers: 

Valid boundaries 18, 19, 57, 58

Invalid boundaries 17, 59

## State Transition 

The state transition visualizes the states of a software system at different time frames and stages of usage. Visual information is simpler to perceive compared to verbal description. Therefore, the state transition allows you to come up with ultimate test coverage more quickly. This technique is effective for creating test suites for systems that have many state variations. It will be helpful if you test a sequence of events with a finite number of input options.

![alt text](/statetransition.png)

## Error Guessing 

Error guessing is the most experimental practice of all, usually applied along with another test design technique. In error guessing, a QA engineer predicts where errors are likely to appear, relying on previous experience, knowledge of the system, and product requirements. Thus, a QA specialist is to identify spots where defects tend to accumulate and pay increased attention to those areas. 

AN EXAMPLE OF ERROR GUESSING 

As a rule, QA engineers start with testing for common mistakes, such as: 

* Entering blank spaces in text fields. 
* Pressing the Submit button without entering data. 
* Entering invalid parameters (email address instead of a phone number, etc.). 
* Uploading files that exceed the maximum limit. … and so on. 

The more experience a QA specialist has, the more error guessing scenarios they can come up with quickly.


## Types of Testing

1. Functional testing
It is a type of testing that involves validating the software application for its functional specifications or business requirements. It aims at verifying each feature of the application by executing the test cases and matching the expected result with the actual result.


2. Non-functional testing
It is a type of testing that includes testing the non-functional attributes or requirements of the system like performance, reliability, security, scalability, and usability.
Corresponding to each parameter, we can have one or more types of testing like we have performance testing that includes load, stress, endurance, spike, and volume testing. Similarly, we have security, reliability, scalability, and usability testing.

3. Manual testing
Manual testing is a software testing type in which test case execution is performed manually by humans without using any automated tool. It helps in ensuring that both functional and non-functional requirements are met. It is considered that 100% automation is not possible. Some software testing types like exploratory, usability, user-friendliness, etc can only be performed manually. So, manual testing is always necessary but with its advantages, there are some disadvantages also like – it is very time-consuming, resource-intensive, and prone to human errors.


4. Automated testing
It is a type of testing in which automated test case execution is performed using different automation tools and test scripts. Its advantage is – once the automated scripts get created, it saves a lot of test execution time. Also, it helps with the implementation of Continous-Integration and Continous Deployment (CICD) in which automated test cases can be made to execute automatically as soon as the new code is pushed. Thus making the product releases automatic and much faster.

5. Black box testing
It is a type of software testing, in which the tester is not required to have any knowledge of the internal architecture or implementation of the system, for carrying out testing. It is performed, considering the software application as black-box only wherein we pass input to the application and verify the actual result with the expected result without considering how the data is getting processed internally.


6. Specification-based testing
It is the same as black-box testing which requires validating the specifications of the application under test without the knowledge of the internal architecture of the system.


7. White box testing
It is a type of software testing, in which the tester needs to have access to and knowledge of the internal architecture of the application. The tester analyses the architecture as well as the source code on different quality parameters like code coverage, code optimization, reusability, etc.


8. Glass box testing
It is the same as white box testing in which knowledge of the internal architecture is required to test the software application.


9. Structure-based testing
It is the same as white-box or glass-box testing in which the structure or the internal implementation of the application is required to test the application.


10. Gray box testing
In Grey box testing, the tester has limited access or knowledge of the internal architecture of the system. For example, the tester might not have access to the full source code of the application but may have access to the design documents or the structure of the database (schema and tables). All this information helps the tester in creating better test cases.


11. Unit testing
It is the first level of testing, usually performed by the developers. In unit testing, a module or component is tested in isolation. Its advantage is, defects in a module can be easily identified at an early stage, thus reducing the overall cost of bug-fixing.


12. Integration testing
It is the second level of testing, in which a group of related modules is tested as an integrating component. It aims at finding interfacing issues between the modules. The integration testing is of four types – big-bang, bottom-up, top-down, and hybrid.


13. System testing
It is the third level of testing, in which the complete integrated application is tested as a whole. It aims at determining if the application conforms to its business requirements.


14. Acceptance testing
It is the final and one of the most important levels of testing, on the successful completion of which, the application is released to production. It is of two types – alpha and beta testing.


15. Big bang Integration testing
In big bang integration, testing starts only after all the modules are integrated. It is different from system testing as it aims at finding interfacing issues with the different integrated modules.


16. Top-down Integration testing
In top-down integration, testing starts from top modules to lower-level modules. At times, the lower-level modules are not created by the time top-level modules are tested. In those cases, ‘Stubs’ are created. These stubs are nothing but dummy modules that simulate the functionality of the lower-level modules.


17. Bottom-up Integration testing
In bottom-up integration, testing starts from lower-level modules to higher-level modules up in the hierarchy. Similar to top-down integration, the higher-level modules might not have got created by the time lower-level modules are tested. In those cases, ‘Drivers’ are used. These drivers are dummy modules that simulate the functionality of higher-level modules.


18. Hybrid Integration testing
It is the combination of both Top-down and bottom-up integration testing. In this approach, the integration starts from the middle layer, and testing is carried out in both directions making use of stubs and drivers, whenever necessary.


19. Alpha testing
It is a type of acceptance testing that is performed by end-users at the developer’s site in a closely monitored environment. It includes both white-box as well as black-box test cases.


20. Beta testing
It is the testing done by end-users at the end user’s site. It allows users to provide direct input about the software to the development company. This includes the execution of only black-box tests.


21. Equivalence partitioning
In equivalence class partitioning, we group the input data into logical partitions called equivalence classes. All the data items lying in those equivalence classes are assumed to be processed in the same way by the software application to be tested when passed as input.

Its advantage is instead of doing exhaustive testing with all the test data which is very time consuming, we can just pick some data from the equivalence classes and save a considerable amount of time.


22. Boundary value analysis
Boundary value analysis is based on equivalence class partitioning. In this technique, we test the application by picking the test data lying in the boundary values of the equivalence classes. Its benefit is the density of defects is more at the boundaries.


23. Decision tables testing
It includes testing based on decision tables that represent the application’s behavior based on different combinations of input values and the expected result in a tabular form.


24. Cause-effect graph testing
It is a software testing type that uses a graphical representation of input and output. Input is the cause and output is the effect. It aims at the creation of minimum possible test cases for maximum test coverage using cause-effect graphs.


25. State transition testing
It is a type of testing based on the state machine model wherein an application is tested based on the change in the application’s state under varying input.


26. Use case testing
It is a type of software testing that is carried out with the help of use cases. It aims at identifying test cases that cover the complete application on each transaction basis from start to finish.


27. Statement testing
It includes the creation of test scripts that are designed to execute the application’s source code. The test coverage using statement testing is the measure of the source code or statements executed by test scripts.


28. Decision or Branch testing
It is the measure of the percentage of decision points(e.g. if-else conditions) executed out of the total decision points in the application.


29. Condition testing
It includes testing the condition outcomes i.e. TRUE or FALSE values. So, getting 100% condition coverage requires covering each condition for both TRUE and FALSE results using the test scripts. Therefore, for n conditions, we will have 2n test scripts.


30. Multiple condition testing
It includes testing the different combinations of condition outcomes. For 100% coverage, we will have 2^n test scripts. This is very exhaustive and it is very difficult to achieve 100% coverage using this technique.


31. Condition determination testing
It is an optimized way of multiple-condition testing in which the combinations which don’t affect the outcomes are discarded.


32. Path testing
It includes testing the independent paths in the system. A path is an executable statement in the application’s line of code from the entry to the exit points.


33. Mutation testing
It is a type of white box testing in which the application’s source code is intentionally mutated or changed in order to cause a defect. After that, test scripts are executed. If the scripts fail due to the change in code, it means things are working fine.

It aims at finding the weak programs in the application that can lead to bugs.


34. Loop testing
It is a type of white box testing that primarily focuses on validating the different kinds of loop constructs – simple loops, nested loops, etc.


35. Performance testing
It is a type of non-functional testing that is performed to evaluate the different performance attributes of the system like – stability, responsiveness, correctness, reliability, etc at a particular load.


36. Load testing
It is a type of performance testing which involves evaluating the performance of the system under the expected workload. A typical load test includes determining the different performance parameters like response time, throughput, error rate, etc during the course of the load test.


37. Stress testing
It is a type of performance testing, in which we evaluate the application’s performance at a load much higher than the expected load. It aims at determining the breakpoint of the application, the point at which the application fails to respond in the correct manner.


38. Endurance testing
Endurance or Soak Testing is a software testing type performed to evaluate if a system can sustain a continuous expected load for very long durations (spanning days). It helps in finding memory leakage issues.


39. Soak testing
It is the same as endurance testing which includes evaluating the application’s performance on continuous load for long durations.


40. Stability testing
It is the same as endurance or soak testing.


41. Spike testing
It is one of the types of software testing in which the behavior of the application is observed with a sudden increase in the number of users. It helps in checking if the application can recover from a sudden increase or decrement in the number of active users.


42. Volume testing
It is a software testing type in which an application is subjected to a very high volume of data. This is performed either by inserting a large amount of data into the database or by passing large files to the application for processing.


43. Experience-based testing
The experienced-based testing techniques are completely based on the experience or intuition of the tester. The two of its most common forms are – Adhoc and Exploratory testing.


44. Adhoc testing
It is an unstructured way of testing that is performed without any formal documentation or proper planning. Its main advantage is – it can uncover defects that are otherwise not possible or really hard to be found using conventional techniques.


45. Exploratory testing
It is one of the types of testing in which a new test case is added and updated while exploring the system or executing the test cases. Unlike scripted and other testing techniques, the test design and execution go in parallel during exploratory testing.


46. Retesting
It is a type of testing in which we verify if the fixed issue is resolved or not. It is the part of the defect life cycle in which a bug once fixed by the developers is assigned to the testers for retesting.


47. Regression testing
It includes testing the application under test to verify that a new code change hasn’t affected the other parts of the application. The regression tests are generally best suited for automated testing.


48. Smoke testing
It includes executing only a subset of test cases covering the major features of the application. It is performed to make sure that the application can be considered for exhaustive testing or not. If the smoke tests fail then the build is rejected and exhaustive testing is not performed.


49. Sanity testing
It is the subset of regression testing, which is carried out when there is some minor fix in the application in a new build. It is a narrow and deep approach wherein a smaller section of the application is tested deeply.


50. Dynamic testing
It is performed by executing or running the application under test either manually or using automation. It is the opposite of static testing which includes – reviews and walkthroughs.


51. Static testing
A type of testing carried out without actually running the code. It involves activities like reviews, inspections, and walk-throughs.


52. Monkey testing
A type of testing that is performed randomly without any predefined set of test cases or test input. It is performed with the intent of breaking the system.


53. Gorilla testing
It involves testing an individual module or functionality of the application heavily in order to test its robustness.


54. Usability testing
It is a type of software testing that aims at determining the extent to which the application is easy to understand and use. Factors like – ease of use, ease of learning, memorability, level of satisfaction, etc are considered during usability testing.


55. Accessibility testing
Accessibility is a software testing type that aims at determining the ease of use or operation of the application specifically for people with disabilities.


56. Installation testing
In installation testing, the installation process is checked based on the installation guide of the software product.


57. Configuration testing
It is used to evaluate the configuration requirements of the software along with the effect of changing the required configuration.


58. Localization testing
It is one of the types of testing in which we evaluate the application’s customization or a localized version of the application to a particular culture or locale.


59. Globalization testing
It is one of the types of testing in which an application is evaluated for its functioning across the world independent of its geographical location or cultural environment.


60. Internationalization testing
It is the same as globalization testing.


61. Negative testing
It is one of the types of software testing in which the application’s robustness (graceful exiting or error reporting) is evaluated when provided with invalid input or test data.


62. Security testing
It is a software testing type that aims at evaluating the integrity, authentication, authorization, availability, confidentiality, and non-repudiation of the application under test.


63. Penetration testing
It is a type of security testing in which the application is evaluated (safely exploited) for different kinds of vulnerabilities that any hacker could exploit.


64. Crowdsourced testing
It is a software testing type that is carried out by a large group or community of QA professionals instead of in-house QAs or hired QA consultants.


65. Database testing
It is one of the types of testing that involves checking the integrity of actual data in the front end with the data present in the database. It involves validating the data in the database, checking that there are no orphan records (records with a foreign key to a parent record that has been deleted), no junk records are present, updating records in the database, and matching the values at the front end with the database values.


66. API testing
It involves testing of the Restful APIs and SOAP web services directly using some clients like Advanced Rest Client or tools like SOAPUI, Postman, etc.


67. ETL testing
Extract-Transform-Load or ETL testing is a software testing type that involves checking the consistency of data after extraction from source to destination.


68. Data warehouse testing
It includes validating that the data in the data warehouse is consistent, reliable, and accurate by creating and executing comprehensive test cases across the different stages of BI or Data warehouse.


69. Robustness testing
It is a software testing type that is performed to find the robustness of the application i.e. the ability of the system to behave gracefully in case of erroneous test steps and test input.


70. A/B testing
It is one of the types of testing in which the two variants of the software product are presented to the end-users. The aim is to find which variant performs better in terms of user experience or any other business goal and then eventually keep the better-performing variant.


71. Split testing
It is the same as A/B testing.


72. Concurrency testing
It is multi-user testing in which an application is evaluated by analyzing the application’s behavior with concurrent users accessing the same functionality.


73. All pair testing
It is a software testing type in which the application is tested with all possible combinations of the values of input parameters.


74. Failover testing
It is used to verify the application’s ability to allocate more resources(more servers) in case of failure and transfer the processing part to a backup system.


75. Fuzz testing
A type of software testing in which a large amount of random data is provided as input to the application in order to find security loopholes and other issues in the application.


76. Fault injection testing
It is a type of testing in which fault is intentionally introduced in the application in order to improve the test coverage.


77. UI testing
UI or user interface testing aims at finding Graphical User Interface defects in the application and checks that the GUI conforms to the specifications.


78. Pilot testing
It is a software testing type that is carried out as a trial by a limited number of users to evaluate the system and provide their feedback before the complete deployment is done.


79. Backend testing
It involves testing the back-end of the system which comprises testing the databases and the APIs in the application.


80. Compatibility testing
It is a type of non-functional testing that involves checking the compatibility of the application with different environmental factors like – operating system, hardware, browser, network, devices, software versions, etc.


81. Browser compatibility testing
It is one of the types of testing that involves validating the correctness and consistency of the application over different browsers.


82. Cross-browser testing
It is the same as browser compatibility testing in which the application’s UI and features are validated across different browsers.


83. Forward compatibility testing
It includes validating the application with a newer version of the other platform or software.


84. Backward compatibility testing
It includes validating the application with an older version of the other platform or software. It is also known as downward compatibility.


85. Downward compatibility testing
It is the same as backward compatibility testing.


86. Component testing
A type of testing that involves testing the functionality of the individual components or modules of the application without integrating them.


87. Module testing
It is the same as component testing which includes validating an individual module of an application.


88. Agile testing
A type of testing that involves following the principles of agile software development methodology. In agile testing, testing is conducted throughout the life cycle of the continuously evolving project instead of being confined to a particular phase.


89. End-to-end testing
A software testing type in which the application’s flow is tested from start to end under real-world scenarios in order to ensure that the application works as per the requirement.


90. Happy path testing
It is a software testing type in which the default or the happy flow of the application with valid input is tested.


91. Incremental testing
It is also known as incremental integration testing. In this testing, integration between the modules is tested and on successful testing, new modules are incrementally added until the time each module of the application is integrated and tested.


92. Recovery testing
It is a type of non-functional testing that involves testing the ability of the system to recover from a crash or failure. The application under test is intentionally made to fail and validated if it can recover from the failure.


93. Risk-based testing
It is one of the types of testing in which test cases are prioritized on the basis of the risk involved or the impact of the failure.
It is particularly helpful when there is limited time for testing as we can focus on the test cases with a higher probability of failure.


94. Vulnerability testing
It is also known as vulnerability analysis or assessment and it involves the evaluation and identification of the vulnerability or weakness in a software application or infrastructure, in order to reduce the probability of security threats.


95. Compliance testing
It is a type of non-functional testing that involves validating that the built product conforms to the organization’s standards and practices. Apart from internal compliance, there could be external compliances as well based on the type of product developed. For example for a software application developed in the healthcare domain, there could be external regulatory bodies whose standards and regulations must be followed.


96. Conformance testing
It is the same as compliance testing.


97. Destructive testing
A software testing type that includes checking the robustness of the application by intentionally breaking or crashing the application. The aim is to find the break-even point of the application, the point at which the application fails to respond correctly.


98. Dependency testing
A software testing type that involves checking the pre-conditions or the initial state and configuration of a system required for its correct functioning.


99. Scenario testing
A software testing type in which testing of complex test flows is simplified by making use of scenarios to easily understand and test complex workflows. With this, the end-to-end flow of the application can be tested.


100. Documentation testing
Documentation testing involves reviewing and validating the documented artifacts produced before, during, or after the software development/testing phase.

With this, we have come to the end of this article on the different types of testing. If you think we have missed any of the popular software testing types, feel free to let us know in the comments section.


## Difference between White Box Testing & Black Box Testing.

| Black Box Testing	| White Box Testing|
|-------------------|------------------|
| The Black Box Test is a test that only considers the external behavior of the system; the internal workings of the software is not taken into account.|	The White Box Test is a method used to test a software taking into consideration its internal functioning.|
|It is carried out by testers.|	It is carried out by software developers.|
|This method is used in System Testing or Acceptance Testing.|	This method is used in Unit Testing or Integration Testing.|
|It is the least time consuming.|	It is most time consuming.|
|It is the behavior testing of the software.|	It is the logic testing of the software.|
|It is also known as data-driven testing, functional testing, and closed box testing.| 	It is also known as clear box testing, code-based testing, structural testing, and transparent testing.|
|Black Box Test is not considered for algorithm testing.|	White Box Test is well suitable for algorithm testing.|


## Difference between Hotfix & Patch.
 
|Hotfix|Patch|
|-------------------|------------------|
|Used specifically to address high-priority bugs.|	Used to resolve major and minor bugs.|
|Bypasses software development pipeline/protocols.|	Usually developed as part of a team’s usual dev pipeline.|
|Often, not tested before release.|	Typically tested before release.|
|Released in response to customer reports of one or more bugs disrupting UX.| 	Released as part of a predetermined schedule. 
|Requires dev and QA teams to hyper-prioritize it over all other tasks and projects.| 	Usually developed and released as part of dev and QA teams’ regular schedules.| 
|Too many hotfixes indicate fundamental issues with dev and test pipelines that need fixing.| 	Too many patches may reveal some issues with the codebase, but a certain number are a natural part of software development and maintenance.|
|Can be applied without a server reboot.|	Usually needs to go through installation processes like server restarts, ancillary dependencies, configuration changes/updates, etc.|

## Test case
A structured test script that describes how a function or feature should be tested, including test steps, expected results preconditions and postconditions.

## Test data
Information that completes the test steps in a test case with e.g. what values to input. In a test case where you add a customer to the system the test data might be customer name and address. Test data might exist in a separate test data file or in a database.

## Test execution
The process of running test cases on the test object.

## Test plan
A document describing what should be tested by whom, when, how, and why. The test plan is bounded in time, describing system testing for a particular version of a system, for example. The test plan is to the test leader what the project plan is to the project manager.

## Test script
Automated test case that the team creates with the help of a test automation tool. Sometimes also used to refer to a manual test case, or to a series of interlinked test cases.

## Defect Life Cycle

1. NEW: When a bug or defect is found in an application by the tester during the testing phase then, it is reported to the development team through the bug management tool JIRA.so the initial level of bug status is assigned by the tester as a “NEW”. Here the tester creates an issue in JIRA by describing the Issue type, summary, description, priority, etc of the bug.

2. ASSIGNED: Once a new status bug is raised by the tester, then the technical/QA leads to validate it and assign the bug to a particular developer in the development team to work on that. Then the status of the bug is marked as “ASSIGNED” i.e. bug is approved by the developer and they will work on it to fix the bug. It is really an issue but when the developer accepts it, it changes to Bug.

3. OPEN: In this phase, once the tester assigns the bug or defect to the developer, they investigate it and resolve it. The status of the bug or defect is shown as “OPEN”. Bug fixing gets started in this phase.

The bug or defect can be passed in four stages:

4. Duplicate: If the bug is already logged before by tester or similar to the previous one, then the developer mentions the status of the bug as “Duplicate”.

5. Rejected: If the bug which was assigned to the developer is not an authentic one, then the developer mentions the status of the bug as “Rejected” with proper reasons.

6. Deferred: If there is a bug but no need to fix in this sprint/release or it is not in project scope and it can be moved to the next release for the fix, then developer mentions the status of the bug as “Deferred”. It is a postpone state.

7. Not a Bug: If the bug does not affect the functionality of the application, then the status of bug assigned as “Not a Bug”.

8. FIXED: When the developer takes necessary actions on coding to fix the defect then it changes the status of a bug as “FIXED” i.e. the defect will remove from the application.

9. RETEST: Once the bug is fixed by the developer, then assign to the testing team to check whether the bug has fixed by the developer or not and the status of the bug as “RETEST”.

10. VERIFIED: The bug is fixed by the developer, then the tester retest the application, if there is no bug then it changes the status assigned as “VERIFIED”.

11. REOPEN: The tester will do a retest of the application after fix bugs by the developer, during that if there is a bug (either a new bug or old bug not fixed), then tester assigned status as “REOPEN” i.e. once again it goes through the bug life cycle.

12. CLOSED: If there is no more bug or issue in the application after a retest, then the status will be assigned as “CLOSED” by the tester.

![alt text](/defectlifecycle.png)


## Differentiate between Positive and Negative Testing 

|Positive Testing|Negative Testing|
|----------------|----------------|
|Positive testing ensures that your software performs as expected. The test fails if an error occurs during positive testing.|Negative testing guarantees that your app can gracefully deal with unexpected user behaviour or incorrect input.|
|In this testing, the tester always looks for a single set of valid data.|Testers use as much ingenuity as possible when validating the app against erroneous data.|

## What do you mean by Defect Triage?
Defect triage is a procedure in which defects are prioritised depending on a variety of characteristics such as severity, risk, and the amount of time it will take to fix the fault. The defect triage meeting brings together several stakeholders - the development team, testing team, project manager, BAs, and so on – to determine the order in which defects should be fixed.
