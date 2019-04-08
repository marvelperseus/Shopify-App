# Shopify-App

Make sure that you first complete these setup instructions:
 1. Install the latest stable version of Node.js.
 2. Install npm packages (run: npm install).
 3. Expose your dev environment.
 4. Get a Shopify API key and Shopify API secret key.
 5. Add the Shopify API key and Shopify API secret key.
 6. Start your app (run: npm run dev).

# Tools
- Node
- React
- Next.js
- GraphQL
- Apollo
- Polaris

# Get Started

1. Expose your dev environment
- npm install ngrok -g
- ngrok http 3000
2. Get a Shopify API key and Shopify API secret key
- From your Shopify Partner Dashboard, click Apps.
- Click Create app.
- Copy the HTTPS version of the forwarding URL from your ngrok terminal tab
- Give your app a name. For example, Sample embedded app.
- Paste the HTTPS version of your ngrok forwarding URL into the App URL field.
- Paste the same HTTPS forwarding URL into the Whitelisted redirection URL(s) field and add /auth/callback to the end of the path.
3. Add the keys and temporary placeholder to the .env file.
4. Packages Install
- npm install
5. Run server
- npm run dev
6. Authenticate and test your app.
- Add the HTTPS version of your ngrok forwarding URL and your store’s URL to the following placeholder and load it in a browser
    HTTPS://YOURNGROKADDRESS.io/auth?shop=YOURSHOPIFYSTORE.myshopify.com
- Click the Install unlisted app button.
