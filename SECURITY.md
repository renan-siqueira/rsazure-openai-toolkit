# 🔐 Security Policy

This document outlines the security model, access policies, and best practices for the `rsazure-openai-toolkit` project.
___

## 👤 Maintainer Control & Branch Protection

This repository is maintained solely by the project owner.

- Direct pushes to any branch are restricted
- Only the maintainer can merge changes
- All releases are manually reviewed and published

This guarantees that all published code is intentional, verifiable, and secure.
___

## ✅ Security Best Practices

While this project does not handle user credentials or transmit data externally, it is recommended that:

- You never expose API keys in source code
- Environment variables are used to manage secrets
- You follow the [principle of least privilege](https://en.wikipedia.org/wiki/Principle_of_least_privilege) when configuring Azure OpenAI
___

## 📝 Logging and Local Data

This toolkit supports **opt-in local logging** to assist with debugging and cost tracking. When enabled via environment variables, the following data may be saved locally:

- Prompts and responses
- Token usage
- Response time
- Model configuration (including seed)

### Important:

- Logging is **disabled by default**
- All data is saved **locally on disk**, never transmitted
- You are responsible for protecting local logs — especially in shared environments

> Configure logging via `RSCHAT_LOG_MODE` and `RSCHAT_LOG_PATH` environment variables.
___

### 🔄 Session Context Persistence (since v0.5.0)

This toolkit supports optional **context persistence** via `SessionContext`, which stores your conversation history on disk (when enabled).

- Context files are saved locally as `.jsonl` and `.meta.json`
- Includes message history, system prompt, and model configuration
- All context storage is **opt-in**, triggered via environment variables
- Full history is saved to a separate `.full.jsonl` file, even if context is trimmed

> ⚠️ Use with care on shared machines. Avoid using sensitive data in prompts or responses if local storage is enabled.
___

## 📣 Reporting a Vulnerability

If you discover a potential security issue in this project, please **report it responsibly**:

- Open a [GitHub Issue](https://github.com/renan-siqueira/rsazure-openai-toolkit/issues), or  
- Email directly: [renan.siqu@gmail.com](mailto:renan.siqu@gmail.com)

You will receive a response as soon as possible. Please **avoid disclosing vulnerabilities publicly** before they are resolved.
___

## 🔒 Security Notes

- This toolkit **does not collect or send any data externally**.
- All logic is executed **locally** and transparently — feel free to audit the code.
- No telemetry, analytics, or external logging mechanisms are used.
___

## 🤝 Responsible Use

This project is open source and shared in the spirit of collaboration.
Please use it ethically and contribute improvements or fixes whenever possible.

Thank you for helping keep the open source ecosystem safe!
