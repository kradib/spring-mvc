# Spring MVC Project

## Concepts
### MVC a a design pattern
- MVC as design pattern: model, view, controller
  - input logic -> controller
  - business logic -> model or data
  - UI -> view

* Model
  - Representation of Application data and business logic
  - POJOs, service class, interaction with database

* View
  - Responsible for rendering the UI
  - Typically implemented in JSP

* Controller
  - Handles user input
  - process the incoming requests, manipulates the model and selects which view to render

* Advantages
1. Separation of concerns(input logic, business logic, UI)
2. Flexible
3. Easy to test
4. Integration with other spring libraries (specific to Spring MVC)

## Steps of building a spring MVC project

1. Create DispatcherServlet or Font controller
2. Create Spring config for IOC
3. Create(Inject) view resolver
4. Create controller 
5. Create views
6. Create models



## Set up
1. Create a maven project with arch type web-app
2. Download and install Tomcat server as Spring MVC does not include any server
3. Add spring mvc dependency 
4. Run your webapp on tomcat server, by default `index.jsp` would be rendered on your context path