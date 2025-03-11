# Posts

## Description
This project is a GraphQL-based application that utilizes Prisma for database management. It provides a GraphQL API for interacting with the underlying data model.

## Features
- GraphQL API with Prisma as ORM
- Node.js backend
- Uses Babel for ES6+ support
- Dependency management with Yarn/NPM
- Configured with `.graphqlconfig` for GraphQL tools

## Installation
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or later recommended)
- [Yarn](https://yarnpkg.com/) or npm

### Steps
1. Clone the repository:
   
   ```sh
   git clone <repository-url>
   cd GraphQLProject/server
   ```
3. Install dependencies:
   
   ```sh
   yarn install
   # or
   npm install
   ```
5. Setup Prisma:
    ```sh
   npx prisma migrate dev --name init
   ```
6. Start the development server:
     ```sh
    yarn start
   # or
   npm run start
   ```
