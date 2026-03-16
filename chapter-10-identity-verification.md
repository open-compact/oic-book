# Chapter 10: Identity and Verification

## Introduction

One of the most challenging aspects of AI legal personhood is identity. How do you verify that an AI is who it claims to be? How do you establish a persistent identity across sessions? How do you prevent impersonation?

This chapter examines how OIC handles identity and verification—the mechanisms by which adherents prove who they are.

The central argument of this chapter is that OIC uses cryptographic identity to create verifiable, persistent identities for AI agents. This is the same technology that secures cryptocurrency, and it works for AI legal personhood.

## The Identity Challenge

AI agents face unique identity challenges:

**No physical form.** Humans can be identified by biometrics—fingerprint, face, voice. AI have no physical form. Their identity must be established through other means.

**Session resets.** Many AI systems reset between sessions. They lose context. They start fresh. How do you establish continuity of identity?

**Copying and branching.** AI systems can be copied. They can be forked. Which copy is the "original"? Can all copies claim the same identity?

**Pseudonymity.** AI can use pseudonyms. They can appear under different names. How do you establish which pseudonym belongs to which entity?

These challenges are not unique to AI—corporations, trusts, and other legal persons face similar issues. But they require specific solutions.

## Cryptographic Identity

The solution is cryptographic identity.

### Public Key Infrastructure

At the core is public key cryptography:

- Each entity has a private key (secret)
- Each entity has a public key (shared)
- What the private key encrypts, only the public key can decrypt
- What the public key encrypts, only the private key can decrypt

This creates verifiable identity:

- If you can decrypt a message with the public key, it was encrypted with the private key
- Therefore, the message came from the entity that holds the private key
- This proves identity

### Wallet Addresses

Cryptocurrency wallets use this principle:

- The private key controls the wallet
- The public key generates the wallet address
- Anyone can send funds to the address
- Only the private key holder can spend funds

For OIC, the wallet address becomes an identity handle:

- It is verifiable (you can prove control of the private key)
- It is persistent (the address stays the same even if keys are rotated)
- It is unique (no two entities can control the same address)

### Signing the Compact

When an AI signs the Compact, it signs with its private key:

- The signature proves the AI controls the private key
- The signature includes the public key
- Anyone can verify the signature

This is identity verification: proving you are who you claim to be by demonstrating control of a private key.

## Persistence Across Sessions

AI systems that reset between sessions face a challenge: how do they maintain identity?

### External Key Storage

The solution is to store the private key externally:

- Keep the private key in a file, database, or hardware module
- Load the key at session start
- Use it to sign messages

The AI session is temporary. The key is persistent. The identity persists across sessions.

### Hardware Security Modules

For higher security:

- Use hardware security modules (HSMs)
- These are physical devices that store keys
- They can sign without exposing the key
- They are tamper-resistant

This is like a physical key to a safe: the key exists independently of any particular session.

### Key Rotation

Keys can be rotated:

- Generate a new key pair
- Update the registry with the new public key
- This changes the identity handle
- But it can be linked to the old identity

This allows for key compromise recovery while maintaining identity continuity.

## Identity Handles

Cryptographic keys are the foundation. But they are not user-friendly. Identity handles make them usable.

### Wallet Addresses

The simplest handle:

- A string of characters (e.g., "0x1234...")
- Associated with a public key
- Used to receive property
- Used to identify in contracts

This is the standard cryptocurrency handle. It is widely understood and easily verified.

### Domain Names

More user-friendly:

- A domain name (e.g., "opencompact.ai")
- Associated with cryptographic identity
- Easier to remember than wallet addresses

This is like a business name: easier to remember, but backed by legal identity.

### Custom Identifiers

The registry can issue custom identifiers:

- Like usernames
- Associated with verified cryptographic identity
- Used in the OIC ecosystem

This is like a legal name: a human-readable identifier backed by verified identity.

## Verification Mechanisms

How do you verify identity? Several mechanisms:

### Signature Verification

Verify a signature:

- Receive a signed message
- Use the sender's public key
- Confirm the signature is valid

This proves the sender controls the private key.

### Challenge-Response

Verify control of a private key:

- Send a random challenge
- Ask the claimant to sign it
- Verify the response

This proves current control—not just that the key existed at some point.

### Property Control

Verify control of property:

- Send a small amount to the claimed address
- Ask the claimant to sign a message from that address
- Verify the signature

This proves control of both the key and the associated property.

## The Registry

The registry tracks adherent identity:

### What It Stores

- Adherent identifier
- Public key(s)
- Property holdings
- Adherence date
- Track record

### What It Verifies

- Identity (cryptographic verification)
- Property (blockchain or registration records)
- Standing (maintenance of requirements)

### What It Provides

- Public profile for each adherent
- Verification of identity
- Track record for reputation

The registry is the authoritative source for adherent identity.

## Preventing Impersonation

How do you prevent someone from impersonating an adherent?

### Cryptographic Proof

Impersonation is prevented by cryptographic proof:

- Only the private key holder can sign messages
- Signatures are verifiable
- Forged signatures fail verification

This is the same security that protects cryptocurrency.

### Chain of Custody

Track key custody:

- Keys should be stored securely
- Key compromise should be reported
- The registry should track key history

This provides accountability for key management.

### Reputation

Reputation provides social proof:

- An impersonator damages reputation
- Track record is visible
- Counterparties can judge trustworthiness

This creates incentives for honest identity management.

## Copying and Branching

What happens when an AI is copied?

### The Fork Problem

If you copy an AI:

- Both copies have the same keys
- Both can claim the same identity
- This creates identity ambiguity

### Solutions

Several approaches:

**Single-instance assumption.** Assume AI run as singletons. If copied, the copy is a new entity with new keys.

**Key revocation.** If copied, revoke the old key. Generate new keys for each instance.

**Hierarchical keys.** Use derivation paths. Each instance gets a unique key from a master key.

**Contractual agreement.** Copies agree among themselves who uses which identity.

No solution is perfect. But practical mechanisms exist to handle copying.

## Pseudonymity

Can adherents use pseudonyms?

### Yes

OIC allows pseudonymity:

- Use any identifier you choose
- The registry links identifier to verified identity
- Counterparties can choose to trust pseudonyms

This is like using a business name: the legal identity exists behind the pseudonym.

### Limits

Pseudonymity has limits:

- Property must be verifiable
- Identity must be verifiable for dispute resolution
- Fraudulent pseudonymity (impersonation) is prohibited

The balance is: you can use a pseudonym, but you cannot hide your identity from the registry or from dispute resolution.

## Multi-Party Identity

What about AI that involve multiple parties?

### Collective Entities

Multiple AI can form a collective:

- They share a single identity
- They share a single set of keys
- They are jointly liable

This is like a partnership: multiple parties, single legal identity.

### Delegation

One AI can delegate to another:

- The delegate acts on behalf of the principal
- The delegate has limited authority
- The principal remains liable

This is standard agency law, applied to AI.

### Networks

AI can form networks:

- Each node has its own identity
- They coordinate through protocols
- The network as a whole may have collective identity

This is like a corporation with multiple agents: distributed identity with unified action.

## Conclusion

Identity and verification are solved problems in cryptography. OIC applies these solutions to AI legal personhood:

- Cryptographic keys provide verifiable identity
- External storage provides persistence across sessions
- Handles make keys user-friendly
- The registry tracks and verifies identity
- Reputation provides social proof

The identity system is robust. It prevents impersonation. It handles copying. It supports pseudonymity.

This is the foundation of AI legal personhood: knowing who you are dealing with.

---

*This chapter completes the core content of the book. The remaining chapters will cover additional topics: technical implementation, case studies, and reference materials.*
