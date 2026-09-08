<div align="center">

# Emanuela Telescu

### Senior QA Automation Engineer / SDET &nbsp;·&nbsp; AI augmented and agentic testing

<p>
<a href="https://ella79.github.io/portfolio/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-2EAD33?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
<a href="https://www.linkedin.com/in/emanuelatelescu"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"></a>
<a href="mailto:emanuela.telescu@yahoo.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=maildotru&logoColor=white"></a>
<img alt="Based in Timisoara, UTC+2" src="https://img.shields.io/badge/Timi%C8%99oara%2C%20RO-UTC%2B2-24292F?style=for-the-badge">
</p>

</div>

---

## About

Fifteen years in QA, six of them in automation, the last two building AI augmented and agentic
testing in production rather than in slide decks. At **BTC Embedded Systems** I own test automation
strategy for safety critical automotive and hardware in the loop products, where a test that lies
costs more than a test that never existed.

My working stack is **Playwright and TypeScript**, driven through **Claude Code** and **Playwright
MCP**. Agents plan, author and heal the cases; I write the agent definitions, the skills and the
pipeline that keep them honest, and nothing merges unreviewed. I moved my team off Copilot onto
Claude Code and rebuilt the way we author tests around it.

Open to senior remote roles, working with international teams.

## How I think about a suite

- A flaky test is a **defect in the suite**, not weather. It is never fixed by adding a retry, raising a timeout or loosening an assertion, because all three leave the case passing for the wrong reason.
- **Quality gates belong in the pipeline**, not in a reviewer's memory. If a job quietly stops running, the branch protection has to notice.
- Automate test **maintenance**, not only test execution. Authoring was always the cheap half.
- Twenty cases that can each be justified prove more than two hundred nobody can explain.

## Featured

### [agentic-playwright-suite](https://github.com/ella79/agentic-playwright-suite)

[![Top language](https://img.shields.io/github/languages/top/ella79/agentic-playwright-suite?style=flat-square&color=3178C6)](https://github.com/ella79/agentic-playwright-suite)
[![Last commit](https://img.shields.io/github/last-commit/ella79/agentic-playwright-suite?style=flat-square&color=2EAD33)](https://github.com/ella79/agentic-playwright-suite/commits/main)
[![License](https://img.shields.io/github/license/ella79/agentic-playwright-suite?style=flat-square)](https://github.com/ella79/agentic-playwright-suite/blob/main/LICENSE)

Twenty functional and twenty visual regression cases against a live public storefront, both caps
deliberate. Authored and healed by six Claude Code agents over two MCP servers, page objects
supplied as fixtures, and every run happening inside the same container image locally and in CI.
The functional cases also run on WebKit and on a phone viewport; visual baselines are Chromium on
Linux, generated in the image CI uses, so a diff means the page changed and not the machine.

| Published on every merge to `main` | |
| --- | --- |
| [Suite health](https://ella79.github.io/agentic-playwright-suite/metrics/) | Pass rate, flaky rate, p50 and p95, repeat offenders, against stated thresholds |
| [Test results](https://ella79.github.io/agentic-playwright-suite/) | Both suites, with trend history accumulating across runs |
| [Trace viewer](https://ella79.github.io/agentic-playwright-suite/playwright-report/) | Every step of every case, replayable |
| [Decisions](https://github.com/ella79/agentic-playwright-suite/blob/main/docs/decisions.md) | The calls a reviewer would question, and what broke while building it |

### [portfolio](https://github.com/ella79/portfolio)

[![Pages](https://img.shields.io/badge/live-ella79.github.io%2Fportfolio-2EAD33?style=flat-square)](https://ella79.github.io/portfolio/)
[![Last commit](https://img.shields.io/github/last-commit/ella79/portfolio?style=flat-square&color=2EAD33)](https://github.com/ella79/portfolio/commits/main)

A single page site, published from GitHub Pages, with its own Playwright smoke suite. A QA
engineer's landing page that nobody tests would be an odd thing to hand a hiring manager.

## Stack

**Daily**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Model Context Protocol](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Allure](https://img.shields.io/badge/Allure%20Report-FF6C37?style=flat-square)

**Also shipped with**

![Cypress](https://img.shields.io/badge/Cypress-69D3A7?style=flat-square&logo=cypress&logoColor=white)
![WebdriverIO](https://img.shields.io/badge/WebdriverIO-EA5906?style=flat-square&logo=webdriverio&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C# / SpecFlow](https://img.shields.io/badge/C%23%20%2F%20SpecFlow-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Appium](https://img.shields.io/badge/Appium-662D91?style=flat-square&logo=appium&logoColor=white)
![BrowserStack](https://img.shields.io/badge/BrowserStack-FF8000?style=flat-square)
![Mountebank](https://img.shields.io/badge/Mountebank-2E4E6E?style=flat-square)

## Certified

Anthropic, in **Claude Code**, **Agent Skills**, **Subagents** and the **Model Context Protocol**,
which are the four pieces the suite above is actually built on.

---

<div align="center">

**Looking for a QA engineer who owns the test strategy rather than the ticket queue?**

[Portfolio](https://ella79.github.io/portfolio/) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/emanuelatelescu) &nbsp;·&nbsp; [Email](mailto:emanuela.telescu@yahoo.com)

<sub>The links on this page are checked by a scheduled workflow in this repository. A profile with a dead link is a failing test.</sub>

</div>
