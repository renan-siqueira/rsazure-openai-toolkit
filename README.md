<!-- ====================== -->
<!--  🔖 Clean Badge Layout -->
<!-- ====================== -->

<!-- 📦 Distribution -->
<p align="left">
  <a href="https://pypi.org/project/rsazure-openai-toolkit/">
    <img src="https://img.shields.io/pypi/v/rsazure-openai-toolkit" alt="PyPI Version" />
  </a>
  <a href="https://pypi.org/project/rsazure-openai-toolkit/">
    <img src="https://img.shields.io/pypi/dm/rsazure-openai-toolkit?color=blue" alt="Downloads" />
  </a>
  <a href="https://github.com/renan-siqueira/rsazure-openai-toolkit/releases">
    <img src="https://img.shields.io/github/v/release/renan-siqueira/rsazure-openai-toolkit?label=latest" alt="Latest Release" />
  </a>
  <a href="https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/renan-siqueira/rsazure-openai-toolkit?color=lightgrey" alt="License" />
  </a>
</p>

<!-- ⚙️ CI & Security -->
<p align="left">
  <a href="https://github.com/renan-siqueira/rsazure-openai-toolkit/actions/workflows/python-ci.yml">
    <img src="https://github.com/renan-siqueira/rsazure-openai-toolkit/actions/workflows/python-ci.yml/badge.svg" alt="CI Status" />
  </a>
  <a href="https://github.com/renan-siqueira/rsazure-openai-toolkit/security">
    <img src="https://img.shields.io/badge/security-scanned-brightgreen" alt="Security Scan" />
  </a>
  <img src="https://img.shields.io/badge/python-3.9+-blue" alt="Python Version" />
</p>

<!-- 👥 Community -->
<p align="left">
  <a href="https://github.com/renan-siqueira/rsazure-openai-toolkit/stargazers">
    <img src="https://img.shields.io/github/stars/renan-siqueira/rsazure-openai-toolkit?style=social" alt="Stars" />
  </a>
  <a href="https://github.com/renan-siqueira/rsazure-openai-toolkit/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/renan-siqueira/rsazure-openai-toolkit?color=blue" alt="Contributors" />
  </a>
</p>

<!-- ====================== -->
<!-- 🧠 Project Title w/ Links -->
<!-- ====================== -->

<h1 align="left">
  rsazure-openai-toolkit
  <a href="https://pypi.org/project/rsazure-openai-toolkit/">
    <img src="https://img.shields.io/badge/PyPI-oficial-blue?logo=pypi" alt="PyPI - Oficial" style="vertical-align: middle;" />
  </a>
  <a href="https://github.com/renan-siqueira/rsazure-openai-toolkit">
    <img src="https://img.shields.io/badge/GitHub-oficial-black?logo=github" alt="GitHub - Oficial" style="vertical-align: middle;" />
  </a>
</h1>

A fast, modular, secure, and auditable Python toolkit to integrate with Azure OpenAI — designed for developers, teams, and production environments.

> 💡 Use via `import rsazure_openai_toolkit as rschat` for access to all core features in one import.

___

## 🚀 What's New in v0.7.0

- Introduced `ConverSession`: the new orchestration core for prompt-based conversations
- Added `Agent`: a structured loader for prompt and config logic via `.rsmeta` and `config.yaml`
- Modular prompt system with variable substitution, versioning, and validation
- Full `.env` integration through `env/config.py` with centralized access
- CLI now delegates to `ConverSession` — cleaner and easier to maintain
- Merged `model_config.py` and `model.py` into unified `prompts/model.py`
- All environment access is now centralized and testable

> Check the full [CHANGELOG](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/CHANGELOG.md) for details.
___

## 📖 Documentation


- [Overview](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/docs/index.md)
- [Quick Start](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/docs/quick_start.md)
- [ConverSession Architecture](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/docs/conversession.md)
- [Environment Configuration](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/docs/config.md)
- [CLI Reference (`rschat` & `rschat-tools`)](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/docs/cli.md)
- [Session Context](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/docs/session_context.md)
- [Troubleshooting](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/docs/troubleshooting.md)
- [Security Policy](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/SECURITY.md)
- [Full Changelog](https://github.com/renan-siqueira/rsazure-openai-toolkit/blob/main/CHANGELOG.md)
___

## 📋 Requirements

- Python **3.9** or higher  
- An active **Azure OpenAI** resource and deployment
___

## 📄 License

This project is open source and licensed under the [MIT License](LICENSE), ensuring maximum flexibility and adoption.

You are free to use it in both personal and commercial projects.
___

## 📦 Changelog

We follow [semantic versioning](https://semver.org/) to ensure predictable upgrades.

- 🔎 Check the full [CHANGELOG.md](CHANGELOG.md) for detailed release notes
- 📌 Visit the [Releases Page](https://github.com/renan-siqueira/rsazure-openai-toolkit/releases) to explore version history
___

## 👨‍💻 About the Author

I'm a software engineer with real-world experience across backend, frontend, DevOps, cloud, and AI — building solutions that are designed to last.

Today, my passion is helping teams make AI development more accessible, maintainable, and truly production-ready — with full control, transparency, and respect for sound engineering principles.

I believe that great tools should be simple, powerful, and built to empower — not to lock people in. That’s the mindset behind everything I build and share.
___

### 📬 Contact

I'm always open to feedback, ideas, or professional collaboration.

- GitHub: [github.com/renan-siqueira](https://github.com/renan-siqueira)
- Email: [renan.siqu@gmail.com](mailto:renan.siqu@gmail.com)
- LinkedIn: [linkedin.com/in/renan-siqueira-antonio](https://www.linkedin.com/in/renan-siqueira-antonio/)

Feel free to connect or open an issue.  
Suggestions, contributions, and responsible disclosures are always welcome.
