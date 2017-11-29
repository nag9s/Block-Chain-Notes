_Merkle tree _ are Hashes of Hashes, they have the advantage that you can verify only a subtree. Ethereum uses  [Modified Merkle Patricia Tries](https://github.com/ethereum/wiki/wiki/Patricia-Tree)  for transactions \(as well as for state and transaction receipts\).

what about  _Patricia _? What does a  _trie _ mean? And how is it used in Ethereum?

**Trie \(also called digital tree, prefix trie or radix trie\)**

An ordered tree data structure that is used to store a dynamic set or associative array where the keys are usually strings. A node's position in the tree defines the key with which it is associated.

![](/assets/trie1.png)

![](/assets/pat.png)



**Merkle Patricia Trie**

As described [here](https://easythereentropy.wordpress.com/2014/06/04/understanding-the-ethereum-trie/), the term Merkle implies that

> the root node becomes a cryptographic fingerprint of the entire data structure



