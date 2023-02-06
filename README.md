# JAIKISAN--BAckEnd


## Available Scripts

- Install Dependencies First

### `npm install`


- In the project directory, you can run:

### `npm start`

```
# Run BackEnd Port :3001
```



## Problem Statement:

```yaml

Create two API’s which can perform the specified CRUD operations.The project structure should
have models, middlewares, controllers and services. Write MongoDB queries to fetch, update,
add or delete data from the specified collections. You can assume that the collections already
exist in the database and just define the project structure.

```

## Models:

### Customer collection field:
```yaml
firstName: string
lastName: string
mobileNumber: string (10 digits long)
DOB: date
emailID: string (e.g. abc@xyz.com)
address: string
customerID: string (UUID)
status: string (ACTIVE / INACTIVE)
```

### Card collection field:
```yaml
cardNumber: string (Auto_increment e.g: C001)
cardType: String ([REGULAR/SPECIAL])
customerName: string
status: string ([ACTIVE/INACTIVE] Default: ACTIVE)
vision: string
customerID: string (Reference from customer table)
```

## APIs Info:

### Customer API:
1. Get all customers List with status ACTIVE [GET]
2. Delete customer. [DELETE]
3. Create new customer [POST]

### Card API:
1. Get all Card List[GET]
2. Create new card [POST]
