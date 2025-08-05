Private Key: Only known to the key holder, its used to sign transactions.

Public Key: Visible to everyone. Derived using private key.

Address: Address of each account will be derived from public key. 

Message Signature: To send a transaction, sender has to sign the transaction.
message signature will be based on the data and private key but using this signature private key cannot be accessed.

Signing Transactions: A "one way" process. Someone with a private key signs the transaction by their private key being hashed with their transaction data (ECDSA is used). Anyone can verify this new transaction hash with your public key.


Address is derived using the public key
public key is derived using private key with the help of ECDSA

-----------------------

How a new account gets created in the metamask

1. Metamask takes the menmonic(Secret Phase) and then add a number
<secret phase> + 0 => hash will be generated.
2. This hash will act as the private key for the new account created.
3. From this private key, public key will be derived
4. From the public key, address will be derived

-----------------------------

Therfore,

Secret Phase is very important, next
Private key is important
