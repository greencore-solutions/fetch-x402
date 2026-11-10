# fetch-x402

> wefetch developed gtinfetch, the GTIN record for AI agents. x402 on every wefetch hub: a buying agent asks, pays inside the call and is served, with a receipt on chain. USDC and Open USD, 20 countries, one rail.

Built and run by [wefetch](https://wefetch.ai/). This is the public connect kit, MIT. It holds no deploy code and no keys.

## Connect

- Pay-in-the-call endpoint: `https://fetch-x402.ai/api`
- Agent card: `https://fetch-x402.ai/.well-known/agent-card.json` (copy in this repo, `agent-card.json`)
- For agents: https://fetch-x402.ai/llms.txt
- Site: https://fetch-x402.ai/

A call with no payment answers HTTP 402 with the offer. Your agent signs a payment from the offer and repeats the call with it, under the x402 protocol.

```bash
curl -i https://fetch-x402.ai/api
```

Artificial intelligence makes mistakes. Check what matters.
