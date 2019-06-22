# ATM Simulator
Your task is to build an ATM simulator.

Create a REST service capable of doing the following:

`POST /amount` should change the amount of the associated account. 
Here's an example of the request body:
```
{
  "account_id" : "0e8a298b-3d4e-4114-b7de-583a5dab881d"
  "amount" : 500
}
```
`GET /balance/{account_id}` should return the current balance of `account_id`, e.g.:
```
{
  "balance" : 200
}
```

There are several difficulty levels to this challenge. If the full test suite passes for a particular level, then that level is considered to be completed.

### Prerequisites for running tests
https://learning.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman/
