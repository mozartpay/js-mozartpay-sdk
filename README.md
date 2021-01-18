# js-mozartpay-sdk
This is a Javascript SDK for the MozartPay REST API. 

# Installation

To install the SDK on your machine, simply add the npm package, for example:

`npm i mozartpay`

Or,

`yarn add mozartpay`

example:

``` 
import { mozartpay } from "mozartpay";

// Creating an environment
const clientId = "<<Mozart-client-id>";
const clientKey = "<<Mozart-client-key>>";
const session = new mozartpay.session(clientId, clientKey);

mozartpay.order({
    "buyerName": "name of buyer",
    "amount": "2",
    "buyerEmail": "buyerEmail",
    "method": "payment method",
    "price": "34",
    "currency": "EUR"
})
```

# Include the script tag directly
Add the MozartPay.js script tag to the <head> of each page on your website, for example:
    
```

<script src="https://mozartpay.com/api/v1" async></script>

```

# MozartPay REST API
https://documenter.getpostman.com/view/9974590/TVzVjGAT
