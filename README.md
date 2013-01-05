HR Service Example
==================
This example shows how to automate the business process of employee onboarding
across Salesforce, GitHub and a Database using CloudHub.

1. Creating an Employee

  $ curl -d @create.json -H "Content-Type: application/json" http://YOURDOMAIN.cloudhub.io/employees
  
2. Retrieving an Employee

Go to your browser and enter:  http://YOURDOMAIN.cloudhub.io/employees?id=123