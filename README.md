# The Detailed Prompt Engineering Collective 🎯

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <!-- Optional Badge -->
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md) <!-- Optional Badge -->
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md) <!-- Optional Badge -->

**A curated collection of specific, detailed, and structured prompts designed for effective interaction with advanced AI models.**

## Motivation & Goal ✨

The power of Large Language Models (LLMs) often lies in the quality of the prompt. While simple prompts can yield basic results, unlocking sophisticated capabilities requires more detailed guidance. Generic prompt collections often lack the specificity needed for complex, reliable, or structured outputs.

This repository aims to be a high-quality resource focusing exclusively on **detailed prompts**. We collect and refine prompts that leverage techniques like:

*   **Clear Role-Playing:** Defining the AI's persona and expertise.
*   **Specific Instructions & Constraints:** Guiding behavior and output format precisely.
*   **Structured Output:** Requesting formatted outputs (JSON, YAML, Markdown tables, etc.).
*   **Chain-of-Thought (CoT) / Reasoning Steps:** Encouraging explicit reasoning for better results on complex tasks.
*   **Few-Shot Examples:** Providing concrete demonstrations within the prompt when needed.

Our goal is to build a community-driven library that helps engineers, researchers, and creators craft more effective and reliable interactions with AI.

## Scope 🔭

This collection focuses on **non-trivial, detailed prompts** like the [AI Paper Reviewer Example](prompts/research_assistance/ai_paper_reviewer.md). We prioritize prompts that require specific formatting, complex instructions, or demonstrate advanced prompting techniques effectively.

Simple, one-line prompts (e.g., "Summarize this text") are generally out of scope unless they demonstrate a particularly clever technique within that simplicity.

## How Prompts Are Organized 📂

Prompts are organized into category-based directories within the `prompts/` folder. Categories reflect the primary task or domain of the prompt (e.g., `code_generation`, `data_analysis`, `research_assistance`).

Each prompt resides in its own Markdown (`.md`) file, containing:
1.  **YAML Front Matter:** Structured metadata (title, description, tags, techniques used, etc.).
2.  **The Prompt:** The core text to be used with the LLM.
3.  **Notes:** Explanations, rationale, limitations, and usage context.
4.  **(Optional) Example Usage/Output:** Demonstrations of how to use it and what to expect.

## How to Use These Prompts 🚀

1.  **Browse:** Navigate the `prompts/` directory by category.
2.  **Select:** Open the `.md` file for a prompt that matches your needs.
3.  **Review:** Read the description, notes, and prompt text carefully. Understand any required inputs or context.
4.  **Copy:** Copy the prompt text from the `## Prompt` section (usually within a ` ```text ` block).
5.  **Adapt & Use:** Paste the prompt into your LLM interface or application. You may need to:
    *   Provide necessary input data *before* the prompt text.
    *   Adapt placeholders within the prompt if any exist.
    *   Adjust based on the specific LLM you are using.

## Contributing 🙏

This is a community effort! We strongly encourage contributions. Please read our **[Contribution Guidelines](CONTRIBUTING.md)** before submitting a Pull Request. We have specific quality standards and formatting requirements to maintain the collection's value.

Key Contribution Areas:
*   Adding new high-quality, detailed prompts.
*   Improving existing prompts (clarity, effectiveness, documentation).
*   Suggesting new categories.
*   Reporting issues with prompts.

## License 📜

This repository and its contents (the prompts) are licensed under the [MIT License](LICENSE). This allows for permissive use, modification, and distribution.

## Code of Conduct 🤝

We adhere to the Contributor Covenant. Please review our [Code of Conduct](CODE_OF_CONDUCT.md) to understand expectations for participation.

---

Let's build an amazing resource together!
