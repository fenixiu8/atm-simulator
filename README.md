# idempotence
Your task is to create a REST service that will provide the following functionality:

`POST /amount` should change the amount of the associated account. The request body will look like:
```
{
	"account_id" : "0e8a298b-3d4e-4114-b7de-583a5dab881d"
	"amount" : 500
}
```
`GET /amount/{account_id}` should return the current amount of `account_id` as JSON:
```
{
	"amount" : 200
}
```

There are several difficulty levels which are defined by test suites under `/tests`. Run one suite at a time starting with level0.
