# Readme for Tracking links

Implementing a standard so Trackers can read the reason why a tracking link isnt redirecting correctly.

All you need to do is ad a 'readme' parameter with the reason of the block. 

Example:
https://readme.offertest.net?redirectUrl=http%3A%2F%2Fplay.google.com%2Fstore&readme=This%20Offer%20Is%20Whitelisted

This link will redirect to http://play.google.com%2Fstore but the user will also know that the reason for this redirect is that "This Offer Is Whitelisted" , tools like OfferTest will be able to display this information.
