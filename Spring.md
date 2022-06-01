##Spring
1.What is a Spring Framework?
It is light-weighted and loosely coupled.
It has layered architecture, which allows you to select the components to use, while also providing a cohesive framework for J2EE application development.
Spring framework is also called the framework of frameworks as it provides support to various other frameworks such as Struts, Hibernate, Tapestry, EJB, JSF etc.
******************************************************************
 2.List the advantages of Spring Framework.
Because of Spring Frameworks layered architecture, you can use what you need and leave which you don’t.
Spring Framework enables POJO (Plain Old Java Object) Programming which in turn enables continuous integration and testability.
JDBC is simplified due to Dependency Injection and Inversion of Control.
It is open-source and has no vendor lock-in.
*************************************************************
3. What are the different features of Spring Framework?
Following are some of the major features of Spring Framework :

Lightweight: Spring is lightweight when it comes to size and transparency. 
Inversion of control (IOC): The objects give their dependencies instead of creating or looking for dependent objects. This is called Inversion Of Control.
Aspect oriented Programming (AOP): Aspect oriented programming in Spring supports cohesive development by separating application business logic from system services.
Container: Spring Framework creates and manages the life cycle and configuration of the application objects.
MVC Framework: Spring Framework’s MVC web application framework is highly configurable. Other frameworks can also be used easily instead of Spring MVC Framework.
Transaction Management: Generic abstraction layer for transaction management is provided by the Spring Framework. Spring’s transaction support can be also used in container less environments.
JDBC Exception Handling: The JDBC abstraction layer of the Spring offers an exception hierarchy, which simplifies the error handling strategy.
************************************************************************************************************************************
6. What is a Spring configuration file?
A Spring configuration file is an XML file. This file mainly contains the classes information. It describes how those classes are configured as well as introduced to each other. The XML configuration files, however, are verbose and more clean. If it’s not planned and written correctly, it becomes very difficult to manage in big projects.

*****************************************************************************************

7.What are the different components of a Spring application?
A Spring application, generally consists of following components:

Interface: It defines the functions.
Bean class: It contains properties, its setter and getter methods, functions etc.
Spring Aspect Oriented Programming (AOP): Provides the functionality of cross-cutting concerns.
Bean Configuration File: Contains the information of classes and how to configure them.
User program: It uses the function.
**********************************************************************************************

8. What are the various ways of using Spring Framework?
Spring Framework can be used in various ways. They are listed as follows:
As a Full-fledged Spring web application.
As a third-party web framework, using Spring Frameworks middle-tier.
For remote usage. 
As Enterprise Java Bean which can wrap existing POJOs (Plain Old Java Objects)

**************************************************************************
9. What is Spring IOC Container?
At the core of the Spring Framework, lies the Spring container. The container creates the object, wires them together, configures them and manages their complete life cycle. The Spring container makes use of Dependency Injection to manage the components that make up an application. The container receives instructions for which objects to instantiate, configure, and assemble by reading the configuration metadata provided. This metadata can be provided either by XML, Java annotations or Java code.
********************************************************************************************
10. What do you mean by Dependency Injection? 
In Dependency Injection, you do not have to create your objects but have to describe how they should be created. You don’t connect your components and services together in the code directly, but describe which services are needed by which components in the configuration file. The IoC container will wire them up together.

****************************************************************************************************************************************
11. In how many ways can Dependency Injection be done?
In general, dependency injection can be done in three ways, namely :

Constructor Injection
Setter Injection
Interface Injection
*********************************************************************************************
13. How many types of IOC containers are there in spring?
BeanFactory: BeanFactory is like a factory class that contains a collection of beans. It instantiates the bean whenever asked for by clients.
ApplicationContext: The ApplicationContext interface is built on top of the BeanFactory interface. It provides some extra functionality on top BeanFactory.
****************************************************************************************************************************************


15.  List some of the benefits of IoC.
Some of the benefits of IoC are:

It will minimize the amount of code in your application.
It will make your application easy to test because it doesn’t require any singletons or JNDI lookup mechanisms in your unit test cases.
It promotes loose coupling with minimal effort and least intrusive mechanism.
It supports eager instantiation and lazy loading of the services.

*******************************************************************************************************


https://enos.itcollege.ee/~jpoial/allalaadimised/reading/Spring-Interview-Questions.pdf
