# Angular_cheat_sheet
# Starting a New Angular Project
Before starting a new project, Node.js must be installed on your machine. Next, Angular has an official CLI tool for managing projects. It can be installed with NPM(Node Package Manager)

![image](https://github.com/user-attachments/assets/bc631011-b7bd-40fd-ac33-79fadeed2462)
# check version
ng v
# Afterward, we can create a new project with the following command:
ng new my-app or ng new my-app --no-standalone(it is Automaticaly decalre in module.ts file and dependency feature)
# You can run a project with either command:
ng serve or ng serve --port 5001
# Creating Components(it is building block to develope specific functionlity on html template and each component define a class that contain app data and logic)
![image](https://github.com/user-attachments/assets/5d7506e1-f77e-48e5-bf76-04eda83ae4ff)
# Angular will generate the component files
componet.html
component.css
component.ts(it contain all the logic variable of the app)
component.spec.ts(for testing purpose)
# Services
Services are objects for outsourcing logic and data that can be injected into our components
![image](https://github.com/user-attachments/assets/b790ca17-f713-4958-9198-cf57f3ffdd25)
# package.json(all about project information/details)
# node_modules(all libiraries inside this folder)
# how to make component, service, module and header
ng g c mycomponent
#
ng g s myservice
#
ng g modules mymodules
#
ng g header myheader
# Four Types of Data Binding in Angular 
![image](https://github.com/user-attachments/assets/629461cf-f833-4200-bf0b-421af5dd7df3)
# interpolation
Interpolation is a way to use the properties in the component’s TypeScript class within the HTML template.
![image](https://github.com/user-attachments/assets/d16113c3-a8fd-49e4-b895-8be2d47a553a)
![image](https://github.com/user-attachments/assets/335fd64d-6edd-43ce-b799-f8f43604c9a5)
# Property Binding
Property Binding is a one-directional and helps us pass the value of HTML properties from the component class to the HTML template that renders them
![image](https://github.com/user-attachments/assets/56f4e57f-2d73-4e4b-9ad2-6a5262fbbd7f)

# Binding in Angular
Binding in Angular is used to define values of HTML properties and events using class members.  



![image](https://github.com/user-attachments/assets/c733a55f-9835-4429-ab6f-da8e9e1e88a2)
![image](https://github.com/user-attachments/assets/ece703b6-5a84-43f8-8b13-57d249fbc42b)



