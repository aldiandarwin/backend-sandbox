# Project Title: Payment Gateway Backend

This is the backend repository for the Payment Gateway project. The backend is built using Express.js, Prisma ORM, and integrates with MySQL database and the Midtrans sandbox for payment processing.

## Tech Stack

Express.js

A fast, unopinionated, minimalist web framework for Node.js.

Prisma ORM

A modern database toolkit for TypeScript and Node.js.

MySQL

A popular relational database management system.

Midtrans Sandbox

A third-party payment gateway for handling transactions.

## Getting Started

Clone the repository:

bash

```Copy code
git clone  <https://github.com/aldiandarwin/backend-sandbox.git>
```

cd payment-gateway-backend

Install dependencies:

bash

```Copy code
npm install
```

Set up the environment variables:

Create a .env file in the root of the project and add the following configuration:

env

```Copy code
PORT=8000
DATABASE_URL="mysql://yourid/password:@localhost:3306/db"
MIDTRANS_APP_URL="https://app.sandbox.midtrans.com"
MIDTRANS_API_URL="https://app.sandbox.midtrans.com"
MIDTRANS_SERVER_KEY="yourserverkey"
FRONT_END_URL="http://localhost:5173"
```

Run the server:

bash

```Copy code
npm start
```

The server will run on <http://localhost:8000>.

### Credits

Special thanks to Prawito Hudoro, a senior developer and content creator on YouTube. He has provided excellent tutorials on the technologies used in this project. You can find his content on his YouTube channel: Prawito Hudoro's YouTube Channel <https://www.youtube.com/@prawitohudoro>
