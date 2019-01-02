# FLO_walletless
FLO walletless Transactions

These are client side scripts that can send FLO transactions to the blockchain

NOTE : Use respective directory/file for mainnet and testnet

## Instructions to use 

Note : open the respective html file in browser

Choose the function you require. (Click button)

There are 3 functions :
----------------------

### Address Generator
This function can generate new FLO address and secret key pair (or) recover FLO address from given secret key.
1. Click on the 'Generate New Address' button to generate FLO address and secret key pair.

    (or)
1. Click on the 'Recover FLO Address' button 
2. Enter the secret key in the prompt to recover the FLO address. 

### Send FLO Data
This function can send FLO data and transactions to the blockchain.
1. Enter the sender's address (for multiple address use comma `,`)
2. Click get balance.
3. Balance of the respective address(es) will be displayed
4. Select the address from which you want to send
5. Enter the Receiver's address
6. Enter amount 
7. Enter FLO data (if required)
8. Click Send
9. Enter the private key for the address in the prompt
10. The transaction will be sent to the blockchain and returns the txid (returns error if any).

Note : Transcation fee is set to 0.0005

### Get FLO Data
This function views the FLO data received by the given address(es).
1. Enter receiver address (for multiple address use comma `,`)
2. Enter sender address (for multiple address use comma `,`) or choose 'All' mode
3. Click getData
4. FloData received by the address(es) will be displayed

Note : There are 2 modes
1. All : display floData received from all addresses
2. Filter : display floData received from given address(es)


#### Note
Seperate files in mainnet and testnet directory can be used for specific functions alone.
