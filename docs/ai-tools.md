# AI Tools for .NET Developers

AI tools are now essential in modern software development. They help you write code faster, debug smarter, understand documentation, and stay productive. Here is a curated list of AI tools every .NET developer should know.

## Coding Assistants (In-IDE)

| **Tool** | **Works With** | **Description** |
| --- | --- | --- |
| [GitHub Copilot](https://github.com/features/copilot) | VS, VS Code, Rider | Most popular AI pair programmer; autocompletes code, explains functions, writes tests |
| [Cursor](https://www.cursor.com/) | Cursor (VS Code fork) | AI-first editor with deep codebase understanding and multi-file edits |
| [JetBrains AI Assistant](https://www.jetbrains.com/ai/) | Rider, other JetBrains IDEs | Native AI assistant for Rider with code generation and refactoring |
| [Visual Studio IntelliCode](https://visualstudio.microsoft.com/services/intellicode/) | Visual Studio | Microsoft's AI-powered code completion trained on open-source .NET code |
| [Tabnine](https://www.tabnine.com/) | VS, VS Code, Rider | Privacy-focused AI code completion, can run fully on-premises |
| [Amazon Q Developer](https://aws.amazon.com/q/developer/) | VS Code, Visual Studio | AWS AI coding assistant, strong on cloud-related code |
| [Supermaven](https://supermaven.com/) | VS Code, Neovim | Very fast AI code completion with large context window |
| [Codeium](https://codeium.com/) | VS Code, Visual Studio, Rider | Free AI code completion with chat and search features |

## AI Chat & Reasoning (For Problem Solving)

| **Tool** | **Best For** | **Description** |
| --- | --- | --- |
| [Claude](https://claude.ai/) | Architecture, code review, long context | Excellent at reasoning through complex .NET problems, reading large files |
| [ChatGPT](https://chatgpt.com/) | General coding help, explanations | Broad knowledge of .NET, C#, and the ecosystem |
| [Gemini](https://gemini.google.com/) | Google integration, multimodal tasks | Strong at explaining errors and integrating with Google Cloud |
| [Perplexity](https://www.perplexity.ai/) | Research with citations | Good for finding up-to-date NuGet packages and .NET blog posts |
| [Phind](https://www.phind.com/) | Developer-focused search | Purpose-built for developers, links to Stack Overflow and GitHub |
| [You.com](https://you.com/) | Code search | Developer-friendly AI search with code mode |

## AI-Powered CLI Tools

| **Tool** | **Description** |
| --- | --- |
| [Claude Code](https://claude.ai/claude-code) | Agentic CLI that reads your entire codebase and completes multi-step coding tasks |
| [GitHub Copilot CLI](https://githubnext.com/projects/copilot-cli/) | Explains and suggests shell commands, git commands, and scripts |
| [Aider](https://aider.chat/) | Open-source AI pair programmer that works inside your terminal with git integration |
| [Continue](https://www.continue.dev/) | Open-source AI code assistant you can self-host with any model |

## AI for Code Review & Quality

| **Tool** | **Description** |
| --- | --- |
| [CodeRabbit](https://coderabbit.ai/) | AI pull request reviewer that posts line-by-line feedback on GitHub/GitLab PRs |
| [Sourcery](https://sourcery.ai/) | Automated code review and refactoring suggestions |
| [DeepSource](https://deepsource.com/) | Static analysis with AI-assisted fix suggestions |
| [SonarQube AI](https://www.sonarsource.com/) | Code quality and security scanner with AI-powered issue explanations |

## AI for Documentation & Learning

| **Tool** | **Description** |
| --- | --- |
| [Microsoft Copilot in Docs](https://learn.microsoft.com/en-us/) | Ask questions directly on Microsoft Learn docs pages |
| [Mintlify Writer](https://writer.mintlify.com/) | Auto-generates XML doc comments for C# methods and classes |
| [DocuWriter.ai](https://www.docuwriter.ai/) | Generates documentation and README files from your code |
| [Pieces for Developers](https://pieces.app/) | AI-powered snippet manager with context-aware search and explanations |

## AI for Testing

| **Tool** | **Description** |
| --- | --- |
| [CodiumAI (Qodo)](https://www.qodo.ai/) | Generates unit tests for your .NET methods automatically |
| [Diffblue Cover](https://www.diffblue.com/) | Enterprise tool that writes xUnit/NUnit tests for Java and .NET code |
| [Copilot for unit tests](https://github.com/features/copilot) | Use GitHub Copilot chat with `/tests` command to generate test cases |

## AI for Architecture & Diagrams

| **Tool** | **Description** |
| --- | --- |
| [Eraser](https://www.eraser.io/) | Generate architecture diagrams and system design docs using AI prompts |
| [Mermaid + AI](https://mermaid.js.org/) | Describe a flow in plain text, let AI convert it to Mermaid diagrams |
| [ChatGPT + draw.io](https://app.diagrams.net/) | Ask ChatGPT to generate XML/draw.io diagrams from your architecture description |

## Tips for .NET Developers Using AI

- **Give context**: Paste your `Program.cs`, middleware setup, or relevant class before asking questions.
- **Mention the framework**: Say ".NET 8 Minimal API" or "ASP.NET Core with EF Core" — not just ".NET".
- **Use AI for boilerplate**: Let AI generate CRUD controllers, DTOs, repository patterns, and migrations.
- **Review AI output**: AI can hallucinate NuGet package names or outdated APIs — always verify against [nuget.org](https://www.nuget.org/) and [learn.microsoft.com](https://learn.microsoft.com/).
- **Combine tools**: Use Copilot for inline completion and Claude or ChatGPT for architectural decisions.
- **Prompt engineering matters**: Clear, specific prompts produce far better results than vague ones.
