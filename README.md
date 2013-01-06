HR Service Example
==================
This example shows how to automate the business process of employee onboarding
across Salesforce, GitHub and a Database using CloudHub.

1. Deploy to CloudHub

Set the following properties:
* salesforce.username
* salesforce.password
* salesforce.securityToken
* github.username
* github.password
* mysql.host
* mysql.db
* mysql.user
* mysql.password

1. Creating an Employee

  $ curl -d @create.json -H "Content-Type: application/json" http://YOURDOMAIN.cloudhub.io/employees
  
The response will include the employee ID.

2. Retrieving an Employee

Go to your browser and enter:  http://YOURDOMAIN.cloudhub.io/employees?id=123