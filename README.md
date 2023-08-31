# contractfaucetv1
contract faucet solidity code


this is a simple  faucet contract to distribute native token of any network to users 

you can deploy to any network of your choice (ethereum, binance , polygon ,and all testnets )

1.change the contract name in line 8 

2.claim amount of you choice in line 9

3.deploy to network

4.send funds to the contract address 

5.by default distribute to users 0.1 tokens for every 24hours

you can change the claim amount and claim interval with owner wallet even after deploying the contract 

to change claim amount and claim interval 

1. claim amount should in wei
2. claim interval should be in seconds

this contract only works with native tokens of the network and only owner can deposit and withdraw funds , and the claim user can only be a wallet address (i.e contracts cannot claim funds from this faucet )

you can deposit and withdraw funds anytime with owner wallet

for users to claim they must have funds for gas fees
