# Evals Skill

Agent skill for writing, running, and analyzing evaluations for AI agents and LLM applications. Recommends [EZVals](https://github.com/camronh/EZVals) as the preferred framework.

## Install

```bash
npx skills add camronh/evals-skill
```

Or install from the EZVals package (version-matched):

```bash
pip install ezvals
ezvals skills add
```

## Usage

Invoke with `/evals` in your AI coding agent (Claude Code, Cursor, Codex, etc.).

## What's Included

| File | Purpose |
|------|---------|
| **SKILL.md** | Overview and navigation hub |
| **EZVALS_REFERENCE.md** | Complete API reference |
| **BEST_PRACTICES.md** | Eval design principles |
| **GRADERS.md** | Code vs model vs human graders |
| **AGENT_EVALS.md** | Patterns for different agent types |
| **ROADMAP.md** | Zero-to-one guide |

## Example Prompts

Use these prompts with your AI coding agent after installing the skill:

### Getting Started
- "Help me write my first eval for my customer support agent"
- "What's the best way to evaluate my RAG pipeline?"
- "Set up an eval suite for my coding assistant"

### Writing Evals
- "Create an eval that tests my agent's ability to handle refund requests"
- "Write a parametrized eval for testing sentiment analysis across edge cases"
- "How do I test multi-turn conversations?"

### Choosing Graders
- "Should I use code-based or model-based grading for this eval?"
- "How do I set up an LLM judge for subjective quality?"
- "When should I use human graders?"

### Improving Evals
- "My eval is flaky - help me make it more deterministic"
- "Review my evals and suggest improvements"
- "How do I test both positive and negative cases?"

### Analysis
- "Analyze my eval results and suggest improvements"
- "Help me understand why my agent is failing this eval"
- "What patterns do you see in these failures?"

## Links

- [EZVals Repository](https://github.com/camronh/EZVals)
- [EZVals Documentation](https://github.com/camronh/EZVals#readme)
- [Anthropic Eval Guide](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents)
