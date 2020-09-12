5G(Reloaded version) integration/staging tree
===========================


What is 5G?
----------------

5G is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. 5G uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. 5G-CASH is the name of open source
software which enables the use of this currency.

Building 5G
----------------

### Static compile

    git clone https://github.com/5G-Cash/FIVEG.git
    cd FIVEG/depends
    make HOST=x86_64-linux-gnu
    cd ..
    ./autogen.sh
    ./configure --prefix=`pwd`/depends/x86_64-linux-gnu
    make


### Shared binary

    git clone https://github.com/5G-Cash/FIVEG.git
    cd FIVEG
    ./autogen.sh
    ./configure
    make
