## State-of-the-Polkadot May 2021

`Polkadot` is a wheel-shaped multi-blockchain system built on principles of democratic governance, parallel processing, and Proof-of-Stake(PoS) validation.

* Relay Chain is a circular, solid center where spokes of the wheel can be situated.
* Parachains are the parallel-blockchains (hence Para-chain), the spokes aligned along the outside of the wheel.

`Kusama: canary-in-a-coalmine` (native token - KSM) shares the same code-base as Polkadot, though Kusama has the newest developed features by serving as the *canary network* by testing Polkadot features with real money and stakes **before** code launches on Polkadot.

*Substrate framework* is the development framework for building polkadot chains and apps.

I. Relay Chain -- responsible for
    i. validating blocks from all parachains simultaneously.
    ii. manages governance for the ecosystem: democracy module for voting
    iii. hosts bridges for transfering value to other chains.

II. Parachains -- Parallel chains attach to the relay-chain. Parachains can have their own native token to process transaction fees, or can use DOT/KSM instead.

    i. Businesses, DeFi Apps, NFT Marketplaces can launch as a Parachain. Polkadot's internal secure messaging scheme helps to securely exchange any data between parachains.
    ii. Parachains must secure their 6mo-2yr slot through a public auction.
    iii. **CrowdLoans incentivize the public to stake their KSM/DOT for the Parachain to win the auction**(iii.). In exchange, the parachain pays out native token rewards proportional to the supporter's % of the total KSM/DOT staked at the auction. (1% DOT staked => 1% of rewards earned)
    iv. Authorized to create a block every 12 seconds alongside the relay chain.

III. *If Parachains require a slot, then how do we build on polkadot?*
    Good question! Anyone can develop and launch a **Parathread** anytime. Parathreads have the same API as a parachain, but produce blocks slightly less often.

## Polkadot Decoded 2021-featured Projects

I. Polkadot/Kusama Featured Projects: projects to keep an eye on.

* `Acala (ACA)`: All-in-1 Dashboard for DeFi legos
  * `Karuna (KAR)`: Kusama sister project
  * partnered with Current, USA mobile banking.
  * swap, earn interest, get loans, spend USDC on current debitcard.
  * smart-contract deployment platform for businesses
  * bridging to other ecosystems (ETH, BSC)
  * **Crowdloan(KSM) for Karuna parachain slot upcoming!**
* `Moonriver (GLMR)`: Multi-chain ecosystem with low-gas fees, embraced by Yearn.finance, band protocol, chainlink, and many more.
  * `Moonriver (RIVER)`: Kusama sister project
  * preparing for the massively crosschain future, liquidity galore, gateways.
  * smart-contract deployment platform for businesses
  * pre-built easy deployment for devs.
  * **Crowdloan(KSM) for Moonriver parachain slot upcoming!**

II. Polkadot projects need a deeper dive, who were also featured on the 2021 event.

* `OriginTrail`: Making Supply Chains work together.
* `Darwinia Network`: Bridge Hub between Polkadot and External networks
* `Energy Blockchain`: Nameless blockchain funded by multi-disciplinary effort by University of Wyoming (5 departments) to drive net-zero carbon efforts.
* `Polkadex`: Feeless swaps & high frequency trading.
* [IoT Polkadot Smart Cities: Massively cool](https://www.youtube.com/watch?v=B-5OR-zKmL)