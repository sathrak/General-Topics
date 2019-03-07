# General-Topics
  - Web Service
  - Software Architectural Patterns
  - Software Design Patterns

# What is Web Service?
 A Web Service is can be defined by following ways:

  - Is a client and server application or application component for communication via the World Wide Web.
    
  - Method of communication between two devices over network.
    
  - Is a software system for interoperable machine to machine communication.
    
  - Is a collection of standards or protocols for exchanging information between two devices or application.

 ## Types of Web Services
   There are mainly two types of web services.

     1. SOAP Web Services
     
     2. REST Web Services

 ## Components of Web Services
   The basic web services platform is XML + HTTP. All the standard web services work using the following components −

    1. SOAP (Simple Object Access Protocol)
    
    2. UDDI (Universal Description, Discovery and Integration)
    
    3. WSDL (Web Services Description Language)

 ## SOAP Web Services
   SOAP stands for Simple Object Access Protocol. It is a XML-based protocol for accessing web services. SOAP is a W3C recommendation for communication between two applications.

   SOAP is XML based protocol. It is platform independent and language independent. By using SOAP, you will be able to interact with other programming language applications.

  ### Advantages of Soap Web Services
   **WS Security:** SOAP defines its own security known as WS Security.

   **Language and Platform independent:** SOAP web services can be written in any programming language and executed in any platform.

  ### Disadvantages of Soap Web Services
   **Slow:** SOAP uses XML format that must be parsed to be read. It defines many standards that must be followed while developing the SOAP applications. So it is slow and consumes more bandwidth and resource.

   **WSDL dependent:** SOAP uses WSDL and doesn't have any other mechanism to discover the service.

 ## REST Web Services
   REST stands for Representational State Transfer. REST is an architectural style not a protocol.

  ### Advantages of REST Web Services
   **Fast:** REST Web Services are fast because there is no strict specification like SOAP. It consumes less bandwidth and resource.

   **Language and Platform independent:** REST web services can be written in any programming language and executed in any platform.

   **Can use SOAP:** REST web services can use SOAP web services as the implementation.

   **Permits different data format:** REST web service permits different data format such as Plain Text, HTML, XML and JSON.
 
# Web service Architecture
Every framework needs some sort of architecture to make sure the entire framework works as desired. Similarly, in web services, there is an architecture which consists of three distinct roles as given below

   **1. Provider** - The provider creates the web service and makes it available to client application who want to use it.
   
   **2. Requestor** - A requestor is nothing but the client application that needs to contact a web service. The client application can be a .Net, Java, or any other language based application which looks for some sort of functionality via a web service.
   
   **3. Broker** - The broker is nothing but the application which provides access to the UDDI. The UDDI, as discussed in the earlier topic enables the client application to locate the web service. 

The diagram below showcases how the Service provider, the Service requestor and Service registry interact with each other. 

<img src="https://github.com/sathrak/General-Topics/blob/master/Webservice1.png" width="250">
	
  **1. Publish** - A provider informs the broker (service registry) about the existence of the web service by using the broker's publish interface to make the service accessible to clients
  
  **2. Find** - The requestor consults the broker to locate a published web service
  
  **3. Bind** - With the information it gained from the broker(service registry) about the web service, the requestor is able to bind, or invoke, the web service.
  

# Software Design Patterns
   Design pattern is a general reusable solution or template to a commonly occurring problem in software design. The patterns typically show relationships and interactions between classes or objects. The idea is to speed up the development process by providing tested, proven development paradigm.
   
 #### Note:
   Design patterns give us a proven solution to existing and recurring problems.(coding design)
   
 #### Goal:
   • Understand the problem and matching it with some pattern.
   
   • Reusage of old interface or making the present design reusable for the future usage.

 #### Example:
   For example, in many real world situations we want to create only one instance of a class. For example, there can be only one active president of country at a time regardless of personal identity. This pattern is called Singleton pattern. Other software examples could be a single DB connection shared by multiple objects as creating a separate DB connection for every object may be costly. Similarly, there can be a single configuration manager or error manager in an application that handles all problems instead of creating multiple managers.

 ### Types of Design Patterns
   There are mainly three types of design patterns:
  #### 1. Creational
   These design patterns are all about class instantiation or object creation. These patterns can be further categorized into Class-creational patterns and object-creational patterns. While class-creation patterns use inheritance effectively in the instantiation process, object-creation patterns use delegation effectively to get the job done.

   Creational design patterns are Factory Method, Abstract Factory, Builder, Singleton, Object Pool and Prototype.

  #### 2. Structural
   These design patterns are about organizing different classes and objects to form larger structures and provide new functionality.

   Structural design patterns are Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Private Class Data and Proxy.

  #### 3. Behavioral
   Behavioral patterns are about identifying common communication patterns between objects and realize these patterns.

   Behavioral patterns are Chain of responsibility, Command, Interpreter, Iterator, Mediator, Memento, Null Object, Observer, State, Strategy, Template method, Visitor
   
  ##### Design patterns : singleton, repository, factory, builder, decorator, etc...
 
 References:
	https://sourcemaking.com/design_patterns
	
# Software Architectural Patterns
   These are patterns for the overall layout of your application or applications.





