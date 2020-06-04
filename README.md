- I built this tool so I could see how the logs for each of the steps in the Auth and Capture process shows up in the Stripe Dashboard. 
- The server for this tool can be found in https://github.com/petrussola/first_netlify_serverless
- Create a config.js file that will containg your publishable key for Stripe:

const config = {
	pk_stripe: '{ADD_YOUR_STRIPE_PUBLISHABLE_KEY_HERE}',
};

- Click on each button in order to activate the step. The result will print in red beneath it.
- You can use the Stripe testing cards from https://stripe.com/docs/testing
- Based on Stripe's new-ish Payment Intents API, fully SCA-ready
