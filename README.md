# SDK Bot Example

This repository contains the Radar Relay Bot example used in the [Building a Bot](https://developers.radarrelay.com/bot-tutorial) tutorial.

![bot_demo](https://user-images.githubusercontent.com/20102664/41552912-6d114cfe-72ed-11e8-9135-40c50614407c.png)

## Setup

1. `npm install`

2. `export RADAR_WALLET_PASSWORD=yourpassword`

3. Run: `npm start` 

  The first time you run the bot it will output the wallet address and wait to receive Kovan ETH.
  Enter the address into a [Kovan Faucet](https://faucet.kovan.radarrelay.com) to obtain Kovan ETH.

4. Once the ETH is received the bot will:
   1. Set WETH token allowance
   2. Wrap ETH
   3. Subscribe to the ZRX/WETH book websocket
   4. Place a ZRX/WETH limit order
