# SDK Bot Example

An example bot built using the `@radarrelay/sdk`.

## Setup

1. `yarn install`

2. `export RADAR_WALLET_PASSWORD=yourpassword`

3. Run: `npm start` 

  The first time you run the bot it will output the wallet address and wait to receive Kovan ETH.
  Enter the address into a [Kovan Faucet](https://faucet.kovan.radarrelay.com) to obtain Kovan ETH.

4. Once the ETH is received the bot will:
   1. Set WETH token allowance
   2. Wrap ETH
   3. Subscribe to the ZRX/WETH book websocket
   4. Place a ZRX/WETH limit order
