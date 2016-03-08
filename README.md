#genereateSecretOffline

#Proposed Features

Generate a key-pair offline using RippleAPI.

Allow users to record key-pair by navigating to an HTML webpage when offline.  

#Current Usage

This package allows a user to generate a ripple secret offline using their web browser's console.

Initial commit fails to provide output of a key-pair, an issue has been raised 
[here](https://forum.ripple.com/viewtopic.php?f=2&p=72445#p72445) on the official ripple forum.

#Instructions:

    Right click and Inspect
    Navigate to the console
    Input api.generateAddress().secret then press enter
    Record your secret offline
