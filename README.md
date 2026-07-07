<h1 align="center">Daniel Fernandes</h1>

<p align="center">
  <b>Sr. Quality Engineering & AI Assurance @ OneOrigin</b><br>
  I build test automation that maintains itself — and knows when not to.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/daniel-fernandes-1808b51b1/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://daniel-fernandes-portfolio.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-222222?style=for-the-badge&logo=netlify&logoColor=00C7B7" alt="Portfolio"></a>
  <a href="mailto:fernandesdaniel.df9@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## About

I design production-grade E2E and API test frameworks, and I work on the layer most teams haven't built yet: **AI-assisted quality assurance**. That means self-healing locators, LLM-arbitrated failure diagnosis, and autonomy that is gated by confidence — automation that escalates to a human instead of guessing.

- 🔭 Currently building **Sentinel**, a self-healing test framework on top of Playwright
- 🧪 Deep in: Playwright, Cypress, TypeScript, API testing, CI/CD pipelines
- 🤖 Exploring: LLM providers (Anthropic, OpenAI, Gemini), agentic workflows, vision-based healing

## How I think about quality

- **Diagnose before healing.** A broken selector and a broken product look identical to a retry loop. They shouldn't.
- **A green build you can't trust is worse than a red one.** Self-healing must never mask a real regression.
- **Autonomy needs an escalation path.** Below a confidence threshold, the right move is to ask a human — not to guess.

## Featured work

### 🛰️ [Sentinel — self-healing test framework](https://github.com/danieldf9/sentinel-test-framework)
Playwright tests pair a deterministic locator with a semantic *intent*. When a locator breaks, Sentinel diagnoses **why** (drift vs. regression vs. environment), heals drift through a tiered pipeline (cached descriptors → fuzzy fingerprints → LLM DOM → vision), and escalates instead of guessing when confidence is low. Fully audited in SQLite, sharded CI with locator-cache persistence, and a chaos harness proving ≥90% drift-heal with zero masked regressions.

`TypeScript` `Playwright` `LLM` `SQLite` `GitHub Actions`

### 🤝 [Francis Legacy — AI assistant platform](https://github.com/danieldf9/francislegacy)
AI-powered assistants for QA, health, and finance. Next.js + TypeScript + Firebase, PWA-ready.

`Next.js` `TypeScript` `Firebase` `Tailwind CSS`

### 🎭 [playwright-e2e-framework](https://github.com/danieldf9/playwright-e2e-framework) · 🌲 [cypress-e2e-framework](https://github.com/danieldf9/cypress-e2e-framework)
Production-grade E2E reference frameworks: Page Object Model, API testing, cross-browser support, CI/CD integration.

`TypeScript` `Playwright` `Cypress` `GitHub Actions`

## Tech stack

**Test automation**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-69D3A7?style=flat-square&logo=cypress&logoColor=black)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Languages & frameworks**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)

**AI / LLM**

![Anthropic](https://img.shields.io/badge/Anthropic_API-191919?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**CI/CD & tooling**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=danieldf9&show_icons=true&theme=default&hide_border=true&rank_icon=github" alt="GitHub stats" height="160">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=danieldf9&layout=compact&hide_border=true" alt="Top languages" height="160">
</p>

## Contact

📫 **fernandesdaniel.df9@gmail.com** · [LinkedIn](https://www.linkedin.com/in/daniel-fernandes-1808b51b1/) · [Portfolio](https://daniel-fernandes-portfolio.netlify.app/)
