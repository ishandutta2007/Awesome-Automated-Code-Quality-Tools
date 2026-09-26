# Awesome-Automated-Code-Quality-Tools

## Top Automated Code Quality Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Static Analysis, SAST, Code Smells, Quality Gates, Technical Debt & Secure Coding Automation*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Code Quality Tools**. These systems scan source code for bugs, vulnerabilities, smells, and style issues—enforcing quality gates in CI before merge.



**Examples** include SonarQube, Codacy, DeepSource, Snyk Code, GitHub Advanced Security (CodeQL), Code Climate, JetBrains Qodana, Semgrep, Veracode, Checkmarx One, and Coverity (the category leaders).



**Open-source emphasis**: Code quality has excellent open tools. **SonarQube Community**, **Semgrep**, **CodeQL** (public repos), **ESLint**, and language linters form a complete stack. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[SonarQube / SonarCloud](https://www.sonarsource.com/)**  

  Industry-standard code quality and security platform—quality gates, maintainability ratings, and SAST across many languages.



- **[GitHub Advanced Security (CodeQL), Snyk Code](https://github.com/security/advanced-security)**  

  Deep semantic analysis and developer-first SAST integrated into GitHub and multi-repo workflows.



- **[Semgrep Code / Semgrep App, Codacy, DeepSource, Code Climate, Qodana](https://semgrep.dev/)**  

  Modern code quality and SAST products with strong PR feedback, custom rules, and IDE integration.



- **[Checkmarx One, Veracode, Coverity (Synopsys)](https://checkmarx.com/)**  

  Enterprise application security testing platforms with deep SAST and compliance reporting.



- **[Other commercial code quality platforms](https://www.sonarsource.com/)**  

  Additional SCA/SAST and quality-management suites.



## Open-Source GitHub Projects



- **[SonarQube Community Edition](https://github.com/SonarSource/sonarqube)**  

  Open-source core of SonarQube—bugs, smells, coverage, and basic security rules with quality gates; self-hosted.



- **[Semgrep](https://github.com/semgrep/semgrep)**  

  Leading open-source SAST engine—fast pattern-based rules that look like source code; highly customizable and CI-friendly.



- **[CodeQL](https://github.com/github/codeql)**  

  Semantic code analysis engine from GitHub—query code as data; free for public repositories (Advanced Security for private).



- **[ESLint, Pylint, RuboCop, Checkstyle & language linters](https://github.com/eslint/eslint)**  

  Essential open linters for style, correctness, and light security—per-language foundations of code quality.



- **[PMD, SpotBugs, FindBugs successors](https://github.com/pmd/pmd)**  

  Open static analyzers for Java and other JVM languages detecting common defect patterns.



- **[Infer (Meta), Error Prone](https://github.com/facebook/infer)**  

  Open static analysis tools for nullability, concurrency, and API misuse at scale.



- **[OWASP Dependency-Check & SCA open tools](https://github.com/jeremylong/DependencyCheck)**  

  Open software composition analysis for known vulnerable dependencies (pairs with SAST).



- **[SonarScanner & CI quality plugins](https://github.com/SonarSource)**  

  Open scanners and build-tool integrations that feed SonarQube and similar engines.



### Additional Strong Open-Source Options



- **Quality + security gate**: SonarQube Community.

- **Fast custom SAST**: Semgrep OSS.

- **Deep semantic (public)**: CodeQL on GitHub public repos.

- **Editor/CI baseline**: ESLint and language-native linters.

- **Composable stacks**: Linters → Semgrep → SonarQube → optional commercial SAST for regulated apps.

- Commercial platforms still lead in rule depth, support, and enterprise reporting.



**Frameworks for building custom systems**:  

**Semgrep** + **SonarQube Community** + **language linters** cover most automated quality needs.  

**CodeQL** for deep queries on public code.  

Commercial tools (SonarCloud, Snyk, Checkmarx, Veracode, Codacy, etc.) add managed scale and premium rules.  

Most teams should run open analyzers in every PR; add commercial SAST where compliance demands it. Fully open quality gates are production-standard for many engineering orgs.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Static analysis reduces but does not eliminate defects or vulnerabilities. Tune rules to control noise, and combine with tests, review, and runtime defenses. False negatives remain possible.

- Open-source tools offer transparency and control but require rule maintenance and infrastructure. Commercial platforms shift product depth and support to the vendor. Neither replaces secure development training and threat modeling.



---



**Made for platform engineers, security champions, and teams shipping cleaner, safer code.**  

Let's expand open automated code quality while recognizing the enterprise rule packs and support that leading commercial platforms deliver.
