## ⛓️ On Chain Buidls

### [Only Buidlors](https://only-buidlors.vercel.app/)
- A dynamic SVG NFT project for the BuidlGuidl
- Uses chainlink functions to verify membership by making request from smart contract to off chain API
- Dynamically displays NFT's background color, build count, and ens name 

### [Vaults of Fortune](https://vaults-of-fortune.vercel.app/)
- A contest where players are airdropped ERC-20 tokens to deposit into ERC-4626 vaults
- Uses Chainlink VRF to randomly determine return on investment for each of the three vaults
- Leaderboard and round state are tracked using events emitted on chain

### [Speedrun Chainlink](https://speedrun-chainlink.vercel.app/)
- Learn how to integrate price feeds in your smart contracts using AggregatorV3Interface
- Spin the wheel of fruit to request a verifiably random number from the VRF Coordinator
- Play with the simple counter contract to understand how chainlink keeper nodes perform automated tasks on chain

### [Etherscript](https://github.com/MattPereira/etherscript)
- Swap tokens using uniswap's smart order router that computes the optimal route before executing the swap
- Gets the price for a base asset in terms of a quote asset using chainlink price feeds
- Fetches abi from etherscan API and output the result to a .json file inside the ./abis directory


## 🕸️ Web2 Builds
### [Contra Costa Golf Club](https://ccgc.vercel.app)
- Full stack, single page web app managing all data for a local golf organization
- Users are able to input their strokes, putts, and greenies as they play each golf round
- Custom built internal API that handles create, read, update, and delete operations 
- Calculates handicaps and points for determining individual tournament and season long champions

### [Tabernacle School](https://www.tabernacle.school)
- Elementary school website promoting services and providing up to date information for parents
- Offers forms that enable users to send the school messages via emails that are DKIM verified with Postmark
- Uses a headless content management system to update data and images displayed on the site


