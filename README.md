cd sdk/typescript
pnpm run prepare:e2e
pnpm run test:e2e
cd sdk/typescript
VITE_FAUCET_URL='https://faucet.devnet.sui.io:443/gas' VITE_FULLNODE_URL='https://fullnode.devnet.sui.io' pnpm test:e2e
