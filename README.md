# js-mozartpay-sdk
Javascript SDk for the MozartPay API


# Installation

`npm i mozartpay`

example:

import { mozartpay } from "mozartpay";

MozartPay.order({
    "buyerName": "name of buyer",
	"amount": "2",
	"buyerEmail": "buyerEmail",
	"method": "payment method",
	"price": "34",
    "currency": "EUR"
})
