Tribe Core 0.12.1
=====================

This is the official reference wallet for Tribe digital currency and comprises the backbone of the Tribe peer-to-peer network. You can [download Tribe Core](https://www.tribe.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run Tribe on your native platform.

### Unix

You need the Qt4 run-time libraries to run Tribe-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/tribe-qt (GUI, 32-bit) or bin/32/tribed (headless, 32-bit)
- bin/64/tribe-qt (GUI, 64-bit) or bin/64/tribed (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run tribe-qt.exe.

### OS X

Drag Tribe-Core to your applications folder, and then run Tribe-Core.

### Need Help?

* See the [Tribe documentation](https://tribepay.atlassian.net/wiki/display/DOC)
for help and more information.
* Ask for help on [#tribepay](http://webchat.freenode.net?channels=tribepay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=tribepay).
* Ask for help on the [TribeTalk](https://tribetalk.org/) forums.

Building
---------------------
The following are developer notes on how to build Tribe on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Tribe repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [TribeTalk](https://tribetalk.org/) forums, in the Development & Technical Discussion board.
* Discuss on [#tribepay](http://webchat.freenode.net/?channels=tribepay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=tribepay).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
