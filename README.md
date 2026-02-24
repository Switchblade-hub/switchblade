# Switchblade

> **A lightweight, security-first AI agent that requests permission before acting.**

Switchblade is a local-first system agent built in Go. While other AI agents may execute commands without oversight, Switchblade acts as a digital gatekeeper. It suggests a "First Move," but no system changes occur until the user provides explicit approval.

## Features
* **Zero Trust Architecture:** No system execution runs without manual approval.
* **Proactive Engine:** Monitors the environment and suggests optimizations via LLM.
* **Dual-Control:** Manage the agent through a Terminal User Interface (TUI) or a Web GUI.
* **Flexible Providers:** Supports local integration with Ollama (optional) or remote API providers.

## Quick Start
1. **Ensure Go is installed** (v1.22+)
2. **Setup Provider (Optional):** Install Ollama and pull a model (e.g., `ollama pull llama3.2`) to keep everything local.
3. **Clone and Run:**
   ```bash
   git clone [https://github.com/Switchblade-hub/switchblade.git](https://github.com/Switchblade-hub/switchblade.git)
   cd switchblade
   go run .
