
# locate.me.free

H/T to @GazChap on Twitter for the naming suggestion.

This was a simple proof of concept thrown together in an evening to demonstrate a simple, secure, means of determining someone's location.

### Background
A prominent three-word proprietary location system has attracted a lot of attention on Twitter and elsewhere and a video was widely circulated showing a real world case where a 999 Call Handler;

* Asked the caller their location
* Sent them a link to download an app
* Had them download an ~112Mb app over 3G
* Install the app and then open it
* Read (verbally) a three word location which research has shown could be easily misheard or confused with another
* The operator enters this location on their application and it is converted to GPS location.

There has to be a better way.

#### Other Commercial Solutions
There is an excellent web-based third party service used by some Mountain Rescue Trusts, but then I saw a tweet where the _company who provide this service_ commented on an incident suggesting they'd "seen a location in this area" 

**Why is a location service provider providing services to the emergency services monitoring what locations are being requested?** 

### A Privacy-First Approach
WebRTC enables secure, _peer-to-peer_ transfer of data between browsers, no party in the middle needs to process, or even be aware of how the service is used or where the user is.

I recognise, however, that support for WebRTC in mobile browsers is still limited so this isn't a viable solution (yet) 

## Proof of Concept 
This code is very much a proof of concept, it's not particularly pretty, or efficient, and probably has bugs in it but it shows just how trivial it is to do this in an objectively better way. 

I'll probably develop it a bit time permitting :) 
