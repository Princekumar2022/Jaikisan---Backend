# Jaikisan---Backend

Available Scripts
Install Dependencies First
npm install
In the project directory, you can run:
npm start
# Run BackEnd Port :3001
Problem Statement:
Create two API’s which can perform the specified CRUD operations.The project structure should
have models, middlewares, controllers and services. Write MongoDB queries to fetch, update,
add or delete data from the specified collections. You can assume that the collections already
exist in the database and just define the project structure.
Models:
Customer collection field:
firstName: string
lastName: string
mobileNumber: string (10 digits long)
DOB: date
emailID: string (e.g. abc@xyz.com)
address: string
customerID: string (UUID)
status: string (ACTIVE / INACTIVE)
Card collection field:
cardNumber: string (Auto_increment e.g: C001)
cardType: String ([REGULAR/SPECIAL])
customerName: string
status: string ([ACTIVE/INACTIVE] Default: ACTIVE)
vision: string
customerID: string (Reference from customer table)
APIs Info:
Customer API:
Get all customers List with status ACTIVE [GET]
Delete customer. [DELETE]
Create new customer [POST]
Card API:
Get all Card List[GET]
Create new card [POST]