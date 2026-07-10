<h1 align="center">Hi, I'm Muzammil (Eunum) 👋</h1>

<h3 align="center">Full-Stack Web3 Builder · Smart Contracts · Frontend & Backend Systems</h3>

<p align="center">
  Building secure, end-to-end decentralized applications. From low-level EVM execution to high-performance client interfaces and robust backend services.
</p>

---

## 📚 About Me

I am a **Full-Stack Web3 Builder** driven by a passion for understanding how decentralized systems work under the hood. Rather than specializing in just one layer of the stack, I focus on the entire lifecycle of decentralized products. I design secure smart contracts, build responsive frontends, implement robust backends, and integrate oracle/infra systems.

- **EVM & Protocols**: Deep interest in EVM internals, storage layouts, and low-level execution semantics.
- **End-to-End Execution**: Experienced in bridging the gap between blockchain state and user interfaces using modern Web3 libraries.
- **Security & Testing**: Emphasize building production-ready protocols backed by strict testing suites (unit, integration, fuzzing, and invariant tests in Foundry).

---

## 🛠️ The Builder Stack

### 🧱 Smart Contracts & Protocol Logic

- **Languages & Frameworks**: Solidity, Foundry, Hardhat, OpenZeppelin
- **Key Concepts**: Upgradeability (UUPS/Transparent), Access Control, Token Standards (ERC-20/721/1155), Account Abstraction (ERC-4337)
- **Security & Testing**: Fuzz & Invariant testing, gas profiling, static analysis, storage collision prevention

### 🌐 Frontend & User Experience

- **Frameworks & State**: React, Next.js, TypeScript, Tailwind CSS, shadcn/ui
- **Web3 Integration**: wagmi, viem, Ethers.js, Web3Modal, RainbowKit
- **Client Performance**: Optimized state synchronization, caching chain queries, reactive UI design

### ⚙️ Backend & Infrastructure

- **Services & DBs**: Node.js, Express, MongoDB, PostgreSQL, REST APIs
- **Oracles & Automation**: Pyth Network, Chainlink (Data Feeds, VRF, Automation, Functions)
- **DevOps & Tooling**: Git/GitHub, Docker, IPFS, deployment scripting, local testnets (Anvil/Hardhat)

---

## 🔨 Highlighted Projects

### ⏳ [Delay Protocol](https://github.com/0xEunum/delay-protocol)

**A tokenized, delayed native-asset transfer primitive built on Ethereum with liquid representation.**
_Built for Ethereum Build Camp (by AyaCommunity, on the Road to Devcon VIII with EFDevcon)._

- **The Stack**: Solidity, Foundry, Node.js + Ethers.js Keeper Bot, React, TypeScript, Vite, Wagmi.
- **Under the Hood**: Enables delayed native ETH transfers with an enforced timelock buffer. Senders retain cancellation rights, and recipients receive tradeable **DToken** claims. An automated off-chain keeper bot daemon polls events and settles claims trustlessly.

### 📈 [HelixFi](https://github.com/0xEunum/helixfi)

**Trustless limit order protocol on Conflux eSpace.**
_Submitted to Conflux Network Global Hackfest 2026._

- **The Stack**: Solidity, Pyth Network Oracles, Swappi Router (Uniswap V2-compatible), Wagmi v2, Viem, React, Node.js.
- **Under the Hood**: Uses `HelixOrderBook.sol` to escrow tokens. Validates price freshness (≤60s) and signatures on-chain using Pyth Network push oracle data, then routes swaps through Swappi. Includes an open-source, gas-optimized backend keeper bot network.

### 🛡️ [Simple AA Wallet](https://github.com/0xEunum/Simple-AA-Wallet)

**ERC-4337 Account Abstraction** simulation built from scratch to run on a local Anvil chain and bundler.

- **Under the Hood**: Simulates off-chain user operations, constructs and signs UserOps, and verifies signatures on-chain via entry point interaction.

### 🔄 [Cross-Chain Rebase Token](https://github.com/0xEunum/foundry-Rebase-Token)

**Elastic supply token protocol** featuring cross-chain transfers using CCIP-style burn-and-mint mechanisms and oracle-driven rebasing.

- **Under the Hood**: Employs fixed-point precision math to handle dynamic balance updates and utilizes automated oracle triggers for state synchronization.

---

## 🏅 Certifications & Education

**Cyfrin Updraft - Smart Contract Engineering & Web3 Track**

- Blockchain Basics & Advanced Solidity ✅
- Foundry Fundamentals & Advanced Testing (Fuzzing, Invariants) ✅
- Chainlink Fundamentals & Oracle Design ✅
- Full-Stack Web3 Development (Frontend & Client Integration) ✅

---

## 🔗 Connect

<p align="center">
  <a href="https://linkedin.com/in/0xeunum">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://x.com/0xEunum">
    <img src="https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://t.me/x0eunum">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?&logo=telegram&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:0xeunum@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" />
  </a>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://awesome-github-stats.azurewebsites.net/user-stats/0xEunum?cardType=github&theme=dark" />
  <br/>
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=0xeunum&layout=compact&theme=dark" />
</p>

---

> 🛠️ Let's design, deploy, and scale robust decentralized systems together.
