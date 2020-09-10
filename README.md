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

3. git add:

To add files from  working directory to staging area
Once we added files to staging  area, then git tracks these files and ready for 
commit.

staging area-->index area or cache area

It is a logical or virtual area but not physical area.

	i)To add all files in cwd
	   git add .
	   git add *
	   git add -A
	ii)To add particular files
	   git add file1.txt file2.txt
	iii) We can use even regular expression patterns also
	   git add *.java
           git add *.txt
4. git commit:

If we wnat to commit staged changes

git commit -m "commit message"

for evey commit a unique commmit id generated (also known as hash) which is
hexadecimal number of 40 characters

For every commit git records
author name and mail id
timestamp
commit message
	for example-
	
	$ git commit -m "New files added"
	[master (root-commit) dcb4108(commit hash fist 7 digit)] New files added
	2 files changed, 2 insertions(+)
	create mode 100644 file1.txt
	create mode 100644 file2.txt
      
	$git log
	commit dcb4108ddc8e5e3ba6b0a11ab4245718bbd7a1da(SHA-1 hash) (HEAD -> master)
	Author: ---- <.................com>
	Date: Sat may 16 20:54:34 2020 +0530
New files added

commit id is unique which can be used to identify commit
The first 7 characteralso unique.(we can use first 7 commit for any reference commit)

	create mode 100644 file1.txt
	create mode 100644 file2.txt
first 3 number means the type of file (100 means ascii text data)
644---->File permission:rw-r--r--(owner,user,group)

r--->4
w--->2
x--->1

5) git log:

It shows history of all commits

commit id
author name and mail id
timestamp
commit message

6) git config:

git config command can be used for git configurations like user name, mail id

git config --list

	to list out all configuration
	user.name=...
	user.email=...
	
used to change config
git config user.name 'Ravi'
git config user.email 'ooo@gmail.com'

After it global configuration is same but while commiting we can see the change

we can also use global option also

git config --global user.name 'Ravi'
git config --global user.email 'ooo@gmail.com'
- global vs with global

For all repository which is mangaed by current git--->global

with global means:configuration applicable for all repository
without global means: configuration applicable only for current repository

### Git log:

If we want to see history all commits in local repository====> git log
most commonly used command.

How to see log information of a particular files:

git log file1.txt

Option-1: --oneline option to get brief information

git log --oneline
	it will show oneline per commit
	commitid(7 chara)+commit message
*** This option is very helpful if we have lot of commits and 
    to identify based in message
    
Option-2: -n option to limit the number of commit ot display

git log -n 2(onlylatest 2 commits)
or git log -2
or git log --max-count=3

Option-3: --grep option to search based on given pattern  in commit messages.

git log --grep=pattern

git log --grep="added" --oneline

Option-4: show commits more recent than a specific date or time.

--since="2020-04-25"
--after="2020-04-25"
--after="10 days ago"
--after="3 hours ago"

Otion-5:Show commits older than a specific time:

--until="17-05-2020"
--before="17-05-2020"
--before="5 minutes ago"

Option-6:Show commits based on author

--author=<pattern>

git log --author=jon

Option-7: --decorate option to display extra inforamtion

branch name, HEAD,tags,information etc

## Git Diff command

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

## Visual tool for checking differences

Helix Visual Merge Tool(p4merge)
Meld
etc

p4merge===>Merge Tool aswell as Diff tool

centarlizes VC - SVN,CVS,ClearCase,Perforce

Perforce 4 merge ===>p4merge

### How to download and install p4merge tool:

https://www.Perforce.com

Download Helix Visual Merge Tool

Select only Merge and Diff Tool.

### How to configure p4merge with git:

#### difftool configuration:

- git config --global diff.tool p4merge
- git config --global difftool.p4merge.path "C:\Program Files\Perforce\p4merge.exe"
- git config --global difftool.prompt false

#### mergetool configuration:

- git config --global merge.tool p4merge
- git config --global mergetool.p4merge.path "C:\Program Files\Perforce\p4merge.exe"
- git config --global mergetool.prompt false

To test these set or not
git config --global --list

Now see diff between stage and working
git difftool file1.txt

#### working directory vs last commit:

git difftool HEAD file1.txt

Note only add tool after diff and remaininig are same as above

Note tool only show diff between one file only
## Git checkout command

we can use checkout commands to discard unstaged changes in the tarcked files 
of working directory.

- unstaged changes ===> The changes which are not added to staging area
- tracked files  ====> The files which are tacked by git

If there is one line in local repo, two line in staging area and three line in
working area. If we want to ignore the changes in working dir we use git checkout
command

$ git checkout

M       file1.txt
It will list out the files for which checkout is applicable.


git checkout -- file1.txt

$ cat file1.txt
first line in file1.txt
second line in file1.txt
(Discard third lines)

2. $ git checkout .

Updated 2 paths from the index

USED to checkout all files

NOTE::

	git checkout -- file1.txt
	
		to discard unstaged changes in file1.txt
		
	git checkout .
	
		to discard unstaged changes in every tracked file of working dire
		
	git checkout
	
		list all eligible files, for which checkout is applicable

### Git references(master and HEAD)

For most of the commands (like git log, git diff etc) we have to use commit ids
as arguments.But remembering these commit ids is very difficult.

40 length commit id | 7 characters

Git provides some sample names for these commit ids. We can use these names directly
instead of commit ids.These are just pointers to commit ids.
These smaples names are nothing but references or refs.

git references are pointers to commit ids.

The most recent commit id ====> master or HEAD

There is a folder called .git and folder inside it called refs directory==>All ref will be stored
heads,tags and remotes.(references examples)

#### What is master?

$ git status
On branch master
nothing to commit, working tree clean

1. master is the name of the branch.
2. It is a reference(pointer) to last commit. Hence where ever last commit id
required, we can use simply master.

git show 7 dig commit id or master (show same result)

git show master

git show 99eb4e5

but 
git show master~1 refer to last but one commit

git show master~2 refer to last but two commit

#### What is HEAD:

HEAD is a reference to master

It is symbolic reference which points to another reference(master)

By default HEAD is always pointing to the master.

master information available in .git/refs/head/master

HEAD information is available in .git directory


Let see info of head
$ cat HEAD
ref: refs/heads/master

### git reset command:

just like reset to default setting

There are two utilities of git reset command:
1.To remove changes from staging area
2.To undo commits at repository level

#### Utility-1: To remove changes from staging area:

It will bring changes from staging area back to working directory.

It is opposite to git add command.

$ git reset file1.txt

Unstaged changes after reset:

M       file1.txt

#### git checkout vs git reset:

git checkout can be used to discard unstaged changes in working directory.

git reset can be used to discard staged changes from staging area.	

#### git rm --cached vs git reset:

git rm --cached file1.txt ===> It will delete the file from staging area

git reset file1.txt ==> The file wont be delete from staging area, but reset to 

previous state(one step back)

Q.We modified the content of file1.txt and added to staging area.But we want to

ignore those changes in both staging area and in working directory. for this which command

are required to use??

1.git reset file1.txt

2.git checkout file1.txt

#### Utitlity-2.To undo commits at repository level

we can also use reset to undo commits at repository level

syntax:

git reset <mode> commit_id

Moves the HEAD to the specified commit, and all remaining recent
commits will be deleted from repository

Mode will decide whether these changes are going to remove from staging area
or not from working directory or not.

The allowed values for the mode are:
	--mixed
	--soft
	--hard

1. --mixed reset mode:

It is the default mode.

git reset --mixed commit_id

git reset commit_id

To discard/remove commits from repository and from staging area also.

It wont touch working directory

We can revert because changes are available in working directory

$ git log --oneline

	dd45bbb (HEAD -> master) file3 added
	60f6643 file2 added ---> HEAD~1
	9443b15 file1 added ---> HEAD~2

To remove last commit:

- git reset 60f6643
- git reset --mixed 60f6643
- git reset HEAD~1
- git reset --mixed HEAD~1


After that

$ git ls-files

file1.txt

file2.txt

$ ls

file1.txt  file2.txt  file3.txt

1.To add file3 to repository again

- git add file3.txt;git commit -m 'file3 added again'

2. to remove from working directory- git checkout -- filename

Note: 
1) It is not possible to remove random commits.
2) mixed reset will remove changes from local repository and staging area.It wont touch working directory
3) We can revert deletion because changes are available in working directory.

Again we have to reverse it we have to add again and commit again

2. --soft reset mode:

Exactly same as --mixed except that is wont touch working directory and staging areas.

To revert:

git commit -m "message"

usecase:

1.If some files are missing in last commit, then add those files and commit again.

2.If we forget to add defact number in the commit message

3. --hard reset mode:

It is exactly same as --mixed mode expect that changes will be removed from everywhere
(local repository,staging area, working directory)

It is impossible to revert back our changes and hence while using this command,
we have to take a bit special care.

--hard

- commit-1
- commit-2
- commit-3
- commit-4
- commit-5

$ git reset --hard 33b79bb(suppose commit-3)

HEAD is now at 33b79bb file3 added again

Then all 1 and 2 are commits are removed from every where

#### --mixed vs --soft vs --hard:

1. --mixed:

 - delete changes from local repo and staging area
 - It wont touch working directory.
 - Possible to revert back changes.
 
	1) git add
	
	2) git commit
	
 - working tree wont be clean

2. --soft:

 - deleted changes only from local repository.
 - It wont touch staging area and working directory
 - Possible to revert back changes.
 
	1) git commit.

 - working tree wont be clean

3. --hard:

- deleted changes from everywhere.
- not possible to revert changes.

- working tree will be clean

NOTE: If the commits are confirmed to local repository and to discard those commits
we can use git reset command.

But if the commits are confirmed to remote repository then not recommanded to use
reset command and we have to use revert command to discard the remote commits.	

### Git Aliasing:

Alias-->Nick name or other alternative name

git log --oneline===>git one

git status===>git s

If we have lengthy command then we have to use alias of git command


Q1. Create alias name 'one' to the following command
	git log --oneline

1) Test whether alias name already used or not:

git one

git: 'one' is not a git command. See 'git --help'.

The most similar commands are

        clone
        notes
	
2) Creating alias name:

  original command: git log --oneline
  
  alias:one
  
  By using 'git config' command we can define aliases
  
  Syntax:
  - git config --global alias.(aliasName) "original command" (Note while using original command dont use 'git')
	
   e.g.
    - git config --global alias.one "log --oneline"

   Result:
   
	 git one
	 60f6643 (HEAD -> master) file2 added
	 9443b15 file1 added
AND Which is same as 

 	 git log --oneline
	 60f6643 (HEAD -> master) file2 added
	 9443b15 file1 added

2) Create alias for status

      $ git config --global alias.s "status"

 NOTE:git config --global alias.ss "git status" wont work if we check for command 'ss' we get
 
	 $ ss
	 bash: ss: command not found
 AND
 
	 $ git ss
	 expansion of alias 'ss' failed; 'git' is not a git command
 
that means

 $ git git status which is not git command

#### Where these aliases will be stored??

we have a file name .gitconfig file

In linux user's home directory

	In window
	C:\Users\SHADOW(username)
	there we have file called .gitconfig
	you see like that
	[alias]
		one = log --oneline
		s = status
		ss = git status

if we change it there will be change in git bash command

Alias will work in any project untill it is configured with global

### Ignoring unwanted files and directory by using .gitignore file
How to ignore unwanted files and directory

In repository, we are saving our files.

for e.g
In locker in your house you will place valuable things like gold,cash,document but 
it is unneccessary to place kids playing toys

for e.g.

	we have files
	 Cstomer.java
	 Account.java
	 ReadME.txt
	 server.log
	 access.log

Here we have to store only source code in reposotry (1 and 2)
We can call git to ignore these files to saving to repository
Dont track these files

For this, 
We have to create a special file:

 .gitignore 
 
In our working directory

E.g

xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)
$ touch Customer.java

xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)
$ touch Account.java a.txt b.txt

xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)
$ touch .x .y

xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)
$ mkdir logs

xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)
$ touch logs/server.log logs/access.log

xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)

	$ git status
	On branch master
	Untracked files:
	  (use "git add <file>..." to include in what will be committed)
		.x
		.y
		Account.java
		Customer.java
		a.txt
		b.txt
		logs/

nothing added to commit but untracked files present (use "git add" to track)

Our mission to not to track a.txt file

xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)
$ vi .gitignore

And write only file name like a.txt to ignore it

xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)

	$ git status
	On branch master
	Untracked files:
	  (use "git add <file>..." to include in what will be committed)
		.gitignore
		.x
		.y
		Account.java
		Customer.java
		b.txt
		logs/

nothing added to commit but untracked files present (use "git add" to track)

To ignore all txt file write only '*.txt'

Ignore all hidden files
 write '.*'

If you want to ignore all file in directory use
 (directory_name)/
 
for eg
logs/

Now we can see result as

xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)

	$ git status
	On branch master
	Untracked files:
	  (use "git add <file>..." to include in what will be committed)
		Account.java
		Customer.java
		b.txt

nothing added to commit but untracked files present (use "git add" to track)

$ cat .gitignore
- Ignore a.txt file
  
  a.txt
  
- Ignore all hidden files

  .*

- Ignore logs directory

  logs/

### How git treats directories:

GIT always worry about files but not directories.

git never give any special importance for directories.

$ mkdir dir

We make one directory now let us check

	$ git status
	On branch master
	nothing to commit, working tree clean

But if we make files in dir directory then git will track it

Whenever we are adding files, then implicitly directories also added

### What is Branch and Need of Branching

Branching:

1. Important concept
2. Mandatory concept and unavailable concept in real time project

We created multiple files, did several commits are said to be in master branch.

Master branch is default branch/main branch in git.

Generally main source code we will place in master branch.

#### What is the need of creating a branch:

master branch--->for developing web application
child branch-1---> for Android compability work
child branch-2--->for iso compata=ibility work

Multiple flows==>parallel development, code base very cleanly.

##### Conclusions:

1. Once we create a branch, all files will be inherited from parent branch

   to child branch.In child branch we can create new files and we can perform
   
   any changes in existing files and we can commit those changes based on our requirement.

2. All branches are isolated to each other.The changes performed in one branch

   are not visible to other branches even to child branches.

3. Once we completed our work in child branch, we can merge that new branch with master

   branch or we can push that branch directly to the remote repository

Meaning of branch - An independent flow of development.

### Various Git commands related to branching

1. To view available branches:

git branch

$ git branch

- '*' master

- '*' indicates the current active branch(even you can use git status command)

2. To create a new branch:

git branch branch_name

git branch androidbr

$ git branch
  - androidbr
  
 - '*' master

3. How to switch from one branch to another branch:

git checkout===>To discard unstaged changes in working dir

git checkout androidbr

$ git checkout androidbr

Switched to branch 'androidbr'

$ git branch

'*' androidbr

  master

#### Shortcut way:

git checkout -b isobr

It will create iosbr and then switch to that branch

$ git checkout -b iosbr

Switched to a new branch 'iosbr'

$ git branch

  androidbr
  
'*' iosbr

  master
  
In nutshell

1. all files and commits inherited.
2. isolated to each other.
   remember the changes of child branch not inherited in parents
   And the changes in master after the child branch creataion are not inheritaed  in child

3. InSVN if we want to impliment branch we have to create a new directory   

   we have to copy all files manually, which is very difficult activity, time cosuming activity

a.) Is git creating a new directory?
- No git wont create any new directry

b) Is git copy all files from parent to child?
  No git wont copy all file from parents to child

But It is logical duplication of files.Not physically(see the difference between files of project while switching branches)

In any branch the head is pointing to last commit of that branch

NOTE: Switching from one branch to another just head pointer changes not the files and brectrioes create to seperate branch


That is why git branching wont required any efforts. It is very speedy

Branch information 
.git/refs/heads/master or(branch in which you switch)

### Multiple use cases and advantages of branching

- Multiple use cases where branching is required???

1. We required to develop a new feature
2. Hot_fixes in production
3. To support multiple  versions of same code base
   if we have bug in java version 3 so we can clone its branch and fix and push to main branch

4. To test new ideas or new technologies without effecting main code

#### Advantages of branching

1. We can enable parallel development
2. We can work one multiple flows in isolated way
3. We can organize source code in clean way
4. Implemanting new features will become very easy
5. Bug fixing will become very easy
6. Testing new ideas or new technologies will become very easy.

### Merging - Fast Forward Merge and Three Way Merge

Merging of a branch:

We created a branch to implement a new feature.
We completed implementation of that new feature.
We have to combined those changes from child branch with parent branch.
This combined process is nothing but merging concept

it merge command.

git merge childbranch(from only master branch bez master branch required these changes)

Demo Example:

make 2 commit of 2 files in master and create another branch feature and create two commit

now to merge  use - git merge feature (from master branch)

	$ git merge feature
	Updating 71c0145..d70ab11
	Fast-forward
	 x.txt | 0
	 y.txt | 0
	 2 files changed, 0 insertions(+), 0 deletions(-)
	 create mode 100644 x.txt
	 create mode 100644 y.txt

	$ git log --oneline
	d70ab11 (HEAD -> master, feature) c12f
	53f3f96 c1f
	71c0145 c2m
	9ee13f5 c1m

In this case git performs Fast-forward

- 2 types of merges:
  1. Fast-forward
  2. Three-way merge

#### Fast-forward merge:

2 branches: parent(master) And child(feature)

After creating child branch, if we are not doing any changes in parent branch,
git will perform Fast-forward merge

In the fast-forward merge, git simply moves parent branch pointer to the last
commit of child branch	

If the same file modified there may be a chance of conflicts.
In fast forward merge, there is no chance of merge conflicts because  updations happend only
in child branch but not in parent branch.

#### Three-way merge:


After creating child branch if parent branch also contains some new commits, 
3-way merge.

May be a chance of conflict

Both parent and child branches updated.

git will perform 3 way merge

Here while mergeing master and feature branch a new commit(merge commit) will be create during 3 way merge

because of this we have to commit for that so it open vim editor to commit that merge

	xSHADOWx@DESKTOP-OTH8UK2 MINGW64 ~/Desktop/project (master)
	$ git merge feature
	hint: Waiting for your editor to close the file...
	[main 2020-09-01T13:06:20.167Z] update#setState idle
	[main 2020-09-01T13:06:50.212Z] update#setState checking for updates
	[main 2020-09-01T13:06:53.916Z] update#setState downloading
	[main 2020-09-01T13:12:14.465Z] update#setState updating
	[main 2020-09-01T13:13:02.516Z] update#setState ready
	Merge made by the 'recursive' strategy.
	 x.txt | 0
	 y.txt | 0
	 2 files changed, 0 insertions(+), 0 deletions(-)
	 create mode 100644 x.txt
	 create mode 100644 y.txt

Here 'recursive' strategy mean three way merge

	$ git log --oneline
	5310216 (HEAD -> master) Merge branch 'feature' into master
	8bce090 c3m
	5cc7545 (feature) c2f
	36d06e5 c1f
	4d71307 c2m
	a393209 c1m

Here total 6 commit (5+1(means merge commit))

	$ git log --oneline --graph
	*   5310216 (HEAD -> master) Merge branch 'feature' into master
	|\
	| * 5cc7545 (feature) c2f
	| * 36d06e5 c1f
	* | 8bce090 c3m
	|/
	* 4d71307 c2m
	* a393209 c1m

### Difference between fast-forward and 3-way

#### Fast-forward

1.After creating child only child branch is modified but parent branch is not modified

2.It does not required any new commit

3.No chance of conflits.

4.It is fully handled by git

### 3-way

1.After creating child, both parent and child branches are updated

2.A new commit will be created which is also known as merge commit

3.may be chance of conflits

4.If there is conflit we have to handle manually

Note : Alternative of merge is Rebase

### Merge confilt


If the same file modified by both parent and child branches then git halts merge
process and raise conflit message.

Git will markup both brnches content in the file to resolve the conflict very easily.

We have to edit the file manually to finalize content.

We have to add to the staging area and then we have to perform commit.

#### Merge Conflits Demo examples:


$ git init

Initialized empty Git repository in C:/Users/xSHADOWx/Desktop/project/.git/

	$ echo 'First line Added' > a.txt

	$ git add a.txt;git commit -m 'c1m'
	warning: LF will be replaced by CRLF in a.txt.
	The file will have its original line endings in your working directory
	[master (root-commit) 4a819fa] c1m
	 1 file changed, 1 insertion(+)
	 create mode 100644 a.txt

	$ echo "Second line Added" >> a.txt

	$ git add a.txt;git commit -m 'c2m'
	warning: LF will be replaced by CRLF in a.txt.
	The file will have its original line endings in your working directory
	[master 487b69c] c2m
	 1 file changed, 1 insertion(+)

	$ ls
	a.txt

	$ git log --oneline
	487b69c (HEAD -> master) c2m
	4a819fa c1m


	$ git checkout -b feature
	Switched to a new branch 'feature'

	$ echo "New data added by Feature Branch" >> a.txt

	$ git add a.txt;git commit -m 'c1f'
	warning: LF will be replaced by CRLF in a.txt.
	The file will have its original line endings in your working directory
	[feature 9f8f84e] c1f
	 1 file changed, 1 insertion(+)

	$ cat a.txt
	First line Added
	Second line Added
	New data added by Feature Branch

	$ git checkout master
	Switched to branch 'master'

	$ cat a.txt
	First line Added
	Second line Added

	$ echo "New dat Added by master branch" >> a.txt

	$ git add a.txt;git commit -m 'c3m'
	warning: LF will be replaced by CRLF in a.txt.
	The file will have its original line endings in your working directory
	[master 0674cba] c3m
	 1 file changed, 1 insertion(+)

	$ git merge feature
	Auto-merging a.txt
	CONFLICT (content): Merge conflict in a.txt
	Automatic merge failed; fix conflicts and then commit the result.

	$ git status
	On branch master
	You have unmerged paths.
	  (fix conflicts and run "git commit")
	  (use "git merge --abort" to abort the merge)

	Unmerged paths:
	  (use "git add <file>..." to mark resolution)
		both modified:   a.txt

no changes added to commit (use "git add" and/or "git commit -a")

	$ cat a.txt
	First line Added
	Second line Added
	<<<<<<< HEAD
	New dat Added by master branch
	=======
	New data added by Feature Branch
	>>>>>>> feature

vi a.txt or using merge tool we have to resolve

From vi editor remove 3, 5, 7 line by using 'dd' one that line and save it

We have to add and commit it(merge commit)

	$ git add a.txt


	$ git commit -m 'Resolved Merge Conflits'
	[master f40a269] Resolved Merge Conflits
