# RewardsProgram

## Sample Input JSON
The input json may contain any number of transactions for any number of users.

It will be returning the consolidated rewards report for each customer, which includes monthly rewards and total rewards they earned.

 

At the moment, I focused more on business logic and handling data sets (request and response).

Please use below Swagger URL for testing.

`http://localhost:8888/swagger-ui.html`

Sample input JSON:

[

  {

    "transactionRef": "transactionRef1",

    "customerID": "customerID1",

    "amount": 1500,

    "transactionDate": "2022-01-23"

  },  {

    "transactionRef": "transactionRef1",

    "customerID": "customerID1",

    "amount": 1500,

    "transactionDate": "2022-01-23"

  },

  {

    "transactionRef": "transactionRef2",

    "customerID": "customerID1",

    "amount": 1200,

    "transactionDate": "2022-02-23"

  },

  {

    "transactionRef": "transactionRef3",

    "customerID": "customerID1",

    "amount": 1100,

    "transactionDate": "2022-03-23"

  },

  {

    "transactionRef": "transactionRef1",

    "customerID": "customerID2",

    "amount": 1000,

    "transactionDate": "2022-01-23"

  },

  {

    "transactionRef": "transactionRef2",

    "customerID": "customerID2",

    "amount": 1000,

    "transactionDate": "2022-02-23"

  },

  {

    "transactionRef": "transactionRef3",

    "customerID": "customerID2",

    "amount": 1000,

    "transactionDate": "2022-03-23"

  }

]