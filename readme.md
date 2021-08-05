CONTENTS OF THIS FILE
---------------------
* Introduction
* Description
* Requirements

Introduction
------------
This is a programming exercise to create web based REST microservice using Spring-Boot, a framework used to develop web java application. 

Description
-----------
* A REST-based web service that provides resources about students and professors is developed using Spring framework  
* This REST service connects to a local mySQL database using Hibernate, a object relational mapping (ORM) framework.
	- The database is configured in hibernate.cfg.xml
	- Classes are annotated using @Entity, @Column, @Table, @Id, @Generated
	- Dependencies are included in pom.xml 
* HTTP verbs including GET, POST and PUT are used to read, create and update entries. 
* This REST service allows the following operations:
	- Create new entities (e.g. student, professor)
	- Retrieve existing entities by specifying a search parameter: id
	- Retrieve all entries of an entity  
	- Update address of existing student entries
	- Update email of existing professor entries
* REST APIs response in JSON

Requirement
-----------
No modules or packages outside the project are required.
