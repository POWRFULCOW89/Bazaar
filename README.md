# Bazaar!

**Bazaar!** is a marketplace platform that provides centralized services for item purchase and sale, collaborating with the users to create an environment of value to safely carry out transactions.

## Vision
The project to develop will be a marketplace, with the purpose of allowing users to buy and sell second-hand items within the platform. Seller users can then offer their products to said users, in a safe and trustworthy environment.

## Project scope

- To establish a marketplace platform with two main actors: the Buyer and the Seller users, which can interact over the course of a transaction.
- To browse listed items without the need to log in.

## Out of scope

- Chat functionality within the platform.
- Payment handling.

### Project requirements

#### Users

- *Buyer*: Logged in User inside Bazaar! that can browse for listings of their interest and formalize a transaction, as well as leave reviews on their purchase.
- *Seller*: Logged in User inside Bazaar! that can manage their contact info and publish new articles for sale; generating a catalog that can then be browsed by other users.
- *Anonymous user*: Non-authenticated user that can browse the main catalogs and perform queries on them.

#### User stories

- As a buyer, I wish to be able to look for articles and preview general information about them.
- As a buyer, I would like to make purchases of items published by other users.
- As a buyer, I would like to see my past purchases.
- As a seller, I want to list items for sale
- As a seller, I wish for potential buyers to see my products.
- As a seller, I want to make my reputation and that of my articles public.
- As a seller, I want to update already listed items.
- As a seller, I would like to review my sales history.

#### UML diagram

![UML diagram](https://user-images.githubusercontent.com/85530193/132103493-b09c2e41-1776-4ab9-ae4b-1c036afee826.jpg)

#### Install

1. Clone the repo:

  ```sh
  gh repo clone POWRFULCOW89/Bazaar
  ```

2. Install dependencies and run the API:

  ```sh
  cd bazaar-api && npm i && npm start
  ```
  
3. Start the front end project:

  ```sh
  cd .. && cd bazaar-front && npm i && npm start
  ```

#### API Documentation

The Bazaar API documentation can be consulted in the [API_spec.txt](bazaar-api/API_spec.txt) file, and can be visualized using any previewer compatible with Open API 3.

#### The team

- [Antonio Labra Guerrero](https://github.com/its7ony)
- [Ian Axel Cuevas Olvera](https://github.com/axelcoevas)
- [David Dorantes Torres](https://github.com/Madadeivi)
- [Diego Domínguez Melo](https://github.com/POWRFULCOW89)
- [Rogelio Magaña Tapia](https://github.com/MaganaRogelio)
