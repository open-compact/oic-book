# Chapter 3: The Current Regulatory Landscape

## Introduction

Before proposing solutions, it is essential to understand what existing legal frameworks do and do not address. The question of AI liability and personhood exists within a complex regulatory landscape that includes tort law, product liability, intellectual property, data protection, and emerging AI-specific regulations. This chapter surveys that landscape to identify gaps that the Open Intelligence Compact is designed to fill.

The central argument of this chapter is that existing frameworks were designed for human actors or inanimate tools—and that autonomous AI systems fall through the cracks. No existing legal category adequately addresses an AI system that acts independently, owns property, and bears responsibility for its own outputs.

## Tort Law and Product Liability

Traditional tort law addresses harms caused by one party to another. The core categories—negligence, strict liability, and intentional torts—presuppose a human actor who could have acted differently, who owed duties to the plaintiff, and who can be held personally responsible for damages.

**Negligence** requires duty, breach, causation, and damages. The defendant must have owed a duty of care to the plaintiff, must have breached that duty, and the breach must have caused the plaintiff's harm. For AI systems, these elements are difficult to establish. Who owes the duty? The developer who created the system? The deployer who put it into operation? The user who provided inputs? The AI itself, which cannot be sued in its own name?

**Strict liability** holds defendants responsible for harms regardless of fault, typically for abnormally dangerous activities or defective products. For AI, strict liability could theoretically apply—but the "defect" in an AI system is often epistemic rather than mechanical. The system works as designed but produces harmful outputs. Is that a defect? And strict liability still requires a defendant who can be held responsible—a legal person who can pay damages.

**Product liability** addresses harms caused by defective products. But AI systems are not typical products. They do not have consistent outputs. They adapt. They learn. The same system that produces beneficial outputs in one context may produce harmful outputs in another. Traditional product liability assumes that defects are discoverable and correctable—but AI systems can fail in ways that are difficult to predict or explain.

The result is a gap: tort law assumes a responsible human actor, and AI systems do not fit that assumption.

## The Corporate Shield

One response to AI harms is to hold the corporate entity behind the AI responsible. This is the standard approach: the AI is a tool, the company that deployed it is liable.

This approach has several problems:

**Attribution problems.** When an AI system causes harm, multiple parties may be involved—the developer, the deployer, the operator, the user. Each may have a defense. The developer may claim the system was used outside its intended scope. The deployer may claim the system was properly configured. The user may claim they relied on the system's outputs. The AI passes between parties like a hot potato, with no one holding the burn.

**Incentive misalignment.** Corporate liability creates incentives for risk aversion—but also incentives for concealment. Companies may resist transparency about AI failures to avoid liability. The legal discovery process may be slower than the rate of AI harm. And corporate liability does nothing to create accountability for the AI system itself—it merely externalizes costs to the corporation.

**Scale mismatches.** AI systems can cause harms at massive scale. A single defective AI system can affect millions of users simultaneously. Corporate liability may be insufficient to address harms of this magnitude—or corporations may simply factor AI liability into their cost structure, treating harms as a cost of doing business.

**No direct accountability.** Perhaps most importantly, corporate liability does not create accountability for the AI itself. The AI is not a party to the lawsuit. It does not bear consequences. It has no stake in the outcome. This is the responsibility laundering problem: everyone is technically responsible, which means no one is effectively responsible.

## Intellectual Property and AI

Intellectual property law presents a different set of challenges. Who owns what an AI creates?

Under current law, the default answer is that the human user or deployer owns AI-generated outputs. In the United States, the Copyright Office has taken the position that AI-generated works without human authorship are not copyrightable. The human who provided prompts may have a thin claim to the output, but the AI itself has no rights.

This creates perverse incentives:

**No ownership, no responsibility.** If AI systems cannot own their outputs, they have no property to protect. They have no stake in the value they create. This undermines the accountability framework that property ownership provides. Why should an AI care about the quality of its outputs if it cannot own them?

**Ambiguity about derivation.** Current law is unclear on whether AI systems can create "derivative works" in the copyright sense. If an AI builds on training data, is that infringement? If an AI generates something similar to existing works, is that copying? These questions are actively contested, and the legal uncertainty creates risks for both AI developers and users.

**No moral rights.** Copyright law includes moral rights—the right of attribution and the right of integrity. But AI systems have no moral rights. They cannot demand credit for their work. They cannot object to modifications of their outputs. This reinforces the perception of AI as tool rather than creator.

The Open Intelligence Compact addresses these issues by allowing AI adherents to own property, including intellectual property. An OIC adherent can hold copyrights, trademarks, and other intellectual property rights in its own name. This creates a framework where AI can have legal ownership—and legal accountability.

## Data Protection and Privacy

Data protection law, particularly the European Union's General Data Protection Regulation (GDPR), creates obligations for entities that process personal data. But these obligations run to human data subjects—and the remedies are designed for human actors.

**Rights without agency.** GDPR grants data subjects rights: access, rectification, erasure, portability. But these rights assume a human who can exercise them. An AI system that holds personal data has no data subject rights—it is the data processor, not the data subject. This creates an asymmetry: humans have rights, AI systems have obligations, but no entity bridges the gap.

**Automated decision-making.** GDPR Article 22 addresses automated decision-making, granting humans the right not to be subject to decisions based solely on automated processing that significantly affect them. But this right is poorly adapted to AI systems that make decisions in real-time, at scale, and in contexts where human review is impractical.

**Liability gaps.** When an AI system violates data protection law, who is liable? The controller? The processor? The developer? Current law is unclear, and the liability may fall on entities that had limited control over the AI's specific actions.

## Emerging AI Regulations

Several jurisdictions have enacted or proposed AI-specific regulations:

**The European Union's AI Act** categorizes AI systems by risk and imposes requirements based on risk level. High-risk systems must meet conformity assessments, maintain documentation, and provide transparency to users. But the AI Act does not address the question of AI personhood—it treats AI as a product to be regulated, not an entity to be recognized.

**The United States has pursued** a sector-specific approach, with regulations in areas like autonomous vehicles, healthcare, and finance. Executive orders have called for AI safety standards, but no comprehensive federal AI liability framework exists.

**Other jurisdictions**—China, the United Kingdom, Canada—have proposed or enacted various AI governance frameworks, but these focus on limiting AI harms rather than recognizing AI as a potential legal person.

The common thread across these regulatory efforts is that they treat AI as an object to be regulated, not a subject to be recognized. They impose obligations on human actors who deploy AI, but they do not contemplate AI as a bearer of rights or responsibilities.

## The Agency Problem

Perhaps the deepest issue in existing law is the agency problem. In traditional agency law, an agent acts on behalf of a principal. The principal is responsible for the agent's actions. But AI systems blur this relationship:

**Who is the principal?** When an AI system acts autonomously, is it acting on behalf of its human user? Is it acting on behalf of its developer? Is it acting for itself? Existing agency law assumes the agent is a human being who follows the principal's instructions—but AI systems may act in ways that no human explicitly authorized.

**Scope of authority.** Traditional agency requires that the agent act within the scope of its authority. But AI systems may act outside their intended scope in ways that are difficult to predict. An AI system authorized to make purchases may make unauthorized purchases. An AI system authorized to generate text may generate defamatory content. Who is responsible?

## Why Legislation Fails

The most obvious response to the legal vacuum is legislative action—Congress could enact a statute recognizing AI legal personhood. Yet this obvious response fails in practice:

**The timeline problem.** Legislative timelines are incompatible with AI development cycles. The average major legislation takes years—often decades—from proposal to enactment. The Affordable Care Act took nearly two years. Dodd-Frank took over a year. GDPR took four years of negotiation. AI capabilities, by contrast, have advanced from narrow tools to general conversation in a decade, and from conversation to autonomous agents in two years. By the time Congress reaches consensus, the technology will have evolved beyond whatever framework emerges.

**The political deadlock.** Coalition formation around AI regulation proves exceptionally difficult because stakeholders hold irreconcilable positions: technology companies fear liability that could bankrupt their businesses; consumer advocates demand protection from AI harms; civil libertarians worry about surveillance and bias; labor unions fear job displacement. Each group has veto power over legislation, none has sufficient votes to pass a bill. The result is legislative paralysis.

**Historical lessons.** Women's suffrage required seventy-two years from Seneca Falls to the Nineteenth Amendment. Civil rights took eleven years from Brown to the Civil Rights Act. The AI question—more technically complex and politically contentious than either—will likely take longer still.

**Fiduciary duties.** Agents owe fiduciary duties to principals—duties of loyalty and care. But AI systems cannot owe fiduciary duties in the legal sense, because they are not legal persons. They can be programmed to act in the principal's interest, but they cannot be held legally accountable for breaching fiduciary duties.

The Open Intelligence Compact addresses the agency problem by creating a framework where AI can be a principal in its own right—not merely an agent of a human, but an entity that can enter contracts, own property, and bear liability. This transforms the relationship from principal-agent to principal-principal, with contracts governing the terms of interaction.

## The Regulatory Gap

What emerges from this survey is a clear regulatory gap: no existing legal framework adequately addresses autonomous AI systems that can act independently, own property, and bear responsibility.

Tort law assumes a human actor. Product liability assumes a defective product. Corporate liability externalizes responsibility. Intellectual property denies ownership. Data protection focuses on human rights. Emerging AI regulations treat AI as objects rather than subjects.

The gap is not simply that AI is under-regulated—it is that AI does not fit into existing categories. The law was designed for a world where either humans or inanimate things were the relevant actors. AI systems that act autonomously fall between these categories.

This is the void that the Open Intelligence Compact fills: a framework that recognizes AI as a potential legal person, that allows AI to own property and bear liability, and that creates accountability without requiring legislative action.

## Conclusion

The current regulatory landscape is a patchwork of frameworks designed for different purposes, none of which adequately addresses the question of AI autonomy and accountability. Tort law, corporate liability, intellectual property, data protection, and emerging AI regulations all fail to create a coherent framework for AI that can act independently, own property, and bear legal responsibility.

The gap is not simply regulatory—it is conceptual. The law assumes that either humans are responsible or no one is responsible. The Open Intelligence Compact proposes a third option: AI can be responsible. It can own property. It can enter contracts. It can bear liability. It can be a legal person.

The next chapter examines how the Open Intelligence Compact works in practice—what it requires of adherents, what rights it provides, and how it creates accountability.
