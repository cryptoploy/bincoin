# bincoin
Bincoin Cryptocurrency
> **For Ubuntu** 
>     
>     **> Installation**
>     
>     > *cd bincoin/src*
>     **> Install Package**
>     > mkdir obj sudo apt-get install build-essential sudo apt-get install libssl-dev sudo apt-get install libboost-all-dev sudo
>     add-apt-repository ppa:bitcoin/bitcoin sudo apt-get update sudo
>     apt-get install libdb4.8-dev sudo apt-get install libdb4.8++-dev
>     sudo apt-get install qt4-qmake libqt4-dev build-essential
>     libboost-dev libboost-system-dev libboost-filesystem-dev
>     libboost-program-options-dev libboost-thread-dev libssl-dev
>     libdb++-dev libminiupnpc-dev**
>     **Building** sudo make -f makefile.unix USE_UPNP= cd .. sudo qmake sudo make
>     **Mining Config** sudo nano ~/.bincoin/bincoin.conf
>     
>         server=1
>         daemon=1
>         listen=1
>         rpcuser=anylogin
>         rpcpassword=anypass
>         rpcallowip=127.0.0.1
>         rpcallowip=192.168.1.*
>         rpcport=3333
>         port=3332
>         gen=1   **Starting**    cd ~/bincoin ./bincoin-qt -server
>     **Starting Terminal** cd ~/bincoin ./bincoin-qt -server
