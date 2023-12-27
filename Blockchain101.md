# Blockchain Basics

https://www.youtube.com/watch?v=kHybf1aC-jE

https://techjury.net/blog/what-is-cryptographic-hash/

Hash: A unique fixed-length string, meant to identify a piece of data.
They are created by placing data into a “hash function”.

Mining: The process of finding the "solution" to the blockchain "problem".
In our example, the problem was to find a hash that starts with "0000"
Nodes get paid for mining blocks.

https://andersbrownworth.com/blockchain/

# Block:

- List of transactions mined together.

Block Id: 1

data: asasasasasasas

To mine this data to the block, we need a unique hash
In this example, we need a unique has that starts with 0000

To get a unique hash that starts with 0000, nonce will be used

Nonce: Number used only once

The validators will write a script to find out, which nonce will give a starting 0000 if we hash with blockId and data.
It will use the brute force method
starting from 1 and all the way to…. 

for the above blockid and data, to get a hash starts with 0000
nonce is “6707”

hash: 0000c423c6adc2801184c5ca1d81a8c5ec3a0c6090bd10c29177dd2f6bd21d63

# BlockChain

Block Id: 1

data: asasasasasasas

prevhash: 0000db35054df6861cfe40cf66150d33245864719e9db30263a910b37fecf3c5

To calculate unique hash that starts with 0000, we have to find a nonce based on above 3 inputs

nonce is 90908

hash: 0000b77da1dd6409b9ff8f1d0719d8577d3b782a86012476f08c60b113ff5ec1

Every block is connected to the prev block, so they are always linked
