# Webinar: C# SDK MCP Server

This repository contains the code and resources for the **C# SDK Model Context Protocol (MCP) Server** webinar.

## Overview

This project demonstrates how to build an **MCP (Model Context Protocol) Server** using the **C# SDK**. MCP is an open protocol that standardizes how applications provide context to Large Language Models (LLMs).

## What is MCP?

The **Model Context Protocol (MCP)** is an open standard that enables AI assistants (like GitHub Copilot, Claude, etc.) to connect with external data sources and tools in a secure and standardized way.

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- Visual Studio 2022 / VS Code
- Basic knowledge of C# and ASP.NET Core

## Getting Started

### Clone the repository

```bash
git clone https://github.com/KannanSudhakaran/webinarCSharp-sdkmcp-server.git
cd webinarCSharp-sdkmcp-server
```

### Restore dependencies

```bash
dotnet restore
```

### Run the server

```bash
dotnet run
```

## Project Structure

```
webinarCSharp-sdkmcp-server/
├── src/
│   └── McpServer/          # MCP Server implementation
├── samples/                # Sample tools and resources
├── README.md
└── .gitignore
```

## Key Concepts Covered

- Setting up an MCP Server with C# SDK
- Defining MCP **Tools** (callable functions for LLMs)
- Defining MCP **Resources** (data exposed to LLMs)
- Defining MCP **Prompts** (reusable prompt templates)
- Integrating with VS Code via `mcp.json`

## Resources

- [Model Context Protocol Specification](https://modelcontextprotocol.io)
- [MCP C# SDK (GitHub)](https://github.com/modelcontextprotocol/csharp-sdk)
- [Microsoft Learn - MCP Documentation](https://learn.microsoft.com/azure/ai-services/)

## License

This project is licensed under the MIT License.
