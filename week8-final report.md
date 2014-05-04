# How to ensure the quality of a software system
Software quality is an extremely important issue throughout the lifetime of the software. So we should pay special attention to the quality assurance in the lifetime of the software to produce high-quality software products.

## What is software quality?

Software quality may include many different attributes and may be defined and perceived differently based on people’s different roles and responsibilities. And high quality means none or few problems of limited damage to customers.

## The major QA acivities

There are three major groups of activities in the quality engineering process. They are labeled in roughly chronological order as pre-QA activities, in-QA activities, and post-QA activities:
* Pre-QA activities: Quality planning. These are the activities that should be carried out before carrying out the regular QA activities. 
* In-QA activities: Executing planned QA activities and handling discovered defects. In addition to performing selected QA activities, an important part of this normal execution is to deal with the discovered problems.
* Post-QA activities: Quality measurement, assessment and improvement. The primary purpose of these activities is to provide quality assessment and feedback so that various management decisions can be made and possible quality improvement initiatives can be carried out. 

## The most important parts of QA---Testing

Testing is one of the most important parts of quality assurance (QA) and the most commonly performed QA activity in the overall software process. Actually, testing for large software systems is typically organized and divided into various sub-phases starting from the coding phase up to post-release product support, including unit testing, component testing, integration testing, system testing, acceptance testing, beta testing, etc.

Unit testing tests a small software unit at a time, which is typically performed by the individual programmer who implemented the unit. Unit testing typically focuses on the implementation details and uses white-box testing techniques, with various coverage criteria as the exit criteria. Black-box testing could also be performed on the unit, while focusing on the input output relations.

Component testing tests a software component at a time, typically by a small group of developers. A component generally includes a collection of smaller units that together accomplish something or form an object.

Integration testing deals with the integration of different product components to work together, with the focus on interface and interaction problems among these components. Therefore, in integration testing, each component is treated as an atomic unit or as a black box, while the interconnections among them are examined and modeled to test component interfaces and interactions.

System testing tests the overall system operations as a whole, typically from a customer’s perspective. The primary concern is how the software system works as a whole under the operational environment of actual customers. High-level functional checklists are often used to ensure that all the major functions expected by the customers are present and perform satisfactorily.

Acceptance testing is usually performed as the final sub-phase of testing to determine if the product should be released. Acceptance testing is a test conducted to determine if the requirements of a specification or contract are met. It may involve black-box testing performed on a system prior to its delivery.

Beta testing is a test for a computer product prior to commercial release. It is the last stage of testing, and normally can involve sending the product to beta test sites outside the company for real-world exposure or offering the product for a free trial download over the Internet.

In different testing sub-phases, the testing perspective includes black-box (functional) and white-box (structural); the Stopping criteria are coverage-based and usage based. Major types of specific testing techniques used, including, informal debugging (db), functional and structural checklists (f-list and s-list), boundary test (BT), finite-state machine based testing (FSM), control flow testing (CFT), data flow testing (DFT), Musa operation profiles (Musa), and Markov operational profiles (Markov).

Although software testing plays a central role in software quality assurance and is the most commonly performed QA activity, it is neither the only viable nor the most effective QA technique under all circumstances. There are many other QA activities (defect prevention, inspection, formal verification, fault tolerance, failure containment) beyond testing.

## What should we do?
I suggest that the software quality assurance process should consist of the following activities: 
* Firstly, we should set up a SQA group; 
* Next, choose and determine the SQA activities, choose quality assurance activities to be undertaken for the SQA group. 
* Then, we have to develop and maintain the SQA plan. This plan defines the relationship between SQA activities and the each stage of software development lifecycle;
* Execute the SQA plan, and train the relevant personnel, choose the appropriate QA tools which can adapt the software engineering environment;
* Finally, we should continue to improve the quality assurance deficiencies exist in the activities, and improve the quality assurance process of the project.
