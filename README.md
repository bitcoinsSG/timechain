# timechain 
> supporting material 


### requirements
access to shell and command [grep](https://en.wikipedia.org/wiki/Grep)



### replicate


occurence of the term "blockchain"

```shell
>grep -nir "blockchain" all-of-satoshis-data
```


occurence of the term "timechain"

```shell
>grep -nir "timechain" all-of-satoshis-data
all-of-satoshis-data/code/bitcoin-0.1.3-tgz/src/main.cpp:1560:        // put the main timechain first
all-of-satoshis-data/code/bitcoin-0.1.0-tgz/bitcoin/src/main.cpp:1560:        // put the main timechain first
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.h:599:// A transaction with a merkle branch linking it to the timechain
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.h:647:// to the timechain.
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.h:722:// to everyone and the block is added to the timechain.  The first transaction
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.h:919:// The timechain is a tree shaped structure starting with the
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.h:1017:void PrintTimechain();
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.h:1026:// Describes a place in the timechain to another node such that if the
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.cpp:42:uint256 hashTimeChainBest = 0;
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.cpp:876:        else if (hashPrevBlock == hashTimeChainBest)
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.cpp:893:        hashTimeChainBest = hash;
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.cpp:1094:void PrintTimechain()
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.cpp:1139:        // put the main timechain first
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.cpp:1224:        bool fIgnoreDiskConflicts = (hashPrevBlock != hashTimeChainBest);
all-of-satoshis-data/code/bitcoin-nov08-tgz/main.cpp:1241:    if (hashTimeChainBest == hash)

```


## licensing

standard MIT license


