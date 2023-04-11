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
 - Read the project [Documentation](https://documenter.getpostman.com/view/21091753/2s93CHuEyq).

#### Screenshot of the report generated using newman

![report using Newman]([Capture](https://user-images.githubusercontent.com/72484940/231229881-6efcaaed-f663-4094-949d-032d3fbba707.PNG)
