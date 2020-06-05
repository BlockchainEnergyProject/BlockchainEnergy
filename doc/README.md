Blockchainenergy Core
=============

Setup
---------------------
[Blockchainenergy Core](http://blockchainenergy.org/wallet) is the original Blockchainenergy client and it builds the backbone of the network. However, it downloads and stores the entire history of Blockchainenergy transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run Blockchainenergy Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/blockchainenergy-qt` (GUI) or
- `bin/blockchainenergyd` (headless)

### Windows

Unpack the files into a directory, and then run blockchainenergy-qt.exe.

### macOS

Drag Blockchainenergy-Qt to your applications folder, and then run Blockchainenergy-Qt.

### Need Help?

* See the documentation at the [Blockchainenergy Wiki](https://github.com/Blockchainenergy-Project/Blockchainenergy/wiki)
for help and more information.
* Ask for help on [BitcoinTalk](https://bitcointalk.org/index.php?topic=1262920.0) or on the [Blockchainenergy Forum](http://forum.blockchainenergy.org/).
* Join our Discord server [Discord Server](https://discord.blockchainenergy.org)

Building
---------------------
The following are developer notes on how to build Blockchainenergy Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Blockchainenergy repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://www.fuzzbawls.pw/blockchainenergy/doxygen/)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=1262920.0) or the [Blockchainenergy](http://forum.blockchainenergy.org/) forum.
* Join the [Blockchainenergy Discord](https://discord.blockchainenergy.org).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
