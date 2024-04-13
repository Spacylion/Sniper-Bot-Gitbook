# 🔄 Unwrap FETH to ETH

### Unwrapping FETH to ETH

1. Your balances of **ETH** and **FETH**, along with the associated chain, will be displayed.
2. Select **“Unwrap X FETH to ETH”** to initiate the unwrapping process.
3. Enter the amount of **FETH** you want to convert to **ETH**. Alternatively, you can select one of the predefined percentages (**25%, 50%,** or **100%**) to quickly set the amount of **FETH** you wish to unwrap.
4. Confirm your selection to complete the unwrapping process.

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption><p>Unwrap FETH to ETH execution transcation</p></figcaption></figure>

This feature allows you to easily manage and convert your funds within the Sniper wallet.

#### ⚠️<mark style="color:yellow;">`Important`</mark>

Unwrapping FETH to ETH consists of two transactions:

1. **Burn FETH** - This initial step marks the reduction of your FETH balance in the blockchain.
2. **Final Unwrap** - Completes the process by converting the burned FETH into ETH in your wallet.

## Burn FETH

The burning and conversion of FETH to ETH are automatically handled by the Sniper bot. Once you initiate the Burn FETH transaction:

* The Sniper bot processes this transaction through the Facet Virtual Machine (VM), where your FETH is burned.
* Following this, the bot automatically engages the minting process, crediting ETH to your wallet.

### Transaction receipt

After the transaction is successfully processed, you will receive a detailed receipt containing the following information:

* **Transaction Hash (TxHash):** A unique identifier for your transaction on the blockchain.
* **Links to View Transaction:**
  * [FacetScan](https://facetscan.com)
  * [Etherscan](https://etherscan.io)
* **Block Number:** The specific block on the blockchain in which your transaction was recorded.
* **Gas Spent:**
  * Ether (ETH) amount.
  * Equivalent USD value (according to [CoinMarketCap](https://coinmarketcap.com/)).

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption><p>Initial Unwrap FETH to ETH</p></figcaption></figure>

#### ⚠️<mark style="color:yellow;">`Important`</mark>

**Please wait patiently for the transaction to fully complete.** To avoid any issues, refrain from using other functions of the wallet until the entire process has concluded.

## Final Unwrap&#x20;

#### Final Transaction Process

After initiating the final unwrap, the transaction will be sent to the Facet VM with encrypted, hashed rules (ethscription) regarding the receipt of receiving ETH. It is crucial to ensure that **no other functions of the wallet are used while this process is ongoing**.

* **Estimated Completion Time:** The entire process is expected to take no more than 2 minutes (but depends on external API responses and limits: Telegram API and others)

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption><p>Final Unwrap FETH to ETH</p></figcaption></figure>

#### ⚠️<mark style="color:yellow;">`Important`</mark>

Please continue to exercise patience and refrain from performing any additional actions within the wallet until you receive explicit confirmation that the transaction has successfully completed.



### Transaction receipt

After the transaction is successfully processed, you will receive a detailed receipt containing the following information:

* **Transaction Hash (TxHash):** A unique identifier for your transaction on the blockchain.
* **Links to View Transaction:**
  * [FacetScan](https://facetscan.com)
  * [Etherscan](https://etherscan.io)
* **Block Number:** The specific block on the blockchain in which your transaction was recorded.
* **Gas Spent:**
  * Ether (ETH) amount.
  * Equivalent USD value (according to [CoinMarketCap](https://coinmarketcap.com/)).
* Amount of Unwrapped FETH
