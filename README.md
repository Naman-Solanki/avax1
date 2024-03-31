# DeFi Kingdom Clone Deployment Guide

## Tools Used

- Unix Computer (MacOS or Linux)
- Solidity
- Remix
- Metamask
- Web Browser

## Project: Step by Step

### 1. Deploy Your EVM Subnet using Avalanche CLI

Use the Avalanche CLI to deploy your EVM subnet on the Avalanche network.

### 2. Add Your Subnet to Metamask

1. Open Metamask and click on the network dropdown.
2. Select "Custom RPC" and enter the details of your EVM subnet:
   - Network Name: Avalanche EVM
   - RPC URL: [Your EVM Subnet RPC URL]
   - Chain ID: [Your EVM Subnet Chain ID]
   - Symbol: AVAX
   - Block Explorer URL: [Leave blank or add if available]

### 3. Connect Remix to Your Metamask

1. Open Remix and navigate to the "Settings" tab.
2. Under "Plugin", select "Solidity Compiler".
3. Scroll down and select "Environment" > "Injected Web3".
4. Remix should automatically connect to Metamask.

### 4. Deploy Smart Contracts

1. Write your smart contracts in the Remix IDE.
2. Compile the contracts by clicking on the "Compile" tab.
3. In the "Deploy & Run Transactions" tab, select the contract you want to deploy from the dropdown.
4. Choose the desired account from Metamask and click "Deploy".

### 5. Test Your Application

1. Once deployed, interact with your contracts using the Remix interface.
2. Deploy tokens, pools, or any other functionality provided by your contracts.
3. Test different functions and scenarios to ensure everything works as expected.

- - -
