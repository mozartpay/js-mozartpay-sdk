# js-mozartpay-sdk
Javascript SDk for the MozartPay API


# Installation

To install the SDK on your machine, simply add the npm package, for example:

`npm i mozartpay`

Or,

`yarn add @sentry/browser`

example:

``` 
import { mozartpay } from "mozartpay";

MozartPay.order({
    "buyerName": "name of buyer",
    "amount": "2",
    "buyerEmail": "buyerEmail",
    "method": "payment method",
    "price": "34",
    "currency": "EUR"
})
```
