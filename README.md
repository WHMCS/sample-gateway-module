# WHMCS Sample Third Party Payment Gateway Module #

## Summary ##

Payment Gateway modules allow you to integrate payment solutions with the WHMCS
platform.

There are two types of gateway module:

* Third Party Gateways - these are payment solutions where checkout occurs
on a remote website, usually hosted by the payment gateway themselves.

* Merchant Gateways - these are payment solutions where credit card details
are collected - usually within the WHMCS application, though more and more
often this will be done remotely, typically via an iframe, with a page hosted
remotely by the payment gateway enabling tokenised storage.

The sample files here demonstrate how we suggest a Third Party Payment Gateway
module for WHMCS be structured and implemented.

For more information, please refer to the documentation at:
http://docs.whmcs.com/Gateway_Module_Developer_Docs

## Recommended Module Content ##

The recommended structure of a third party gateway module is as follows.

```
 modules/gateways/
  |- callback/gatewaymodule.php
  |  gatewaymodule.php
```

## Minimum Requirements ##

For the latest WHMCS minimum system requirements, please refer to
http://docs.whmcs.com/System_Requirements

We recommend your module follows the same minimum requirements wherever
possible.

## Useful Resources
* [Developer Resources](http://www.whmcs.com/developers/)
* [Hook Documentation](http://docs.whmcs.com/Hooks)
* [API Documentation](http://docs.whmcs.com/API)

[WHMCS Limited](http://www.whmcs.com)
