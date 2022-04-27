# CS571 - Workshop 01
## MongoDB Rich Documents Workshop
Please find below a schema structure for a bank application, each document has the following structure for `banks` collection:
```JavaScript
{
    "_id":1,
    "name: "BOA",
    "users":[
        {"_id":1, "name": "Michael", "accounts":[
            {"_id":1, "type": "debit", "number": 123, "routing": 123, "amount": 100},
        ]}
    ]
}
```
Create an Express application that connects to a MongoDB instance (local or cloud service), and write code for 6 MongoDB queries within 6 pre-defined routes in `app.js` file:
1. Add a new account to a specific user
2. Update an account's number
3. Delete an account
  
*Note: Queries should comply with Rest design. You may use Mongoose if that's your preference.*
