Based on another github Repo:

    https://github.com/darconeous/docker-profile-service

which in turn is based on an Apple Demo:

    https://developer.apple.com/library/ios/documentation/NetworkingInternet/Conceptual/iPhoneOTAConfiguration/Introduction/Introduction.html

Only known to work under Ruby 2.3.

Requires these libraries/gems:

* webrick
* webrick/https
* openssl
* uuidtools
* plist

Change all instances of 34.248.222.32 to your IP address before running.

Run on command line.  Will create necessary keys and certificates and then
start listening on port 8443 and 4443.  Only port 8443 services are known
to work.  Port 4443 services apparently require a client SSL certificate.
