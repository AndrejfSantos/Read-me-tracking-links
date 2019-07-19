# Readme for Tracking links

Implementing a standard so Trackers can read the reason why a tracking link isnt redirecting correctly.

All you need to do is ad a 'readme' parameter with the reason of why the link isnt redirrecting correctly.

For Example if your offer has a whitelist and send the offer to the store directly instead of a tracker when the source is not part of the whitelist like this:

https://play.google.com/store/apps/details?id=jp.co.ncjapan.lineagem&hl=ja

you could add the reason when sending to the store, like this:

https://play.google.com/store/apps/details?id=jp.co.ncjapan.lineagem&hl=ja&readme=whitelist

That way the user that is testing the offer will also know that the reason for this redirect is the "whitelisted" , tools like OfferTest will be able to display this information and notify the user.
This will make the publishers that you want aware and will prevent them from stop sending traffic because they think the offer is broken.

Other possible examples include "Capped offer", "blocked subid" or "wrong target".
