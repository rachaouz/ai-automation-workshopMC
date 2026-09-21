# ai-automation-workshopMC
AI Automation workshop resources and challenges for MicroClub
### From an AI that answers to an AI that acts

A workshop about understanding and designing AI-powered automation systems.

## About the Workshop

Everyone is talking about AI agents, AI workflows, and AI automation.

But what do these concepts actually mean?

This workshop explores how AI can understand natural language, transform it into structured information, interact with external tools, and participate in automated systems.

The goal is not just to learn definitions, but to understand how to design an AI automation architecture.

## Objectives

By the end of this workshop, participants should be able to:

- Understand the difference between traditional automation and AI automation.
- Understand how LLMs interpret user requests.
- Explain the role of structured output.
- Understand how tool calling works.
- Distinguish between RAG and structured lookups.
- Differentiate workflows from agents.
- Identify when guardrails and human review are necessary.
- Consider security, cost, latency, and monitoring.

## Workshop Content

### 1. Traditional Automation vs AI Automation

Traditional automation relies on predefined rules and predictable inputs.

AI automation uses an LLM to interpret natural language before triggering an action.

Example:

> "I forgot my password. How can I get back in?"

An AI system can understand that the user wants to reset their password, even if they do not use the exact words "reset password".

### 2. LLMs and Structured Output

An LLM can understand a user's request and transform it into structured information.

Example:

```json
{
  "intent": "password_reset",
  "confidence": "high"
}
