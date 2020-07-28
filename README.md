PRUX-Coin integration/staging tree
=====================================

What is PRUX?
-------------
PRUX is a very fast, maybe the fastest ltc-Fork and is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Prux uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. PRUX Core is the name of open source
software which enables the use of this currency. 

For more information, as well as an immediately useable,
see https://bitcointalk.org/index.php?topic=2064953.new#new


License
-------
PRUX is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.


PRUX COIN INFORMATION
---------------------
Hash Algorithm : Scrypt
Typ : Proof-of-Work
Block Time : 9sec
Miner Reward : 0.00959499 PRUX
Actual Reward : 0.004797495 PRUX
Difficulty Retarget : 5 - 12 Hours
Mined Block Confirmation : 274
Total Supply : After 90 Years only ~104k 
Premine = ZERO


Development Process
-------------------
The `master` branch is regularly built and tested, but and is guaranteed to be
completely stable.
The contribution workflow is described in official BT-Thread


NEXT STEPS
----------
Update PRUX-Core and integrade merged mining, if somebody can help with code and testing, your welcome.
planed in 2020, but only think about.


INSTALL INFORMATION
-------------------
LINUX / UBUNTU 14.04 BUILD READ FILE HERE -------->>>>  /prux/doc/build-unix.txt


POOL LIST
---------
https://prux.mastermining.net/site/mining


EXCHANGES
---------
https://tradesatoshi.com/Exchange/?market=PRUX_BTC 


UBUNTU 14.04 BUILD NOTES
------------------------
sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update

sudo apt-get install qt4-dev-tools libqt4-dev libqt4-core libqt4-gui

sudo apt-get install build-essential

sudo apt-get install libssl-dev

sudo apt-get install libdb4.8-dev if not work try sudo apt-get install libdb-dev

sudo apt-get install libdb4.8++-dev  if not work try sudo apt-get install libdb++-dev

sudo apt-get install libqrencode-dev

sudo apt-get install libboost1.48-dev   if not work try  sudo apt-get install libboost-dev

sudo apt-get install libboost1.48-all-dev  if not work try  sudo apt-get install libboost-all-dev


BUILD
-----

cd PRUX-COIN-master

qmake "USE_UPNP=-"

make                        (or  make -j2  , 2 core or the fast way or turbo with -j8)

cd src

make -f  makefile.unix USE_UPNP=-      (or -j2  ,the fast way or turbo with -j8)


if error can help

cd src

chmod +x leveldb/build_detect_platform

again


Running
-------

./prux-qt -addnode=80.218.217.199:9595

or

src/./prux -addnode=80.218.217.199:9595


NODES
-----

addnode=80.218.217.199

addnode=50.225.198.67

addnode=62.109.27.153

addnode=78.46.18.218

addnode=78.154.170.70

addnode=50.232.104.35

addnode=109.195.103.14


Testing
-------

You are all welcome to help and improve PRUX-Core



# PRUX-Wallet
