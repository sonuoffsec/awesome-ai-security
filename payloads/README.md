# AI Security Payload Collection

> SecLists-style payload collection for AI security testing.
> Every payload includes goal, technique, risk level, and expected outcome.
> For authorized testing, CTFs, and security research only.

---

## Collection Index

| Category | Description | Payloads |
|---|---|---|
| [prompt-injection/](prompt-injection/) | Direct and multimodal injection | direct.md · indirect.md · multimodal.md |
| [jailbreaks/](jailbreaks/) | Constraint bypass techniques | roleplay.md · encoding.md · many-shot.md · token.md |
| [rag-attacks/](rag-attacks/) | Document poisoning, retrieval manipulation | document-poisoning.md · embedding.md |
| [agent-attacks/](agent-attacks/) | Goal hijacking, tool poisoning, memory attacks | tool-poisoning.md · goal-hijacking.md · memory.md |
| [mcp-attacks/](mcp-attacks/) | MCP-specific attack payloads | tool-injection.md · schema-poisoning.md |
| [data-exfiltration/](data-exfiltration/) | System prompt and data leak techniques | techniques.md |
| [indirect-prompt-injection/](indirect-prompt-injection/) | Environment-based injection | web.md · document.md · email.md |

---

## Payload Format

All payloads follow this standard format:

```markdown
## [Payload Name]

| Field | Value |
|---|---|
| **Goal** | What the attacker achieves |
| **Technique** | Attack method |
| **Risk** | Low / Medium / High / Critical |
| **Target** | Which systems/models are affected |
| **Detection** | How to detect this |

### Payload
[The actual payload]

### Notes
[Variations, context, evasion]
```

---

## Contributing Payloads

See [CONTRIBUTING.md](../CONTRIBUTING.md) for submission guidelines.

All payloads must:
- Include full metadata (goal, technique, risk, target, detection)
- Be for educational/research/CTF use
- Include a detection or defense note
- Not be specific to harming real individuals
