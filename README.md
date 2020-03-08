meteor-accounts-stripe
======================

stripe connect package

Allow users to connect via their stripe account.  


Atmosphere: `https://atmospherejs.com/mrt/accounts-stripe`

**This package is still functional! I just added instructions on how to use it for future users

# How to install
This uses the accounts-ui package so make sure you already have that. 

1. In your meteor project's directory, run ```meteor add mrt:accounts-stripe```
2. Start your app, head to your login page and click "Configure Stripe"
3. In the popup, fill out your ```app_id```, ```secret key```, and ```scope (read_write)```

_All of this can be found in your Stripe account_

4. Now in your stripe account go to https://dashboard.stripe.com/settings/applications and click Connect
5. Scroll down to Integration and click on **+ Add URI**

If you're running this in localhost, set the URI to ```http://localhost:3000/_oauth/stripe?close=close```
If you're running this in production, set the URI to ```https://example.com:3000/_oauth/stripe?close=close```

