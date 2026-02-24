# Switchblade

> **A lightweight, security-first AI agent that requests permission before acting.**

Switchblade is a local-first system agent built in Go. While other AI agents may execute commands without oversight, Switchblade acts as a digital gatekeeper. It suggests a "First Move," but no system changes occur until the user provides explicit approval.

## Features
* **Zero Trust Architecture:** No system execution runs without manual approval.
* **Proactive Engine:** Monitors the environment and suggests optimizations via LLM.
* **Dual-Control:** Manage the agent through a Terminal User Interface (TUI) or a Web GUI.
* **Flexible Providers:** Supports local integration with Ollama (optional) or remote API providers.

## Installation

### Option 1: Fast Install (Recommended)
1. Download the latest release for your operating system (.zip for Windows, .tar.gz for Linux/Mac).
2. Extract the folder.
3. Run the `switchblade` executable file.

### Option 2: Build from Source
If you wish to compile the project yourself, follow these steps:

**1. Install Go**
* **Windows:** Download the installer from [go.dev/dl](https://go.dev/dl/).
* **Linux (Ubuntu/Mint):** Run `sudo apt install golang-go`.
* **Mac:** Run `brew install go`.

**2. Compile the Project**
Navigate to the extracted `switchblade` folder in your terminal and run:
```bash
go mod tidy
go build -o switchblade
