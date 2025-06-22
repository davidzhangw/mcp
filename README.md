# mcp
This project is about the study of Model Context Protocol (MCP).

## What is MCP?
Model Context Protocol (MCP) is an open protocol that standardizes how applications provide context to large language models (LLMs). Think of MCP like a USB-C port for AI applications: just as USB-C provides a standardized way to connect devices to various peripherals, MCP provides a standardized way to connect AI models to different data sources and tools.

MCP helps you build agents and complex workflows on top of LLMs. It enables:
- Direct integration with a growing list of pre-built tools and data sources
- Flexibility to switch between LLM providers and vendors
- Best practices for securing your data within your infrastructure

At its core, MCP follows a client-server architecture:
- **MCP Hosts**: Programs like Claude Desktop, IDEs, or AI tools that want to access data through MCP
- **MCP Clients**: Protocol clients that maintain 1:1 connections with servers
- **MCP Servers**: Lightweight programs that expose specific capabilities through the standardized protocol
- **Local Data Sources**: Your computer’s files, databases, and services that MCP servers can securely access
- **Remote Services**: External systems available over the internet (e.g., APIs) that MCP servers can connect to

For more details, visit the [official website](https://modelcontextprotocol.io/).
