# Pharos Doc-Search CLI

A lightweight command-line tool built in **Java** on top of Developer Docs MCP that lets developers search Pharos documentation directly from their terminal and get concise, sourced answers.

## 📋 Requirements Met

1. **Natural Language Input (Req. 01):** Accepts natural language questions as input (e.g., `pharos-docs "how do i deploy a contract"`).
2. **Concise Answers & References (Req. 02):** Returns a concise answer accompanied by links or references to the source documentation sections.
3. **Graceful Fallback (Req. 03):** Handles "no good answer found" gracefully instead of hallucinating or inventing false information.
4. **Install & Usage Instructions (Req. 04):** Complete README with installation instructions, usage guidelines, and 3 example queries with sample outputs.

---

## 🚀 Installation & Usage

### Prerequisites
- Java JDK 8 or higher installed on your system.

### Compilation
```bash
javac DocSearchCli.java
