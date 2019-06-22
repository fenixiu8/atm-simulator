# idempotence
Your task is to create a REST service that simulates ATM functionality.

You will need to implement the following endpoints:

`POST /amount` should change the amount of the associated account. The request body will look like:
```
{
  "account_id" : "0e8a298b-3d4e-4114-b7de-583a5dab881d"
  "amount" : 500
}
```
`GET /balance/{account_id}` should return the current amount of `account_id` as JSON:
```
{
  "balance" : 200
}
```

There are several difficulty levels which are defined by test suites under `/tests`. Run one suite at a time starting with level0.

### Prerequisites for running tests
https://learning.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman/
