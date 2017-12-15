Vivo Core staging tree 0.12.1
===============================

`master:` [![Build Status](https://travis-ci.org/vivocoin/vivo.svg?branch=master)](https://travis-ci.org/vivocoin/vivo) `v0.12.0.x:` [![Build Status](https://travis-ci.org/vivocoin/vivo.svg?branch=v0.12.0.x)](https://travis-ci.org/vivocoin/vivo/branches) `v0.12.1.x:` [![Build Status](https://travis-ci.org/vivocoin/vivo.svg?branch=v0.12.1.x)](https://travis-ci.org/vivocoin/vivo/branches)

https://www.vivocrypto.com


What is Vivo?
----------------

VIVO is an advanced, decentralized and secure digital currency. Based on Dash, it's an enhanced and further developed version, featuring the masternode technology, near-instant and secure payments as well as anonymous transactions. With a fast block time of only 2 minutes, transactions will usually confirm and be successfully processed very quickly. VIVO's blockchain uses the advanced NeoScrypt Proof-of-Work algorithm to secure the network. NeoScrypt is ASIC resistant and ensures a fair and stable return on investment for the miners.
 
Additional information, wallets, specifications & roadmap: https://bitcointalk.org/index.php?topic=2110690.0


License
-------

Vivo Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/vivocoin/vivo/tags) are created to indicate new official,
stable release versions of Vivo Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](/doc/unit-tests.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows
and Linux, OS X, and that unit and sanity tests are automatically run.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

