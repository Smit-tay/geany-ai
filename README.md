# Geany AI

# Under Construction 

**Geany AI** is a flexible, multi-provider AI assistant plugin for the [Geany](https://www.geany.org/) IDE. Forked and extended from Geany Copilot, it brings the power of leading AI models (Grok, Claude, OpenAI, Ollama, and more) directly into your editor with a strong emphasis on safety and usability.

Whether you need intelligent code completions, refactoring, explanations, or creative writing assistance, Geany AI lets you configure your preferred AI provider and apply changes only after explicit user confirmation.

## Features

- **Multi-Provider Support**: Seamlessly switch between Grok (xAI), Claude (Anthropic), OpenAI, Ollama/local models, and other compatible APIs.
- **Safe Code Editing with Permission Prompts**: AI suggestions are never applied automatically. A clear confirmation dialog (with optional diff preview) always asks for your explicit permission before making changes.
- **Context-Aware Code Assistance**: Generate completions, refactor code, fix bugs, write tests, or explain selected code.
- **Creative Copywriting & Text Tools**: Generate, refine, or get feedback on documentation, comments, or any text content.
- **Customizable Behavior**: Per-provider settings, custom system prompts, temperature, max tokens, and more.
- **Seamless Geany Integration**: Works with selections, whole files, keyboard shortcuts, and menu items.
- **Robust Error Handling**: Informative dialogs for API issues, rate limits, or configuration problems.
- **Undo-Safe Changes**: All edits go through Geany’s native undo stack.

## Installation

### Prerequisites
- Geany IDE with Lua support enabled (GeanyLua plugin).
- `lunajson` Lua library for JSON handling.
- `cURL` for making HTTP requests.

### Steps

1. **Clone your fork** (replace with your repo URL):
   ```bash
   git clone https://github.com/YOURUSERNAME/geany-ai.git
   cd geany-ai