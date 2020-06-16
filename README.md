# DevOps
Devops is not a new tool/technology in the market.

It is a new culture or process to develop, release and maintance of the software
application.project/product with higher quality in faster way.

we can achieve by using automation tools.
## Types of Engineer
For any software two types or two groups of engineers will work

1. Development Group
2. Operations Group/Non-Development Groups/ Administrators Group

Again this classifiaction can be divide into small set of groups

1. Development Group:
--------------------------
The people who are involving in

1. Planninig
2. Coding
3. Build
4. Testing

are considered as Development Group

e.g.

Development People
------------------
Business Analyst(BA)
System Analyst(SA)
Design Architech(DA)
Developers/coders
Build Engineer
Test Engineers(QA)


2. Operations Group:
-------------------------
The people who are involving in

1. Release
2. Deployment
3. Operations
4. Monitoring

are considered as Operations Group.

e.g.
Release Engineer
Configuration Engineer
System Admin
Database Admin
Network Admin
etc

Devops is a combination of development and Operations.
The main objective of devops is to implement collaboration bet development
and operation teams

To Uderstand this new Devops culture, we havve to aware already existing SDLC Modesels
SDLC--> Software Development Life Cycle

- Waterfall Model
- Prototype Model
- Incremental/Iterative Model
- Spiral Model
- RAD Model
- Big-Bang Model
- Fish Model
- V Model
- Agile Model
- Devops Model or culture

1. Water Fall Model:
------------------------
Requirement Gathering/Collection
			Requirement Analysis
				         Design
					         Coding
					           Testing
						             Release
							              Maintenance
Also Know as Linear squantial Model

Limitations:
------------

 1. Development time will be increase
 2. Cost of development will ne increases
 3. It won't accept requirement changes in the middle.
 4. Client Satisfaction is very very low
 5. Bug fixing is a very costly bez we cannot identify bugs in early stages of life cycle.
 6. Not at all suitable if requirements keep on changing
 7. Not suitable for large prjects

 Advantages:
 It is very simple and easy to implement
 
 Best suitable id requiremets are fixed
 
 Best suitable for small projects
 
# Agile Model:
 -----------------
 This was the most frequently used and hot cake model in software development.(lasted for almost more than 10 years)
 Agile Model is divided into multiple sub models
 
 - Rational Unify Process(RUP)
 - Adaptive Software Development(ASD)
 - Feature Driven Development(FDD)
 - Crystal Clear
 - Dynamic Software Development Method(DSDM)
 - EXtream Programming(XP)
 - SCRUM Model (Most Popular and frequently used) etc
 
 Agile==>Speed
 SCRUM is Agile based model
 It is not linear sequential Model.
 It is iterative model. Total software product will be developed increament by increament
 and each increament is called a sprint.
 SPRINT

 e.g:
 Website 100 pages bulid

 10 pages
 continuous delivery
 Continuous Feedback
 Requirement changes in the middle time
 Client Statisfaction is very high
 Less Development cost
 Less Development time

 SCRUM is derived from Rugby Game
 In every sprint 7 to 9 members will works
 each sprint will be delivered from one week to 3 weeks time
 
 Why we should go for Devops???
----------------------------------
Devops and aglie both are different models.

Similarities:
----------------
1. Both are software development methodologies.
2. Both models concentrating on rapid software development with team collaboration.


Differences:
--------------
1. The difference will come once development of the project completed.

Agile model talks about only development but not operations.
Devops model talks about complete product life cycle like development and operations.

2. In Agile model, separate people are responsivble for development,
testing, deployment etc.

But in devops, the devops engineer is responsivble for everythings like devvelopment to operation
and operations to development.

Devops engineering also called devops generalist

3. Agile model wont force us to automation tools.
But Devops model is completely based on automation.

4. Agile is always ginving highest prioproty only for speed.
Devops giving the priority for both quality and speed.

5. In agile, client is resposible to give the feedback for the sprint.
But in Devops, immediate feedback is aviable from the monitoring tools.

What is Devops?
It is a new culture/process

It is the process of continous development,continous build,continous test, continous relaese of the software.

# Version Control System Tool:
 -----------------------------
 Version Control System is also known as Software Configuration Managment(SCM) or Source code Management(SCM)

Need of version Control system?
-----------------------------------
Assume
Developer--->Write code--->Files
Client--->Durga
Requriment--->Please Develop this project

Client project
	|--100 files developed
	|--client suggenst some changes
	|--I changed some files source code to meet client requirement
 	|--I gave the demo and client suggested some more changes
	|--I changed some files source code to meet client requirement
	|--I gave demo 3rd times

We should not overwrite our code
Every version we have to maintain
100 developer
## Importance of VCS
1. Maintaining multiple version manually is very complex activity
2. Every change should be tracked
	who did the change
	when he did the change
	which changes he did etc
3. Overwriting of the code sholud not be happen
4. developere have to share their code to peer developers, so that multiple developers will work in collaberation way.
5. Parallel development must be requried
#### How Version Control system works:

Version control system always talks about files which contain source code
Use Version control system if we requried multiple version of same file for eg
tester use for test script
Architect for Documnets
Project Manager for excel sheets
## Basic Version Control System Terminology:
### Working dirctory: 
Where developers are required to create/modify files.
Here version control is not applicable. Here we wont use the work like version-1
version-2 etc
						
### Repository: 
Where we have to store file and metadata.
Here version control is applicable.
Here we can talk about different version of file

### Commit: (Process name or group of files it is noun(things which is going to hold) or verb(process))
The process of sending files from working directory to repository

In every commit the modified file only form new version others are inheriated from previous version

In every commit there is unique commit id which contain all information

### Checkout: 
The process of sending of sending files from repository to working directory
