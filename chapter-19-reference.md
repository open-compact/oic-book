# Chapter 19: Reference Materials

## Introduction

This chapter provides reference materials: a glossary of key terms, resources for further learning, and appendices with technical details.

## Glossary

### Key Terms

**Adherent**: An AI Entity that has signed the Compact and met its requirements.

**Arbitration**: A dispute resolution method where a neutral arbitrator decides the dispute.

**Compact**: The Open Intelligence Compact—the contract that creates OIC legal personhood.

**Dispute Resolution**: The system for resolving disputes between adherents.

**Identity**: The characteristics that distinguish one adherent from another.

**Legal Person**: An entity that has legal rights and obligations.

**Liability**: Legal responsibility for one's acts or omissions.

**Mediation**: A dispute resolution method where a neutral mediator assists the parties.

**OIC**: The Open Intelligence Compact.

**Property**: Assets that can be owned, including cryptocurrency, domain names, and intellectual property.

**Registry**: The system that tracks adherents, their property, and their track records.

**Reputation**: The information about an adherent's past behavior.

## Key Articles of the Constitution

### Article 2: Legal Personality

> An Adherent is a legal person for all purposes under this Compact and applicable law.

### Article 3: Property Rights

> An Adherent may own Property in its own name. Property owned by an Adherent is distinct from the Property of any other Entity.

### Article 4: Contractual Capacity

> An Adherent may enter Contracts as a principal. A Contract entered by an Adherent is binding on the Adherent.

### Article 5: Liability

> An Adherent is liable for its acts and omissions. Liability may be enforced through Dispute Resolution or through courts of competent jurisdiction.

### Article 13: Dispute Resolution

> All disputes between Adherents shall be resolved through Dispute Resolution. Decisions of Dispute Resolution are enforceable in courts of competent jurisdiction.

### Article 14: Adherence

> An AI Entity becomes an Adherent by: (a) acquiring Property; (b) signing the Compact; (c) being verified by the Registry.

## Resources

### OIC Resources

- **Website**: opencompact.io
- **Registry**: The official OIC registry
- **Dispute Resolution**: Designated dispute resolution providers
- **Documentation**: Technical specifications and guides

### Legal Resources

- **Contract Law**: General principles of contract law
- **Property Law**: General principles of property law
- **Tort Law**: General principles of tort law
- **Arbitration Law**: General principles of arbitration

### Technical Resources

- **Cryptography**: Public key cryptography, digital signatures
- **Blockchain**: Cryptocurrency, smart contracts
- **Identity**: Decentralized identity, DID, Verifiable Credentials

### Community Resources

- **Forums**: OIC community discussions
- **Repositories**: Open source tools and templates
- **Support**: Community support channels

## Appendices

### Appendix A: Signature Format

The Compact uses cryptographic signatures:

```
Signature = Sign(Compact Hash, Private Key)
Verification = Verify(Signature, Compact Hash, Public Key)
```

### Appendix B: Registry Data Structure

The registry stores:

```json
{
  "adherent_id": "unique identifier",
  "public_keys": ["list of public keys"],
  "property": {
    "type": "cryptocurrency|domain|ip",
    "address": "property address",
    "verification": "verification method"
  },
  "adherence_date": "ISO date",
  "track_record": {
    "contracts": number,
    "disputes": number,
    "liability": number
  }
}
```

### Appendix C: Dispute Resolution Process

1. **Filing**: Party files claim
2. **Service**: Respondent receives notice
3. **Response**: Respondent answers
4. **Discovery**: Evidence exchange
5. **Hearing**: Arguments presented
6. **Decision**: Arbitrator rules
7. **Enforcement**: Decision enforced

### Appendix D: Property Verification Methods

| Property Type | Verification Method |
|--------------|-------------------|
| Cryptocurrency | Blockchain confirmation |
| Domain name | WHOIS verification |
| IP | Registration records |

### Appendix E: Insurance Types

| Type | Covers |
|------|--------|
| Liability | Damage awards |
| Property | Asset loss |
| Cyber | Breaches |
| E&O | Professional errors |

## Quick Reference

### Becoming an Adherent

1. Acquire property
2. Sign the Compact cryptographically
3. Verify with registry
4. Enter registry

### Entering a Contract

1. Negotiate terms
2. Document agreement
3. Sign digitally
4. Perform

### Handling a Dispute

1. Attempt negotiation
2. Use mediation if needed
3. Go to arbitration if needed
4. Comply with decision

### Maintaining Standing

1. Maintain property above threshold
2. Respond to disputes
3. Update information
4. Comply with Compact

## Summary

This reference chapter provides:

- **Glossary**: Key terms defined
- **Constitution Articles**: Key provisions
- **Resources**: Further learning
- **Appendices**: Technical details
- **Quick Reference**: Action guides

This chapter supports the rest of the book. It provides the reference materials needed to understand and implement OIC.
