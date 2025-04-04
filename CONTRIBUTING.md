# Contributing to the Detailed Prompt Engineering Collective

First off, thank you for considering contributing! This project thrives on community contributions, and your help is essential for building a valuable resource of high-quality, detailed prompts.

We aim to collect prompts that are specific, structured, well-documented, and demonstrate effective prompting techniques beyond simple requests.

## How Can I Contribute?

*   **Reporting Issues:** If you find a prompt that doesn't work as expected, is unclear, or could be improved, please [open an issue](https://github.com/kahloncoder/Prompt-Collection/issues) using the "Bug Report" or "Improvement Suggestion" template.
*   **Suggesting New Prompts/Categories:** Have an idea for a new prompt or a new category? [Open an issue](https://github.com/kahloncoder/Prompt-Collection/issues) using the "New Prompt Idea" template to discuss it.
*   **Submitting New Prompts:** This is the primary way to contribute! Please follow the guidelines below.

## Submitting a Prompt (Pull Request Process)

1.  **Fork the Repository:** Click the "Fork" button on the top right of the repository page.
2.  **Clone Your Fork:** `git clone https://github.com/kahloncoder/Prompt-Collection.git`
3.  **Create a Branch:** `git checkout -b feat/add-my-new-prompt` (Use a descriptive branch name, e.g., `feat/add-code-refactoring-prompt` or `fix/improve-paper-reviewer-notes`).
4.  **Add Your Prompt:**
    *   Find the appropriate category directory under `prompts/`. If a suitable one doesn't exist, feel free to create a new directory with a clear, descriptive name (e.g., `prompts/data_visualization/`). Use lowercase and underscores for directory names.
    *   Create a new Markdown file (`.md`) for your prompt. Use a descriptive filename (e.g., `python_docstring_generator.md`).
    *   Format your prompt file according to the **Prompt File Format** section below.
5.  **Commit Your Changes:** `git add .` and `git commit -m "feat: Add prompt for [brief description]"` (Follow conventional commit messages if possible: https://www.conventionalcommits.org/).
6.  **Push to Your Fork:** `git push origin feat/add-my-new-prompt`
7.  **Open a Pull Request (PR):** Go to the original repository on GitHub and click "New Pull Request". Choose your fork and branch. Provide a clear description of the prompt you're adding, why it's valuable, and any testing you performed. Link to any relevant issues.

## Prompt Quality Standards (IMPORTANT!)

We are looking for **detailed, specific, and high-quality** prompts. Submissions should meet the following criteria:

*   **Specificity:** Targets a clear, non-trivial task or goal. Avoid overly generic prompts.
*   **Detail:** Provides sufficient context, constraints, role-playing elements, and instructions for the LLM to perform the task effectively.
*   **Structure:** Uses clear formatting (like Markdown, defined tags `<TAG>`, or specific output structures like JSON/YAML). The prompt itself should be easy to read and understand.
*   **Effectiveness:** The prompt should demonstrably guide an LLM towards the desired output.
*   **Tested:** You should test the prompt with at least one capable LLM (e.g., GPT-4, Claude 3, Gemini Pro). Briefly mention the model(s) tested and whether the results were satisfactory in the PR description or the prompt's Notes section.
*   **Documented:** The prompt file *must* include metadata (see **Prompt File Format**) and potentially a `Notes` section explaining the prompt's design, limitations, or usage context.

## Prompt File Format

Each prompt must be in a `.md` file and use **YAML Front Matter** for metadata, followed by the prompt and explanatory sections in Markdown.

```markdown
---
title: "Concise Title for the Prompt"
description: "A brief (1-2 sentence) description of what the prompt does."
author: "[Your Name/GitHub Handle]" # Optional, but nice for attribution
date: "YYYY-MM-DD" # Date added or last significantly updated
version: "1.0" # Simple versioning (e.g., 1.0, 1.1, 2.0)
tags: ["tag1", "relevant", "keywords", "task-specific", "output-format"] # Helps searchability
technique: ["Zero-Shot", "Few-Shot", "CoT", "Role-Playing", "Output Formatting"] # List relevant techniques used
tested_models: ["GPT-4", "Claude 3 Opus"] # Optional: Models it worked well on
use_case: "Describe the primary application or scenario for this prompt."
---

## Prompt

```text
<-- Paste the exact prompt text here. -->
<-- Use appropriate formatting within the prompt if needed. -->
<-- Use ```text code blocks for the prompt itself for easy copying. -->

You are an AI assistant... Be specific... Structure your output as follows...
Provide examples if it's a few-shot prompt.
Let's think step-by-step if it's CoT.
