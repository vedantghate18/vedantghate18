<div align="center">

# Vedant Ghate

### AI & Software Engineer | Building AI-Powered Applications, Backend Systems & Web3 Infrastructure

<p align="center">
  <a href="https://vedantghateportfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-vedantghateportfolio.vercel.app-10B981?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/vedant-ghate-40b622290/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/_0xshunya_"><img src="https://img.shields.io/badge/X-Follow%20%40__0xshunya__-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="mailto:vedantghate11@gmail.com"><img src="https://img.shields.io/badge/Email-vedantghate11%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

</div>

I am a software engineer focused on building practical AI-powered applications, resilient backend services, and decentralized infrastructure. I enjoy taking ideas from initial concept to working software—combining modern full-stack architectures, LLM orchestration, and smart-contract logic into reliable, well-tested systems.

---

## 🔭 About Me

- 🤖 **Applied AI & Intelligent Workflows:** Designing end-to-end applications that integrate LLMs for document processing, structured generation, and workflow automation.
- ⚙️ **Backend & Full-Stack Development:** Architecting responsive frontends and modular backend APIs using Next.js, Node.js, Python, and modern relational/document databases.
- ⛓️ **Blockchain & Smart Contract Specialization:** Deep technical experience in Solidity protocol engineering, Foundry test suites (unit, fuzz, invariant), and EVM mechanics.
- 🛠️ **Systems & Code Quality:** Prioritizing clear architecture, reproducible development environments, automated testing, and clean, maintainable code.

---

## 🚀 Featured Projects

### 1. [Praxis — AI-Powered Application Writing](https://www.0xpraxis.tech)
*An applied AI application that automates the generation of tailored, role-specific job application cover letters from resumes and job descriptions.*

- **Full-Stack Architecture:** Built with a Next.js frontend interface and a Python backend service handling parsing and generation pipelines.
- **LLM Integration & Inference:** Leverages Groq-hosted open LLMs accessed through the OpenAI-compatible API for fast inference and high contextual accuracy.
- **Document & Context Processing:** Extracts structured candidate history from uploaded resumes and cross-references key requirements from target job descriptions.
- **Controlled Generation:** Employs structured prompts and validation rules to ensure high-relevance output while preventing generic boilerplate and hallucinations.
- **Automated Document Compilation:** Integrates ReportLab to programmatically compile and format generation results into clean, downloadable PDFs.
- **Links:** [Live Application](https://www.0xpraxis.tech) · `[Repository: Private / Available on Request]`

---

### 2. [Aave V3 Liquidation Finder Bot](https://github.com/vedantghate18/liquidation-finder-bot)
*An event-driven monitoring bot that tracks Aave V3 lending positions on Ethereum Mainnet to identify undercollateralized borrow positions.*

- **Event-Driven Ingestion:** Subscribes to and processes real-time `Borrow` logs across Aave V3 contracts via Viem and Alchemy RPC endpoints.
- **Risk Categorization:** Evaluates collateral and debt balances on-chain, calculating user health factors and classifying positions as `SAFE`, `RISKY`, or `LIQUIDATABLE`.
- **Telemetry & Logging:** Implements structured persistent logging for historical position analysis and auditability.
- **Configurable Scheduling:** Built with configurable polling intervals (default: 60s) for steady-state data retrieval without hitting RPC rate limits.
- **Links:** [GitHub Repository](https://github.com/vedantghate18/liquidation-finder-bot)

---

### 3. [DeFi Algorithmic Stablecoin Protocol](https://github.com/vedantghate18/Defi-Stablecoin)
*An overcollateralized, exogenous-collateral decentralized stablecoin system implemented in Solidity and tested rigorously with Foundry.*

- **Core Protocol Logic:** Implements an ERC-20 stablecoin with collateral deposit, minting, and burning logic governed by algorithmic collateral ratio checks.
- **Oracle Valuation:** Connects with Chainlink decentralized price feeds to establish real-time asset pricing for collateral calculations.
- **Liquidation Mechanics:** Features an automated liquidation function that incentivizes third-party liquidators with a collateral discount to preserve protocol solvency.
- **Comprehensive Testing:** Validated with a Foundry test suite spanning unit tests, fuzz testing, and stateful invariant tests to enforce solvency invariants under adversarial conditions.
- **Links:** [GitHub Repository](https://github.com/vedantghate18/Defi-Stablecoin)

---

### 4. [Merkle Airdrop + EIP-712 Signatures](https://github.com/vedantghate18/merkle-airdrop-signatures)
*A gas-efficient token distribution smart contract combining cryptographic Merkle trees with off-chain signature authorization.*

- **Merkle Proof Verification:** Verifies claim eligibility on-chain using cryptographic Merkle proofs, avoiding expensive on-chain whitelist storage.
- **EIP-712 Signature Authorization:** Implements typed-data hashing and ECDSA signature recovery, allowing eligible claimants to delegate claims gaslessly.
- **Testing & Verification:** Developed in Foundry with local Anvil deployments, unit testing, and edge-case fuzz tests.
- **Links:** [GitHub Repository](https://github.com/vedantghate18/merkle-airdrop-signatures)

---

### 5. MinimalAccount — ERC-4337 Smart Account
*An account abstraction implementation exploring smart contract wallets and custom execution flows on Ethereum.*

- **EntryPoint Integration:** Implemented smart account verification and execution logic conforming to the ERC-4337 `UserOperation` standard.
- **Local Validation:** Tested and deployed on local Anvil nodes with custom signature validation and bundled execution.
- **Exploratory Scope:** Ongoing exploration of gas optimization patterns, testnet deployment, and L2 native account abstraction (e.g., zkSync).
- **Status:** Local Implementation · `[Repository Placeholder]`

---

## 🛠️ Tech Stack

### Applied AI & Data
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F05A28?style=for-the-badge&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch_(Learning)-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

### Software & Backend Engineering
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### Blockchain & Web3
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-black?style=for-the-badge&logo=ethereum&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Viem](https://img.shields.io/badge/Viem-1E1E1E?style=for-the-badge&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF04D?style=for-the-badge&logoColor=black)
![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=chainlink&logoColor=white)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=for-the-badge&logo=openzeppelin&logoColor=white)
![IPFS](https://img.shields.io/badge/IPFS-65C2CB?style=for-the-badge&logo=ipfs&logoColor=white)

### Additional Experience
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)

---

## 📚 Current Learning & Technical Growth

- **LLM Application Architecture:** Studying advanced prompt engineering, context management, structured model outputs, and evaluation workflows for practical AI applications.
- **Machine Learning Fundamentals:** Strengthening core machine learning concepts, data preprocessing, and evaluation metrics using scikit-learn.
- **Deep Learning Foundations:** Exploring neural network fundamentals, tensor computation, and training loops using PyTorch.
- **Backend Architecture & APIs:** Deepening knowledge of backend system design, database indexing, API reliability, and asynchronous processing.
- **EVM Internals & Smart Contract Security:** Practicing Foundry invariant and stateful fuzz testing, opcode inspection, and vulnerability patterns.

---

## 🎯 Areas of Interest

- **Applied AI Products:** Developing useful software where machine learning models and LLMs solve concrete user problems.
- **Full-Stack & Backend Engineering:** Building performant services, clean REST APIs, and responsive web experiences.
- **Web3 & Protocol Infrastructure:** Designing secure on-chain mechanisms, financial primitives, and event-driven monitoring tools.

---

## 📊 GitHub Analytics

<div align="center">

<img height="150em" src="https://github-readme-stats.vercel.app/api?username=vedantghate18&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Vedant's GitHub Stats" />
<img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vedantghate18&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />

</div>

---

## 📬 Let's Connect

- **Portfolio:** [vedantghateportfolio.vercel.app](https://vedantghateportfolio.vercel.app/)
- **LinkedIn:** [linkedin.com/in/vedant-ghate-40b622290](https://www.linkedin.com/in/vedant-ghate-40b622290/)
- **X / Twitter:** [@_0xshunya_](https://x.com/_0xshunya_)
- **Email:** [vedantghate11@gmail.com](mailto:vedantghate11@gmail.com)

---

<p align="center">
  <em>Building software with purpose—from applied AI applications to resilient backend and on-chain systems.</em>
</p>
