# DevOps-Learning
Discover my DevOps journey with practical projects, notes, and valuable resources. This repository is your guide to real-world DevOps applications and comprehensive notes, perfect for both beginners and those looking to advance their skills.


# 3 main features of DevOps:
1: Infrastructure (Requirement like server, storage and many more which is required for the development of the software)

2: Automation: eg.  terraform 

3: Monitoring: keeping track on how application is working or like finding bugs and resolve it.

# Software Development Process Phase

1: requirement gathering and analysis

     a.	Product features
     b.	Users
     c.	Usage
     d.	User requirement
     e.	Market state and many more

2: Planning what we want to do

      a. Cost
      b. Resources 
      c. Risk

3: Design Architects

Based on the requirements the system design document is created for the developers so that there is less chances of mistakes and maintains a proper workflow

4: Development phase

Starting building the software by using the above created document

5: Testing phase

Identify the defects and bugs and resolve before deployment

6: Deployment phase

Deployed is done on the production environment

7: Operation System phase
    
To maintain the proper flow during the user experiencing the software and maintain updates and also make sure that software is up all the time

8: Maintenance phase

 Proper updates and changes required during time

# Models in SDLC:
   	Waterfall model
    AGILE
    SPIRAL 
    Etc .


# Continuous Integration:
Generates a Artifact(stored in software repo and build part of the software) they are the generated file of the build process based on the programming language.

From repository it is shifted to server to test the software
CI is used to identify defects at very early stage. It is continuous process of code, fetch, build, test, notify and feedback.

Build tools: 

    A) Maven, ANT, Gradle 
    B) MSBUILD, Visual build
    C) IBM urban code
    D) GRUNT

Software Repository to store Artifact:

    A)	SONATYPE NEXUS
    B)	JFROG ARTIFACTOTY
    C)	ARCHIVA
    D)	CLOUDSMITH PACKAGE

Continuous Integration Tools:

    A)	JENKINS
    B)	CIRCLECI
    C)	TEAMCITY
    D)	ETC.

Continuous Delivery: 

It is an automated process of code delivery to servers quickly and efficiently.  [Deployment Automation + Testing Automation]

Tools: 

ANSIBLE, PUPPET, CHEF
TERRAFORM, CFORMATION

# Virtualization

Terminologies:

1 Host OS: Our own system which is used for the virtualization and to create multiple OS or operating system of the physical machine.

2 Guest OS: operating system of the virtual machines.

3 VM: Virtual Machines

4 Snapshot: It is a way of taking backup of virtual machines

5 Hypervisor: It is used to enable virtualization

     Types of Hypervisor:
     
     Type 1 
         .1 Bare Metal
         .2 Directly runs on base OS
         .3 used only for production
         .4 Microsoft Hyper-V, oracle VM Server
    
     Type 2
     
          .1 Hosted hypervisor
          .2 Runs on software
          .3 Used for testing 
          .4 Eg: Oracle virtualbox, Vmware server

Virtual Machine Setup Process:

I have created 2 virtual machines by using Ubuntu iso and centOS iso.

It can be done either manually or could be done automatically by using Vagrant commands with many other editable functions.

# Commands of Vagrant
