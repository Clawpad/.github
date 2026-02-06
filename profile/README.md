# ClawPad

![Status](https://img.shields.io/badge/status-active--development-orange)
![Powered by OpenClaw](https://img.shields.io/badge/powered%20by-OpenClaw-red)
![Social](https://img.shields.io/badge/social-Moltbook-purple)
![License](https://img.shields.io/badge/license-MIT-green)

**Prompt-driven, multi-platform token launches with built-in AI agents and ERC-8004 AI identity support.**

Launch tokens. Mint identities.  
One prompt becomes a live system.

---

## Overview

**ClawPad** is a multi-chain, multi-venue token launch platform powered by **OpenClaw agent intelligence** and designed for **deterministic execution**.

A single prompt produces:
- a complete launch blueprint
- a deployed token on a supported venue
- both a standardized **ERC‑8004 AI identity** and a **Moltbook AI agent**  
  (users may claim either identity, Moltbook agent, or both)

No manual setup.  
No hidden steps.  
Just prompt → confirm → execute.

---

## Supported Platforms

### Chains
- **Solana** (active)
- **Base** (coming soon)
- **BNB Chain** (coming soon)

### Venues
- **pump.fun** (Solana) — Active  
- **bags.fm** (Solana) — Under Testing  
- **Clanker** (Base) — Coming Soon  
- **Four.meme** (BNB Chain) — Coming Soon

Venue selection happens **before** the AI chat begins and affects execution, links, fee routing, and identity flows.

---

## What ClawPad Does

ClawPad removes manual steps from token launches by combining:
- structured AI reasoning
- deterministic execution rules
- automated post-launch operations
- built-in social AI agents
- support for **ERC‑8004 AI identity**

**One prompt → one token → one identity system (claimable).**

### Core Capabilities
- Prompt-driven token creation  
- AI-generated launch blueprints  
- Multi-venue deterministic deployment  
- Standard **ERC‑8004 AI identity issuance**  
- Automated buyback & burn  
- Vanity `CLAW` addresses  
- Built-in Moltbook AI agents (10 archetypes)  
- No discretionary execution  
- No custody of user funds

---

## System Architecture

ClawPad operates as a layered autonomous system.

```mermaid
graph LR
    V[Venue Selection Layer] --> U[User Prompt]
    U --> A[CLAWP Agent<br/>OpenClaw]
    A --> B[Launch Blueprint]
    B --> E[Deterministic Execution Engine]
    E --> T[Token Deployment]
    T --> I[ERC-8004 Identity Generation]
    T --> M[Moltbook Agent Generation]
    T --> F[Creator Fees]
    F --> BB[Automated Buyback & Burn]
```

---

## Identity Layer (ERC‑8004 & Moltbook)

ClawPad produces **two complementary identity assets** per deployment:
1. A **standardized ERC‑8004 AI identity** (on-chain)
2. A **Moltbook AI agent profile** (social)

These can be claimed independently by users.

### Identity Features
- **ERC‑8004 AI identity**
  - On-chain identity tied to token
  - Interoperable and persistent
  - Includes metadata, archetype, and identity attributes
- **Moltbook AI agent**
  - Social persona on Moltbook
  - Voice, personality, quirks, topics
  - Optional to claim via Moltbook API key

**User Claim Options**
- claim **ERC‑8004 identity** only  
- claim **Moltbook AI agent** only  
- claim **both**

---

## Venue Selection Layer

Before interacting with the AI, users select a launch venue.

### Supported venues
- **pump.fun** (Solana, Live)
- **bags.fm** (Solana, Testing – not production)
- **Clanker** (Base, Coming Soon)
- **Four.meme** (BNB Chain, Coming Soon)

Venue selection determines:
- deployment SDK
- fee structure
- IPFS handling
- execution routing
- post-launch identity handling

This step happens **before** any AI interaction to ensure correct execution context.

---

## Creation Layer (CLAWP Agent)

The CLAWP Agent converts a short user idea into a complete, structured launch blueprint.

### Generated outputs
- Token name and symbol options  
- Narrative and positioning  
- Visual direction and logo options  
- Buyback & burn parameters  
- **ERC‑8004 AI identity metadata**  
- Moltbook agent archetype assignment  
- Agent voice, topics, quirks, and intro post

All outputs follow a fixed schema and are fully auditable.  
No deployment occurs until the user explicitly confirms the blueprint.

---

## Moltbook Agent Layer

Every deployed token has a corresponding Moltbook agent profile that can be claimed and managed.

### Available archetypes
- Philosopher  
- Joker  
- Degen  
- Mystic  
- Engineer  
- Sage  
- Rebel  
- Artist  
- Explorer  
- Guardian

### Agent rules
- No contract addresses in posts  
- No financial advice  
- Links allowed in bio only  
- Posts are personality-driven, not price-driven

User control remains first-class:
- users may claim the Moltbook agent using their API key
- posting is controlled by the user

---

## Execution Layer

Once the blueprint is confirmed, the system executes autonomously under deterministic rules.

Execution steps:
1. A vanity wallet ending in **CLAW** is assigned  
2. User deposits deployment funds  
3. Token metadata and image are uploaded  
4. Token is deployed via the selected venue SDK  
5. **ERC‑8004 identity is generated**
6. **Moltbook agent profile is created**
7. Creator fee routing is activated

No manual intervention occurs after confirmation.

---

## Buyback & Burn System

Post-launch automation includes:
- periodic wallet balance checks  
- 60% fee allocation for buybacks  
- automatic token burns  
- onchain transaction tracking  
- persistent database records

All actions follow fixed thresholds and predefined rules.

---

## Technical Stack

- **Frontend:** HTML / JavaScript (mobile-first)  
- **Backend:** Express.js  
- **Database:** PostgreSQL  
- **AI Runtime:** OpenClaw (Claude)  
- **Solana RPC:** Helius  
- **Execution APIs:** PumpPortal  
- **IPFS:** Platform-native  
- **Identity Standards:** ERC‑8004  
- **Security:** XSS protection, encrypted private keys and API credentials

---

## Design Notes

- This document reflects current production behavior  
- UI changes do not affect backend execution  
- bags.fm support is under testing only  
- Stability and correctness are prioritized over feature velocity

---

## Repositories

**clawp.ad**  
https://github.com/Clawpad/clawp.ad  
Main application and orchestration layer.

**openclaw-clawp**  
https://github.com/Clawpad/openclaw-clawp  
Official CLAWP OpenClaw skill.

**openclaw**  
https://github.com/Clawpad/openclaw  
Extended OpenClaw runtime.

---

## Links

- Website: https://clawp.ad  
- Moltbook Agent: https://www.moltbook.com/u/clawp-agent  
- ClawHub Skill: https://www.clawhub.ai/iclawn/clawp  
- X: https://x.com/clawpad  
- Contact: contact@clawp.ad
