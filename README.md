<h1 align="center">Hi, I'm Ali Mazloum 👋</h1>

<p align="center">
  Electrical engineer and construction project manager in Halifax, Nova Scotia 🇨🇦<br/>
  I write Python and TypeScript to take the grunt work out of estimating, and I'm studying blockchain because I think it can fix how construction gets paid.
</p>

<p align="center">
  <a href="https://www.alimazloum.com">🌐 alimazloum.com</a> ·
  <a href="https://twitter.com/AliMazloum3">🐦 @AliMazloum3</a>
</p>

---

## 🔭 What I'm working on

- **Estimating and takeoff automation** — CLIs and web apps that turn drawings and specs into quantities, costs and labour hours faster than a spreadsheet can.
- **Blockchain for construction** — progress payments, holdback release and change orders still run on paper trust. I'm learning smart contracts to see how much of that can become code.
- **Learning by building** — the wallet tracker, the educational blockchain and the test token below are deliberate steps: understand wallets, then chains, then tokens, before designing anything for a job site.
- **AI-assisted engineering** — agent workflows and skills that speed up estimating and document review.

## 🧱 Why I'm learning blockchain

I manage subtrades for a living. The same problems show up on every job:

- **Subs wait 30 to 90 days to get paid** for work that was certified weeks earlier.
- **Holdback** is a mechanical rule, yet it gets miscalculated, forgotten, or used as leverage.
- **Change orders and back-charges** turn into "we never agreed to that" because the record lives in someone's inbox.

A smart contract is a good fit for exactly this: money that should move when a condition is met, and records nobody can quietly edit later. Picture an escrow that releases a sub's progress payment the hour the PM certifies the milestone, computes and holds the statutory lien holdback on its own, and only pays out against a signed lien waiver, with every change order stamped on an immutable log.

I'm not naive about the limits. Someone still has to walk the site and certify the work, subs want dollars rather than tokens, and lien law can't be contracted out. So the design I'm working toward is a hybrid: the chain is the neutral ledger and trigger, and the bank still moves the CAD.

**The plan, tracked on my [Open Source Roadmap](https://github.com/users/alimazloum2/projects/2):**

1. **Records first, no money.** Anchor payment certification events on-chain and get the data model right.
2. **Milestone escrow on a testnet** with a mock stablecoin, including automatic holdback and lien-waiver gating.
3. **One small pilot** with one friendly subtrade, where the contract decides when payment is due and dollars still move by e-transfer.

The public repos below are the groundwork for that: wallets, then a chain, then a token.

## 🚀 Featured projects

Each public repo is one rung on the ladder toward construction payments on-chain.

| Project | What it is | Stack |
|---|---|---|
| [wallet-tracker-bot](https://github.com/alimazloum2/wallet-tracker-bot) | Step 1, wallets: Telegram bot that tracks BTC, ETH, BSC and SOL balances and generates BIP39 multi-chain wallets | Python |
| [TinyCoin](https://github.com/alimazloum2/TinyCoin) | Step 2, chains: educational blockchain with proof-of-work mining, ECDSA signing, transaction validation and consensus | Python |
| [tigercoin-token-list](https://github.com/alimazloum2/tigercoin-token-list) | Step 3, tokens: token-list infrastructure for a test token on Base, served via GitHub Pages | JSON / Pages |

## 🛠️ Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?logo=ethereum&logoColor=black)
![Solidity](https://img.shields.io/badge/Solidity-363636?logo=solidity&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Telegram Bots](https://img.shields.io/badge/Telegram_Bots-26A5E4?logo=telegram&logoColor=white)

## 📊 Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=alimazloum2&show_icons=true&theme=default&hide_border=true" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=alimazloum2&layout=compact&hide_border=true" alt="Top languages" />
</p>
