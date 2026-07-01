# Bruno Fulia - QA Engineer

## ISTQB Certified | Web · Mobile · API · AI Platform Validation

QA Engineer focused on validating complex software ecosystems across Web, Mobile, APIs, and AI-powered platforms.

With a background combining Web Development and Business Law, I approach Quality Assurance from two perspectives: software reliability and risk-based analysis. I design automation frameworks, quality gates, and testing strategies that help teams detect functional, security, and compliance risks before production.

My focus is building practical QA solutions that connect engineering practices with real-world product requirements, including accessibility, API reliability, security validation, and AI system behavior.

---

## 📑 Table of Contents

- [Technical Ecosystem](#-technical-ecosystem)
- [Featured Quality & Automation Frameworks](#-featured-quality--automation-frameworks)
  - [1. Web Compliance & Accessibility QA Framework](#-1-web-compliance--accessibility-qa-framework)
  - [2. API & Data Privacy Contract Testing Framework](#-2-api--data-privacy-contract-testing-framework)
  - [3. AI Trust & Safety / LLM Validation Framework](#-3-ai-trust--safety--llm-validation-framework)
- [Professional Connection](#-professional-connection)
  
---

## 🛠️ Technical Ecosystem

| Domain | Core Technologies, Libraries & Environments |
| --- | --- |
| **Test Automation** | Playwright, Robot Framework, Selenium WebDriver, Cucumber (BDD) |
| **API & Backend Validation** | Postman, Insomnia, Bruno, Karate DSL, SQL |
| **Mobile Testing** | Appium, Android Debug Bridge (ADB), Scrcpy, Logcat |
| **Languages & Scripting** | TypeScript, Python, JavaScript, Java, PHP, HTML, CSS |
| **CI/CD & DevOps** | GitHub Actions, Docker, VirtualBox, Linux Shell |
| **Quality Management** | Jira, Xray, Confluence, Notion, ClickUp, Obsidian |

---

# 📂 Featured Quality & Automation Frameworks

My portfolio focuses on **controlled failure validation**: frameworks designed not only to verify expected behavior, but also to detect, capture, and report critical deviations through explicit quality gates.

Each project demonstrates how automated testing can transform failures into actionable engineering signals through logs, traces, screenshots, and diagnostic artifacts.

```mermaid
graph LR
    A[CI/CD Execution] --> B{Quality Gate Verification}
    B -->|Passed| C[Stable Release]
    B -->|Issue Detected| D[Controlled Failure State]
    D -->|Logs / Traces / Screenshots| E[Blocked Release]
````

---

## 📄 1. Web Compliance & Accessibility QA Framework

Automated regression framework focused on validating user interfaces, accessibility requirements, and browser-level behaviors.

**Stack**

TypeScript · Playwright · axe-core · Node.js

**Architecture**

- Page Object Model with reusable components.
- Custom fixtures for cleaner test execution.
- Separation between test logic, UI models, and validation layers.

**Technical Scope**

- WCAG 2.1 accessibility validation.
- Browser context and dialog handling.
- Regression coverage for complex web applications.

**Controlled Failure Validation**

- Executes invalid scenarios to confirm that quality gates detect regressions.
- Captures traces, screenshots, network activity, and DOM information.

🔗 Repository: [Link](https://github.com/brunofulia/Web_Compliance_And_Accessibility)

---

## 📦 2. API & Data Privacy Contract Testing Framework

Backend validation framework focused on API contracts, data exposure prevention, and authorization rules.

**Stack**

TypeScript · Playwright API · JSON Schema Validation

**Architecture**

- Modular API request layer.
- Contract-based assertions.
- Automated validation of expected backend behavior.

**Technical Scope**

- Response schema validation.
- Sensitive data exposure checks.
- RBAC authorization testing.
- Privacy-oriented API validation.

**Controlled Failure Validation**

- Simulates unauthorized access scenarios.
- Blocks execution when protected endpoints behave unexpectedly.

🔗 Repository: [Link](https://github.com/brunofulia/API_Data_Privacy_Contract_Testing)

---

## 🤖 3. AI Trust & Safety / LLM Validation Framework

Testing framework focused on evaluating AI behavior, prompt robustness, and safety boundaries.

**Stack**

Python · PyTest · Promptfoo · Garak · FastAPI

**Architecture**

- Provider-independent testing layer.
- JSON-based adversarial datasets.
- Automated AI behavior validation pipeline.

**Technical Scope**

- Prompt injection testing.
- Jailbreak scenario evaluation.
- Response safety checks.
- AI reliability testing.

**Controlled Failure Validation**

- Detects unsafe model outputs.
- Converts AI behavior deviations into visible test failures.

🔗 Repository: [Link](https://github.com/brunofulia/LLM_Quality_And_Security_Framework)

---

# 👥 Professional Connection

- Email: [brunofulia@gmail.com](mailto:brunofulia@gmail.com)
- LinkedIn: linkedin.com/in/bruno-fulia


