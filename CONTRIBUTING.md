# Contributing to Awesome A2A Libraries

Thank you for considering contributing! 🎉
Your help is essential for keeping this list accurate, focused, and useful for developers building **Agent-to-Agent (A2A)** systems.

This document outlines the guidelines for contributing to **Awesome A2A Libraries**.

---

## Table of Contents

* [Code of Conduct](#code-of-conduct)
* [How Can I Contribute?](#how-can-i-contribute)

  * [Suggesting Libraries](#suggesting-libraries)
  * [Adding Libraries (Pull Requests)](#adding-libraries-pull-requests)
  * [Reporting Issues](#reporting-issues)
* [Contribution Guidelines](#contribution-guidelines)

  * [What to Add](#what-to-add)
  * [What NOT to Add](#what-not-to-add)
  * [Quality Standards](#quality-standards)
  * [Formatting](#formatting)
* [Commit Message Guidelines](#commit-message-guidelines)
* [Pull Request Process](#pull-request-process)
* [Questions?](#questions)

---

## Code of Conduct

This project is governed by the [Code of Conduct](CODE_OF_CONDUCT.md).
By participating, you agree to uphold this code and help maintain a respectful community.

---

## How Can I Contribute?

### Suggesting Libraries

If you know of an **A2A-compatible library or SDK** but don’t want to open a PR yourself, feel free to **open an Issue** with:

* a link to the repository
* the programming language
* a short explanation of how it supports A2A

Please ensure the suggestion meets the [Contribution Guidelines](#contribution-guidelines).

---

### Adding Libraries (Pull Requests)

Pull Requests are the preferred way to contribute.

Before submitting, make sure your addition:

* strictly relates to **A2A**
* is a **library or SDK**, not a product or platform
* is added under the **correct programming language**

---

### Reporting Issues

Please open an Issue if you find:

* broken or outdated links
* incorrect classifications
* libraries that no longer support A2A
* structural or organizational problems

Suggestions for improving the list structure are also welcome.

---

## Contribution Guidelines

### What to Add

We accept **only code libraries** that **implement or directly support the Agent2Agent (A2A) protocol**, including:

* **SDKs & Client Libraries** — Language-native A2A clients or SDKs
* **Servers & Infrastructure** — A2A-compatible servers, registries, discovery services, or transports
* **Utilities** — Message schemas, validation tools, adapters, or helpers directly enabling A2A

Libraries must be **usable programmatically** and publicly accessible.

---

### What NOT to Add

Please do **NOT** add:

* General agent or AI frameworks without A2A support
* Tutorials, blog posts, or conceptual articles
* Example apps or demos that are not reusable libraries
* SaaS platforms or hosted products
* Prompt collections or templates
* Vague, promotional, or abandoned repositories

If a resource does not clearly support A2A, it does not belong in this list.

---

### Quality Standards

All submissions should meet the following criteria:

* **Relevance** — Explicit A2A support or implementation
* **Clarity** — Clear purpose and documentation
* **Maintenance** — Actively maintained or reasonably complete
* **Accuracy** — Correct classification and description

Maintainers may reject or remove entries that do not meet these standards.

---

### Formatting

Use the following format for entries:

* **Library Name**
  Short, objective description

  * Role: sdk | client | server | utility
  * Model: peer-to-peer | hybrid
  * Maturity: experimental | stable | production

**Guidelines:**

* Keep descriptions concise and factual
* Place the entry under the correct language section
* Avoid marketing language
* Do not add emojis to list items

---

## Commit Message Guidelines

Please use clear, consistent commit messages.

**Format:**
[Emoji] [Action]: [Short description]

**Examples:**

* 📦 Add A2A SDK for Rust
* 🐛 Fix broken link in Python section
* 📝 Improve contribution guidelines
* 🔥 Remove unmaintained A2A library

**Common Emojis:**

* 📦 New library or SDK
* 🐛 Fix or correction
* 📝 Documentation update
* 🔥 Removal of outdated entries
* 🎨 Formatting or structural changes

---

## Pull Request Process

1. Fork the repository
2. Clone your fork:
   git clone [https://github.com/YOUR_USERNAME/awesome-a2a-libraries.git](https://github.com/YOUR_USERNAME/awesome-a2a-libraries.git)
3. Create a branch:
   git checkout -b add-a2a-library
4. Add your entry to README.md following the formatting rules
5. Commit your changes using the guidelines above
6. Push your branch and open a Pull Request
7. Clearly explain what you added and why it belongs

Maintainers may request changes before merging.

---

## Questions?

If you’re unsure whether a library belongs in this list, open an Issue with the label `question` and we’ll discuss it.

Thank you for helping keep **Awesome A2A Libraries** focused and high-quality ❤️

---

### Why this adaptation works

* ✅ Zero ambiguity about scope
* ✅ Prevents list dilution
* ✅ Reinforces *libraries only*
* ✅ Easy to maintain long-term
* ✅ Complements (not competes with) other awesome lists

If you want next, I can:

* tighten it further (more strict)
* align it with the exact README structure
* add a **PR checklist**
* or make a **minimal version** if you prefer less process

Just tell me.
