# matrix-paywall

A way to charge for matrix services (bridges, bots, etc) without implementing payment processing in each application. This is intended to be used by bridges who require payment processing or homeserver owners who wish to offer paid services, such as [matrix-appservice-twilio](https://github.com/turt2live/matrix-appservice-twilio).

# Discontinued

This project is not being implemented due to concerns that it can't feasibly be done. Instead, bridges are encouraged to process payments on their own or rely on integration managers.

# Features (that aren't implemented at all)

* [ ] NodeJS library to interact with a paywall instance
* [ ] Payment handling (provider?)
* [ ] Alternative billing model support (pre-pay, post-pay, pay for usage, etc)
