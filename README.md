# Cryptocurrency-assignment-Bitcoin-Wallet
Use the testnet faucet to send testnet coins to the testnet wallet’s receive address. 
Look up the transaction ID at the testnet blockchain explorer at https://www.blocktrail.com/tBTC to see if the transaction was submitted to the network. 
Be sure to receive at least one confirmation in case a double-spend attack prevented you from receiving the coins. 
The faucet may send the same coin to you in multiple different transactions, so the blockchain explorer may tell you that the coin has been double-spent. 
To find the actual transaction that successfully sent you coins, run the WalletInitTest and watch the WalletInitTest.monitor method’s periodic reporting of the transactions it receives from its peers. 
The output will tell you which transaction succeeded and which is dead.
