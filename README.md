# Python AI Agent (Q&amp;A)

A lightweight, rule-based question-answering agent built in Python. The agent parses user questions, matches them against a programmed knowledge base using string matching and conditionals, and returns the best available answer.

> Built as a first step toward LLM-powered assistants — the architecture is intentionally modular so the answer logic can be upgraded without rewriting the agent.

## How It Works

1. The agent takes a question as input.
2. It normalizes the text (lowercase, strip punctuation).
3. It matches the question against a set of known questions/patterns.
4. It returns the corresponding programmed answer.

## Tech Stack

- **Language:** Python 3
- **No external dependencies** — runs on the standard library

## Getting Started

```bash
# Clone the repository
git clone https://github.com/Spark-ui-ai/python-ai-agent.git
cd python-ai-agent

# Run the agent
python agent.py
```

## Example

```
You: What is your name?
Agent: I am PyAgent, a rule-based Q&A assistant.
```

*(Replace with a real example from the script's actual Q&amp;A pairs.)*

## Roadmap

- [ ] Move Q&amp;A pairs from hardcoded logic to a JSON/database store
- [ ] Add fuzzy matching for more flexible question handling
- [ ] Add conversation memory (follow-up questions)
- [ ] Connect to an LLM API for open-domain answers

## What I Learned

- Structuring Python programs with functions for extensibility
- Designing input parsing and text normalization
- Thinking ahead: separating data (Q&amp;A pairs) from logic (matching)

## Author

**Kunal Sharma** — B.E. CSE @ Chandigarh University

- GitHub: [Spark-ui-ai](https://github.com/Spark-ui-ai)
- LinkedIn: [Kunal Sharma](https://www.linkedin.com/in/kunal-sharma-8662a7306)
