# Banking Application (Spring Boot)

## Project Overview

This is a RESTful Banking Application built using Spring Boot. It allows users to manage bank accounts with operations like create account, deposit, withdraw, and delete account.

## Tech Stack

* Java
* Spring Boot
* Spring Data JPA (Hibernate)
* MySQL
* Thunder Client (VS Code)

## Architecture

* Controller Layer
* Service Layer
* Repository Layer
* Entity Layer

## Features

* Create Account
* Get Account Details
* Deposit Money
* Withdraw Money
* Delete Account

## API Endpoints

| Method | Endpoint               | Description    |
| ------ | ---------------------- | -------------- |
| POST   | /api/accounts          | Create Account |
| GET    | /api/accounts/{id}     | Get Account    |
| PUT    | /api/accounts/deposit  | Deposit Money  |
| PUT    | /api/accounts/withdraw | Withdraw Money |
| DELETE | /api/accounts/{id}     | Delete Account |

## Testing

Tested using Thunder Client extension in Visual Studio Code for API validation and request handling.

## Future Improvements

* Add Authentication & Authorization
* Add Transaction History
* Implement Fund Transfer
* Add Frontend Integration

## Author

Hari Kissan G
