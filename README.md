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
# Benefite of Version Control System:

1. We can different versions and we can choose any version based on client
2. With every version/commit we can maintain metadata like
 	commit message
	who did changes
	when he did the change
	what changes he did
3. Developers can share the code to the peer developers in very easy way.
4. Multiple developer can work in collaborative way
5. Parallel development.
6.We can provide access the control like
 	who can read code
	who can modify code
	
### Types of version control sytems:
- Centralized Version Control System
-  De-centralized/ Distributed Version Control System

#### Centralized Version Control System:
Centralized----------->
Only one central repository, every developer is required to connect with that to
continue his work
The total project code wiill be stored in central repository
It is very easy to setup and easy to use.
CVS,SVN,Perforce,Clearcase,TFS etc...

### Limitations:

1. The total code stored at a single place(center repository)
   Single point of failure.
   If Something goes wrong....recovery is very difficult.

2. All checkout and commit operations will be performed by connecting with remote
   central repository server. i.e. all developers should be connected with central repository.
   If network outages(down),version control wont be available for the developers
developers.

 Bank---->Server down
3. All checkout and commit operations will be performed by connecting with remote central repository server.
The operations will be performed over the network and performance is low.

4. IF huge numbers of developer or number of files increases then organizartion of central repository is a bit difficult.

Repository is distributed
If 4 developers are there, then 4 repositories will be there.

1. All commit and checkout operation will be performend locally and hence performance is more.

2. Even network outage, still version control is available.
3. There is no question of single point of failure, because  repository is availble on every developer


Commit and Checkout:
----------------------
These operations will be performed locally between working directory and repository.
To perform these operations netwok is not required.

Pull and Push:
---------------

Push: The process of sending files from our repository to other's repository
Pull: The process of getting files from our repository to other's repository

push and pull will be performed between 2 repositories.
These are remote operatios.
Compulsory network must be there.


e.g:GIT, Mercurial, Fossil(For distributed VCS)


Distributed VCS with Remote Repository:
-----------------------------------------
Remote Repository vs Centralized Repository:
-------------------------------------------
1. Commit and Checkout operations are performing on local repository but not on remote repository
2. every developer has his own local repository.

The main josb of remote repository is just to share our code to peer developers.
 

Remote Repository server:
------------------------
- Github
- Gitlab
- BitBucket
- Cloud platform

## GIT:

GIT is Distributed Version Control System Tool.

Linux===>It is not an operating system. It is just Kernel name.
Who develop linux kernel Linus Torvalds(Finnish Software Engineer)

Operating system name: GNU/Linux

GIT is developed by Linus Torvalds.

### Features of GIT:
---------------------
Why GIT is very popular???

1. Distributed:
---------------
A) No single point of faliure. Every developer has local repository.
B) Performance ismore | speed is more. because commit and checout happens in local repository
C) Without network also, developer can continue his work.
   Workspace and remote repository need not be connected always.
D)...


2. Staging Area:
----------------
In GIT commit is 2-step process.
First we have to add files to the staging area and then we have to commit  from that staging area.

Advantage of staging area is we can cross check or double check our changes before commit . 
If everything is fine then we can commit.

Assume
12GB files we have to store in SVN (Centralized repository)
GIT requires only 420MB.
The data stored in Git is always in hashing
Only Snapshot of our data is taken by Git(it is internally using some mechanism, some algorithm to convert data in hashing object that converted data is going ti store)

3. Branching And Merging:
--------------------------
We can create and work on mutilpe branches simutaneously and all these  branches
are isolated from each other. It enables multiple worl flows.

4. Freeware and  and open source
5. It provides support for multiple platforms

GIT Architecture:
------------------
Git has 2 types of repository
1. Local repository
2. Remote repository

Usually the total project code will be available in remote repository
The current work of developer will be stored in local repository.

New files will be created in working directory.
Once wrk completed, we have to add these files to staging are for this we have to use
Command - git add

git add===>Sending files from working directory to staging area
git commit===>Staged changes will be moved to local repository
git push===>To move files from local repository to remote repository
git clone===>To create a new local repository from the remote repository
git push===> To get updated files from remote repository to local repository

cloning===>creating exactly duplicate copy
