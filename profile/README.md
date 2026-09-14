# sonar-samples

This org contains runnable samples, workshop repos, and blueprint companion code maintained by the Sonar team. Repositories can opt in to [SonarQube Cloud](https://www.sonarsource.com/products/sonarqube/cloud/) analysis after they have been onboarded and configured.

## Repos by content type

### Workshops and tutorials (`learn-`)

| Repo | Description |
|------|-------------|
| [learn-codex-workshop](https://github.com/sonar-samples/learn-codex-workshop) | Wire Codex CLI to SonarQube Cloud: secrets scanning, SQL injection detection, agentic analysis |

## Naming convention

Repo names follow the pattern `{prefix}{feature}-{context}`, all kebab-case:

| Prefix | Use for | Example |
|--------|---------|---------|
| `sample-` | Runnable apps, infra templates, CI configs | `sample-vulnerable-java` |
| `blueprint-` | Companion repos to blueprint articles | `blueprint-quality-gate-github-actions` |
| `learn-` | Workshops and tutorials | `learn-codex-workshop` |

## Topics

Every repo carries at least three [GitHub topics](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics):

- **Product** — `sonarqube-cloud`, `sonarqube-server`, or `sonarqube-for-ide`
- **Language** — `java`, `python`, `javascript`, `typescript`, etc.
- **Integration or content type** — `github-actions`, `jenkins`, `azure-devops`, `blueprint`, `workshop`, `sample`, or `ci-template`

Optional cross-cutting topics: `agentic`, `mcp`, `remediation-agent`.
