# FLO_walletless
FLO walletless Transactions

These are client side scripts that can send FLO transactions to the blockchain

NOTE : Use respective directory for mainnet and testnet

## Instructions to use 

Note : open the respective html file in browser

1. Enter the sender's address (for multiple address use comma `,`)
2. Click get balance.
3. Balance of the respective address(es) will be displayed
4. Select the address from which you want to send
5. Enter the Receiver's address
6. Enter amount (only in FLO_sendAmt_data.html)
7. Enter FLO data (if required)
8. Click Send
9. Enter the private key for the address in the prompt
10. The transaction will be sent to the blockchain and returns the txid (returns error if any).

### FLO_sendData
This webpage sends the FLO comments (data) to the blockchain
The default amount is set to 0.002 in testnet and 0.0002 in mainnet
Transcation fee is set to 0.0005 in testnet and 0.00005 in mainnet

### FLO_sendAmt_Data
This webpage sends the FLO amount and comments (data) to the blockchain
Transcation fee is set to 0.0005 both in mainnet and testnet

### FLO_getData
This webpage views the FLO data received by the given address.
1. Enter receiver address
2. Enter sender address or choose 'All' mode
3. Click getData
4. FloData received by the address will be displayed

There are 2 modes
1. All : display floData received from all address
2. Filter : display floData received from given address
