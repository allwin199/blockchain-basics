Private Key: Only known to the key holder, its used to sign transactions.

Public Key: Visible to everyone. Derived using private key.

Address: Address of each account will be derived from public key. 

Message Signature: To send a transaction, sender has to sign the transaction.
message signature will be based on the data and private key but using this signature private key cannot be accessed.

Signing Transactions: A "one way" process. Someone with a private key signs the transaction by their private key being hashed with their transaction data. Anyone can verify this new transaction hash with your public key.
