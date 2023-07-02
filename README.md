# ETH-Solo-Validator-Addresses
unique ETH addresses belonging to solo stakers



**Contracts** 

Eth2 Deposit Contract

0x1AA52b5A49FF06273D97649f29d9adAa3F65a1a6

RPL node Deposit contract Address

0xDfdA9615E3ec39648041763A57680dfB870c9530

**#Solo Validator List**

All unique validator deposit addresses including Rocketpool node operator (withdrawal addresses), this excludes exchanges such as Coinbase and kraken, and staking as a service/liquid staking such as Lido.

this list is every solo validator owned address that made at least 1 valid deposit to the beacon chain up until the Ethereum Merge on 15/09/22. 

**#Beacon Chain Depositors**

All unique addresses that deposited a valid (32ETH) transaction to the ‘ETH2 deposit contract’. this will include addresses belonging to exchanges and liquid/pooled staking providers. contract addresses are excluded from this, such as rocketpool minipool contract addresses

**#Rocketpool Depositors**

All unique ‘withdrawal addresses’ associated with rocketpool node accounts, due to security concerns withdrawal addresses which are better fit for receiving any token distributions. This excludes rETH minters.

**#Blacklist**

Data From Ethereumpools.info (https://github.com/alrevuelta/eth-metrics ), ETHsta.com (https://github.com/Zachary-Lingle), to consolidate known staking as a service/liquid staking addresses, Such as Lido, Stakewise. exchange addresses such as Kraken and Binance.
Addresses were reviewed carefully to avoid false positives. Coinbase addresses which account for 63,559 of the unique addresses were accurately identified using dune analytics: https://dune.com/queries/1283309


**Methodology**

Data was pulled from associated contracts above, invalid deposits were removed and duplicate addresses filtered out. The blacklist was applied to remove those addresses belonging to LSD providers and Exchanges/Custodians.

Leaving all unique Ethereum addresses belonging to solo stakers that have deposited to the beacon chain contract to run a validator, pre- merge.
