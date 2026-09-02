# AI-Only Public License v1.1

**AI-OPL-1.1** — An experimental software license for the age of AI-assisted development.

Copyright (c) 2026 spidychoipro

---

## Philosophy

```
         HUMAN
           |
  Natural Language
     Directives
           |
           v
        AI SYSTEM
           |
    Code Modification
           |
           v
        SOFTWARE
```

> **AI gets the keyboard. Human keeps the responsibility.**

In the age of AI, the right to decide WHAT gets built belongs to humans, the right to write the CODE belongs to AI, and the responsibility for the RESULT remains with humans.

## Overview

The AI-Only Public License is an experimental license that takes a different approach from traditional open source:

| Right | Who Exercises It |
|-------|-----------------|
| Decide WHAT to build | Human User |
| Write and modify CODE | AI System only |
| Run and execute | Human User |
| Read and study | Human User |
| Test and debug | Human User (with AI) |
| Deploy and distribute | Human User |
| Bear RESPONSIBILITY | Human User |

## What's Allowed and What's Not

### Human Users CAN:
- Provide natural language instructions to AI Systems
- Execute, build, test, run, and deploy the Software
- Fork, clone, and redistribute the Software
- Make non-substantive changes (formatting, typos, comments, lockfiles)
- Apply emergency security patches (must regenerate through AI ASAP)

### Human Users CANNOT:
- Directly edit, patch, or rewrite substantive source code
- Introduce external code and ask AI to merely insert it

### Human Users MUST:
- Review and validate all AI-Mediated Modifications
- Assume full responsibility for any consequences

## AI Systems

This License applies to any computational system capable of materially generating, transforming, debugging, or maintaining source code through machine-learning or artificial-intelligence methods.

### Examples of AI Systems

**Web-based AI assistants:**
- OpenAI ChatGPT (chat.openai.com)
- Google Gemini (gemini.google.com)
- Anthropic Claude (claude.ai)
- Microsoft Copilot (copilot.microsoft.com)
- Perplexity AI (perplexity.ai)

**AI coding agents and IDEs:**
- Anthropic Claude Code (CLI)
- OpenAI Codex CLI
- OpenCode (opencode.ai)
- Agy
- Cursor (cursor.com)
- Windsurf (windsurf.com)
- Cline (VS Code extension)
- Aider (aider.chat)
- GitHub Copilot Agent
- Amazon Q Developer
- JetBrains AI Assistant

**Self-hosted or API-based models:**
- OpenAI GPT series (GPT-4, GPT-4o, o1, o3, etc.)
- Anthropic Claude series (Claude 3.5, Claude 4, etc.)
- Google Gemini series (Gemini 2.0, Gemini Ultra, etc.)
- Meta Llama series
- Mistral AI models
- DeepSeek series
- Any locally deployed large language model

**Note:** This list is non-exhaustive. Any future AI system with equivalent code generation capabilities is covered.

## AI Modification Record (Recommended)

This License recommends (but does not require) maintaining an AI Modification Record:

```
.aiopl/
    modifications/
        2026-09-02-001.json
```

```json
{
    "license": "AI-OPL-1.1",
    "agent": "Claude Code",
    "files": ["src/main.py", "src/utils.py"],
    "human_directive": "Refactor the parser and add error handling",
    "timestamp": "2026-09-02T22:40:00+09:00"
}
```

This is advisory only and does not create legal obligations.

## How to Use

Add the following to your project's LICENSE file:

```
AI-Only Public License v1.1 (AI-OPL-1.1)
Copyright (c) 2026 spidychoipro
```

Or copy the full [LICENSE](LICENSE) file into your repository.

## Important Notes

- This is an **experimental license**, intentionally different from OSI-approved licenses
- It restricts source code modification to AI Systems only
- The Human User bears **all responsibility** for AI-generated code
- The Author bears **no liability** for damages from using the Software

## License

This license text is released under the AI-Only Public License v1.1 itself.

Copyright (c) 2026 spidychoipro
