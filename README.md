<h1 align="left">Mohamed Zakir Hussain</h1>

<p align="left">
  <strong>AI Quality Engineering &amp; Test Automation Lead</strong><br>
  Senior QA Engineer · Software Engineer 2 at IQVIA
</p>

<p align="left">
  <a href="https://iamzakirzr.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/portfolio-iamzakirzr.github.io-35D399?style=flat-square&logo=githubpages&logoColor=0D131B"></a>
  <a href="https://linkedin.com/in/zakirz"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-zakirz-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:zakir9622@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-zakir9622%40gmail.com-94A2B4?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

---

8.5 years of test automation across healthcare and life sciences platforms at **IQVIA**,
**Mindtree** and **Indium Software**. I build the frameworks that let teams trust their
regression suites — and, increasingly, the evaluation harnesses that decide whether an
LLM-driven feature is fit to ship.

- 🧪 **Now** — quality engineering for LLM, RAG and agentic AI systems: faithfulness,
  context precision, hallucination rate, tool-calling accuracy, prompt-injection probing
- 🏗️ **Frameworks** — Playwright, Selenium, Cypress, AccelQ and Squish suites in Python
  and C#, wired into Azure DevOps so regression runs daily instead of pre-release
- 📉 **Impact** — cut regression execution time 75%, shortened the release feedback loop
  40%, lifted automation coverage 25%
- 👥 **Team** — lead five QA engineers across Scrum, Kanban and Waterfall delivery

### Tools of the trade

![Python](https://img.shields.io/badge/Python-18222F?style=flat-square&logo=python&logoColor=35D399)
![C#](https://img.shields.io/badge/C%23-18222F?style=flat-square&logo=dotnet&logoColor=35D399)
![Playwright](https://img.shields.io/badge/Playwright-18222F?style=flat-square&logo=playwright&logoColor=35D399)
![Selenium](https://img.shields.io/badge/Selenium-18222F?style=flat-square&logo=selenium&logoColor=35D399)
![Cypress](https://img.shields.io/badge/Cypress-18222F?style=flat-square&logo=cypress&logoColor=35D399)
![PyTest](https://img.shields.io/badge/PyTest-18222F?style=flat-square&logo=pytest&logoColor=35D399)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-18222F?style=flat-square&logo=azuredevops&logoColor=35D399)
![Jenkins](https://img.shields.io/badge/Jenkins-18222F?style=flat-square&logo=jenkins&logoColor=35D399)
![Docker](https://img.shields.io/badge/Docker-18222F?style=flat-square&logo=docker&logoColor=35D399)
![JMeter](https://img.shields.io/badge/JMeter-18222F?style=flat-square&logo=apache&logoColor=35D399)
![RAGAS](https://img.shields.io/badge/RAGAS-18222F?style=flat-square&logoColor=A78BFA)
![DeepEval](https://img.shields.io/badge/DeepEval-18222F?style=flat-square&logoColor=A78BFA)
![LangSmith](https://img.shields.io/badge/LangSmith-18222F?style=flat-square&logo=langchain&logoColor=A78BFA)

---

## About this repository

This is the source of **[iamzakirzr.github.io](https://iamzakirzr.github.io/)** — a
single page of hand-written HTML with an inline stylesheet. No framework, no npm, no
build step, no Jekyll. Open `index.html` in a browser and that is the whole thing.

```
index.html            the page (content + styles + JSON-LD)
assets/og-image.png   1200x630 link preview card for LinkedIn / X / Slack
assets/favicon.svg
robots.txt            allows everything, points at the sitemap
sitemap.xml
.nojekyll             tells GitHub Pages to serve the files as-is
```

### Publishing

Because the repository is named `iamzakirzr.github.io`, GitHub Pages serves it at the
domain root. Enable it once under **Settings → Pages → Source: Deploy from a branch →
`main` / `/ (root)`**; every push to `main` republishes.

### Editing

Everything lives in `index.html`, in document order: `<head>` metadata, then one
`<style>` block, then the sections (`#about`, `#impact`, `#ai`, `#experience`, `#work`,
`#recognition`, `#contact`). Colours are CSS custom properties on `:root`. The JSON-LD
`Person` block at the bottom mirrors the visible content — update both when the résumé
changes.

The page deliberately omits a phone number and a downloadable résumé PDF, since it is
public and crawlable; the contact section uses a `mailto:` with a "Request résumé"
subject instead.

`assets/og-image.png` is a screenshot of a small HTML card rendered at exactly
1200×630. LinkedIn needs a raster image and caches aggressively, so validate any
replacement with LinkedIn's Post Inspector.
