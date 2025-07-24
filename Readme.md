# Introducing AgriShield: Empowering Farmers with Innovative Technology Solutions for Optimal Farm Operations and Stable Market Access.

AgriShield is an innovative platform designed to revolutionize the agriculture sector by bridging the gap between farmers and buyers. The solution leverages **AI-driven price prediction models** to forecast crop prices up to 12 months in advance, enabling farmers to make informed decisions about crop selection and planning. 

Using **blockchain technology**, AgriShield ensures tamper-proof, transparent digital contracts that secure agreements between farmers and buyers. The platform also incorporates **dynamic pricing negotiation tools**, allowing flexibility with initial and final price adjustments to adapt to market changes, and introduces a **minimum base price** feature to guarantee farmers a stable income.

AgriShield emphasizes inclusivity with its **multi-language support** and **voice-command-enabled interface**, making the platform accessible to farmers from diverse regions and literacy levels. Additional features include real-time communication through WhatsApp, SMS, email, and live chat, **secure payment processing** via Razorpay, and quality checks with crop insurance to safeguard against natural calamities. 

By fostering transparency, market stability, and efficiency, AgriShield empowers farmers, ensures consistent buyer supply, and promotes sustainable agricultural practices.

## Live Link

https://agrishield.vercel.app

## Working Demo Video

Watch AgriShield in action:

[![AgriShield Demo](https://img.youtube.com/vi/0Azk-UR1WD8/0.jpg)](https://www.youtube.com/watch?v=0Azk-UR1WD8)

## Installation Guide

### 1. Fork & Clone the Repository

#### Fork the Repository:
Go to the repository URL and click on the Fork button to create a copy under your GitHub account.

#### Clone the Forked Repository:
In your terminal, clone the repository to your local machine:

```sh
git clone https://github.com/harshtr8/AgriShield
```
### Navigate to the Project Directory:

```sh
cd AgriShield
```
### 2. Set Up the Client (Vite)

#### Navigate to the Client Directory:

```sh
cd client
```

#### Install Dependencies:

```sh
npm install
```

#### Set up your environment variables:
Create a .env file in the backend directory and add the following variables:

```sh
VITE_GOOGLE_CLIENT_ID=<Your Google Client ID>
VITE_GOOGLE_CLIENT_SECRET=<Your Google Client Secret>
VITE_SERVER_URL=<Your Server URL>
VITE_EMAIL_JS_SERVICE_ID=<Your EmailJS Service ID>
VITE_EMAIL_JS_USER_ID=<Your EmailJS User ID>
VITE_EMAIL_JS_CONTACT_US_TEMPLATE_ID=<Your EmailJS Contact Us Template ID>
VITE_AGRISHIELD_EMAIL=<Your AgriShield Email>
VITE_RAZORPAY_KEY_ID=<Your Razorpay Key ID>
```

#### Start the Client:
Run the following command to start the client:

```sh
npm run dev
```

The client will typically be available at http://localhost:3000

### 3. Set Up the Server (Express)

#### Navigate to the Server Directory:

```sh
cd server
```

#### Install Dependencies:

```sh
npm install
```

#### Set up your environment variables:

Create a .env file in the backend directory and add the following variables:

```sh
PORT=5001
dbURL=<Your MongoDB URL>
SESSION_SECRET=<Your Session Secret Key>
COOKIE_SECRET=<Your Cookie Secret Key>
clientID=<Your Google Client ID>
clientSecret=<Your Google Client Secret>
CLOUDINARY_CLOUD_NAME=<Your Cloudinary Cloud Name>
CLOUDINARY_API_KEY=<Your Cloudinary API Key>
CLOUDINARY_API_SECRET=<Your Cloudinary API Secret>
CLOUDINARY_URL=<Your Cloudinary URL>
JWT_SECRET=<Your JWT Secret Key>
VERIFICATION_URL=<Your Verification URL>
AGRISHIELD_EMAIL=<Your Email>
AGRISHIELD_EMAIL_PASSWORD=<Your Password>
OPENCAGE_LOCATION_API_KEY=<Your OpenCage API Key>
AWS_S3_URL=<Your AWS S3 URL>
CLIENT_URL=<Your Client URL>
RAZORPAY_KEY_ID=<Your Razorpay Key ID>
RAZORPAY_KEY_SECRET=<Your Razorpay Key Secret>
```

#### Start the Server:

Run the following command to start the server:

```sh
npm run dev
```

The server will typically run on: http://localhost:5001

