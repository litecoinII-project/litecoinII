LitecoinII Core
=============

Setup
---------------------
LitecoinII Core is the original LitecoinII client and it builds the backbone of the network. It downloads and, by default, stores the entire history of LitecoinII transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download LitecoinII Core, visit [litecoinII.org](https://litecoinII.org/).

Running
---------------------
The following are some helpful notes on how to run LitecoinII Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/litecoinII-qt` (GUI) or
- `bin/litecoinIId` (headless)

### Windows

Unpack the files into a directory, and then run litecoinII-qt.exe.

### macOS

Drag LitecoinII Core to your applications folder, and then run LitecoinII Core.

### Need Help?

* See the documentation at the [LitecoinII Wiki](https://litecoinII.info/) for help and more information.
* Ask for help on [#litecoinII](https://webchat.freenode.net/#litecoinII) on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#litecoinII).
* Ask for help on the [LitecoinIITalk](https://litecoinIItalk.io/) forums, in the [Technical Support board](https://litecoinIItalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build LitecoinII Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The LitecoinII repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.bitcoincore.org/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [LitecoinIITalk](https://litecoinIItalk.io/) forums.
* Discuss general LitecoinII development on #litecoinII-dev on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#litecoinII-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
