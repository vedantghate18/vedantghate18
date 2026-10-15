# `>_ VEDANT GHATE`

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2500&pause=800&color=00F7FF&center=true&vCenter=true&width=800&lines=AI+%26+Software+Engineer;Building+Practical+AI+Apps+%26+Backend+Systems;Solidity+%7C+DeFi+%7C+EVM+Infrastructure;Turning+ideas+into+shipped+software)](https://git.io/typing-svg)

</div>

---

## `whoami`

```bash
$ whoami
vedant-ghate (he/him)

$ cat /etc/developer.env
ROLE="AI & Software Engineer"
PRIMARY_FOCUS="Applied AI, Full-Stack & Backend Systems"
SPECIALIZATION="Smart Contracts, DeFi Protocols & EVM Infrastructure"
PHILOSOPHY="Ship working software. Understand systems down to the bytecode."
```

I'm a software engineer focused on building practical AI-powered products, resilient backend systems, and decentralized infrastructure. I enjoy taking projects from idea to deployment: the model orchestration, the API layer, the user interface, and the verifiable on-chain contracts that back them up.

[Portfolio](https://vedantghateportfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/vedant-ghate-40b622290/) · [X / Twitter](https://x.com/_0xshunya_) · [Email](mailto:vedantghate0603@gmail.com)

**Currently building & exploring:**
- 🤖 **Applied AI & LLM Systems:** Document intelligence, structured generation rules, and agentic workflows.
- ⚙️ **Backend Engineering:** Fast REST APIs, event-driven pipelines, and relational/document databases.
- ⛓️ **EVM & Smart Contract Security:** Invariant testing with Foundry, DeFi mechanisms, and account abstraction (ERC-4337).

---

## `tech_stack`

### Applied AI & Data Science
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-f55036?style=for-the-badge) ![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch_(Learning)-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

### Software & Backend Engineering
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Blockchain & Web3
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white) ![Foundry](https://img.shields.io/badge/Foundry-black?style=for-the-badge&logo=ethereum&logoColor=white) ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white) ![Viem](https://img.shields.io/badge/Viem-646CFF?style=for-the-badge&logoColor=white) ![Hardhat](https://img.shields.io/badge/Hardhat-FFF04D?style=for-the-badge&logoColor=black) ![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=chainlink&logoColor=white) ![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=for-the-badge&logo=openzeppelin&logoColor=white) ![IPFS](https://img.shields.io/badge/IPFS-65C2CB?style=for-the-badge&logo=ipfs&logoColor=white)

### Additional Experience
![React Native](https://img.shields.io/badge/React_Native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![Redux](https://img.shields.io/badge/Redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)

---

# `projects/`

## 01. [Praxis](https://www.0xpraxis.tech) · [live](https://www.0xpraxis.tech)

An applied AI product that automates personalized, role-specific job application cover letters from candidate resumes and job descriptions with strict hallucination control and formatting constraints.

```
Resume (.pdf / text) ────┐
                         ├──► Context & Extraction Engine ──► Structured Prompting
Job Description (text) ──┘                                           │
                                                                     ▼
Downloadable PDF ◄── ReportLab Engine ◄── Schema Validation ◄── Groq (Llama-3 / OpenAI API)
```

**Stack:** `Next.js` `Python` `Groq API` `OpenAI API Spec` `ReportLab` `Tailwind CSS`  
**Highlights:** Automated resume parsing · requirement-matching prompt pipelines · deterministic schema-compliant generation · programmatic PDF compilation with ReportLab · [Live Demo](https://www.0xpraxis.tech)

<details>
<summary><b>🔍 View Pipeline Execution Flow & Constraints</b></summary>
<br/>

```json
{
  "pipeline": "resume_parser_v1",
  "extraction": {
    "source": "candidate_resume.pdf",
    "extracted_entities": ["core_skills", "project_history", "impact_metrics"]
  },
  "inference_layer": {
    "provider": "Groq",
    "model": "llama-3.3-70b-versatile",
    "temperature": 0.2,
    "rules": [
      "Strict grounding: Map candidate evidence directly to job requirements",
      "Zero hallucination: Reject unverifiable metric claims",
      "Format constraint: Deterministic structural layout for ReportLab PDF compilation"
    ]
  },
  "output": "tailored_cover_letter.pdf"
}
```

</details>

---

## 02. [Aave V3 Liquidation Finder Bot](https://github.com/vedantghate18/liquidation-finder-bot) · [repo](https://github.com/vedantghate18/liquidation-finder-bot)

A high-throughput, event-driven Node.js bot that streams real-time borrow events on Ethereum Mainnet to identify undercollateralized positions on Aave V3.

```
Ethereum Mainnet (Alchemy RPC)
          │
          ▼ (Real-Time Borrow Event Stream)
Viem Event Ingestion ──► Health Factor Calculation ──► Risk Classification
                                                               │
Persistent Telemetry Logs ◄── [SAFE | RISKY | LIQUIDATABLE] ◄── Polling Scheduler (60s)
```

**Stack:** `Node.js` `Viem` `Alchemy RPC` `Aave V3` `JavaScript`  
**Highlights:** Real-time event streaming via Viem · dynamic collateral & borrow balance evaluation · tri-state risk categorization (`SAFE`, `RISKY`, `LIQUIDATABLE`) · persistent disk logging for auditability

<details>
<summary><b>📊 View Sample Event Telemetry Log</b></summary>
<br/>

```text
[INFO] 2026-10-15 14:02:01 | Viem WebSocket connected to Ethereum Mainnet (Block #20451980)
[SCAN] Parsing Borrow event: User 0x8a92...4b1c | Pool: Aave V3 Pool
[EVAL] Collateral: $142,500.00 (45.2 WETH) | Total Debt: $138,200.00 (USDC)
[RISK] Computed Health Factor: 1.0312 -> Status: [RISKY] -> Warning threshold tripped
[INFO] Log entry persisted to /var/log/aave_liquidations/2026-10-15.log
```

</details>

---

## 03. [DeFi Algorithmic Stablecoin](https://github.com/vedantghate18/Defi-Stablecoin) · [repo](https://github.com/vedantghate18/Defi-Stablecoin)

An overcollateralized, exogenous-collateral stablecoin protocol inspired by DAI, engineered with automated liquidation incentives and oracle valuation.

```
User Deposits Collateral (WETH / WBTC) ──► Chainlink Price Feeds (Valuation)
                                                      │
Mint dUSD (Mint/Burn Engine) ◄────────────────────────┴── Minimum Collateral Ratio (150%)
                                                      │
Undercollateralized Position ──► Liquidation Engine ──► Collateral Seized + Bonus to Liquidator
```

**Stack:** `Solidity` `Foundry` `Chainlink Oracles` `ERC-20` `OpenZeppelin`  
**Highlights:** Algorithmic debt ceiling & collateral ratios · Chainlink oracle integration · third-party liquidation incentive mechanics · comprehensive Foundry testing suite including unit, stateful fuzz, and invariant tests

---

## 04. [Merkle Airdrop + EIP-712 Signatures](https://github.com/vedantghate18/merkle-airdrop-signatures) · [repo](https://github.com/vedantghate18/merkle-airdrop-signatures)

A gas-optimized token distribution contract combining Merkle tree proofs with off-chain cryptographic signature authorization.

```
Off-Chain Merkle Tree Generation ──► Root Stored On-Chain
                                             │
Claimant ──► EIP-712 Typed Signature ──► Relayer / Direct Claim
                                             │
Tokens Transferred ◄── ECDSA Verification + Merkle Proof Check
```

**Stack:** `Solidity` `Foundry` `EIP-712` `Merkle Trees` `Anvil`  
**Highlights:** O(log n) on-chain proof verification · EIP-712 typed-data signing for gasless delegation · full Foundry test coverage (unit, fuzz, and integration) · local deployment & verification on Anvil

---

## 05. MinimalAccount — ERC-4337 Smart Account

An account abstraction implementation exploring smart contract wallets and programmable execution flows on Ethereum.

```
UserOperation ──► EntryPoint v0.7 ──► MinimalAccount.validateUserOp()
                                                    │
Target Contract Execution ◄── MinimalAccount.execute() ◄── (Signature Verified)
```

**Stack:** `Solidity` `Foundry` `ERC-4337` `Anvil`  
**Highlights:** Conforms to ERC-4337 `UserOperation` standard · custom ECDSA signature verification · bundled execution on local Anvil · exploratory roadmap: gas profiling and native L2 account abstraction (zkSync)

---

# `learning/`

Currently diving deeper into:

- **LLM Application Architecture:** RAG pipelines, context pruning, evaluation frameworks, and agent workflows.
- **Machine Learning & Deep Learning:** Core statistics, feature engineering, loss functions, and neural network training in PyTorch.
- **Backend Systems:** High-concurrency architectures, caching layers, database indexing, and asynchronous job queues.
- **EVM Internals & Audit Methodology:** Yul/assembly patterns, storage packing, invariant test modeling, and vulnerability attack surfaces.

---

# `github_stats/`

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=vedantghate18&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vedantghate18&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

# `engineering_notes/`

Selected technical deep-dives and architectural write-ups:

- 📝 **[Taming Hallucinations in Production Document Generation](https://vedantghateportfolio.vercel.app/)** — Practical patterns for ground-truth enforcement and schema-constrained LLM output.
- 📝 **[Stateful Fuzzing & Invariant Modeling with Foundry](https://vedantghateportfolio.vercel.app/)** — Writing adversarial invariant test suites to preserve DeFi protocol solvency.
- 📝 **[Real-Time Event Processing on the EVM via Viem](https://vedantghateportfolio.vercel.app/)** — Low-latency event streaming, log decoding, and health factor math on Aave V3.

---

# `current_status`

```
╔══════════════════════════════════════════════════════════╗
║                                                          ║
║  Role: AI & Software Engineer                            ║
║  Focus: Practical AI Products • Backend • Web3           ║
║  Mode: Building → Benchmarking → Shipping                ║
║                                                          ║
║  [✓] Applied AI & LLM Systems                            ║
║  [✓] Full-Stack & Backend Engineering                    ║
║  [✓] Smart Contract Development & Testing (Foundry)      ║
║  [~] Deep Learning & PyTorch Foundations                 ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

---

# `connect`

[![Portfolio](https://img.shields.io/badge/Portfolio-vedantghateportfolio.vercel.app-10B981?style=for-the-badge&logo=vercel&logoColor=white)](https://vedantghateportfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vedant-ghate-40b622290/)
[![X](https://img.shields.io/badge/X-Follow%20%40__0xshunya__-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/_0xshunya_)
[![Email](https://img.shields.io/badge/Email-vedantghate0603%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vedantghate0603@gmail.com)

---

> *"The best way to understand complex systems—whether neural networks or decentralized protocols—is to build them from first principles."*
