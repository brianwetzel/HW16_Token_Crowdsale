![alt=“”](EvaluationEvidence/kasei_coin_logo.png)

# Kasei Coin ICO • How to Puchase
Congratultions!  So you want to purchase Kasei Coin, eh?  Great choice.  Don't worry, it's totally not a rug pull, I promise.  Here are instructions with examples to help you make the purchase:

<br>

But First, a little background on how this was built....

<br>

----------------------

<br>

## Complie Contracts

Both solidity files for Kasei Coin and the Crowdsale compiled succesfully in Remix with no bugs.  
<br>
![alt=“”](EvaluationEvidence/1_compile.png)

<br>

![alt=“”](EvaluationEvidence/2_compile.png)

<br>

----------------------
<br>

## Deploy Contract
Once the contracts compiled, I deployed the `KaseiCoinCrowdsaleDeployer` contract to the Ethereum Network.  Below are the details associated with deploying the contacts.

<br>

![alt=“”](EvaluationEvidence/3_deploy.png)

<br>

Here the MetaMask wallet of the deploying address confirms the transcation and pays the gas fees.  Whoa, expensive!

<br>

![alt=“”](EvaluationEvidence/4_deploy_metamask.png)

<br>

Then I used the `KaseiCoinCrowdsaleDeployer` contract to deploy two more contracts: KaseiCoinCrowdsale and KaseiCoin.  The `KaseiCoin` contract is the contract for the actual coin itselft.  And the `KaseiCoinCrowdsale` contract allows user to buy the coin. 

<br>

![alt=“”](EvaluationEvidence/5_deploy_addresses.png)

<br>

All three contracts deployed:

![alt=“”](EvaluationEvidence/6_Deply_3_Contracts.png)

<br>

----------------------

<br>

## Buy Tokens
Ok, now to the fun part... let's buy some tokens!  Use the `KaseiCoinCrowdsale` contract.  
1. In the 'value' section on the left side of remix, enter how much you want to spend in Ethereum.
![alt=“”](EvaluationEvidence/value.png)

2. Scroll down to the `KaseiCoinCrowdsale` and enter the wallet address you want to send the coins to. 
![alt=“”](EvaluationEvidence/buy.png)

3. Click 'transact'

4. Metamask will pop up and ask you confirm you transcation.  Click Confirm.
![alt=“”](EvaluationEvidence/10_confirm_buy.png)


### Kaboom, You are now the proud owner of Kasei Coin!

<br>

----------------------

<br>

## Confirm Token Balance

So now you own some Kasei Coin.  Sick!  But don't take my word for it.  You know what they say: "Don't trust, verify."

1. Navigate to your MetaMask wallet a click `Assets`.  This is where you can see all the coins and tokens in your wallet.  Don't see Kasei Coin?  Don't worry, we probably need to import the contract address.
2. In MetaMask, scroll down to `Import Tokens`
3. In the next window, copy the Kasei Coin contract address from Remix, and paste it in.  Then click 'Add Custom Token' and then click 'Import Tokens'
![alt=“”](EvaluationEvidence/import_tokens.png)
4. Shazam!  Now under aseets in your MetaMask wallet, you can see your Kasei Coin (ticker KAS) balance.  
![alt=“”](EvaluationEvidence/token_balance.png)

<br>

----------------------

<br>

## Total Supply
Among many things, we can also check the total supply of Kasei Coins.  

In the left side of remix, navigate down to the `KaseiCoin` contract.  At the bottom of the options click the button `totalSupply`.  Right now, the total supply is 10,000,000,000,000,000,000 Wei.  This is equivelant to 10 Eth, which is the exact amount that we purchased in the example above. 
 
![alt=“”](EvaluationEvidence/total_supply.png)

<br>

----------------------

<br>

## To the Moon!
Ok, now just hang on and hopefully this Kasei Rocket Ship goes to the moon. 
<br>

![alt=“”](EvaluationEvidence/moon_gif.gif)


















