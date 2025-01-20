# Lumos AI Agent 🤖

Lumos AI-Agent is an intelligent assistant designed to enhance the user experience within the Lumos application. This agent leverages advanced artificial intelligence to:

- Provide precise and personalized guidance on calculating Impermanent Loss (IL).
- Help interpret simulations of liquidity strategies in Full-Range and CLMM Pools.
- Offer real-time recommendations to optimize automated management of CLMM positions.
- Enable informed decision-making using Starknet's blockchain technology for fast and efficient data processing.

With Lumos AI-Agent, users can effectively navigate the DeFi ecosystem and maximize the potential of their liquidity strategies.

## Disclaimer 🚨

We took inspiration from the Eliza Starter project and began building upon this repository: [https://github.com/elizaOS/eliza-starter](https://github.com/elizaOS/eliza-starter).

## Steps to Run 🏃🏻

### 1. Installations 💻

- Node.js: 23.6.0
- pnpm: 10.0

### 2. Copy the .env File and Add the Together API Key 🔧

```bash
cp .env.example .env
```

You can download the API key here: [https://api.together.ai/](https://api.together.ai/)

### 3. Run the Agent 😁

```bash
pnpm install
pnpm build
pnpm start --characters="characters/lumos.character.json"
```
