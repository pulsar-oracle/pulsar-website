# Pulsar Website

Landing page for [Pulsar](https://github.com/pulsar-oracle/pulsar-contracts), the decentralized oracle network for Soroban smart contracts on Stellar.

It's a single static page (`public/index.html`) deployed on Vercel. `vercel.json` serves `public/` as the output directory.

## Local Preview

```bash
npx serve public
```

## Related Repositories

| Repository | Contents |
|------------|----------|
| [pulsar-contracts](https://github.com/pulsar-oracle/pulsar-contracts) | Soroban aggregator contract (Rust) |
| [pulsar-feeder](https://github.com/pulsar-oracle/pulsar-feeder) | Off-chain feeder node (TypeScript) |
| **pulsar-website** (this repo) | Landing page |

## License

MIT — see [LICENSE](./LICENSE).
