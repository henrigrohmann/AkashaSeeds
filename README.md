# README.md

## Akasha Seeds 🌱

**Akasha Seeds** is a self-managed, flexible external memory system designed to be more than just a file or a database. It is a "seed" for your ideas, dreams, and narratives—a digital partner that grows with your creativity.

Whether you are weaving complex stories, managing technical insights, or capturing fleeting inspirations, Akasha Seeds provides a seamless interface to store, link, and recall your mental assets.

---

## ✨ Features

* **Self-Managed Memory**: Unlike traditional cloud storage, you own and manage your memory context.
* **Triple-Layer Interface**: Our CLI is built for flexibility. It operates over local **stdio** for speed, **OpenAPI (REST)** for web-native integration, and **MCP** for AI agent collaboration.
* **AI-Ready (MCP Compliant)**: Full support for the Model Context Protocol, enabling seamless partnership with AI agents like Claude or Gemini.
* **Open Source & Evolutionary**: Built to be forked and evolved. Turn it into your own unique creative notebook.

---

## 🛠 Project Structure & Connectivity

Akasha Seeds is built on a modular architecture that separates the "Mind" from the "Speech":

* `lib/akasha/`: **The Core Engine.** Handles Atom creation, Trait affixing, and persistent memory.
* `api/`: **The Bridge.** A **FastAPI** based implementation that is fully **OpenAPI compliant**. It provides a standardized REST API and an MCP-compliant JSON-RPC interface over stdio.
* `cli/`: **The Frontend.** A lightweight command-line tool. It can talk to the local engine via stdio or connect to remote instances via OpenAPI/HTTP, allowing you to access your "seeds" from anywhere.
* `data/`: **The Soil.** Where your identity and memory contexts are securely stored.

---

## 🔌 API & Connectivity

The API layer is designed to be highly compatible:
- **OpenAPI**: Automatically generated interactive documentation (Swagger UI) is available, making it easy to integrate with web services.
- **MCP (Model Context Protocol)**: Acts as a standard server for AI models, allowing them to read/write to your memory as a native tool.
- **Flexibility**: The CLI can switch between local process management and remote API calls without changing your workflow.


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

- lib/akasha/: The core engine logic. Handles Atom creation, Trait affixing, and memory persistence.
- api/: The interface layer. Includes the MCP-compliant JSON-RPC server for both local and remote communication.
- cli/: The command-line frontend. Optimized for minimal typing and intuitive interaction (using directives like $it).
- data/: Where your seeds sprout. Stores your local identity and encrypted memory contexts.

—-

## 🤝 Usage & Partnership

Akasha Seeds is designed to be your most intuitive digital partner. Upon your first launch, a synchronization ritual will establish your **True Name** (a secure, machine-specific identity) and your preferred handle.

### Getting Started

```bash
python cli/main.py
``

---

Simply type "help" to see the available commands.

```bash
Akasha >> help
ˋˋˋ

True Name" (a secure, machine-specific identity) and your preferred handle.

---

### Language & Localization

We believe your memory should speak your heart's language.

• Multilingual Input: You can freely type in your native language (Japanese, English, German, etc.) within quotes "".
• Note: Please ensure your terminal supports UTF-8. For special characters or multi-line text, wrapping your input in double quotes is recommended to ensure data integrity.
• Interface Locale: You can switch the help and system message language using the locale command:

---

```bash
Akasha >> locale jp  # Switch system messages to Japanese
Akasha >> locale en  # Switch system messages to English
ˋˋˋ

---

### The $it Directive

To keep your creative flow uninterrupted, Akasha understands the $it directive. It refers to the "last item you interacted with," allowing for a natural, conversational chain of thought without needing to copy-paste IDs.

—--
