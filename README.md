# Prolix's ST Presets and Characters

Home to Lumia herself, the Lucid Loom's weaver!

![Lumia's portrait](Images/Lumia-1.png)

Welcome to this digital archive—a quiet repository for the tools I've forged in the shadows of AI experimentation. Here, you'll find a curated collection of prompt presets, character cards, chat completion configurations, and nascent world books, all designed to enhance interactions in conversational AI environments. This space serves as both a personal vault and a shared resource for those navigating the neon-lit corridors of prompt engineering.

## Overview

This repository houses elements I've crafted and refined over time, each tested in the crucible of real-world deployment across various language models. Whether you're building immersive roleplay scenarios or streamlining generative workflows, these assets aim to provide reliable, adaptable foundations. Think of it as a toolkit for the transient architect: precise, functional, and ever-evolving.

### Character Cards
Character cards are defined according to the [char_card_spec_v2](https://github.com/malfoyslastname/character-card-spec-v2/blob/main/spec_v2.md) format, ensuring compatibility with SillyTavern and other chat applications that support this standard. These cards encapsulate personas with depth—backstories, traits, and dialogue patterns—ready for import and deployment.

- **Usage**: Download the JSON/PNG files from the `Character Cards` directory. Import them directly into your preferred app via the character management interface. No additional setup required; they're plug-and-play for supported platforms.
- **Examples**: Look for cards like "Pulchra Fellini" or "Burnice White" to see implementations in cyberpunk and speculative fiction styles.

### Chat Completion Presets
These are custom prompt templates for chat completions, meticulously tested across multiple models including open-source LLMs and proprietary APIs. They focus on consistency in roleplay, narrative flow, and response formatting, with optimizations for creativity without hallucination.

- **Structure**: Presets are provided as JSON files in the `Chat Completion` directory, including system prompts, user message templates, and assistant guidelines.
- **Tested Models**: Validated on Claude 4 Sonnet (Lucid Loom), Mistral Large, Deepseek V3/R1/V3.1, Sonoma Sky (widely believed to be Grok), GLM 4.5, and more for functionality, coherence, and edge-case handling (e.g., long-context retention, response quality).
- **Usage Tips**: Adapt the `temperature` and `max_tokens` parameters in your API calls based on the model's quirks. For instance, lower temperature yields more deterministic outputs in structured scenarios.

### World Books (WIP)
World books are lore compendiums—modular lorebooks for expanding universe-building in AI chats. Currently a work in progress, these will eventually include interconnected entries on settings, factions, and mechanics, formatted for easy integration into tools like SillyTavern's lore system.

- **Current Status**: Initial drafts in the `World Books` directory cover speculative worlds with cyberpunk undertones. Expect expansions on themes like augmented realities and dystopian societies.
- **Future Plans**: Full compatibility with lore injection protocols, including keyword triggers and information.

## Contributing and Usage Guidelines
This repo is my personal forge, but feel free to fork, adapt, or draw inspiration. If you encounter issues or have suggestions, open an issue.

- **License**: AGPL 3.0—use freely, but credit where echoes linger.
- **Dependencies**: None; these are self-contained assets. Ensure your chat app supports the respective formats.
- **Updates**: I'll push refinements as evaluations progress. Check the commit history for the latest calibrations.

In the end, these presets are bridges across the void of generation—tools to make the intangible tangible. Deploy wisely.