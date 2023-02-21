# ussd-poc
PoC of a simple USSD application for mobile networks - based on Kamailio

# Kamailio Version
This PoC requires Kamailio Dev-Version, as the latest version includes functionalities to send requests within dialogs from Script - together with the patch to update CSeq numbers.
The Kamailio Version from this Branch needs to be used:
https://github.com/kamailio/kamailio/tree/carstenbock/dialog_cseq_update/src/modules

# IMS Configuration
The IMS needs to have a service profile configured, which will point the SIP Messages for USSD towards the USSD-PoC-AS.

# Demo Video
https://www.youtube.com/shorts/JIJsVIwDUX4

# References
- https://nickvsnetworking.com/failures-in-cobbling-together-a-ussd-gateway/
