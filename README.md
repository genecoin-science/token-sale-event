# token-sale-event

Establishes the basis for the Token Sales Event: pre-initial offer, initial offer, token distribution. It could be merged with cryptocurrency contract.

Actions performed by the contract:
2.1) Pre-ICO offer
2.1.1)Description: ICO will be performed in Tiers, starting with the Pre-ICO with a higher minimum cap and a 50% discount of the price. It should be possible to set a limit to X tokens (10,000,00 ?)
2.2) ICO Tiers
2.2.1) Description: Tiers will give discount in price of tokens during set periods. Discount, period and amount of tokens available can be changed in contract if necessary. It should be considered a possibility of referral links providing further discount or bonus. A maximum cap should also be considered; 
1st Tier ICO with 25% discount of the price
limited to X tokens (20,000,00 + residual balance ?) or end time (sold out push 2nd Tier)
2nd Tier ICO with 15% discount of the price
limited to X tokens (20,000,00 + residual balance ?) or end time (sold out push 3nd Tier)
3rd Tier ICO with 7,5% discount of the price
limited to X tokens (20,000,00 + residual balance ?) or end time (sold out push 3nd Tier)
4th Tier ICO with no discount (residual balance up to complete the 70,000,000 tokens to be sold)
2.2.2) Benchmark: https://github.com/TokenMarketNet/ico 
2.3) Minimum cap check
2.3.1) Description: After the end of the ICO and before burn, a check is performed to see if the total amount of tokens sold generated the minimum cap of Ether expected to the project to go on.
Actions: start to send back Ether to accounts of supporters, or just a buyout rotine that exchange the token back to Ether under request and for a limited time. Returning deposits will only be performed to the same account that sent the ETH to buy the tokens.
2.4) Token distribution
2.4.1) Description: After the ICO period and before burn, all tokens bought during the pre-ICO and ICO, as well as founders, management, marketing and early adopters (swap) tokens should be sent to their respective wallets, unless a minimum cap is not reached.
Founders will hold X% (10%?) of total amount of tokens - To be sent to a multisignature  wallet (account would be set in the contract and should be updatable)
NPO or manage institution will hold X% (10%?) of total amount of tokens - To be sent to a multisignature  wallet (account would be set in the contract and should be updatable)
Marketing Account will hold X% (5%?) of total amount of tokens - To be sent to a multisignature wallet (account would be set in the contract and should be updatable)
Early Adopters will hold X% (1% up to 5%?) of total amount of tokens - To be sent to a multisignature wallet for future swap of distributed experimental Tokens
In case of network congestion, provision to send tokens to a multisignature wallet for continue the token distribution should be part of the scope of the contract. 
2.5) Balance of unsold and not transfered tokens will be burned but calling the function in contract #1
Obs: All Ether received during pre-ICO and ICO should be sent to a multisignature account and will serve as the source of resources to execute the project.
Whitelisting buyers should be considered and may be part of the contract as an option to be executed.
