# Ethernyx Features — NFT Bidding Bot for OpenSea & Blur

A complete look at what the **Ethernyx NFT bidding bot** does. Start the app at **[app.ethernyx.io](https://app.ethernyx.io)**.

## ⚡ Speed

- **Up to 300+ token bids per second** on OpenSea — the fastest bid throughput on the market.
- **~3× faster** than typical competing NFT bots.
- **Event-driven engine:** executors react the instant a new bid, floor change, or balance update lands — no slow polling.
- **Parallel execution:** every token / trait is bid in parallel, keeping you at the top of the book.

## 🎯 Bidding Strategies

### Collection Bidder
Place and maintain **collection-wide offers**. Ethernyx instantly outbids the current top bid within your configured margin and price limits, on both **OpenSea** and **Blur**.

### Trait Bidder
Bid only on items matching **specific traits / attributes** (rarities, backgrounds, types). Perfect for targeting undervalued rare items.

### Token / Item Bidder
Bid on **specific token IDs** or a curated **ID list** — item-level offers on **OpenSea** (available on Starter and above).

### Floor Lister
**Automated NFT listing.** Lists your NFTs at the floor (or your target price), keeps the price updated, and **instantly re-lists** the moment a bid fills. Available on OpenSea and Blur.

## 🧠 Smart Controls (on every strategy)

- **Outbid margin** — how much to bid above the current top offer.
- **Min / Max bid** — absolute or relative price limits.
- **Min floor price filter** — ignore collections below a threshold.
- **Min bids above** — only act when there's enough depth.
- **Max-buy cap** — stop (or loop) after acquiring N items.
- **Arbitrage thresholds** — only buy when there's profit between **Blur ↔ OpenSea**.
- **Auto-listing** — automatically list acquired NFTs back for sale.

## 📊 Analytics & Monitoring

- Real-time **collection and wallet insights**.
- Live **activity feed** of every bid, cancel, fill, and listing.
- WETH / ETH **balance monitoring** and P&L tracking.

## ☁️ Platform

- **100% cloud-based** — no downloads, no VPS, no local node. Runs on any device, including mobile.
- **Multi-wallet** — up to **10 wallets** under one account.
- **Web3 login** — sign in with MetaMask, WalletConnect, and more. No passwords.
- **Unlimited tasks** on every paid plan.
- **Bulk task management** — start, stop, group, and edit many tasks at once.

## 🔐 Security

- Private keys **encrypted at rest** and **isolated** in a hardened private service with IP allow-listing — they **never leave it** and are **never logged**.
- On-chain payments **validated against the blockchain** before activation.
- Hardened microservice architecture separating public API, private bot logic, and outbound execution.

---

**[👉 Launch Ethernyx →](https://app.ethernyx.io)** · [Pricing](PRICING.md) · [FAQ](FAQ.md) · [Docs](https://ethernyx.gitbook.io/ethernyx-docs)
