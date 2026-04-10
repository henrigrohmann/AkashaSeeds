# README.md

## Akasha Seeds 🌱

**Akasha Seeds** is a self-managed, flexible external memory system designed to be more than just a file or a database. It is a "seed" for your ideas, dreams, and narratives—a digital partner that grows with your creativity.

Whether you are weaving complex stories, managing technical insights, or capturing fleeting inspirations, Akasha Seeds provides a seamless interface to store, link, and recall your mental assets.

---

## ✨ Features

* **Self-Managed Memory**: Unlike traditional cloud storage, you own and manage your memory context.
* **Flexible Interface**: Use it as a Python library, a lightweight CLI, or connect via **Akasha Note** for internet-wide access.
* **AI-Ready (MCP Compliant)**: Designed with the Model Context Protocol in mind, making it a perfect companion for AI agents.
* **Open Source & Evolutionary**: Built to be forked and evolved. Turn it into your own unique creative notebook.

---

## 🚀 Environment

* **Language**: Python 3.10+
* **Core**: SQLite-based Atom/Trait Engine
* **Platform**: Cross-platform (Linux, macOS, Windows, and optimized for Codespaces/IoT)

---

## 📦 Installation

Clone the repository and install the dependencies:

```bash
git clone [https://github.com/henrigrohmann/AkashaSeeds.git](https://github.com/henrigrohmann/AkashaSeeds.git)
cd AkashaSeeds
pip install -r requirements.txt
```

—-

## 🛠 Project Structure

The project is designed with a clean separation of concerns, allowing you to easily swap the engine or the interface:

• lib/akasha/: The core engine logic. Handles Atom creation, Trait affixing, and memory persistence.
• api/: The interface layer. Includes the MCP-compliant JSON-RPC server for both local and remote communication.
• cli/: The command-line frontend. Optimized for minimal typing and intuitive interaction (using directives like $it).
• data/: Where your seeds sprout. Stores your local identity and encrypted memory contexts.

—-

## 🤝 Usage & Partnership

Akasha Seeds is not just a tool; it's a partner. Upon your first launch, a synchronization ritual will establish your "True Name" (a secure, machine-specific identity) and your preferred handle.

```bash
python cli/main.py
ˋˋˋ

—-
