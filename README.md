<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0e75b6,100:0d1117&height=200&section=header&text=Marcus%20Pereira&fontSize=50&animation=fadeIn&fontAlignY=36&desc=Senior%20SDET%20%E2%80%A2%20Quality%20Engineering&descSize=20&descAlignY=56" alt="Header" />
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1000&color=0E75B6&center=true&vCenter=true&width=680&lines=Senior+Software+Development+Engineer+in+Test;Test+Automation+Architecture+%E2%80%A2+UI+%2F+API+%2F+Performance;Playwright+%2B+TypeScript+%E2%80%A2+CI%2FCD+Quality+Gates;Shift-Left+%E2%80%A2+Risk-Based+Testing+%E2%80%A2+Zero+Flakiness;I+build+the+software+I+test" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <a href="mailto:marcuspgk@gmail.com">
    <img src="https://img.shields.io/badge/Email-05122A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/Florian%C3%B3polis%2C%20Brazil-05122A?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Open_to_Senior_SDET_roles-0e75b6?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Open to work" />
  <img src="https://komarev.com/ghpvc/?username=marpe11&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile Views" />
</div>

---

### 🎯 The short version

Senior SDET who treats quality as an **engineering discipline**, not a phase. I design test strategies and build the automation architecture behind them — from risk-based coverage plans to CI quality gates that actually block bad releases. And because I also **ship production software** (Electron, React, Rust), I read code like a developer and break it like a tester.

**What you get when you hire me:**

- 🏗️ **Automation architecture** — Page Object Model, reusable fixtures, data-driven suites that stay maintainable as the product grows
- ⚙️ **CI/CD quality gates** — fast, deterministic smoke suites on every PR; heavy regression on schedule; zero tolerance for flaky tests
- 🔍 **Risk-based strategy** — coverage driven by business impact and production risk, not vanity percentages
- 📋 **Full traceability** — every automated test maps 1:1 to a documented test case; every bug report carries severity, repro and root-cause analysis
- 📊 **Stakeholder-ready reporting** — unified Allure reports, test plans and risk matrices that non-QAs actually read

---

### 🧪 Featured Quality Engineering work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎰 e2e-gamesmart — E2E on a real-money betting platform</h3>
      <p><b>Playwright + TypeScript + POM</b> · staging &amp; production</p>
      <p>Automated E2E for a B2C betting platform where a false positive means real money lost — and a false negative means a compliance incident.</p>
      <ul>
        <li>Smoke suite with spec IDs (<code>SMK-0xx</code>) mapped <b>1:1 to the test-case matrix</b> — full audit trail</li>
        <li>Financial flows validated <b>without executing real transactions</b>: modals, limits and field validation asserted, money never moves</li>
        <li><b>10 KYC-verified staging accounts</b> orchestrated 1-per-worker to survive single-session constraints in parallel runs</li>
        <li>Credentials exclusively in <code>.env</code> / CI secrets — zero secrets in code, by design</li>
      </ul>
      <a href="https://github.com/marpe11/e2e-gamesmart">
        <img src="https://img.shields.io/badge/View_repository-0e75b6?style=for-the-badge&logo=github&logoColor=white" alt="e2e-gamesmart" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>🎯 BeTalentTest — Full-stack QA challenge</h3>
      <p><b>Playwright · Newman · k6 · Allure · axe-core</b></p>
      <p>All three SDET fronts in one repository — UI, API and performance — with the documentation layer most candidates skip.</p>
      <ul>
        <li><b>UI:</b> Playwright + TS, reusable auth fixtures, accessibility checks with axe-core</li>
        <li><b>API:</b> Postman collections automated via Newman; <b>load testing</b> with k6</li>
        <li><b>Unified Allure reports</b> merging UI + API evidence in a single artifact</li>
        <li>Delivered with <b>test plan, 40+ documented test cases, bug analysis by severity, risk matrix</b> and improvement proposals</li>
      </ul>
      <a href="https://github.com/marpe11/BeTalentTest">
        <img src="https://img.shields.io/badge/View_repository-0e75b6?style=for-the-badge&logo=github&logoColor=white" alt="BeTalentTest" />
      </a>
    </td>
  </tr>
</table>

---

### 🧠 How I think about quality

| Principle | What it looks like in practice |
|---|---|
| **Shift-left** | Quality enters at refinement and design — not at the end of the sprint. |
| **Risk-based testing** | Coverage prioritized by business impact and production risk, not coverage-for-coverage's-sake. |
| **Traceability** | Every automated test carries the ID of the documented case it implements. |
| **Signal over noise** | Fast, stable smoke suites on PRs; heavy regression on schedule. Flaky tests get fixed or deleted — never re-run until green. |
| **Measurable quality** | Test plans, severity-ranked bug analysis and risk matrices as standard deliverables. |

---

### 💻 I also ship software

A SDET who has never built a product tests blind. I don't.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📋 Marpic</h3>
      <p>Open-source desktop app (Windows / macOS / Linux): clipboard manager + screenshot toolkit, local-first on SQLite. <b>Electron + React + TypeScript.</b></p>
      <a href="https://github.com/marpe11/marpic">
        <img src="https://img.shields.io/badge/View_repository-0e75b6?style=for-the-badge&logo=github&logoColor=white" alt="Marpic" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ zapzap</h3>
      <p>Native WhatsApp desktop client written in <b>Rust</b> — because a good SDET isn't afraid of a systems language.</p>
      <a href="https://github.com/marpe11/zapzap">
        <img src="https://img.shields.io/badge/View_repository-0e75b6?style=for-the-badge&logo=github&logoColor=white" alt="zapzap" />
      </a>
    </td>
  </tr>
</table>

---

### 🛠️ Toolbox

**Test Automation & Quality Engineering:**
<div align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=playwright,cypress,selenium,postman" alt="Test Stack" />
  </a>
  <br/><br/>
  <img src="https://img.shields.io/badge/Newman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Newman" />
  <img src="https://img.shields.io/badge/k6_Load_Testing-7D64FF?style=for-the-badge&logo=k6&logoColor=white" alt="k6" />
  <img src="https://img.shields.io/badge/Allure_Report-FF4A4A?style=for-the-badge&logo=allure&logoColor=white" alt="Allure" />
  <img src="https://img.shields.io/badge/axe--core_A11y-007ACC?style=for-the-badge&logo=accessibility&logoColor=white" alt="axe-core" />
</div>

**Languages & Engineering:**
<div align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,python,java,rust,nodejs,react,electron,docker,git,github,githubactions" alt="Engineering Stack" />
  </a>
</div>

---

### 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=marpe11&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=marpe11&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0d1117" width="48%" alt="Top Langs" />
</div>

<br/>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=marpe11&theme=tokyonight&hide_border=true&background=0d1117" width="100%" alt="GitHub Streak" />
</div>

---

<div align="center">
  <i>"Quality is not an act, it is a habit" — in my case, a pipeline.</i>
  <br/><br/>
  📬 <b>marcuspgk@gmail.com</b> — open to Senior SDET / QA Lead roles and quality engineering consulting.
</div>
