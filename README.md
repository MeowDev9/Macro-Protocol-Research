# Macro Protocol Research

Research, methodology, data, and supporting sources for **Macro Protocol**, a research project focused on how financial infrastructure is moving on-chain.

Macro Protocol covers tokenized real-world assets, stablecoins, DeFi infrastructure, financial market structure, blockchain architecture, and on-chain capital markets through a systems-oriented, data-driven lens.

**No price predictions. No coin shilling. No hype.**

---

## Research

### 01. RWA Concentration Risk

**RWA Concentration Risk: What the Tokenized Treasury Data Actually Shows**

An analysis of concentration across the tokenized U.S. Treasury market, including product market share, issuer concentration, custody, and the institutional infrastructure behind on-chain assets.

Key questions:

- How concentrated is the tokenized Treasury market?
- How much market share sits with the largest products?
- Has BlackRock's BUIDL become more or less dominant over time?
- Does distributing assets across public blockchains meaningfully decentralize the institutions behind them?

[View research →](https://macroprotocol.substack.com/p/rwa-concentration-risk-what-the-tokenized)

---

### 02. Who Controls the Transfer?

**Who Controls the Transfer of Tokenized Treasuries?**

A study of BlackRock's BUIDL and Franklin Templeton's BENJI, with USDC used as a point of comparison, examining the difference between recording an asset on-chain and controlling its transfer, ownership, custody, and governance.

Key questions:

- Who can receive and transfer a tokenized fund share?
- What is enforced by the blockchain and what remains institutionally administered?
- How do allow-listed transfers differ from an open-by-default blocklist model?
- What counts as the authoritative ownership record?
- Who holds the underlying assets?
- Where does decentralization end and institutional control begin?

[View research →](https://macroprotocol.substack.com/p/who-controls-the-transfer-of-tokenized)

---

## Research Framework

Macro Protocol does not treat "on-chain" or "decentralized" as single yes-or-no properties.

Where relevant, financial systems are examined across distinct layers:

1. **Ledger**: who validates and records transactions?
2. **Settlement**: how does value move between participants?
3. **Ownership**: what constitutes the authoritative record of ownership?
4. **Custody**: who holds the underlying assets?
5. **Governance**: who can permit, restrict, correct, freeze, or restore activity?

This framework is intended to separate blockchain infrastructure from the legal, operational, and institutional systems surrounding it.

---

## Methodology

Research prioritizes primary and reproducible sources wherever possible, including:

- regulatory filings and official notices
- issuer and fund documentation
- smart contracts and technical documentation
- blockchain explorers and on-chain data
- protocol documentation
- financial and market datasets

Where a claim comes directly from a primary source, it is identified accordingly.

Where a conclusion is based on analysis, interpretation, or inference rather than an explicitly documented fact, that distinction is preserved.

Each research folder contains its own methodology, source list, supporting data, and figures where applicable.

---

## Repository Structure

```text
macro-protocol-research/
│
├── README.md
│
├── research/
│   ├── 01-rwa-concentration-risk/
│   │   ├── README.md
│   │   ├── methodology.md
│   │   ├── sources.md
│   │   ├── data/
│   │   └── figures/
│   │
│   └── 02-who-controls-the-transfer/
│       ├── README.md
│       ├── methodology.md
│       ├── sources.md
│       ├── data/
│       └── figures/
│
└── assets/
