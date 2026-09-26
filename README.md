# Awesome Automated Code Quality Tools 🚀

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

> **A curated landscape of top Static Application Security Testing (SAST), Static Code Analysis, Linters, Code Smells, Software Composition Analysis (SCA), and Automated Quality Gate platforms.**

The **Automated Code Quality & SAST** market is estimated at **~$3.2 Billion USD**, projected to reach **~$7.5 Billion by 2030** (CAGR ~18.5%). The sector is **moderately fragmented**, featuring high enterprise consolidation around major platform vendors (Microsoft/GitHub, Synopsys, SonarSource, Snyk, Veracode, Checkmarx) alongside a thriving ecosystem of open-source linters and specialized static engines.

---

## 📋 Table of Contents
- [Market Overview](#-market-overview)
- [SaaS & Commercial Hosted Platforms](#-saas--commercial-hosted-platforms)
- [Open-Source GitHub Projects](#-open-source-github-projects)
- [Key Features Comparison & Selection Criteria](#-key-features-comparison--selection-criteria)
- [How to Contribute](#-how-to-contribute)
- [Disclaimer](#-disclaimer)

---

## 📊 Market Overview

Automated code quality tools scan source code in CI/CD pipelines to detect security vulnerabilities, code smells, performance bottlenecks, and style violations before pull requests are merged. 

- **Enterprise Platform Trend**: Convergence of SAST (Security), SCA (Dependencies), and Code Quality (Maintainability/Smells) into unified Developer Security Platforms.
- **Open-Source Engine Standard**: Modern developer workflows rely heavily on fast, local open-source linters and SAST tools (Ruff, ESLint, Semgrep, Trivy) combined with centralized SaaS quality gates.

---

## 🏢 SaaS & Commercial Hosted Platforms

*Sorted by Company Financial Scale / Valuation (Descending)*

| Platform / Product | Starting Price (Tier) | Free Tier / Trial Limit | Company Scale (Valuation / Revenue) | Key Strengths |
| :--- | :--- | :--- | :--- | :--- |
| **[GitHub Advanced Security (CodeQL)](https://github.com/security/advanced-security)** | `$49/developer/month` (GHAS Add-on) | Free forever for all public open-source GitHub repos | **Microsoft** (`$3.1T Market Cap` / `$245B Annual Rev`) | Native GitHub PR integration, semantic CodeQL queries, secret scanning |
| **[Coverity (Synopsys Polaris)](https://www.synopsys.com/software-integrity/security-testing/static-analysis-coverity.html)** | `$3,500/year` per contributor tier | Free via scan.coverity.com for open-source; 30-day enterprise trial | **Synopsys** (`$75B Market Cap` / `$5.3B Annual Rev`) | Deep interprocedural static analysis, enterprise compliance, safety standards |
| **[Snyk Code](https://snyk.io/product/snyk-code/)** | `$25/developer/month` (Team Plan) | Free forever plan with 100 code tests/mo for private repos; unlimited for open-source | **Snyk** (`$7.4B Valuation` / `$200M+ ARR`) | Developer-first SAST, fast AI-assisted analysis, unified SCA & container scan |
| **[SonarCloud / SonarQube](https://www.sonarsource.com/products/sonarcloud/)** | `€10/month` (~$11/mo for 100k LOC) | Free forever for public open-source repos; 14-day free trial for private repos | **SonarSource** (`$4.7B Valuation` / `$200M+ ARR`) | De-facto standard quality gates, technical debt tracking, 30+ programming languages |
| **[Veracode](https://www.veracode.com/)** | `$1,200/year` per app scan tier | 14-day free trial with up to 5 project scans | **Veracode** (`$2.5B Valuation` / `$300M ARR`) | Enterprise-wide governance, AI auto-remediation (Veracode Fix), binary analysis |
| **[Checkmarx One](https://checkmarx.com/)** | `$99/developer/month` (Essentials Plan) | 14-day full-feature trial limited to 1,000 LOC scans | **Checkmarx** (`$1.15B Valuation` / `$200M ARR`) | Multi-tenant cloud enterprise SAST, supply chain security, IaC scanning |
| **[Semgrep Code (App)](https://semgrep.dev/)** | `$20/developer/month` (Pro Team Plan) | Free forever for up to 10 active monthly contributors on private repos; unlimited for open-source | **Semgrep (r2c)** (`$500M+ Valuation` / `$84M Raised`) | Custom rule creation in syntax-matched patterns, lightning-fast CI scanning |
| **[JetBrains Qodana](https://www.jetbrains.com/qodana/)** | `$6/developer/month` (Contributor Plan) | Free 60-day trial; free community license for open-source projects | **JetBrains** (`$500M+ Annual Rev`) | Native IntelliJ/JetBrains IDE integration, deep inspection parity in CI/CD |
| **[Code Climate](https://codeclimate.com/)** | `$20/developer/month` (Quality Plan) | Free forever for public open-source repos; 14-day free trial for private repos | **Code Climate** (`$150M Valuation` / `$50M Raised`) | Automated test coverage & maintainability analysis with GitHub PR feedback |
| **[Codacy](https://www.codacy.com/)** | `$15/developer/month` (Pro Plan) | Free forever for public open-source repos; 14-day free trial for private repos | **Codacy** (`$50M Valuation` / `$23M Raised`) | Automated code reviews, multi-linter orchestration, security coverage tracking |
| **[DeepSource](https://deepsource.com/)** | `$12/developer/month` (Starter Plan) | Free forever for individuals & open-source (up to 3 members, 1 private repo) | **DeepSource** (`$40M Valuation` / `$13M Raised`) | Zero-config static analysis, automatic pull request autofixes, clean dev UX |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub Star Count (Descending)*

| Repository / Project | Stars Badge | Category / Focus | Key Features |
| :--- | :--- | :--- | :--- |
| **[ShellCheck](https://github.com/koalaman/shellcheck)** | [![GitHub stars](https://img.shields.io/github/stars/koalaman/shellcheck?style=social&color=white)](https://github.com/koalaman/shellcheck/stargazers) | Shell Linter | Static analysis tool giving warnings and suggestions for bash/sh shell scripts. |
| **[Ruff](https://github.com/astral-sh/ruff)** | [![GitHub stars](https://img.shields.io/github/stars/astral-sh/ruff?style=social&color=white)](https://github.com/astral-sh/ruff/stargazers) | Python Linter / Formatter | Extremely fast Python linter and code formatter written in Rust (10-100x faster than Flake8). |
| **[ESLint](https://github.com/eslint/eslint)** | [![GitHub stars](https://img.shields.io/github/stars/eslint/eslint?style=social&color=white)](https://github.com/eslint/eslint/stargazers) | JS/TS Linter | Industry standard pluggable linting utility for JavaScript and TypeScript. |
| **[Trivy](https://github.com/aquasecurity/trivy)** | [![GitHub stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social&color=white)](https://github.com/aquasecurity/trivy/stargazers) | Security / SCA / IaC | Comprehensive security scanner for vulnerabilities, misconfigurations, secrets, and SBOM. |
| **[Biome](https://github.com/biomejs/biome)** | [![GitHub stars](https://img.shields.io/github/stars/biomejs/biome?style=social&color=white)](https://github.com/biomejs/biome/stargazers) | JS/TS Toolchain | High-performance toolchain for web projects, linting, and formatting JavaScript/TypeScript in Rust. |
| **[golangci-lint](https://github.com/golangci/golangci-lint)** | [![GitHub stars](https://img.shields.io/github/stars/golangci/golangci-lint?style=social&color=white)](https://github.com/golangci/golangci-lint/stargazers) | Go Linter Orchestrator | Fast Go linters runner managing multiple linters concurrently with smart caching. |
| **[Infer](https://github.com/facebook/infer)** | [![GitHub stars](https://img.shields.io/github/stars/facebook/infer?style=social&color=white)](https://github.com/facebook/infer/stargazers) | Static Analyzer (Meta) | Static analysis engine for Java, C, C++, and Objective-C detecting null pointers and memory leaks. |
| **[PHPStan](https://github.com/phpstan/phpstan)** | [![GitHub stars](https://img.shields.io/github/stars/phpstan/phpstan?style=social&color=white)](https://github.com/phpstan/phpstan/stargazers) | PHP Static Analyzer | PHP static analysis tool finding bugs without requiring execution of runtime code. |
| **[Semgrep OSS](https://github.com/semgrep/semgrep)** | [![GitHub stars](https://img.shields.io/github/stars/semgrep/semgrep?style=social&color=white)](https://github.com/semgrep/semgrep/stargazers) | Multi-Language SAST | Fast pattern-matching engine for code analysis using syntax-aware queries. |
| **[Hadolint](https://github.com/hadolint/hadolint)** | [![GitHub stars](https://img.shields.io/github/stars/hadolint/hadolint?style=social&color=white)](https://github.com/hadolint/hadolint/stargazers) | Dockerfile Linter | Smart Dockerfile linter enforcing best practices and parsing ASTs into ShellCheck rules. |
| **[SonarQube Community](https://github.com/SonarSource/sonarqube)** | [![GitHub stars](https://img.shields.io/github/stars/SonarSource/sonarqube?style=social&color=white)](https://github.com/SonarSource/sonarqube/stargazers) | Code Quality / SAST Server | Self-hosted platform for code inspection, technical debt tracking, and security analysis. |
| **[RuboCop](https://github.com/rubocop/rubocop)** | [![GitHub stars](https://img.shields.io/github/stars/rubocop/rubocop?style=social&color=white)](https://github.com/rubocop/rubocop/stargazers) | Ruby Linter & Formatter | Ruby static code analyzer and code formatter enforcing the community Ruby Style Guide. |
| **[Checkstyle](https://github.com/checkstyle/checkstyle)** | [![GitHub stars](https://img.shields.io/github/stars/checkstyle/checkstyle?style=social&color=white)](https://github.com/checkstyle/checkstyle/stargazers) | Java Style Linter | Development tool to help programmers write Java code that adheres to standard coding style rules. |
| **[CodeQL Queries](https://github.com/github/codeql)** | [![GitHub stars](https://img.shields.io/github/stars/github/codeql?style=social&color=white)](https://github.com/github/codeql/stargazers) | Semantic Analysis Engine | Query language and engine for searching code as database structures for semantic vulnerabilities. |
| **[Error Prone](https://github.com/google/error-prone)** | [![GitHub stars](https://img.shields.io/github/stars/google/error-prone?style=social&color=white)](https://github.com/google/error-prone/stargazers) | Java Compiler Analyzer | Google's Java static analysis tool catching common compile-time errors at build time. |
| **[OWASP Dependency-Check](https://github.com/jeremylong/DependencyCheck)** | [![GitHub stars](https://img.shields.io/github/stars/jeremylong/DependencyCheck?style=social&color=white)](https://github.com/jeremylong/DependencyCheck/stargazers) | Software Composition Analysis | Open-source SCA tool identifying publicly disclosed vulnerabilities in project dependencies. |
| **[Detekt](https://github.com/detekt/detekt)** | [![GitHub stars](https://img.shields.io/github/stars/detekt/detekt?style=social&color=white)](https://github.com/detekt/detekt/stargazers) | Kotlin Linter | Static code analysis tool for Kotlin enforcing complexity metrics and rule sets. |
| **[Bandit](https://github.com/PyCQA/bandit)** | [![GitHub stars](https://img.shields.io/github/stars/PyCQA/bandit?style=social&color=white)](https://github.com/PyCQA/bandit/stargazers) | Python SAST | Security oriented static analyzer built to find common security issues in Python code. |
| **[Pylint](https://github.com/pylint-dev/pylint)** | [![GitHub stars](https://img.shields.io/github/stars/pylint-dev/pylint?style=social&color=white)](https://github.com/pylint-dev/pylint/stargazers) | Python Linter | Comprehensive static code analysis for Python inspecting errors and refactoring recommendations. |
| **[PMD](https://github.com/pmd/pmd)** | [![GitHub stars](https://img.shields.io/github/stars/pmd/pmd?style=social&color=white)](https://github.com/pmd/pmd/stargazers) | JVM/Multi-Language Analyzer | Extensible cross-language static code analyzer catching unused variables, empty blocks, and flaws. |
| **[SpotBugs](https://github.com/spotbugs/spotbugs)** | [![GitHub stars](https://img.shields.io/github/stars/spotbugs/spotbugs?style=social&color=white)](https://github.com/spotbugs/spotbugs/stargazers) | Java Bytecode Analyzer | Successor of FindBugs for static analysis inspecting Java bytecode for bug patterns. |
| **[Flake8](https://github.com/PyCQA/flake8)** | [![GitHub stars](https://img.shields.io/github/stars/PyCQA/flake8?style=social&color=white)](https://github.com/PyCQA/flake8/stargazers) | Python Linter Wrapper | Modular python tool wrapper uniting PyFlakes, pycodestyle, and Ned Batchelder's Naming plugin. |

---

## 🛠️ Key Features Comparison & Selection Criteria

When building an automated code quality pipeline:
1. **Developer Experience (Shift-Left)**: Local editor linters (Ruff, ESLint, Biome) yield immediate feedback (<1 second).
2. **Pull Request Quality Gates**: Tools like SonarCloud, Semgrep, or Codacy enforce non-negotiable coverage thresholds and zero high-severity bugs before merging.
3. **Deep Application Security Testing (SAST)**: GitHub CodeQL, Coverity, or Veracode run comprehensive interprocedural analysis to catch complex memory or injection flaws.

---

## 🤝 How to Contribute

1. Fork this repository.
2. Update or add relevant tools in `README.md` maintaining table formatting.
3. Ensure accurate pricing, free tier specs, and official stargazer links.
4. Submit a Pull Request.

---

## 📜 Disclaimer

*This curated repository is for informational and educational purposes. Product pricing, valuations, and free tier limits are subject to change by respective vendors.*
