CSC
===

4 x 1 1/2 hour sessions

Timeline
--------

* Abstract by friday
* Deadline in jan
* Delivery in jan/feb

Rough Agenda for Continuous Delivery
------------------------------------

### Session 1 – Deployment Pipeline

* Introduction and Motivation 
 	* Discuss why we want to do continuous delivery
	* Examples - yes it can be done!
* Improving Current process 
	* value stream mapping
	* Muda – Identify waste that does not add value to the process
	* Kaisen – Don't try to fix everything at once, but foster a culture of continual improvement
* Principles
* Prerequisites
* Stages
* How to implement

#### Homework

Describe your current process as a value stream

	* identify handoffs and wait times
	* estimate the cycle time of your current process – from the idea to the time it goes live
	* identify branch and source control practices
	* How often do developers check into the source repository? 
	* How often do you merge?
	* How large is the average check in? (No of files, No of lines) 
	* How often do developers rollback, or revert changes?
	* Do defect rates spike at particular times
	* describe the team structures – are teams built around features? Around Applications?

### Session 2 – Continuous Integration & Branching

* Feature Branching
	* Late integration means conflicts
	* Everything must be re-tested close to production
	* (include slides from the end of Jez' presentation)
* Continuous Integration
	* It is a practice not a tool
	* How? (leads into...)
	* Testing 
	* Integration testing
	* Performance testing
	* AUTOMATION
* Vertical slicing
	* teams should not be working on horizontal pieces
	* Walking skeleton/Story mapping to break up releases
* Branch by Abstraction
	* feature toggles
* Integration testing
	* Consumer driven contracts for SOA

#### Homework

Consider your current process value stream from the previous homework.

	* **Muda** – Identify one wasteful thing in your process.
	* **Kaisen** – Identify one thing you could do to improve the process.

Describe your current program's approach to data management

	* Who controls schema/database changes? Is it siloed? Do developers know SQL?
	* How are required changes to schemas propagated to production? 
	* How **often** are required changes to schemas propagated to production? 

### Session 3 – Data Management

**TODO** - this seems a little light on for a 1.5 hour presentation - should we put in something else? More testing maybe?

* Database Migrations
	* Incremental database design
	* versioning your db with the code
* Tools
	* DBDeploy
	* Examples
* DB rollback strategies
	* event sourcing
	* Decoupling the DB from the app
	* backup and restore

#### Homework

Consider your data management process from the previous homework.

	* **Muda** – Identify one wasteful thing in your process.
	* **Kaisen** – Identify one thing you could do to improve the process.

Describe your current program's approach to environment and infrastructure management

	* Who controls deployments? 
	* How often are individual projects deployed? 
	* How many projects are deployed every year/month? 
	* How does the rate of deployment for an individual project relate to the number of projects that must be deployed? I.e. how busy are your ops people? What time do they deploy?

### Session 4 – Environment & Infrastructure Management

* Managing Infrastructure
	* Needs of the operations team
	* Modeling and managing infrastructure
	* Configuration
	* Virtualization
	* Cloud computing
* Managing Componenents and Dependencies
	* Feature switches
	* Managing libraries
	* Components
	* Managing dependencies
* Managing Continuous Delivery
	* Project Lifecycle
	* Risk Management
	* Common Problems
	* Compliance
	* Maturity model
* Summary and recap

Consider your environment and infrastructure process from the previous homework.

	* **Muda** – Identify one wasteful thing in your process.
	* **Kaisen** – Identify one thing you could do to improve the process.

Rough Agenda for For QA
-----------------------

The QA course - the agile one not the hands on.

He wants a focus on acceptance test driven development. 

* Structuring test suites
* What to test
	* Pyramid (mostly unit tests)
	* Scenario based tests not Acceptance tests!

