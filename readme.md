# Awesome AI-Assisted Coding [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI-Assisted Coding tools, frameworks, methodologies and learning resources

AI-assisted coding is a spectrum from traditional human-driven development using line completions to AI-augmented workflows and vibe coding. This list focuses on tools and practices that enhance developer productivity while maintaining code quality and understanding.

## Contents

- [IDE Integration](#ide-integration)
- [Command Line & Extensions](#command-line--extensions)
- [Specialized AI Tools](#specialized-ai-tools)
- [Code Review & Quality](#code-review--quality)
- [Context & Prompt Engineering](#context--prompt-engineering)
- [Best Practices](#best-practices)

## IDE Integration

AI-powered development environments and standalone IDEs built for AI-first coding.

- [Cursor](https://cursor.sh/) - AI-first code editor with advanced autocomplete and chat features, built on VS Code
- [Windsurf](https://windsurf.com/) - AI-powered "agentic" IDE with collaborative coding features and AI Flows
- [Trae IDE](https://traeide.com/) - Free AI-powered IDE by ByteDance with GPT-4 and Claude 3.5 integration, unlimited access
- [Zed](https://zed.dev/) - Blazing fast Rust-based editor with AI integration and Edit Prediction powered by Zeta model
- [Replit](https://replit.com/) - Browser-based IDE with Ghostwriter AI technology for collaborative coding

## Command Line & Extensions

Terminal tools and VS Code extensions for AI-assisted development.

**Command Line Tools**
- [Claude Code](https://www.anthropic.com/claude-code) - Agentic command line tool for delegating coding tasks
- [Aider](https://aider.chat/) - AI pair programming in your terminal with free tool requiring API keys
- [GitHub Copilot CLI](https://githubnext.com/projects/copilot-cli/) - AI-powered command line assistance

**VS Code Extensions**
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer with support for multiple models including Claude 3.5 Sonnet, o1, and GPT-4o
- [Cline](https://cline.bot/) - Autonomous coding agent capable of creating/editing files, executing commands, and using the browser
- [Continue](https://continue.dev/) - Open-source AI code assistant plugin
- [Tabnine](https://www.tabnine.com/) - Privacy-focused AI code completion with local and cloud models, team-trained models

**MCP Servers**
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Browser automation and testing integration
- [Nx MCP](https://github.com/nrwl/nx-console/blob/master/apps/nx-mcp/README.md) - Monorepo management and code generation
- [Git MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Git operations and repository context

## Specialized AI Tools

AI tools designed for specific aspects of development workflow.

- [Qodo](https://www.qodo.ai/) - Agentic AI platform with test generation, code review, and auto-documentation capabilities
- [Sourcegraph Cody](https://sourcegraph.com/cody) - AI assistant for code search and navigation across large, complex codebases
- [CodeGeeX](https://codegeex.ai/) - Multilingual code generation with support for multiple IDEs and programming languages
- [AskCodi](https://www.askcodi.com/) - Comprehensive coding assistance with educational focus and clear explanations
- [CodeWP](https://codewp.ai/) - WordPress-specific AI code generator trained on WordPress standards and best practices
- [v0 by Vercel](https://v0.dev/) - AI-powered UI generator that creates React components with Tailwind CSS from natural language prompts, enabling rapid prototyping and frontend development

## Code Review & Quality

AI-powered tools for code review, quality assurance, and security.

**Code Review**
- [CodeRabbit](https://coderabbit.ai/) - AI-powered code review with comprehensive overviews and best practices suggestions
- [Sourcery](https://sourcery.ai/) - Python-focused code quality improvement through AI-powered refactoring

**Security & Testing**
- [Snyk](https://snyk.io/) - AI-powered security platform with DeepCode AI for vulnerability analysis and real-time scanning
- [DeepCode AI](https://www.deepcode.ai/) - Security-focused code analysis specializing in identifying and fixing potential vulnerabilities
- [Semgrep](https://semgrep.dev/) - Fast, open-source static analysis tool with AI-powered noise filtering, supporting 30+ languages and providing semantic code analysis with minimal false positives

## Context & Prompt Engineering

Tools and techniques for improving AI coding assistance through better context and prompting.

**Codebase Context Tools**
- [Repomix](https://github.com/yamadashy/repomix) - Pack your entire repository into a single AI-friendly file with token counting, Git-aware processing, and security features
- [16x Prompt](https://prompt.16x.engineer/) - Desktop application for managing source code context with workspace organization and API integrations
- [SnapSource](https://marketplace.visualstudio.com/items?itemName=LeonKohli.snapsource) - VS Code extension for one-click copy of project tree structure and file contents to clipboard
- [Context7](https://context7.com/) - MCP server that fetches up-to-date, version-specific documentation and code examples directly from official sources into AI prompts, eliminating hallucinated APIs and outdated code

**Rules Files & Configuration**
- **.cursorrules** - Project-specific rules for Cursor IDE with support for MDC format and file pattern matching
- **CLAUDE.md** - Special file that Claude Code automatically pulls into context for documenting project-specific practices
- **llms.txt** - General-purpose AI instruction files for establishing project context and security guidelines

**Best Practices**
- Keep rules concise (under 500 lines), focused, and actionable with concrete examples
- Use security-focused prompting to significantly reduce vulnerabilities in AI-generated code
- Start with PRD (Product Requirements Document) explaining what you're building, user flows, and tech stack
- Break down tasks into 1-3 story points and use fresh chat sessions for each component

## Best Practices

Core methodologies and approaches for effective AI-assisted development.

**Development Methodologies**
- **Design-First Approach** - Start with comprehensive design documents and specifications before AI generation
- **Incremental Generation** - Generate code in small, reviewable chunks to maintain quality and understanding
- **Human-in-the-Loop Review** - Maintain human oversight and understanding of generated code to ensure trust and quality

**Quality Assurance**
- **Continuous AI Review** - Teams using AI review see 81% quality improvements vs. 55% for teams without review
- **Consistency Alignment** - Ensure AI suggestions align with team style and standards to avoid 1.5x higher frustration rates
- **Deterministic-First Integration** - Prioritize deterministic tools like [ESLint](https://eslint.org/) and [Prettier](https://prettier.io/) with AI augmentation

**Prompt Engineering Tips**
- Start with simple, clear goals and treat prompts like API contracts with detailed specifications
- Add warnings like "(Do not change anything I did not ask for)" to prevent unwanted modifications
- Stick to widely-used, well-documented technologies for better AI suggestions
- Use version control frequently and write tests to verify AI-generated code

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
