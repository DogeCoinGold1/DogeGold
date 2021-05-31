Dogegold Core 0.14.2
=====================

Setup
---------------------
[Dogegold Core](http://dogegold.com/) is the reference Dogegold client and it builds the backbone of the network. However, it downloads and stores the entire history of Bitcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

Running
---------------------
The following are some helpful notes on how to run Dogegold on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/dogegold-qt` (GUI) or
- `bin/dogegoldd` (headless)

### Windows

Unpack the files into a directory, and then run dogegold-qt.exe.

### OS X

Drag Dogegold-Core to your applications folder, and then run Dogegold-Core.

### Need Help?

* See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#dogegold](http://webchat.freenode.net?channels=dogegold) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=dogegold).
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Dogegold thread](https://bitcointalk.org/index.php?topic=361813.0).

Building
---------------------
The following are developer notes on how to build Dogegold on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Dogegold repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Dogegold thread](https://bitcointalk.org/index.php?topic=361813.0).
* Discuss on [#dogegold-dev](http://webchat.freenode.net/?channels=dogegold-dev) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=dogegold-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the Bitcoin developers for use in [Dogegold Core](https://www.bitcoin.org/). 
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
