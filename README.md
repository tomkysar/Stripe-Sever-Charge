# Stripe-Server-Charge

A Stripe charge example using a PHP server side script.

# Installing

Requires the Stripe PHP library.

```
pip install stripe
```

Send a POST request to the script from your client with the customers email, and authorization token generated by Stripe in your client. You must have error and success destinations for handling the response, and enter your API key into charge.php.
