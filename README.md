
# MySQL MCP Server

MySQL MCP Server to connect Claude Desktop LLM to the MYSQL Db and Query Database Claude.

## Getting Started

Follow the steps below to set up the project locally:

### 1. Clone the Repository

git clone <https://github.com/ankitkjha/mcp-server-mysql.git>

cd mcp-server-mysql

### 2. Install uv Package Manager

Windows

powershell -ExecutionPolicy ByPass -c "irm <https://astral.sh/uv/install.ps1> | iex"

macOS/Linux

curl -LsSf <https://astral.sh/uv/install.sh> | sh

### 3. Create and Activate Virtual Environment

### Create Virtual Environment

uv init

uv venv

### Activate Virtual Environment

### macOS/Linux

source .venv/bin/activate

### Windows

.venv\Scripts\activate

### 4. Install Required Dependencies

uv add -r requirements.txt

MCP server is part of a system that integrates LLM agents with external data (like weather APIs) and tools via Claude Desktop using MCP (Module Context Protocol).
