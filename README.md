# Awesome AI Agent Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of frameworks, SDKs, memory layers, evaluation tools, and resources for building AI agents.

AI agents are moving fast — new frameworks ship weekly, and yesterday's "best practice" is often outdated by next month. This list tries to stay current and useful rather than exhaustive. PRs welcome.

## Contents

- [Full Frameworks](#full-frameworks)
- [Vendor / Provider SDKs](#vendor--provider-sdks)
- [Autonomous Agents](#autonomous-agents)
- [Memory](#memory)
- [Observability & Evaluation](#observability--evaluation)
- [Protocols](#protocols)
- [Managed / Enterprise Platforms](#managed--enterprise-platforms)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

## Full Frameworks

General-purpose libraries for building and orchestrating agents.

- [LangGraph](https://github.com/langchain-ai/langgraph) - Graph-based orchestration for stateful, multi-agent workflows. Supports checkpointing, pausing/resuming, and time-travel debugging.
- [LangChain](https://github.com/langchain-ai/langchain) - The most widely adopted agent/LLM app framework, with a huge library of pre-built integrations.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Fast path to a working multi-agent prototype using a role-based crew model.
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript-first framework with workflows, memory, and a built-in studio environment.
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) - Merger of Semantic Kernel and AutoGen; Microsoft's unified agent framework.
- [LlamaIndex Workflows](https://github.com/run-llama/llama_index) - Event-driven workflow engine with strong data-retrieval and RAG roots.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Type-safe agent framework built on Pydantic's validation model.
- [Google ADK](https://github.com/google/adk-python) - Google's Agent Development Kit for building and deploying agents.
- [Strands Agents](https://github.com/strands-agents/sdk-python) - Model-driven agent SDK, pairs well with Amazon Bedrock AgentCore.
- [Smolagents](https://github.com/huggingface/smolagents) - Minimal, code-first agent library from Hugging Face.
- [Haystack Agents](https://github.com/deepset-ai/haystack) - Agent support built on the Haystack NLP/RAG framework.
- [Vercel AI SDK](https://github.com/vercel/ai) - Add agentic features to an existing Next.js/React app rather than building agent-first.

## Vendor / Provider SDKs

Agent SDKs maintained by model providers, built to work best with their own models.

- [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python) - Anthropic's SDK; the same one Claude Code itself runs on. Native MCP support, hooks, and subagents.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - OpenAI's lightweight agents framework, successor to Swarm.
- [AG2 (formerly AutoGen)](https://github.com/ag2ai/ag2) - Community-driven continuation of AutoGen's multi-agent conversation model.

## Autonomous Agents

Standalone agents you run rather than frameworks you build with.

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - One of the earliest and still most-starred autonomous agent projects.
- [OpenClaw](https://github.com/openclaw/openclaw) - Self-hosted autonomous coding agent.

## Memory

- [Hyperconsciousness](https://github.com/louis030195/hyperconsciousness) - Developer-alpha Rust CLI and MCP knowledge store for encrypted append-only agent notes with scoped, expiring access grants.
- [Mem0](https://github.com/mem0ai/mem0) - Memory layer for agents, adds persistent long-term memory across sessions.

## Observability & Evaluation

- [LangSmith](https://www.langchain.com/langsmith) - Framework-agnostic tracing, evaluation, and debugging platform.
- [AutoGen Tracing](https://microsoft.github.io/autogen/) - Built-in tracing tools for AutoGen/Agent Framework pipelines.

## Protocols

- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol) - Open standard for connecting agents to tools and data sources. Now supported natively by nearly every major framework.
- [Agent2Agent (A2A)](https://github.com/google/A2A) - Emerging protocol for cross-agent interoperability.

## Managed / Enterprise Platforms

For teams that want a governed, procurement-friendly platform instead of a library.

- Microsoft Copilot Studio + Microsoft 365 Agents
- AWS Bedrock AgentCore
- Google Vertex AI Agent Builder
- OpenAI Agent Platform
- Salesforce Agentforce 360
- ServiceNow AI Agents
- IBM watsonx Orchestrate

## Learning Resources

- [Anthropic: Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) - Widely cited guide to agent design patterns.
- [GitHub Octoverse Report](https://octoverse.github.com) - Annual data on open-source and AI agent adoption trends.

## Contributing

Contributions welcome! Please make sure any repo you add:

1. Is actively maintained (commits within the last ~6 months)
2. Has clear documentation
3. Fits an existing category, or justifies a new one

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guide.

## License

[CC0](LICENSE) - This list is dedicated to the public domain.
