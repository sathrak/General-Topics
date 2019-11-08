                              # Angular@7 #
                      
## What,Why, use in (google)angular Js?
  - Angular 7 is an open source JavaScript framework.
  - Angular is the most stable and most popular javascript based platform now-a-days.
  - Building web applications and apps.
    * Web developer
    * Web app developer
    * UI developer
    * UX developer
    * Front-end developer
    * JavaScript developer
  - Use JavaScript, html, and Typescript which is a superset of JavaScript.
  - Angular is a modern MVVC framework and platform that is used to build enterprise Single-page Web Applications (or SPAs) using HTML and TypeScript. Angular is written in TypeScript
  
## Angular Features(build-in) 
  - Angular provides built-in features for animation, http service, and materials which in turn have features such as auto-complete, navigation, toolbar, menus, etc.
  - The code is written in Typescript, which compiles to JavaScript and displays the same in the browser.
  
## Applications of Angular 7
   1. Google Supported Community - Google actively supports Angular and its development. Angular is used in various Google Apps.
   2. POJO based development - Angular heavily used Plain Old JavaScript Object and it helps in learning Angular in an easier way.
   3. Declarative User Interface - Angular uses HTML as view language and extends its functionality. It helps in handling UI vs code differentiation and UI is loosely coupled with code.
   4. Typescript - Typescript is super set of javascript and is easy to debug. It is highly secure and is object oriented.
   5. Modular Structure - Angular development is highly modular, is component based and is highly maintainable.
   6. Multi-platform support - Angular code works well on all platforms without much change in code.
   
## Angular Update to V7
    - Angular 7 is a major release where in the angular core framework, Angular CLI, Angular Materials are updated.
    - The version of Angular Material/CDK is updated in Angular 7. Also there are 2 features added to CDK − virtual scrolling, and drag and drop.
    
## Update Command - ng update @angular/cli @angular/core

## Environment Setup required for Angular 7. To install Angular 7, we require the following −
   1. Nodejs(8.x or 10.x)
   2. Npm(5.6 or 6.5)
   3. Angular CLI
   4. IDE for writing your code

## installations - Open CMD and type the below command
    - npm install –g @angular/cli
    - ng new <Application Name>
    - cd <Application Name>
    - ng serve --host 0.0.0.0 --port 8800
    - ng version (Chech the angular version and installation)
    
## Folder Structure & File Structure

  We will consider the angular7-app project. Let us open the angular7-app and see how the folder structure looks like.
    https://www.tutorialspoint.com/angular7/images/angular7_app.jpg
    
  ### The angular7-app/ folder has the following folder structure−
  
    1. e2e/ − end to end test folder. Mainly e2e is used for integration testing and helps ensure the application works fine.

    2. node_modules/ − The npm package installed is node_modules. You can open the folder and see the packages available.

    3. src/ − This folder is where we will work on the project using Angular 7.Inside src/ you will app/ folder created during the project setup and holds all the required files required for the project.
    
  ### The angular7-app/ folder has the following file structure −

    1. angular.json − It basically holds the project name, version of cli, etc.

    2. .editorconfig − This is the config file for the editor.

    3. .gitignore − A .gitignore file should be committed into the repository, in order to share the ignore rules with any other users that clone the repository.

    4. package.json − The package.json file tells which libraries will be installed into node_modules when you run npm install.
    
    5. tsconfig.json − This basically contains the compiler options required during compilation.

    6. tslint.json − This is the config file with rules to be considered while compiling.

    The src/ folder is the main folder, which internally has a different file structure.
    
## app - Folder Structure :
    It contains the files described below. These files are installed by angular-cli by default.
    
    app  
      app.module.ts
      app.component.html
      app.component.spec.ts
      app.component.ts
      app-routing.module.ts
    Assets              - You can save your images, js files in this folder.
    
    Environment         - This folder has details for the production or the dev environment.The folder contains two files.
      environment.prod.ts
      environment.ts
      
    favicon.ico         - This is a file that is usually found in the root directory of a website.
    
    index.html          - This is the file which is displayed in the browser.
                          <html lang = "en"> 
                             <head>
                                <meta charset = "utf-8"7gt;
                                <title>Angular7App</title> 
                                <base href = "/">
                                <meta name = "viewport" content = "width=device-width, initial-scale=1"> 
                                <link rel = "icon" type = "image/x-icon" href = "favicon.ico"> 
                             </head> 
                             <body> 
                                <app-root></app-root> 
                             </body> 
                          </html>
                          
    main.ts             - It starts with importing the basic module which we need. Right now if you see angular/core,     
                          angular/platform-browser-dynamic, app.module and environment is imported by default during angular-cli 
                          installation and project setup.
    
    polyfill.ts         - This is mainly used for backward compatibility.
    
    styles.css          - This is the style file required for the project.
    
    test.ts             - The unit test cases for testing the project will be handled.
    
    tsconfig.app.json   - This is used during compilation, it has the config details that need to be used to run the application.
    
    tsconfig.spec.json  - This helps maintain the details for testing.
    
    typings.d.ts        - It is used to manage the Typescript definition.
    
    
## Angular7 - Component :
    ### What Is an Angular Component?
         Components are the most basic building block of an UI in an Angular application. An Angular application is a tree of Angular 
         components. Angular components are a subset of directives. Unlike directives, components always have a template and only 
         one component can be instantiated per an element in a template.

        Components are defined using the @component decorator. A component has a selector, template, style and other properties.

        The file structure has the app component and it consists of the following files −
            app.component.css
            app.component.html
            app.component.spec.ts
            app.component.ts
            app.module.ts

        And if you have selected angular routing during your project setup, files related to routing will also get added and the files are as follows −
            app-routing.module.ts

    ### angular-cli has a command to create your own component.     
        ng g component new-cmp

      ```
      > ng generate component nav
      // output

      > ng g c about
      // output

      > ng g c contact
      // output

      > ng g c home
      // output ```

## Angular7 - Modules :
    ### What is a Angular js Modules?
       In Angular, a module is a mechanism to group components, directives, pipes and services that are related, in such a way that  
       can be combined with other modules to create an application.

       To define module, we can use the NgModule.   
          import { NgModule } from '@angular/core';

      #### The structure for the ngmodule is as shown below −
          @NgModule({ 
             declarations: [
                AppComponent, 
                NewCmpComponent 
             ],
             imports: [ 
                BrowserModule, 
                AppRoutingModule 
             ], 
             providers: [], 
             bootstrap: [AppComponent] 
          })

        @NgModule and contains an object which has declarations, imports, providers and bootstrap.

            Declaration - It is an array of components created.

            Import - It is an array of modules required to be used in the application.

            Providers - This will include the services created.

            Bootstrap - This includes the main app component for starting the execution.

    
## Angular7 - Data Binding :

    We use curly braces for data binding - {{}}; this process is called interpolation.

    ### What is interpolation in Angular JS?
        Interpolation markup with embedded expressions will provide data-binding to text nodes and attribute values. The AngularJS allows the user to manually run the template compilation. Interpolation allows us to live update a string of text based upon conditions of a scope, for instance.

    ### app.component.ts
          import { Component } from '@angular/core';
          @Component({
             selector: 'app-root', 
             templateUrl: './app.component.html', 
             styleUrls: ['./app.component.css'] 
          }) 
          export class AppComponent { 
             title = 'Angular 7'; 

             // declared array of months. 
             months = ["January", "February", "March", "April", "May", "June", "July", 
                "August", "September", "October", "November", "December"]; 

             isavailable = true; //variable is set to true 
          }

    ### app.component.html
          <div style = "text-align:center"> 
             <h1> Welcome to {{title}}. </h1> 
          </div>

          <div> Months : 
             <select> 
                <option *ngFor="let i of months">{{i}}</option>
             </select> 
          </div> 
          <br/>

          <div> 
             <span *ngIf = "isavailable; then condition1 else condition2">
                Condition is valid.
             </span> 
             <ng-template #condition1>Condition is valid</ng-template> 
             <ng-template #condition2>Condition is invalid</ng-template> 
          </div>
      
      
## Angular7 - Event Binding :

    ### What is a Event Binding?
       When a user interacts with an application in the form of a keyboard movement, a mouse click, or a mouse over, it generates an event. These events need to be handled to perform some kind of action.


    ### app.component.ts
          myClickFunction(event) {
            //just added console.log which will display the event details in browser on click of the button.
            alert("Button is clicked");
            console.log(event);
         }

         changemonths(event) {
            console.log("Changed month from the Dropdown");
            console.log(event);
         }

    ### app.component.html
           <select (change) = "changemonths($event)">
                <option *ngFor = "let i of months">{{i}}</option>
           </select>

          <button (click) = "myClickFunction($event)">
             Click Me
          </button>
          
          Event Listing :
            (focus)="myMethod()"
            (blur)="myMethod()" 
            (submit)="myMethod()"  
            (scroll)="myMethod()"

            (cut)="myMethod()"
            (copy)="myMethod()"
            (paste)="myMethod()"

            (keydown)="myMethod()"
            (keypress)="myMethod()"
            (keyup)="myMethod()"

            (mouseenter)="myMethod()"
            (mousedown)="myMethod()"
            (mouseup)="myMethod()"

            (click)="myMethod()"
            (dblclick)="myMethod()"

            (drag)="myMethod()"
            (dragover)="myMethod()"
            (drop)="myMethod()"
      
## Angular7 - Templates :
    Angular 7 uses the <ng-template> as the tag instead of <template>which is used in Angular2. <ng-template> has been in use 
    since the release of Angular 4 , and the earlier version i.e Angular 2 uses <template> for the same purpose
   
    ### <template> to <ng-template> This was one of the major changes made in Angular 4 version.
   
   
    ### The templates are to be called as follows −
        <ng-template #condition1>Condition is valid from template</ng-template> 
        <ng-template #condition2>Condition is invalid from template</ng-template>

    ### app.component.ts    
       myClickFunction(event) { 
        this.isavailable = !this.isavailable; 
        // variable is toggled onclick of the button 
       } 

    ### app.component.html 
       <div> 
         <span *ngIf = "isavailable; else condition2">
            Condition is valid.
         </span>
         <ng-template #condition1>Condition is valid from template </ng-template> 
         <ng-template #condition2>Condition is invalid from template</ng-template> 
      </div>

     <button (click) = "myClickFunction($event)">Click Me</button>
     
## Angular7 - Directives :
    Directives are instructions in the DOM. They specify how to place your components and business logic in the Angular.

    Directives are js class and declared as @directive. There are 3 directives in Angular.
      ### Component Directives
      ### Structural Directives
      ### Attribute Directives

    Component Directives: Component directives are used in main class. They contain the detail of how the component should be processed, instantiated and used at runtime.

    Structural Directives: Structural directives start with a * sign. These directives are used to manipulate and change the structure of the DOM elements. For example, *ngIf and *ngFor.

    Attribute Directives: Attribute directives are used to change the look and behavior of the DOM elements. For example: ngClass, ngStyle etc.
    
    
## Angular 7 Pipes :
    In Angular 1, filters are used which are later called Pipes onwards Angular2. In Angular 7, it is known as pipe and used to transform data. It is denoted by symbol |.
    
    ### Use the pipe symbol in component.html file:
        <h1>  
           {{ title | uppercase }} <br/></h1>  
        <h1>  
          {{ title | lowercase }} <br/></h1>  
    
    ### Angular 7 provides some built-in pipes:
        Lowercasepipe
        Uppercasepipe
        Datepipe
        Currencypipe
        Jsonpipe
        Percentpipe
        Decimalpipe
        Slicepipe

## Angular7 - Routing :
    Routing basically means navigating between pages. You have seen many sites with links that direct you to a new page. This can be achieved using routing. Here the pages that we are referring to will be in the form of components. 
    
        import { NgModule } from '@angular/core'; 
        import { Routes, RouterModule } from '@angular/router'; 
        import { HomeComponent } from './home/home.component'; 
        import { ContactusComponent } from './contactus/contactus.component';

        const routes: Routes = [ 
           {path:"home", component:HomeComponent}, 
           {path:"contactus", component:ContactusComponent} 
        ];
        @NgModule({ 
           imports: [RouterModule.forRoot(routes)], 
           exports: [RouterModule] 
        })
        export class AppRoutingModule { }
    
    The array of components i.e., RoutingComponent is imported in app.module.ts
      @NgModule({ 
         declarations: [ 
            SqrtPipe,
            AppComponent, 
            NewCmpComponent, 
            ChangeTextDirective, 
            RoutingComponent 
         ]

## Angular7 - Services :
    We might come across a situation where we need some code to be used everywhere on the page.
    we can access methods and properties across other components in the entire project.
    
    ### To create a service, we need to make use of the command line as given below −
        ng g service myservice
        
        C:\projectA7\angular7-app>ng g service myservice 
        CREATE src/app/myservice.service.spec.ts (348 bytes) 
        CREATE src/app/myservice.service.ts (138 bytes)
        
    ### myservice.service.ts
          import { Injectable } from '@angular/core';
          @Injectable({
             providedIn: 'root' 
          }) 
          export class MyserviceService {
             constructor() { }
          }
          
      Here, the injectable module is imported from the @angular/core. It contains the @Injectable method and a class called MyserviceService.
          
          import { MyserviceService } from './myservice.service';
            @NgModule({ 
               declarations: [
                  SqrtPipe, 
                  AppComponent, 
                  NewCmpComponent, 
                  ChangeTextDirective, 
                  RoutingComponent 
               ], 
               imports: [ 
                  BrowserModule, 
                  AppRoutingModule
               ], 
               providers: [MyserviceService], 
               bootstrap: [AppComponent] 
            })
            export class AppModule { }
      
## Angular7 - Http Client:
    HttpClient will help us fetch external data, post to it, etc. We need to import the http module to make use of the http service.
