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


Life Cycle of File in Git:
-----------------------------
Every file in the git is one of the following 4 states:

1.Untracked
2.Staged
3.In Repository/Committed
4.Modified

1. UNtracked:
-------------
Every new file will be created in working directory . Git does not aware these new
files. Such type of files are said to be in "untracked"

git status
---> To know status of files in all area

2. Staged:
--------------
The files which are added to staging area are said to be in the staged area

git add abc.txt
git add abc.txt bcd.txt
git add .
git add *.txt

3. Any file which is commited is said to be in repositroy state or commited state

We can staged changes by using git commit 

git config --global user.email "------"
git config --global user.name "username"

git message===> Mandatory

git commit -m "A new file a.txt added"


Created a file in working directory with some content==>Untracked
Once we add this file to stating area===>Staged state
		git add a.txt

we have to commit changes from staged area to local repository==>In
Repository/Commited state
 git commit -m "Commit message"

4. Modified:
-----------
If the file added to staging  area or commited===>tracked by git

is===>It will list all files in working dirctory.It is linux command.
git ls-files====>It will list all files which are tracked by git and it id git command.

Modified:Any file which is already tracked (add or commit), but it is modified in working directory
is said to be in modified state

-- git log is used to see the different version of files

## How to download Git
#### How to install git on windows:
 -- https://git-scm.com/download/win

 git-scm===>Software Configuration Management

project1

git init ===> To provide/create an empty repository to our workspace so that version
control is available to our working directory.
 The folder name is .git

	GIT log - used to see the history of commited 

If the folder has aleady initalize git agian reinitialization wont affect the folder

If Git already tracked the file the adding and commiting stage is done by single command
	git commit -a -m 'commit messaged'

### Examples TO describe basic Git commands

1.git init

Once we create workspace, if we want version control,
we required a repository.called local repository(.git)

2. git status:

It shows the current status of all files in each area, like
untracked files
modified files
staged files etc

If we want concise output we have to use -s option
## git Diff command
------------------
#### In the content of file
- working directory vs staging area
- working directory vs last commit
- staging area vs last commit
- working directory vs specified commit
- staging area vs specified commit .etc....
Demo project:
file1.txt
first line in file1.txt
second line in file2.txt

file2.txt
-----------
first line in file1.txt
second line in file2.txt

first commit: 2 files and each have 2 lines

file1.txt
--------
first line in file1.txt
second line in file2.txt
Third line in file1.txt
Fourth line in file2.txt

file2.txt
-----------
first line in file1.txt
second line in file2.txt
Third line in file1.txt
Fourth line in file2.txt

git commit -am "2 files and each have four line"

second commit: 2 file and each have four line

NOw
file1.txt
--------
first line in file1.txt
second line in file1.txt
Third line in file1.txt
Fourth line in file1.txt
fifth line in file1.txt

git add file1.txt

file1.txt
--------
first line in file1.txt
second line in file1.txt
Third line in file1.txt
Fourth line in file1.txt
fifth line in file1.txt
sixth line in file1.txt

case-1:To see difference in file content between working directory and staging area
-----------------------------------------------------
git diff file1.txt
 	To compare working directory and staging area 

output:
1) diff --git a/file1.txt b/file1.txt
a/file1.txt---->scoure copy which means staging area
b/file1.txt--->Destination copy which means working directory

2) index 8445404..246caab 100644
  8445404---->hash of source file content(staging)
  246caab---->hash of destination file content(working directory)

  100644----->Git file mode

  first 3 digits(100) ----> represents the type of file ASCII text
  Next 3 digit(644) ------> represents file permission
			644--> rw-r--r--
			4-->r
			2-->w
			1-->x
3) --- a/file1.txt
	source copy missing some line(staging area)
4) +++ b/file1.txt
	+++ means new line is add in destination		

5) @@ -3,3 +3,4 @@
 -3,3
- means source version(staging area)
  from 3rd line onwards total 3 line
 Third line in file1.txt
 Fourth line in file1.txt
 Fifth line in file1.txt

 +3,4
   + means destination version
   from 3rd line onwards total 4 lines

    Third line in file1.txt
    Fourth line in file1.txt
    Fifth line in file1.txt
   +sixth line in file1.txt

if any line prefixed with space means it isunchanged.
if any line prefixed with + means it is added in destination copy.
if anuy line prefixed with - means it is removed in destinatin copy



We can conclude one new line added in working copy when compared with  staged copy

2) Working directory VS last commit:
---------------------------------------
Last commit can be referenced by HEAD

git diff HEAD file1.txt
	compare last commit and working directory


3) staged copy vs last commit:
------------------------------------
We have to use --staged option or --cached option

git diff --staged HEAD file1.txt or
git diff --staged (HEAD optional) file1.txt

4) working directory vs specific commit:
---------------------------------------------

git log --online 
d616daf (HEAD -> master) 2 files and each file contains 4 lines
ef7a19f 2 files and each file contains 2 lines
 
git diff ef7a19f(hash above commit) file1.txt

5) staging area vs specific commit:
---------------------------------
git diff --staged ef7a19f file1.txt

6) Between two specified commit:
-------------------------------------

d616daf (HEAD -> master) 2 files and each file contains 4 lines
ef7a19f 2 files and each file contains 2 lines

git diff(source) ef7a19f d616daf file1.txt

Lets do some opposite
 git diff(des)d616daf (source) ef7a19f file1.txt

7) last commit vs last but one commit:
--------------------------------------
E.g.
commit -7
commit -6
commit -5
commit -4
commit -3
commit-2
commit -1
we have to do between 7 and 6
git diff HEAD HEAD~1(last but one commit i.e. 6) file1.txt
git diff HEAD HEAD^1(last but one commit i.e. 6) file1.txt
git diff HEAD HEAD^(last but one commit i.e. 6) file2.txt

8) compare all files:
---------------------------
d616daf (HEAD -> master) 2 files and each file contains 4 lines
ef7a19f 2 files and each file contains 2 lines

git diff ef7a19f d616daf
or git diff HEAD~1 HEAD

9) To see the differences in content of between 2 branches
-------------------------------------------------------------
git diff master test

10) To see difference in local repository and remote repository
--------------------------------------------------------------
git diff master(local) origin/master(remote)

summary:
1) Working directory vs staged copy
   git diff file1.txt

2) working directory vs last commit 
   git diff HEAD file1.txt

3) Staging area Vs last commit
   fir diff --staged HEAD file1.txt
   git diff --cached HEAD file1.txt
   git diff --staged file1.txt

4) Working dir vs specified commit:
   git commitid file1.txt

5) Staging area vs specified sommit:
   git diff --staged commitid file1.txt

6) Between two commits
   git diff source_commit_id destination commit_id file1.txt

7) last commit vs last but one commit:
   git diff HEAD HEAD~1 file1.txt
   git diff HEAD HEAD^1 file1.txt

8) To compare all file
  git diff source_commitid destination_commit_id

9) Two branches in local repository
  git diff source_branch_name destination_branch_name

10) local repo vs remote repo:

- git diff local_branch_name remote_branch_name
- git diff master origin/master

## Git checkout command::
-------------------------------
we can use checkout commands to discard unstaged changes in the tarcked files 
of working directory.

- unstaged changes ===> The changes which are not added to staging area
- tracked files  ====> The files which are tacked by git
