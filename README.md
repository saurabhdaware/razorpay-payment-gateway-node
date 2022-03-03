# Razorpay Payment Gateway Example

Razorpay Payment Gateway Integration with Node.js and Client

## Setup

- **Clone this repository**
- **Install dependencies**
```sh
npm install
```
- **Setup Environment Variables**
Create `.env` file on root with Razorpay tokens. Checkout [How to Create Razorpay API Keys](https://razorpay.com/docs/payments/dashboard/settings/api-keys/) to get the keys -
```sh
# .env
RAZORPAY_SECRET_KEY=<Your-razorpay-secret-key>
RAZORPAY_KEY_ID=<Your-razorpay-key-id>
```
Set the same key id in `index.html` file.
```js
const RAZORPAY_KEY_ID = ""
```
- **Start Server**
```sh
npm start
```

