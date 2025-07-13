# Contributing to HAP

Thank you for your interest in contributing to the **Hybrid Attack Panel (HAP)**.

We welcome contributions of all kinds — data, code, documentation, insight. This is an open intelligence project grounded in rigor, humility, and transparency. Whether you're a researcher, developer, analyst, or curious observer, there's a place for your work here.

---

## 🗂 Data Contributions

We maintain a **[Live Activity Log](docs/activity-log.md)** of hybrid threat incidents, manually curated for now. You can contribute entries by:

1. Forking the repo and editing `docs/activity-log.md`  
2. Adding a new row in the existing table with:
    - **Date**
    - **Event Type**
    - **Region**
    - **Source (linked)**
    - **Signal Category** (from [typology](docs/typology.md))
    - **Brief Notes**
3. Submitting a pull request with the updated file

Alternatively, open a GitHub issue with the details and we’ll format it for you.

---

## 📡 Feed Recommendations

To expand our **[Manual Feed Index](docs/feed-index.md)**, please suggest:

- The feed’s name and link
- Update frequency (real-time / daily / weekly)
- Domain relevance (cyber, infrastructure, InfoOps, etc.)
- Brief rationale

You can submit this as an issue or a pull request.

---

## ⚙️ Code Contributions

We are building tools for:

- Ingesting and parsing data feeds
- Normalizing and tagging hybrid attack signals
- Generating visual or tabular panels
- Alerting and dashboard integration

Please see the `src/` directory for the current structure.

If you're submitting a script:
- Prefer Python 3.10+
- Follow PEP8 style guidelines
- Include a docstring and test if possible
- Use open-source libraries where applicable
- Avoid hard-coded API keys or credentials

For new features, feel free to open a discussion or issue before you code.

---

## ✍️ Documentation & Insights

You can help us by:

- Improving clarity in `docs/`
- Translating typology definitions into other languages
- Suggesting refinements to categories
- Providing field-specific or geopolitical context

Even a thoughtful paragraph can shape our framing — don’t underestimate the value of brief, grounded input.

---

## 🧭 Community Standards

We expect all contributors to follow the spirit of:

- Transparency over obfuscation  
- Grounded insight over speculation  
- Respect for lived realities in conflict zones  
- Intellectual humility

This is a project for sense-making, not spectacle. We moderate accordingly.

---

## 📫 Get in Touch

To start a conversation:
- Open a GitHub Issue or Discussion
- Reach out via the Ardens project: [https://github.com/eirenicon/Ardens/wiki](https://github.com/eirenicon/Ardens/wiki)

Thank you for helping us make sense of the world, one signal at a time.
