# LLM & AI Agents Lab

This repository is my personal learning lab to improve practical skills in:

- LLM application development
- AI agent design and orchestration
- Prompt engineering and evaluation
- Retrieval-Augmented Generation (RAG)
- Tool use, memory, and multi-step workflows

The focus is on **running experiments**, documenting results, and building strong engineering habits.

---

## Goals

1. Build a solid foundation in LLM and agent concepts.
2. Implement small, testable experiments regularly.
3. Compare approaches (prompts, models, frameworks, tools).
4. Track outcomes using simple, repeatable evaluation criteria.
5. Gradually move from prototypes to production-style patterns.

---

## Learning Scope

### 1) Core LLM Skills
- Prompt design (zero-shot, few-shot, role prompting, structured prompting)
- Output control (JSON mode, schemas, constrained generation)
- Token usage and context window strategies
- Hallucination mitigation techniques

### 2) Agent Skills
- Planning vs reactive agents
- Tool calling and function execution
- State management and memory (short-term + long-term)
- Multi-agent coordination patterns
- Guardrails and failure recovery

### 3) RAG Skills
- Chunking strategies
- Embeddings and vector search basics
- Retrieval quality and reranking
- Grounded answering and citation patterns

### 4) Evaluation Skills
- Define task-specific success metrics
- Build small benchmark sets
- Regression testing for prompt/agent changes
- Cost-latency-quality tradeoff analysis

---

## Initial Roadmap

### Phase 1: Foundations
- Build prompt baselines for 2–3 tasks
- Add structured output validation
- Start documenting failures and fixes

### Phase 2: Tool-Augmented Agents
- Create a single-agent tool-calling loop
- Add retries and tool error handling
- Compare planner-style vs direct execution

### Phase 3: RAG + Evaluation
- Build first RAG pipeline
- Add small golden evaluation set
- Track metrics over multiple iterations

### Phase 4: Production Thinking
- Add observability (inputs, outputs, latency)
- Add safety checks and fallbacks
- Refactor into reusable modules
