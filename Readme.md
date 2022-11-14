# Quick Start

+ dependency

   - nodejs 16 LTS
   - metamask
   - infura

+ download package
```
npm i
```
+ create env files
```
cd polygon-ethereum-nextjs-marketplace && touch .env && touch .infuraid
```
   + example of .env
```
JSON_RPC_PROVIDER="http://127.0.0.1:8545"
INFURA_IPFS_PROJECT_ID="YOUR_IPFS_ID"
INFURA_IPFS_PROJECT_SECRET="YOUR_IPFS_SECRET"
INFURA_IPFS_URL="YOUR_DOMAIN"

NEXT_PUBLIC_WORKSPACE_URL=$CLIENT_URL
```
   + example of .infuraid
```
justyourid
```
+ start local node
```
npx hardhat node
```
+ deploy your contract
```
npx hardhat run scripts/deploy.js --network localhost
```
+ run the project
```
npm run build // if you need
npm run dev
```
---
# NOTIFICATION

Do not change the version of NEXT.js!

It should be '12.1.6'. or crush.

---
