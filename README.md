# Node.js PayPal REST SDK

This project is a Node.js application that allows users to purchase products online using the PayPal REST SDK.

## Prerequisites

- Node.js (version 14 or higher)
- PayPal Developer Account

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/3laaElsadany/node_paypal_rest_sdk.git
   ```

2. Navigate to the project directory:

   ```bash
   cd node_paypal_rest_sdk
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

## Setup

1. Create a `.env` file in the root of the project and add the following information:

   ```bash
   PAYPAL_CLIENT_ID=your_paypal_client_id
   PAYPAL_CLIENT_SECRET=your_paypal_client_secret
   ```

   Replace `your_paypal_client_id` and `your_paypal_client_secret` with your actual PayPal credentials from your PayPal Developer account.

## Running the Application

Once the setup is complete, you can start the application using the following command:

```bash
npm start
```

The application will run on `http://localhost:3000`.

## Usage

- Visit `http://localhost:3000` to begin the checkout process.
- Follow the instructions to complete the payment through PayPal.
