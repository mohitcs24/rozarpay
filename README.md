# rozarpay
Razorpay React Demo
npm react

A demo of Razorpay Node Sdk with React.js showcasing the payments and refunds scenarios:

Getting Started
git clone https://github.com/ashwamegh/razorpay-react-demo.git
cd razorpay-react-demo
Prerequisites
Get your Razorpay API keys [key_id and key_secret] for test environment variables from here, https://dashboard.razorpay.com/#/app/keys

Installation
For Frontend
Note: make sure you have added Razorpay script <script src="https://checkout.razorpay.com/v1/checkout.js"></script> in your HTML file to get the Razorpay constructor reference. For Eg: To access it using window.Razorpay or Razorpay

npm install or yarn
touch .env
Copy the contents from sample.env to .env and replace the dumb characters(xxxxx) with your Razorpay key and the Server URL, which you will be creating soon(local default is already there in the file).

npm start or yarn start
For Backend/Server
Note: Server Needed to talk with Razorpay using Node SDK

cd server
npm install or yarn
touch .env
Copy the contents from sample.env to .env and replace the dumb characters(xxxxx) with your Razorpay key and secret

Now run,

npm start or yarn start
You can goto http://localhost:8080 and try out this demo, later you can deploy the server code to server app containers like heroku, glitch, aws, etc and replace the URL in frontend's .env file with your new server URL.
