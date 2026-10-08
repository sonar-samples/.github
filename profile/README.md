<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="img/sonar-logo-dark.svg">
    <img src="img/sonar-logo.svg" alt="Sonar" width="220">
  </picture>

  <p><strong>Practical examples and step-by-step guides for integrating Sonar into agentic developer workflows</strong></p>

  <p>
    <a href="https://www.sonarsource.com/">Website</a> ·
    <a href="https://docs.sonarsource.com/">Docs</a> ·
    <a href="https://community.sonarsource.com/">Community</a> ·
    <a href="https://x.com/SonarSource">@SonarSource</a>
  </p>
</div>

<br>

AI agents write code faster than most teams can review it. That gap is verification debt, and it grows every time a pull request merges before anyone has actually checked what changed. [Sonar](https://www.sonar.com/) calls the discipline of closing that gap the [Agent Centric Development Cycle](https://sonarsource.com/acdc), or AC/DC: guide agents with the right context, verify what they produce, and solve the issues verification finds. The repositories in this org are hands-on guides for each stage of that cycle.

The repositories linked from this page are example implementations, not supported Sonar products. They exist to help you learn and adapt Sonar for your own workflows. Test, secure, and validate anything you use here against your team’s standards before it touches production.

Choose what you want to do, then open the repository that matches your tool or environment. Each guide repository includes the complete steps and supporting files.

**I want to:**

- [Work with AI coding agents](#work-with-ai-coding-agents)
- [Improve pull request reviews with Gitar](#improve-pull-request-reviews-with-gitar)
- [Manage application architecture](#manage-application-architecture)
- [Browse every workshop, blueprint, and sample](#browse-by-content-type)

## Find what you need

### Work with AI coding agents

| If you use | Start here | What you will set up |
|---|---|---|
| Claude Code | [Set up Sonar Vortex in Claude Code](https://github.com/sonar-samples/blueprint-sonar-vortex-claude) | Project guidance, automatic analysis after edits, multi-file analysis, and secrets detection |
| OpenAI Codex | [Wire your team for agentic development with SonarQube and OpenAI Codex](https://github.com/sonar-samples/learn-codex-workshop) | A hands-on SonarQube Cloud workflow for finding secrets, investigating issues, and verifying AI-generated code |
| Cursor | [Set up the SonarQube plugin for Cursor](https://github.com/sonar-samples/blueprint-sonarqube-plugin-cursor) | The SonarQube plugin, SonarQube MCP Server, analysis hooks, secrets detection, and project context |
| A terminal or multiple coding agents | [Get started with the SonarQube CLI](https://github.com/sonar-samples/blueprint-sonarqube-cli) | Local analysis, agent integrations, Git hooks, project queries, and SonarQube authentication |

### Improve pull request reviews with Gitar

| If you want to | Start here |
|---|---|
| Learn the full review workflow in a browser | [Gitar workshop](https://github.com/sonar-samples/gitar-workshop) |
| Make reviews aware of repository conventions and rules | [Configure Gitar context for project-aware code reviews](https://github.com/sonar-samples/blueprint-gitar-context-ingestion) |
| Add organization instructions, Jira, Slack, or custom context | [Extend Gitar with organization and external context](https://github.com/sonar-samples/blueprint-gitar-advanced-config) |
| Run the application used in the Gitar context blueprints | [Gitar context ingestion sample](https://github.com/sonar-samples/sample-gitar-context-ingestion) |

### Manage application architecture

| If you want to | Start here |
|---|---|
| Explore current architecture, define an intended architecture, and find deviations | [Get started managing your architecture with SonarQube](https://github.com/sonar-samples/blueprint-architecture-management-sonarqube-cloud) |

## Browse by content type

### Hands-on workshops

| Repository | What it covers |
|---|---|
| [`learn-codex-workshop`](https://github.com/sonar-samples/learn-codex-workshop) | Connect Codex CLI to SonarQube Cloud and work through secrets detection, issue investigation, and verification of AI-generated code. |
| [`gitar-workshop`](https://github.com/sonar-samples/gitar-workshop) | Use Gitar to review pull requests, enforce repository conventions, and investigate a failing CI pipeline. |

### Implementation blueprints

| Repository | What it covers |
|---|---|
| [`blueprint-sonar-vortex-claude`](https://github.com/sonar-samples/blueprint-sonar-vortex-claude) | Set up Sonar Vortex in Claude Code with project context, code verification, and secrets detection. |
| [`blueprint-sonarqube-plugin-cursor`](https://github.com/sonar-samples/blueprint-sonarqube-plugin-cursor) | Add the SonarQube plugin and its supporting integrations to Cursor. |
| [`blueprint-sonarqube-cli`](https://github.com/sonar-samples/blueprint-sonarqube-cli) | Use the SonarQube CLI for local analysis, agent integrations, Git hooks, and project data. |
| [`blueprint-architecture-management-sonarqube-cloud`](https://github.com/sonar-samples/blueprint-architecture-management-sonarqube-cloud) | Explore current architecture, define an intended architecture, and find deviations in SonarQube Cloud. |
| [`blueprint-gitar-context-ingestion`](https://github.com/sonar-samples/blueprint-gitar-context-ingestion) | Configure repository context for project-aware Gitar reviews. |
| [`blueprint-gitar-advanced-config`](https://github.com/sonar-samples/blueprint-gitar-advanced-config) | Extend Gitar reviews with organization instructions, Jira, Slack, and custom integrations. |

### Runnable samples

| Repository | What it covers |
|---|---|
| [`sample-gitar-context-ingestion`](https://github.com/sonar-samples/sample-gitar-context-ingestion) | Run the Flask application and intentional error-handling bugs used by the Gitar context blueprints. |

## Search by topic

Use GitHub topics to narrow the repository list by product, workflow, tool, or language.

- **Content:** [`blueprint`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Ablueprint), [`workshop`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Aworkshop), [`sample`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Asample)
- **Product and workflow:** [`sonarqube-cloud`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Asonarqube-cloud), [`sonarqube-cli`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Asonarqube-cli), [`sonar-vortex`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Asonar-vortex), [`gitar`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Agitar), [`architecture`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Aarchitecture), [`code-review`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Acode-review)
- **Tool:** [`claude-code`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Aclaude-code), [`codex`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Acodex), [`cursor`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Acursor), [`github`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Agithub), [`github-actions`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Agithub-actions), [`jira`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Ajira), [`slack`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Aslack)
- **Language:** [`python`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Apython), [`java`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Ajava), [`flask`](https://github.com/orgs/sonar-samples/repositories?q=topic%3Aflask)

## How repositories are organized

Repository names signal what kind of content they contain.

| Name | Content |
|---|---|
| `blueprint-` prefix | Step-by-step implementation guides with supporting configuration, code, or screenshots |
| `learn-` prefix or `-workshop` suffix | Hands-on workshops that can also be followed as standalone tutorials |
| `sample-` prefix | Focused applications, templates, or configurations used by guides and workshops |

## About these repositories

These repositories are examples designed for learning and reference. Review the prerequisites and product documentation for your own environment.

For Sonar product documentation, visit [docs.sonarsource.com](https://docs.sonarsource.com/). For product questions, use the [Sonar Community](https://community.sonarsource.com/).
