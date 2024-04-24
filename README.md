# UniswapV2_

Welcome to our Uniswap V2 fork repository! Here, I've utilize Uniswap V2 core contracts, Router02 from Uniswap V2 periphery, and the WETH contract from Etherscan to build our template.

## Contents:

1. **Smart Contracts:** 
    - Explanation of the smart contracts utilized in our forked version of Uniswap V2.

2. **Deployment:**
    - Details on how to deploy the smart contracts and set up the environment for testing.

3. **Pending Features:**
    - Information about pending features, particularly the token swapping functionality, which is currently under development.

## Smart Contracts:

Our forked version of Uniswap V2 leverages the following smart contracts:
- **Uniswap V2 Core Contracts:** These contracts form the core functionality of Uniswap V2, enabling token swapping and liquidity provision.
- **Router02 from Uniswap V2 Periphery:** The router contract facilitates interactions with Uniswap V2, allowing users to perform swaps, add liquidity, and more.
- **WETH Contract from Etherscan:** We use the WETH (Wrapped Ether) contract to represent ETH as an ERC-20 token, enabling seamless integration with Uniswap V2.

## Deployment:

To deploy the demo version of our forked Uniswap V2, follow these steps:
1. Clone this repository to your local machine.
2. Install any necessary dependencies.
3. Compile the smart contracts using your preferred Solidity compiler.
4. Deploy the compiled contracts to your desired Ethereum network (mainnet, testnet, or a local blockchain environment).
5. Configure the deployment parameters such as initial liquidity pools, fees, and other settings as needed.
6. Verify the deployment and ensure that all contracts are functioning correctly.

 Sure, here's the updated section:

## Repository Structure:

- **core:** Contains Uniswap core smart contracts and interfaces, along with the token1 and token2 contracts.
- **periphery:** Contains the router contracts and interfaces, as well as the WETH contract.
- **migration:** This directory contains the contracts responsible for managing liquidity migration and user incentives. It includes:
    - **UniswapV2Pair:** Contract representing a pair of tokens on Uniswap V2.
    - **Bonus Token (ERC20):** An ERC20 token used as a bonus or incentive for liquidity providers.
    - **Liquidity Migrator:** Contract facilitating the migration of liquidity from other platforms to our forked version of Uniswap V2. This contract also enables investors to claim bonus tokens if they provide liquidity to our platform.


## Pending Features:

- **Token Swapping Functionality:** 


