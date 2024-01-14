# Backend-Ecommerce
E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

Your challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.


## Installation

### FIRST Clone repo to destinaton.

### Install dependencies using:

```bash
npm install
```

Rename the `.env.EXAMPLE` file to `.env`. Update with your credentials.

```bash
DB_NAME=databasename #replace with the database name
DB_USER=yourusername # replace with your user name
DB_PW=yourpassword # replace with your password
```

### Database 

Log in to MySQL, and use the following command to set up database:

```bash
source db/schema.sql
```

In a terminal, run the following command to seed the database:

```bash
npm run seed
```

## Usage

From the root directory, run the following to start the application:

```bash
npm run start
```

Use Insomnia to GET, POST, PUT, and DELETE on the routes (categories, products, tags).

## Demo
### [Walkthrough Video]()