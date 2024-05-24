# angular_questions

# 1. Explain what Angular is.

Angular (also referred to as "Angular 2+") is a TypeScript-based, free and open-source single-page web application framework run on Node.js. 
It is led by the Angular Team at Google and by a community of individuals and corporations. 
Angular is a complete rewrite from the same team that built AngularJS. 
Angular ecosystem consists of a diverse group of over 1.7 million developers, library authors, and content creators.

![image](https://github.com/dades1986/angular_questions/assets/29290099/679f781a-b7c1-4b72-842c-a121c07451f0)


## C/C Google designed Angular as a ground-up rewrite of AngularJS.

# 2. Which skills are required to use Angular?

To know that HTML, CSS, JavaScript, and (of course) Angular knowledge are vital skills required to use Angular?
To be aware that TypeScript and Angular Command Line Interface knowledge is also important.

# 3. Which soft skills do Angular developers need?

Some of the crucial soft skills required to be a skilled Angular developer include empathy, 
time management, communication, and attention to detail.
Teamwork is also vital for Angular developers

# 4. Explain the kind of data binding that Angular deploys.

# 5. Explain how Angular is different from AngularJS.

- Google designed Angular as a ground-up rewrite of AngularJS.
* Angular does not have a concept of "scope" or controllers; instead, it uses a hierarchy of components as its primary architectural characteristic.
+ Angular has a different expression syntax, focusing on "[ ]" for property binding, and "( )" for event binding
+ Modularity – much core functionality has moved to modules
+ Angular recommends the use of Microsoft's TypeScript language, which introduces the following features:
  -  Static typing, including Generics
  - Type annotations
  - Dynamic loading
  - Asynchronous template compilations
  - Iterative callbacks provided by RxJS.
  - Support to run Angular applications on servers.


# 6. Explain what a decorator is in Angular.


In Angular, a decorator is a special kind of declaration that can be attached to a :
   - class
   -  method
   -  property
   -  or parameter

   Decorators provide a way to add metadata to these structures, which can then be used by Angular to configure and enhance their behavior.

   Decorators are extensively used in Angular to define various aspects of components, directives, services, and other building blocks of an Angular application.

1. Syntax:
   - Decorators are denoted by the '@' symbol followed by an identifier.
   - Examples: @Component, @Directive, @Injectable, etc.

2. Metadata:
   - Decorators attach metadata to classes, methods, properties, or parameters.
   - This metadata provides information to Angular about how to process and use the associated structure.

3. Role in Angular:
   - Decorators are crucial for Angular's:
        - dependency injection system
        - template compilation
        - and component lifecycle management.
   - They define :
     - component metadata
      -  inject dependencies
      -  specify template and style information
      -   handle events
      -    etc.

4. Built-in Decorators:
   - Angular provides built-in decorators such as:
    
**_1. __@NgModule__: Defines and configures Angular modules.

2. __@Component__: Defines a component along with its metadata.

3. __@Directive__: Declares a directive along with its metadata.

4. __@Pipe__: Marks a class as a pipe for transforming data within a template.

5. __@Injectable__: Marks a class as available to the Angular dependency injection system.

6. __@Input__: Defines an input property for a component or directive.

7. __@Output__: Defines an output property for a component or directive.

8. __@HostBinding__: Binds a host element property to a directive or component property.

9. __@HostListener__: Listens to events on the host element of the directive or component.

10. __@ViewChild__: Queries a single child component, directive, or element within the view of a component.

11. __@ViewChildren__: Queries multiple child components, directives, or elements within the view of a component.

12.__@ContentChild__: Queries a single projected content child within the host component.

13. __@ContentChildren__: Queries multiple projected content children within the host component.

14. __@Host__: Defines that a directive should inject the host element.

15. __@Self__: Restricts the scope of a dependency resolution to a single element.

16. __@SkipSelf__: Skips the current element and tries to resolve a dependency from a parent element.

17. __@Optional__: Specifies that a dependency is optional during injection.

18. __@Attribute__: Injects an attribute value from the host element.

19. __@NgModuleRef__: Injects a reference to the current NgModule.

20. __@ComponentRef__: Injects a reference to the current component.

21. __@PipeMetadata__: Injects metadata about the pipe being instantiated._**


5. Custom Decorators:
   - Custom decorators can be created to encapsulate reusable behavior or apply additional logic to classes, methods, or properties.

6. Use Cases:
   - Decorators are extensively used in Angular applications for defining component and directive metadata, configuring dependency injection, applying styles and templates, handling events, etc.

### 7. Describe some benefits of using Angular.
- Modular Architecture: Angular allows breaking down applications into smaller, reusable components, promoting code reusability and maintainability.
- Two-way Data Binding: Angular's two-way data binding feature synchronizes the model state with the view, simplifying development.
- Dependency Injection: Angular's dependency injection system manages components and their dependencies, enhancing code organization.
- MVVM Architecture: Angular follows the MVVM pattern, separating concerns between the presentation layer and application logic.
- Cross-platform Development: With tools like NativeScript or Ionic, Angular enables cross-platform mobile app development.
- Powerful CLI: Angular CLI offers tools for creating, building, testing, and deploying applications, enhancing productivity.
- Strong Community: Angular has a large community, extensive documentation, and a rich ecosystem of third-party libraries.

### 8. Explain what a template is in Angular.
In Angular, a template is an HTML file that contains the view part of the application. It includes Angular-specific markup and directives, allowing developers to define the structure and layout of the user interface.

### 9. Explain what annotations are in Angular.
Annotations in Angular are decorators used to modify the behavior of classes or their members. They provide metadata that Angular uses to understand how to process and instantiate classes.

### 10. Explain what directives are in Angular.
Directives in Angular are markers on a DOM element that tell Angular's HTML compiler (`$compile`) to attach a specified behavior to that DOM element or even transform the DOM element and its children.

### 11. Define AOT compilations.
AOT (Ahead-of-Time) compilation is the process of compiling Angular application code during the build phase, rather than at runtime in the browser. This results in smaller bundle sizes, faster startup times, and improved security.

### 12. Describe some benefits of using AOT compilations.
Benefits of using AOT compilation in Angular include smaller bundle sizes, faster startup times, improved runtime performance, and enhanced security by detecting template errors early in the development process.

### 13. Explain what a component is in Angular.
In Angular, a component is a building block of an application that encapsulates the data, logic, and view. It consists of a TypeScript class with a template and metadata, defining the behavior and appearance of a UI element.

### 14. Explain what pipes are in Angular.
Pipes in Angular are a feature that allows transforming data in templates before displaying it in the view. They are used to format, filter, or manipulate data, providing a convenient way to customize the display output.

### 15. Explain what the PipeTransform interface is.
The PipeTransform interface in Angular is a built-in interface that defines a transform method. Custom pipes implement this interface to perform data transformations in Angular applications.

### 16. Explain what Pure Pipes are.
Pure Pipes in Angular are pipes that are stateless and immutable. They are re-evaluated only when the input value or its reference changes, optimizing performance by reducing unnecessary recalculations.

### 17. Explain what Impure Pipes are.
Impure Pipes in Angular are pipes that maintain internal state and may have side effects. They are re-evaluated on every change detection cycle, potentially impacting performance.

### 18. Explain what an ngModule is.
In Angular, an NgModule is a class with the @NgModule decorator that defines a cohesive block of code with related components, directives, pipes, and services. It helps organize and configure the application's functionality.

### 19. Explain what Angular filters are.
Angular filters are a feature that allows formatting and manipulating data before rendering it in the view. They provide a way to modify the presentation of data without changing the underlying model.

### 20. What is the Angular date filter?
The Angular date filter is a built-in filter that formats dates according to the specified format string. It allows displaying dates in various formats such as short date, long date, time, etc.

### 21. What is the inbuilt Angular Json filter?
The inbuilt Angular JSON filter is used to format JSON objects for display in the view. It converts JavaScript objects or arrays into JSON strings, making them human-readable.

### 22. What is the limitTo Angular filter?
The limitTo Angular filter is used to limit the number of items displayed in an array or string. It takes a numeric argument to specify the maximum number of items to display.

### 23. What is the lowercase Angular filter?
The lowercase Angular filter is used to convert a string to lowercase format in the view. It transforms all characters of the string to lowercase letters.

### 24. Explain what view encapsulation is in Angular.
View encapsulation in Angular refers to the mechanism of isolating styles defined in a component's template from affecting other components. It ensures that styles are scoped to the component, preventing unintended style leakage.

### 25. Explain what Angular controllers are.
Angular controllers are JavaScript functions that contain application logic and interact with the view and model components of an Angular application. They manage the data flow between the view and the model.

### 26. Explain what scope means in Angular.
In Angular, scope refers to the context in which variables are accessible within an application. It acts as a glue between the controller and the view, providing data binding and event handling.

### 27. Explain what lifecycle hooks are in Angular.
Lifecycle hooks in Angular are predefined methods that allow developers to tap into the lifecycle of Angular components and perform actions at specific stages, such as initialization, content projection, and destruction.

### 28. Explain what String Interpolation means in Angular.
String interpolation in Angular is a way to bind data from the component to the view template. It uses double curly braces (`{{ }}`) to embed expressions or variables into HTML templates, dynamically updating the content.

### 29. Explain what a Template statement is in Angular.
A Template statement in Angular is an expression or code snippet that is evaluated in response to an event triggered in the template. It allows executing actions or updating data based on user interactions.

### 30. Name a disadvantage of using Angular.
One disadvantage of using Angular is its steep learning curve, especially for beginners. The framework's complexity and the frequent updates may require significant time and effort to master.

### 31. Explain what DOM means.
DOM stands for Document Object Model. It is a programming interface for web documents that represents the structure of HTML and XML documents as a tree of nodes. The DOM allows scripts to dynamically access and manipulate the content, structure, and style of web pages.

### 32. How is jQuery different from Angular?
jQuery is a JavaScript library primarily focused on DOM manipulation and simplifying client-side scripting, whereas Angular is a comprehensive front-end framework for building single-page web applications. Angular provides features like two-way data binding, dependency injection, and component-based architecture, which jQuery does not inherently offer.


# 33. Architecture of an Angular application, services, and dependency injection
![image](https://github.com/dades1986/angular_questions/assets/29290099/59b21f7b-cf7d-4a95-a763-2e1d32d7afd8)

# 34. Describe some benefits of using Angular.
We should know that Angular’s strength is that it enables developers to write clean code that’s easy to maintain.
We should be aware that Angular provides reusable components and data binding and offers modules that make application creation smoother.

