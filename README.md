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




