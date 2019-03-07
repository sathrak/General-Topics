# General-Topics

# Advantages of GraphQL:

### GraphQL is declarative: 
   Query responses are decided by the client rather than the server. A GraphQL query returns exactly what a client asks for and no more.

### GraphQL is compositional: 
   A GraphQL query itself is a hierarchical set of fields. The query is shaped just like the data it returns. It is a natural way for product engineers to describe data requirements.

### GraphQL is strongly-typed: 
  A GraphQL query can be ensured to be valid within a GraphQL type system at development time allowing the server to make guarantees about the response. This makes it easier to build high-quality client tools

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
   
# software architectural patterns
   These are patterns for the overall layout of your application or applications.



## What are Web Services?
   Web Services are client and server applications that communicate over the World Wide Web's (WWW) Hypertext Transfer Protocol (HTTP). As described by the World Wide Web Consortium (W3C), web services provide a standard means of interoperating between software applications running on a variety of platforms and frameworks.
   
   Web Services can be looked as a code on demand. Just like we call functions and methods, web services can be looked upon as calling a function or method over the internet using some sort of protocols and some agreements.
 
   A web service is a function or method which we can call by sending an HTTP request to a URL, with arguments and the service returns the result back as response.
   
   The biggest advantage of the web services is that it is platform independent.
   
   
## Types of Web Services
### Some types of web services:
1. SOAP Web Services (Simple Object Access Protocol.)
2. REST Web Services (Representational State Transfer)
3. WSDL (Web Services Description Language)
   
   
```HTML
<table class="MsoTableGrid" style="border-collapse: collapse; border: none; mso-border-alt: solid windowtext .5pt; mso-padding-alt: 0in 5.4pt 0in 5.4pt; mso-yfti-tbllook: 1184;" cellspacing="0" cellpadding="0" border="1">
 <tbody>
<tr>
  <td style="border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<b><span style="color: red; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">S.No<o:p></o:p></span></b></div>
</td>
  <td style="border-left: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<b><span style="color: red; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP<o:p></o:p></span></b></div>
</td>
  <td style="border-left: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<b><span style="color: red; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">REST<o:p></o:p></span></b></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">1<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP is a <strong>protocol</strong>.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">REST is an <strong>architectural style</strong>.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">2<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP stands for <strong>Simple Object Access Protocol</strong>.<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">REST stands for <strong>REpresentational State Transfer</strong>.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">3<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP <strong>can't use REST</strong>
  because it is a protocol.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">REST <strong>can use SOAP</strong> web
  services because it is a concept and can use any protocol like HTTP, SOAP.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">4<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP <strong>uses services interfaces to expose
  the business logic</strong>.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">REST <strong>uses URI to expose business logic</strong>.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">5<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP <strong>defines standards </strong>to
  be strictly followed.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">REST does not define
  too much standards like SOAP.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">6<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP <strong>defines standards </strong>to
  be strictly followed.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">REST does not define
  too much standards like SOAP.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">7<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP <strong>requires more bandwidth</strong>
  and resource than REST.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">REST <strong>requires less bandwidth</strong>
  and resource than SOAP.<span style="color: red;"><o:p></o:p></span></span></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">8<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP <strong>defines its own security</strong>.<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">RESTful web services <strong>inherits security measures</strong>
  from the underlying transport.<o:p></o:p></span></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">9<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP <strong>permits XML</strong> data
  format only.<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><table class="MsoNormalTable" cellpadding="0" border="0">
   <tbody>
<tr>
    <td style="padding: .75pt .75pt .75pt .75pt;"></td>
    <td style="padding: .75pt .75pt .75pt .75pt;"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;;">REST permits different data format such as Plain text, HTML, XML,
    JSON etc.<o:p></o:p></span></div>
</td>
   </tr>
</tbody></table>
<div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;"><o:p></o:p></span></div>
</td>
 </tr>
<tr>
  <td style="border-top: none; border: solid windowtext 1.0pt; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 35.9pt;" width="48" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">10<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 212.5pt;" width="283" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">SOAP
  is <strong>less preferred</strong>
  than REST.<o:p></o:p></span></div>
</td>
  <td style="border-bottom: solid windowtext 1.0pt; border-left: none; border-right: solid windowtext 1.0pt; border-top: none; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt; padding: 0in 5.4pt 0in 5.4pt; width: 3.2in;" width="307" valign="top"><div class="MsoNormal" style="margin-bottom: 0.0001pt;">
<span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;;">REST <strong>more preferred</strong> than
  SOAP.</span><span style="font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;;"><o:p></o:p></span></div>
</td>
 </tr>
</tbody></table>
```

   
