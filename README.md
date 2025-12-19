<div align="center">
  <h1>Awesome Agent-to-Agent (A2A) Libraries</h1>

  <img src="assets/banner.png" alt="Awesome A2A Banner - Abstract network or connection graphic" width="100%">
</div>


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/nMaroulis/awesome-a2a-libraries.svg?style=social&label=Stars)](https://github.com/nMaroulis/awesome-a2a-libraries)
[![GitHub forks](https://img.shields.io/github/forks/nMaroulis/awesome-a2a-libraries.svg?style=social&label=Forks)](https://github.com/nMaroulis/awesome-a2a-libraries)


A curated list of **Agent-to-Agent (A2A) libraries and SDKs**, organized by **programming language**.

This list focuses **exclusively on code libraries** that implement or support the **Agent-to-Agent (A2A) protocol** for interoperable agent communication.

## What is A2A?

**Agent-to-Agent (A2A)** is an open protocol designed to enable **secure, peer-to-peer communication and collaboration between autonomous AI agents**, regardless of framework, runtime, or vendor. By standardizing the way agents exchange tasks, messages, and results, A2A allows developers to build **interoperable, multi-agent systems** capable of complex cross-application automation.

Key features of A2A include:

- **Framework-agnostic:** Works across different AI agent frameworks and programming languages.
- **Peer-to-peer communication:** Direct agent-to-agent messaging, with optional server-mediated routing.
- **Async-first design:** Supports long-running tasks and human-in-the-loop scenarios.
- **Modality-agnostic:** Handles text, files, forms, streams, and other data types.
- **Opaque execution:** Agents interact without exposing internal logic or proprietary tools.
- **Enterprise-ready:** Includes authentication, security, privacy, and monitoring considerations.

### Official Resources

- [Announcement Blog Post](https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/) – Google's introduction to A2A.
- [GitHub Repository](https://github.com/a2aproject/A2A) – Source code, spec, and official samples.
- [Official Documentation](https://a2aproject.github.io/A2A) – Detailed technical reference and examples.


## Table of Contents

1. [Scope](#scope)  
2. [How to Read This List](#how-to-read-this-list)  
3. [Libraries by Language](#libraries-by-language)  
   - [Python](#python)  
   - [JavaScript / TypeScript](#javascript--typescript)  
   - [Java](#java)  
   - [Go](#go)  
   - [Rust](#rust)  
   - [C#](#c)  
4. [Related Ecosystem](#related-ecosystem)  
5. [Contribution Guidelines](#contribution-guidelines)  
6. [License](#license)  

## Scope

**Included**
- A2A SDKs and client libraries  
- A2A servers, registries, and transports  
- Language-native agent libraries with A2A support  
- Utilities directly enabling A2A communication  

**Excluded**
- Non-A2A agent frameworks  
- SaaS platforms or hosted products  
- UI tools or prompt collections/templates  

For broader agent framework coverage, see *awesome-agents* or *awesome-ai-agents* lists.

## Programming Languages

Currently, libraries for the following programming languages are supported:

<p align="center">
  <font color="#888" size="2">[ Python ]</font>   <font color="#888" size="2">[ JavaScript / TypeScript ]</font>   <font color="#888" size="2">[ Rust ]</font> <font color="#888" size="2">[ Java ]</font> <font color="#888" size="2">[ Go ]</font> <font color="#888" size="2">[ C# ]</font>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/pheralb/svgl/06a1c7f443bb702317165c5091e4a648a6bc2eda/static/library/python.svg" width="45" alt="Python" title="Python"/>  <img src="https://raw.githubusercontent.com/pheralb/svgl/06a1c7f443bb702317165c5091e4a648a6bc2eda/static/library/javascript.svg" width="45" alt="JS" />  <img src="https://raw.githubusercontent.com/pheralb/svgl/06a1c7f443bb702317165c5091e4a648a6bc2eda/static/library/rust.svg" width="45" alt="Rust" />  <img src="https://raw.githubusercontent.com/pheralb/svgl/06a1c7f443bb702317165c5091e4a648a6bc2eda/static/library/java.svg" width="45" alt="Java" />  <img src="https://go.dev/blog/go-brand/Go-Logo/SVG/Go-Logo_Blue.svg" width="45" alt="Go" />  <img src="https://raw.githubusercontent.com/pheralb/svgl/06a1c7f443bb702317165c5091e4a648a6bc2eda/static/library/csharp.svg" width="45" alt="Csharp" />
</p>


## How to Read This List

Libraries are grouped **by programming language**. Each entry includes several classifications to help you quickly understand its purpose, readiness, and usability.

### Classification Rules

- **Role** – what part of the A2A ecosystem the library enables:  
  - `Client` – implements *initiator* behavior, sending tasks to other agents according to A2A.  
  - `Server` – implements *receiver/executor* behavior, accepting tasks and returning results.  
  - `Client + Server` – supports both initiating and handling A2A interactions.  
  - `Agent Framework` – higher-level library including client/server behavior plus orchestration or workflow tools.  
  - `Utility` – helps implement, test, debug, or validate A2A (e.g., schemas, validators, tooling).  

- **Architecture / Model** – how agents communicate:  
  - `Peer-to-peer` – direct agent-to-agent communication.  
  - `Hybrid` – combination of peer-to-peer and server-mediated communication.  

- **Readiness / Stability** – how mature and production-ready the library is:  
  - `Experimental` – early-stage, APIs may change; mainly for testing or learning.  
  - `Stable` – well-maintained and suitable for serious projects.  
  - `Production-ready` – proven in production, actively maintained, enterprise-ready.  

- **Complexity / Learning Curve** – level of experience needed to use the library effectively:  
  - `Beginner-friendly` – easy to install and use, well-documented.  
  - `Intermediate` – some learning or configuration required.  
  - `Advanced` – low-level or highly configurable, intended for experts.  

- **Notes** – highlight extra features,

- **Optional Tags** - tags to highlight features:  
  - ✅ Beginner-friendly  
  - ⚡ High-performance  
  - 🌐 Multi-agent support  
  - 🏢 Enterprise-ready  
  - 🧪 Experimental / research  


> Tip: Only include libraries that are **publicly available, actively maintained**, and relevant to **A2A** or **agent orchestration**.


## Libraries by Language

### Python

- **[A2A Python SDK](https://github.com/a2aproject/a2a-python)**  
  The official Python SDK for the Agent2Agent (A2A) Protocol, enabling building A2A‑compliant agents and servers.  
  - Role: Client + Server  
  - Architecture: Peer-to-peer  
  - Readiness: Stable  
  - Complexity: Intermediate  
  - Notes: Official SDK with HTTP/gRPC support, async Python support via `a2a-sdk` package.  
  - Optional Tags: 🌐 Multi-agent support

- **[Pydantic AI](https://github.com/pydantic/pydantic-ai)**  
  A Python agent framework with native A2A support via `to_a2a()` that can expose agents as A2A servers using FastA2A.  
  - Role: Client + Server / Agent Framework  
  - Architecture: Peer-to-peer  
  - Readiness: Stable  
  - Complexity: Intermediate  
  - Notes: Built by the Pydantic team, strong type safety, FastAPI-style ergonomics, supports exposing agents as A2A servers.  
  - Optional Tags: 🌐 Multi-agent support, ✅ Beginner-friendly

- **[`cA2A`](https://github.com/a2aproject/a2a-samples)** *(CLI utility)*  
  A simple CLI utility for interacting with A2A agents, useful for debugging or prototyping.  
  - Role: Utility  
  - Architecture: Peer-to-peer  
  - Readiness: Experimental  
  - Complexity: Beginner-friendly  
  - Notes: Great for quick experimentation with A2A agents.  
  - Optional Tags: 🧪 Experimental / research

---

### JavaScript / TypeScript

- **[A2A JS SDK](https://github.com/a2aproject/a2a-js)**  
  Official JavaScript/TypeScript SDK for A2A Protocol, enabling agent servers and clients in Node.js/TS projects.  
  - Role: Client + Server  
  - Architecture: Peer-to-peer  
  - Readiness: Stable  
  - Complexity: Intermediate  
  - Notes: Includes an Express adapter for server usage.  
  - Optional Tags: 🌐 Multi-agent support

---

### Java

- **[A2A Java SDK](https://github.com/a2aproject/a2a-java)**  
  Official Java SDK for building A2A‑compliant agents and servers.  
  - Role: Client + Server  
  - Architecture: Peer-to-peer  
  - Readiness: Stable  
  - Complexity: Intermediate  
  - Notes: Supports JSON-RPC, gRPC, and REST transports.  
  - Optional Tags: 🌐 Multi-agent support

---

### Go

- **[A2A Go SDK](https://github.com/a2aproject/a2a-go)**  
  Official Go SDK for implementing A2A servers and clients.  
  - Role: Client + Server  
  - Architecture: Peer-to-peer  
  - Readiness: Stable  
  - Complexity: Intermediate  
  - Notes: Examples include both server and client usage.  
  - Optional Tags: 🌐 Multi-agent support

- **[tRPC-A2A-Go](https://github.com/trpc-group/trpc-a2a-go)** *(community implementation)*  
  Community Go implementation that follows the A2A protocol with examples and utilities.  
  - Role: Client + Server  
  - Architecture: Peer-to-peer  
  - Readiness: Experimental  
  - Complexity: Intermediate  
  - Notes: Includes session management and auth capabilities.  
  - Optional Tags: 🧪 Experimental / research

---

### Rust

- **[a2a-rs](https://github.com/EmilLindfors/a2a-rs)**  
  Rust implementation of the A2A protocol with examples and production-like use cases.  
  - Role: Client + Server  
  - Architecture: Peer-to-peer  
  - Readiness: Experimental  
  - Complexity: Advanced  
  - Notes: Includes demo agents showcasing HTTP/WebSocket usage.  
  - Optional Tags: 🧪 Experimental / research

---

### C#

- **[A2A .NET SDK](https://github.com/a2aproject/a2a-dotnet)**  
  Official .NET implementation of the A2A Protocol for C# applications.  
  - Role: Client + Server  
  - Architecture: Peer-to-peer  
  - Readiness: Stable  
  - Complexity: Intermediate  
  - Notes: Suitable for .NET and ASP.NET Core apps.  
  - Optional Tags: 🌐 Multi-agent support

- **[a2a-dotnet](https://github.com/a2aproject/a2a-dotnet)** *(community options)*  
  Other .NET A2A implementations focusing on interoperability.  
  - Role: Client + Server  
  - Architecture: Peer-to-peer  
  - Readiness: Experimental  
  - Complexity: Intermediate  
  - Notes: Useful alternatives or enhancements.  
  - Optional Tags: 🧪 Experimental / research


---

## Related Ecosystem

- **[A2A Protocol Specification](https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/)** – Official protocol documentation  
- **[awesome-agents / awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents)** – Broader agent framework lists  
- Multi-agent orchestration frameworks may integrate with A2A but are listed elsewhere  


## Contribution Guidelines

Contributions are welcome! Please follow these guidelines:  
- Only add **actively maintained** libraries  
- Include **links, roles, model type, and maturity**  
- Submit via pull requests with descriptive information  

See full guidelines: [CONTRIBUTING.md](CONTRIBUTING.md)


## License

This list is released under the **MIT License**.
