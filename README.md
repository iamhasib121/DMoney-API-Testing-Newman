### DMoney-API-Testing-Newman
Automated dmoney API using Postman where test cases are added for Login, Creating users, Searching users and performed testing for CRUD operations.
 Steps to run this project:.
 - Give the following commands by opening terminal in the project folder to create newman Report:
 ```
 npm i newman
 ```
 ```
 npx newman run .\collection\DmoneyUsers.json
```
```
npm i newman-reporter-htmlextra
```
```
node .\report.js
```
 - Read the project [Documentation](https://documenter.getpostman.com/view/26615256/2s93RWMq1A).

#### Screenshot of the report generated using newman

![report using Newman](![Capture](https://user-images.githubusercontent.com/72484940/231231144-c9a6d8b9-c517-420d-bb68-960fe204ab7b.PNG))
