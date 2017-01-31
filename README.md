Jitsi
=====

Jitsi is a free open-source audio/video and chat communicator that supports protocols such as SIP, XMPP/Jabber, AIM/ICQ, IRC and many other useful features.

Helpful Resources
-----------------
- https://jitsi.org
- [Download](https://download.jitsi.org) pre-built packages
- [Mailing lists](https://jitsi.org/Development/MailingLists)
 
Submitting Issues
-----------------
Before you open an issue, please discuss it on one of our [mailing lists](https://jitsi.org/Development/MailingLists).

Contributing
------------
Please, read the [contribution guidelines](CONTRIBUTING.md) before opening a new issue or pull request.

Building hwaddressretriever lib on Raspberry Pi
-----------------------------------------------
Add libdbus-1-dev package. Of course, you'll also need default-jre, default-jdk if you don't have them installed.
Make sure you've set JAVA_HOME to `/usr/lib/jvm/default-java` in `.bashrc`

Then build the lib as follows:
```
cd src/native
ant hwaddressretriever
```

The library can be picked up from `lib/native/linux/libhwaddressretriever.so`
