# Agent Tooling Lab

Lab for small AI agent tools, RAG notes, and tool-calling experiments.

## What's here
- Tiny tool wrappers for agent loops
- Notes on tool schemas for LLM function calling
- Lightweight RAG prototypes

## Experiment ideas
- Compare tool-calling prompts across open models
- Measure retrieval hit-rate on personal not







es
- Log failed tool invocations

## Minimal tool stub

```python
def echo_tool(text: str) -> str:
    return f"echo: {text.strip()}"

if __name__ == "__main__":
    print(echo_tool("hello from agent-tooling-lab"))
```

Honest learning lab — prototypes, not production software.










