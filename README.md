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

This is the source of **[iamzakirzr.github.io](https://iamzakirzr.github.io/)** — hand-written
HTML with an inline stylesheet. No framework, no npm, no build step, no Jekyll. Open
`index.html` in a browser and that is the whole thing.

```
index.html                       the page (content + styles + ~25 lines of scroll-spy JS)
case-studies/llm-eval.html       draft — noindex, not linked from the portfolio
case-studies/surgimap.html       draft — noindex, not linked
case-studies/ci-regression.html  draft — noindex, not linked
assets/og-image.png              1200x630 link preview card for LinkedIn / X / Slack
assets/favicon.svg
robots.txt                       allows everything, points at the sitemap
sitemap.xml                      the homepage only; case studies excluded while unpublished
.nojekyll                        tells GitHub Pages to serve the files as-is
```

### Layout

Two columns above 1024px: a sticky left column (name, title, availability, nav, socials)
beside a scrolling right column. Below 1024px it collapses to one column and the nav
detaches into a fixed bottom bar. Scroll-spy marks the active nav link via
`IntersectionObserver`; with JavaScript off the links are still plain anchors.

### Pending — things only Zakir can supply

1. **Headshot.** Save it as `assets/photo.jpg` (square crop, 176px or larger, plain or
   blurred background) and uncomment the `<img class="photo">` line at the top of
   `<aside class="side">` in `index.html`.
2. **Metric baselines.** The impact grid shows bare percentages. A before→after pair is a
   much stronger claim. Each tile carries a `TODO(zakir)` comment with the markup:
   `<div class="metric-value"><span class="from">4h</span> <span class="arrow">→</span> 1h</div>`
3. **Case-study detail.** Each draft has amber `[Needs Zakir: …]` blocks marking the
   judgement calls — why those test cases, what was traded off, what the outcome was, what
   you'd change. Those are the parts that make it a case study rather than a project blurb.
4. **The illustrative eval scores.** The hero terminal is labelled as a sample because the
   numbers in it are not measured. Real numbers from the IQVIA chatbot work would be
   stronger than any label — swap them in if they're shareable.

### Publishing the case studies

Once the `[Needs Zakir: …]` blocks in a page are filled:

1. Delete that page's `<meta name="robots" content="noindex, nofollow">`.
2. In `index.html`, uncomment the `PUBLISH STEP: case studies` block and add a
   `case studies` link to the nav.
3. Add the page's URL to `sitemap.xml`.

### Editing

Everything lives in `index.html` in document order: `<head>` metadata, one `<style>` block,
the left column, then the right-column sections (`#about`, `#impact`, `#ai`, `#experience`,
`#work`, `#recognition`, `#contact`), then the scroll-spy script and JSON-LD. Colours are
CSS custom properties on `:root`. The case-study pages copy the same `<style>` block — a
palette change has to be applied to all four files.

The page deliberately omits a phone number, a location, and a downloadable résumé PDF,
since it is public and crawlable; the contact section uses a `mailto:` with a "Request
résumé" subject instead.

`assets/og-image.png` is a screenshot of a small HTML card rendered at exactly 1200×630.
LinkedIn needs a raster image and caches aggressively, so validate any replacement with
LinkedIn's Post Inspector.
