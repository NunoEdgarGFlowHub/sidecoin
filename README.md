## Sidecoin

[![Build Status](https://travis-ci.org/AugurProject/Sidecoin.svg?branch=master)](https://travis-ci.org/AugurProject/Sidecoin)

The sidecar to Bitcoin's motorcycle.  Sidecoin is a fork of Bitcoin v. 0.9.1.  Sidecoin allows you to take a snapshot of Bitcoin's current distribution and load it into a new blockchain.

    - P2P port: 6543 (16543 for testnet)
    - RPC port: 6544 (16544 for testnet)

Our Bitcoin [snapshot](http://augur.link/snapshotToImport.txt).

### Installation

If you're on a somewhat recent version of Ubuntu, you can install using:

    $ ./install.sh

### OS X Build Instructions

use brew to get boost

Install using:

	./autogen.sh
	sudo ./configure --with-boost=/usr/local/Cellar/boost/1.55.0_2/ --with-incompatible-bdb --with-qt
	make

Make the sidecoin directory in /Users/username/Library/Application\ Support/Sidecoin

Copy the sidecoin.conf file to that directory, also create a dir in that dir called balances and 
place the balances.txt inside that folder.

Questions?  Email Joey (joey@augur.net) or Jack (jack@augur.net).
