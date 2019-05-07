# Geartron 1.0, developed by 韓哈斯 and 江祿檠
A Blockchain-based cryptocurrency repository. This blockchain is based off the proof of work consensus mechanism.

Problem description: https://hackmd.io/s/SJEuT2NvE#%E5%8D%80%E5%A1%8A%E6%A8%99%E9%A0%AD-Block-Headers

Compilation (provisional): g++ main.cpp Block.cpp Blockchain.cpp sha256.cpp -o geartron

* TODO:
  * Create miner client separate from Blockchain
  * Create server-client classes for P2P


* The material that we referenced for this project includes the following.
  * Basic blockchain example (partial derivation): https://github.com/teaandcode/TestChain
  * SHA-256 Algorithm: https://github.com/QuantumMechanics/Kraken/blob/master/sha256.cpp
  * This is a very useful reference for creating P2P structure: https://github.com/tko22/simple-blockchain
  * We use this library for reading and writing to JSON files: https://github.com/nlohmann/json
