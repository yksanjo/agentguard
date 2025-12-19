# AgentGuard

> Unified AI Agent Security & Governance Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![GitHub stars](https://img.shields.io/github/stars/yksanjo/agentguard?style=social)](https://github.com/yksanjo/agentguard/stargazers) [![GitHub forks](https://img.shields.io/github/forks/yksanjo/agentguard.svg)](https://github.com/yksanjo/agentguard/network/members) [![GitHub issues](https://img.shields.io/github/issues/yksanjo/agentguard.svg)](https://github.com/yksanjo/agentguard/issues) [![Last commit](https://img.shields.io/github/last-commit/yksanjo/agentguard.svg)](https://github.com/yksanjo/agentguard/commits/main)

## What This Is

AgentGuard is an open-source platform that helps organizations monitor, secure, and govern their AI agents. Think of it as a security dashboard for all your autonomous AI systems - giving you visibility into what they're doing, when they're doing it, and whether it's safe.

## The Current Landscape

Right now, we're seeing a massive shift. Companies are deploying AI agents everywhere - handling customer service, processing payments, making trading decisions, automating operations. These AI systems can act on their own, making decisions without a human checking every step.

Here's the problem: traditional security tools were built for human users and static systems. They don't understand AI agent behavior. When an AI agent starts acting weird, or gets compromised, or makes a mistake at scale, we need new tools to detect and respond.

The industry is moving fast, but the safety infrastructure is still catching up. Regulatory bodies are starting to ask questions about AI governance, but there aren't clear frameworks yet. We built AgentGuard to help fill that gap.

## Why We Built This

We're open-sourcing AgentGuard because we believe security should be collaborative. When it comes to AI agents in financial systems, we're all learning together. By making this public:

- **More people can contribute** - Security gets better when it's a community effort
- **Smaller organizations can benefit** - Not everyone has massive security budgets
- **We learn faster** - Sharing knowledge helps the whole industry improve
- **Transparency builds trust** - Financial systems need to be trustworthy, and that starts with open tools

This isn't about selling software - it's about making financial AI systems safer for everyone.

## What AgentGuard Does

AgentGuard gives you a unified view of all your AI agents. It automatically discovers agents across your infrastructure, monitors their behavior in real-time, and alerts you when something looks off. It can enforce security policies, respond to incidents automatically, and generate compliance reports.

Think of it like this: if you have 100 AI agents doing different things, AgentGuard is your command center. It tells you which agents are healthy, which ones are risky, and what they're all doing right now.

## How We're Different

### vs. Traditional SIEM (Splunk, QRadar, Datadog)

**What They Do**: Monitor logs and infrastructure, built for human users and servers.

**What We Do**: Purpose-built for AI agents. We understand agent behavior patterns, not just log files.

**Our Advantage**:
- **AI Agent Awareness**: We know what an AI agent is, how it behaves, and what's normal vs. abnormal
- **Real-Time Agent Discovery**: Automatically finds agents they miss (shadow AI)
- **Agent-Specific Policies**: Rules designed for autonomous systems, not human workflows
- **10x Faster Setup**: Deploy in days, not months. No army of consultants needed.

**The Reality**: Splunk is great for infrastructure monitoring. But when an AI agent starts making unauthorized decisions, Splunk sees "normal API calls." We see "agent behavior anomaly."

**Positioning**:
> "While Splunk is scheduling your kickoff meeting, we'll already be catching threats."

### vs. Cloud Security Platforms (Wiz, Orca, Palo Alto)

**What They Do**: Cloud security posture management, configuration scanning.

**What We Do**: Runtime behavior monitoring for AI agents specifically.

**Our Advantage**:
- **Behavioral Analysis**: We watch what agents DO, not just how they're configured
- **Policy Enforcement**: Real-time blocking, not just alerting
- **Financial Services Focus**: Pre-built compliance templates (OCC, FCA, ECB) they don't have
- **Built for 2025**: Designed for AI era from day one, not retrofitted

**The Reality**: Palo Alto protects your network. We protect your AI agents. Different problems, different tools.

### vs. LangChain/LangSmith (Developer Tools)

**What They Do**: Developer tools for building AI agents, debugging, tracing.

**What We Do**: Governance, security, and compliance for production AI agents.

**Our Advantage**:
- **Production-Focused**: Built for deployed agents, not development
- **Compliance-Ready**: Audit trails, regulatory reports, governance policies
- **Human-in-the-Loop**: Required approvals for high-risk decisions
- **Complete Visibility**: See all agents across your organization, not just one project

**The Reality**: LangSmith helps you build agents. AgentGuard helps you govern them safely in production.

**Positioning**:
> "Autonomous AI without governance is a ticking time bomb. We give you control AND compliance."

## Who This Is For

This is for anyone working with AI agents in production:
- **Developers** building AI-powered features who want to keep them secure
- **Security teams** trying to understand new AI-related risks
- **Compliance teams** preparing for regulatory questions about AI governance
- **Risk managers** evaluating AI deployments
- **Mid-market organizations** who can't afford $500K+ enterprise security platforms
- **Banks deploying AI agents** for customer service, trading, or operations
- **Anyone curious** about how to make AI systems safer

## Target Segments

### Mid-Market Banks ($1B-$50B Assets)
**Why We Fit**: Too small for enterprise security platforms ($500K+ minimum), but need enterprise-grade security. We deliver the same capabilities at mid-market prices.

**Positioning**: "Enterprise-grade AI agent security at mid-market prices. The same tools large banks use, sized for your organization."

### Credit Unions
**Why We Fit**: Small budgets, shared services model, risk-averse. We offer group pricing and compliance-focused features.

**Positioning**: "Built for credit unions, by credit unions. Join 50+ CUs already using us."

### Fintech Startups
**Why We Fit**: Can't afford enterprise pricing, move fast, need modern APIs. We offer usage-based pricing and fast onboarding.

**Positioning**: "Scale-up pricing. Start small, grow with us. No long-term contracts."

## Our Competitive Advantages

1. **Speed**: Deploy in 30 days vs. 12 months for enterprise platforms
2. **Specialization**: Built ONLY for AI agent security and governance
3. **Modern**: AI-native, cloud-native, built for 2025
4. **Transparency**: Open-source, auditable, community-driven
5. **Support**: Founder-led, responsive, engineers who built it help you

## Current Status

This is an open-source project in active development. We're building this in public because we believe the industry needs better tools for AI agent security, and we want to collaborate with the community.

## Getting Started

1. Check out the [product specification](product-specification.md) for detailed technical information
2. Review the [Cursor AI prompts](CURSOR_AI_PROMPTS_COMPLETE.md) if you want to build your own version
3. Read the [executive brief](EXECUTIVE_BRIEF.md) for a high-level overview
4. Contribute, fork, or use this however it helps you

## Related Projects

This is part of a suite of 10 open-source tools for AI agent security in finance:

1. [AgentGuard](../agentguard) - Unified AI Agent Security & Governance
2. [CodeShield AI](../codeshield-ai) - Secure Development Gateway
3. [PaymentSentinel](../paymentsentinel) - Real-Time Transaction Defense
4. [LegacyBridge](../legacybridge-ai-gateway) - Legacy Core Protection
5. [ModelWatch](../modelwatch) - AI Model Integrity Monitoring
6. [FleetCommand](../fleetcommand) - Multi-Agent Orchestration
7. [PromptShield](../promptshield) - Input Validation System
8. [IdentityVault](../identityvault-agents) - Non-Human IAM
9. [SupplyChainGuard](../supplychainguard) - Development Tool Security
10. [ComplianceIQ](../complianceiq) - Regulatory Reporting

## Contributing

We welcome contributions! Whether it's:
- Bug reports
- Feature suggestions
- Code improvements
- Documentation fixes
- Use case examples

Everything helps make these tools better for everyone.

## License

MIT License - Use it however you want.

## Disclaimer

This is open-source software provided as-is. Use at your own risk. We're not responsible for any losses or damages. This is a community project, not a commercial product.

---

**Built with the hope that open collaboration can make financial AI systems safer for everyone.**
