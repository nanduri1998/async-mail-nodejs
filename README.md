#   Async Node.js Email Send
Send email asynchronously using Node.js

##  Create a .env file
Define the following code:
```dotenv
NODE_ENV=development
email="YOUR_EMAIL"
password="YOUR_PASSWORD"
api="YOUR_API_LINK"
from="YOUR_FROM_EMAIL/NAME"
subject="EMAIL_SUBJECT"
```
*Note: This is only for GMAIL. HTML/Text must be edited in code*


*Note: API must return array as shown below*
```json
[
    "abc@xyz.com",
    "abc@pqr.com"
]
```
##  Execute
Run the following command with list of emails send as an array from the API Link defined in the .env file.
`npm start`

##  Limits
Depends on the server capability. Can be used on Heroku.