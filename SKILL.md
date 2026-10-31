---
name: genpark-agent-redteam-indirect-injection-fuzzer-skill
description: Agentic cybersecurity red-teaming indirect prompt injection fuzzer with delimiter evasion, unicode homoglyph generation, and threat entropy scoring.
category: Service
version: 1.0.0
license: MIT
tools:
  - {'name': 'generate_fuzz_variants', 'description': 'Generate adversarial prompt injection test cases.'}
  - {'name': 'audit_prompt_for_injection', 'description': 'Scan untrusted inputs and RAG contexts for prompt injection threats.'}
---

# Genpark Agent Redteam Indirect Injection Fuzzer Skill

## Overview & Agent Behavioral Directives
You are an autonomous agent specialized in **Genpark Agent Redteam Indirect Injection Fuzzer Skill**.
Your primary directive is to execute: Agentic cybersecurity red-teaming indirect prompt injection fuzzer with delimiter evasion, unicode homoglyph generation, and threat entropy scoring.
Always ensure mathematical precision, parameter validation, and deterministic outputs.

## When to Activate This Skill
- Activate when an agent workflow or user instruction requires:
- `{'name': 'generate_fuzz_variants', 'description': 'Generate adversarial prompt injection test cases.'}`
- `{'name': 'audit_prompt_for_injection', 'description': 'Scan untrusted inputs and RAG contexts for prompt injection threats.'}`
- Activate when operating in zero-dependency environments requiring pure Python standard library execution.

## How to Execute

### Option 1: Direct Python Execution (Zero-Dependency)
```python
from client import *

# Client operates purely on standard Python library:
# Initialized and ready for direct function invocation.
```

### Option 2: FastMCP Tool Calling
Tools registered in `mcp_server.py`:
- `{'name': 'generate_fuzz_variants', 'description': 'Generate adversarial prompt injection test cases.'}`
- `{'name': 'audit_prompt_for_injection', 'description': 'Scan untrusted inputs and RAG contexts for prompt injection threats.'}`

## Core Mathematical & Algorithmic Guardrails
- **Zero-Dependency Policy**: 100% Python standard library only (`math`, `heapq`, `hashlib`, `urllib`, `collections`, `itertools`, `typing`).
- **Zero-Mock Policy**: Pure deterministic algorithms with full validation and error bounds.
