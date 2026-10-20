# Zhihui Teacher · 智绘老师

**Start with a math problem. Understand through visuals. Think through guided questions.**

[Try the product](https://exam.thinkmoon.cn/) · [中文介绍](README.md)

![Guided math learning with visual explanations](assets/overview.png)

Zhihui Teacher is a Chinese-language AI math tutoring product for primary-school learners. It combines photo-based problem input, step-by-step questions, visual explanations and learning summaries.

- **Guided reasoning:** students respond to questions and hints as they work through a solution.
- **Visual math:** diagrams and animations help explain relationships involving fractions, areas, distances and other quantities.
- **Review:** students can revisit learning summaries and records.

[![Area visualization from an existing product example](assets/area-demo.gif)](https://exam.thinkmoon.cn/)

The recordings show specific existing examples. Prebuilt examples and explanations generated for uploaded problems are distinct experiences. Animation availability varies; recognition and explanations can contain errors.

## Repository scope

This repository contains the public **marketing website**, screenshots and demonstration recordings. It does **not** contain the tutoring backend, model configuration, accounts or student data. Visit **https://exam.thinkmoon.cn/** to use the complete product.

## Preview locally

Open `index.html` directly, or run this command with an existing Python 3 installation:

```bash
python -m http.server 8080 --bind 127.0.0.1
```

Then visit `http://127.0.0.1:8080`. No dependencies, build step or API keys are required. This repository does not automatically deploy to production or enable GitHub Pages.

## Contributions and licensing

See [CONTRIBUTING.md](CONTRIBUTING.md). Please do not include personal student information in public issues.

The marketing website code is released under the [MIT License](LICENSE). Product branding and media have separate terms described in [NOTICE.md](NOTICE.md).
