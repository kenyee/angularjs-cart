angularjs-cart
==============

AngularJS Shopping Cart forked from [Bernado Castilho's sample
on Code Project](http://www.codeproject.com/Articles/576246/A-Shopping-Cart-Application-Built-with-AngularJS) so I could add
Stripe.js support to it.

Changes
-------
* Switched to Visual Studio 2012
* Added support for Stripe.js

Blogged about the [changes needed for Stripe support](http://www.keysolutions.com/blogs/kenyee.nsf/d6plinks/KKYE-993K3H).

Usage
-----
Update app.js with your Paypal/Google/Stripe tokens/IDs to use this in your application.

For Stripe.js, change the chargeurl parameter so it points to a form processing handler on your web site that [commits the charge](https://stripe.com/docs/tutorials/charges).  Stripe is different than Paypal/Google in that it's a two-step process that's similar to an OAuth login.

