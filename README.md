Airin Core 
=================================================

<p align="center">
  <img src="https://raw.githubusercontent.com/sambuca911/greenstrawberrycoin/master/doc/bitcoin_logo_doxygen.png" width="256" />
</p>




Airin is a cryptocurrency, and development platform which enables shared multi-nodes in larger high marketcap coins.


Airin is currently a hybrid Proof of Stake (POS), and Masternode (MN) coin. The Platform is being built to feature shared multinodes in larger well known established projects.  Investors without large amounts of capital will be able to use the platform to connect with huge projects currently paying out coins equivalent to thousands of U.S. Dollars per month. In addition, those who wish to participate at higher levels can purchase a full Airin Masternode.
The Airin development team is active, and goal oriented.  The community is able to participate, along with the developers, in the progress of Airin through very active Discord, Twitter, and Telegram accounts. The community is to be involved in matters involving the further development of the platform, especially in the adding of new shared masternodes. The Airin team believes in a steady flow of news just like you do.

## Links:

- Website: https://airin.cc/
- White paper: https://airin.cc/Airin_white_paper_v_1_0_1.pdf
- Explorer: http://explorer.airin.cc/
- Twitter: https://twitter.com/airincoin
- Instagram: https://www.instagram.com/airincoin/
- Github: https://github.com/airincoin
- Telegram#1: https://t.me/airinofficial
- Telegram#2: https://t.me/airingroup


License
-------

Airin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/airincoin/airin/tags) are created to indicate new official,
stable release versions of Airin Core.

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