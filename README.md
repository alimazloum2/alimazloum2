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
- **Change management as one flow** — [Change Ledger](https://github.com/alimazloum2/change-ledger): RFI → CCN → subtrade pricing → estimate → CO → forecast, starting from the joins existing tools handle badly.
- **Blockchain for construction** — progress payments, holdback release and change orders still run on paper trust. I'm learning smart contracts to see how much of that can become code.
- **Learning by building** — the wallet tracker, the educational blockchain and the test token below are deliberate steps: understand wallets, then chains, then tokens, before designing anything for a job site.
- **AI-assisted engineering** — agent workflows and skills that speed up estimating and document review.

## 🧱 Why I'm learning blockchain

**The problem is trust, not software.** In Canadian construction, money flows owner → general contractor → subtrade → supplier, and every hand it passes through holds it a little longer. The Ontario study behind that province's prompt-payment law found subtrades waiting an average of 71 days to be paid for certified work. Ontario, Nova Scotia and the federal government have since legislated 28-day payment deadlines and fast adjudication. The law now says *when* money must move. Nothing enforces it except lawyers.

**Existing tools can't fix this, because one party owns them.** Procore, Textura, GCPay: all good products, all controlled by the contractor who is also holding the money. A ledger only one side can audit is a promise, not a record. What's missing is a shared source of truth that the owner, the GC, the sub and the surety all read from, and none of them can quietly edit.

**That is the one thing a blockchain does well.** Not speculation, not coins. A neutral, append-only ledger with rules that execute themselves. On a job site that means:

- A progress payment is certified, and escrow releases it the same hour, not on day 71.
- The 10% lien holdback is computed and held automatically and released on the statutory date, not when someone remembers or decides.
- Release is gated on a signed lien waiver, so the sub's own suppliers and workers are protected down the chain.
- Every change order, back-charge and notice is timestamped where nobody can rewrite it later.

**I know where the line is.** Someone still has to walk the site and certify the work. That is my job, and it stays human. Subs want CAD, not tokens. Lien law can't be contracted out. So the target is a hybrid: the chain owns the arithmetic and the audit trail, the bank moves the dollars, and the PM keeps the judgment.

**Why me.** I'm the person who signs the payment certificate. I know which decisions on a payment application are judgment and which are arithmetic, and the arithmetic is most of it. That is the part worth turning into code.

**The plan**, tracked on my [Open Source Roadmap](https://github.com/users/alimazloum2/projects/2):

1. **Records first, no money.** Anchor payment certification events on-chain and get the data model right.
2. **Milestone escrow on a testnet** with a mock stablecoin, automatic holdback and lien-waiver gating.
3. **One pilot, one subtrade, one job.** The contract decides when payment is due; dollars still move by e-transfer.

The public repos below are the groundwork: understand wallets, then a chain, then a token, before designing anything for a job site.

## 🚀 Featured projects

Change Ledger is the day job problem. The three below it are rungs on the ladder toward construction payments on-chain.

| Project | What it is | Stack |
|---|---|---|
| [change-ledger](https://github.com/alimazloum2/change-ledger) | Construction change management as one Change Event flow, from RFI to revised contract and forecast. Spec first, code next | Spec / Python |
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
