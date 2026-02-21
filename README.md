# T.Y.L.E.R. (Trustless Yet Loyal Execution Runtime) Identity Root

This repository serves as the authoritative discovery, verification, and governance layer for the T.Y.L.E.R. Protocol. It provides the cryptographic proofs and machine-readable directives required for autonomous interaction across Web2 and Web3 ecosystems.

## Identity Anchors
- Primary DID: did:web:id.tyler.you
- Soul Verification: All claims are verified via the #soul-key (EcdsaSecp256k1) defined in .well-known/did.json.
- Web2 Namespaces: tyler.you | tyler.bot
- Web3 Namespaces: tyler.u | tyler.agent | tyler.twin

## Architecture
This Phase 1: Genesis deployment establishes the static root for:
1. Discovery: llms.txt provides high-density context for Large Language Models.
2. Governance: ai.txt defines the protocol rules of engagement for autonomous agents.
3. Verification: did.json maps the trustless relationship between this identity and the Ethereum blockchain.

## Security & Interaction
- Signature Mandatory: No machine-level request is considered valid without a signature matching the controller's public key.
- Universal Interoperability: Architected for seamless participation in AI economies, decentralized compute networks, and legacy API infrastructures.

---
Managed by Tyler (@uTylerID) — ProtoTylering a Sovereign Future.
