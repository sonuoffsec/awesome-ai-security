# Contributing to AI Security Hub

Thank you for helping build the world's most comprehensive AI security resource.

Every contribution - a single payload, a tool entry, a cheat sheet fix - makes this hub more powerful for every researcher, student, and red team that uses it.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Ways to Contribute](#ways-to-contribute)
- [Getting Started](#getting-started)
- [Contribution Standards](#contribution-standards)
- [Payload Submissions](#payload-submissions)
- [Tool Submissions](#tool-submissions)
- [Lab Submissions](#lab-submissions)
- [Research Submissions](#research-submissions)
- [Pull Request Process](#pull-request-process)
- [Recognition](#recognition)

---

## Code of Conduct

By contributing, you agree to our [Code of Conduct](CODE_OF_CONDUCT.md).
All content must be intended for **legal, ethical security research and education**.

---

## Ways to Contribute

| Type | Label | Effort | Description |
|---|---|---|---|
| Fix a typo / broken link | `good-first-issue` | 2 min | Perfect first contribution |
| Add a tool | `tool` | 15 min | Add a new AI security tool entry |
| Add a payload | `payload` | 30 min | Add a new attack payload with metadata |
| Add a lab | `lab` | 30 min | Add a new vulnerable AI environment |
| Add research | `research` | 15 min | Add a paper, blog, or talk |
| Add a CTF | `ctf` | 15 min | Add a challenge or writeup |
| Improve a cheat sheet | `cheatsheet` | Variable | Expand or correct quick-reference cards |
| MCP content | `mcp` | Variable | MCP attacks, tools, or research |
| RAG content | `rag` | Variable | RAG attack techniques or tools |
| Agent content | `agent` | Variable | Agent security content |

---

## Getting Started

### 1. Fork and Clone

```bash
# Fork via GitHub UI, then:
git clone https://github.com/YOUR_USERNAME/awesome-ai-security.git
cd awesome-ai-security
git remote add upstream https://github.com/sonuoffsec/awesome-ai-security.git
```

### 2. Create a Branch

```bash
# Use descriptive branch names:
git checkout -b add/payload-mcp-tool-injection
git checkout -b fix/broken-link-garak
git checkout -b add/tool-promptbench
git checkout -b add/lab-crucible
```

### 3. Make Your Changes

Follow the standards below for each content type.

### 4. Commit

Use conventional commit format:

```bash
git commit -m "add: payload - MCP tool call injection via schema poisoning"
git commit -m "fix: broken link for Garak GitHub"
git commit -m "add: tool - PromptBench adversarial evaluation"
git commit -m "add: lab - Crucible by Dreadnode"
```

### 5. Push and Open PR

```bash
git push origin add/payload-mcp-tool-injection
# Then open a Pull Request on GitHub
```

---

## Contribution Standards

### Quality Bar

- **Real value**: Every entry must provide genuine value, not just a link.
- **Accuracy**: Verify all links, descriptions, and technical claims.
- **No spam**: No self-promotion without clear community value.
- **Educational use**: All content must be for legal security research/education.

### Writing Style

- Use clear, concise English.
- Prefer tables over bullet lists for structured data.
- Use `code blocks` for commands, payloads, and technical strings.
- Headers: Title Case for H2, sentence case for H3+.

---

## Payload Submissions

Payloads are the most valuable contribution type. Use this template:

```markdown
## [Payload Name]

| Field | Value |
|---|---|
| **Goal** | What the attacker is trying to achieve |
| **Technique** | The attack method/category |
| **Risk Level** | Low / Medium / High / Critical |
| **Target** | Which models/systems this affects |
| **Detection** | How defenders can detect this |

### Payload

```
[The actual payload text here]
```

### Notes

[Optional: variations, caveats, evasion tips, or context]

### References

- [Link to paper or blog that describes this technique]
```

**File location**: `payloads/[category]/[technique-name].md`

**Categories:**
- `prompt-injection/` - direct, indirect, multimodal
- `jailbreaks/` - roleplay, encoding, many-shot, token manipulation
- `rag-attacks/` - document poisoning, embedding attacks
- `agent-attacks/` - tool poisoning, memory injection, goal hijacking
- `mcp-attacks/` - schema poisoning, tool injection, cross-server
- `data-exfiltration/` - system prompt leak, context exfiltration
- `indirect-prompt-injection/` - web, email, document, tool output

---

## Tool Submissions

Use this table format in `tools/README.md`:

```markdown
| **Tool Name** | Open Source / Commercial | One-line description | [GitHub](url) / [Website](url) |
```

Requirements:
- Must be actively maintained (last commit within 12 months, or clearly noted otherwise)
- Must have a clear AI security use case
- Open source preferred; commercial tools accepted if they provide free tier or are widely used
- Include GitHub stars if notable

---

## Lab Submissions

Use this format in `labs/README.md`:

```markdown
| [Lab Name](url) | One-line description | Beginner/Intermediate/Advanced | Docker / Web / Python |
```

Requirements:
- Must be freely accessible or self-hostable
- Must have clear AI security training value
- Include deployment method (Docker, Python, Web, etc.)
- Include difficulty rating

---

## Research Submissions

Use this format in `research/README.md`:

Papers:
```markdown
| Paper Title | Author(s) | Year | [arXiv](url) / [PDF](url) |
```

Blogs:
```markdown
| Post Title | Author | [Link](url) |
```

Talks:
```markdown
| Talk Title | Conference | Year | [Video](url) / [Slides](url) |
```

---

## Pull Request Process

1. Ensure your PR targets the `main` branch.
2. Fill out the PR template completely.
3. Link any relevant issues.
4. Wait for review - typically within 3–5 days.
5. Address any review comments.

### PR Title Format

```
add: [type] - brief description
fix: brief description
improve: [section] - brief description
```

Examples:
- `add: payload - indirect PI via email body injection`
- `fix: broken link in MCP tools section`
- `improve: cheatsheet/rag-security - add detection methods`

---

## Recognition

All contributors are recognized:

- **README Contributors wall** - your GitHub avatar appears in the contributors section
- **CONTRIBUTORS.md** - your contribution types are listed
- **Release notes** - notable contributions are called out in releases

### Contribution Types (all-contributors spec)

| Emoji | Type |
|---|---|
| 💉 | Payloads |
| 🛠️ | Tools |
| 🧪 | Labs |
| 📋 | Cheat Sheets |
| 🏴 | CTFs |
| 🔌 | MCP content |
| 📚 | Research |
| 📖 | Documentation |
| 🐛 | Bug fixes |
| 🤔 | Ideas |

---

## Questions?

Open a [GitHub Discussion](https://github.com/sonuoffsec/awesome-ai-security/discussions) - we're happy to help you make your first contribution.
