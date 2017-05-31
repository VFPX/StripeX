# StripeX
**Provides a wrapper for working with Stripe.com**

## IMPORTANT 3/16/17: This works with the OLD Stripe API that worked with TSL 1.0. It will not work with the current Stripe API.  If you created your Stripe account prior to 1/1/17, this should work. If you have a newer Stripe account, this will no longer work due to Stripe's security change. 

Project Manager: [Todd Landrum](mailto:todd@paladinpgm.com)

A wrapper class for working with Stripe.com. Currently supports:

* Authenticating a stripe.com connection and account
* Charging a credit card, can do different currency types. 
* Adding/updating customers, Getting cursor of customer IDs
* Working with [Code Functions](http://blog.paladinpgm.com/2015/11/17/stripe-card-functions/)
* [Plan and Subscription Functions](http://blog.paladinpgm.com/2015/12/08/stripe-plan-and-subscription-functions/)
* Working with [ChargeCard](http://blog.paladinpgm.com/2016/01/12/stripe-charge-a-card-on-file/)
