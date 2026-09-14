<h1 align="left">Mohamed Zakir Hussain</h1>

<p align="left">
  <strong>Senior SDET · AI Quality Engineering</strong><br>
  Senior QA Engineer · Software Engineer 2 at IQVIA
</p>

<p align="left">
  <a href="https://iamzakirzr.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/portfolio-iamzakirzr.github.io-35D399?style=flat-square&logo=githubpages&logoColor=0D131B"></a>
  <a href="https://linkedin.com/in/zakirz"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-zakirz-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:zakir9622@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-zakir9622%40gmail.com-94A2B4?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

---

Test automation across healthcare and life sciences at IQVIA, Mindtree and Indium
Software since 2018. I build the frameworks teams rely on to trust their regression
suites, and lately the evaluation harnesses that decide whether an LLM feature is fit
to ship.

- 🏗️ **Frameworks** · Playwright, Selenium, Cypress, AccelQ and Squish in Python and C#,
  Page Object Model as the framework design, UI, API, Kafka events and SQL in one run
- ⚙️ **Pipelines** · Azure DevOps nightly regression, GitHub Actions on pull requests,
  Jenkins across a 20-machine grid, suites running against Kubernetes environments
- 🧪 **AI quality** · LLM, RAG and agentic systems: faithfulness, context precision,
  hallucination rate, tool-calling accuracy, prompt-injection probing
- 📉 **Impact** · regression execution time down 75%, release feedback loop 40% faster,
  automation coverage up 25%
- 👥 **Team** · five QA engineers, across Scrum, Kanban and Waterfall

### Tools of the trade

![Python](https://img.shields.io/badge/Python-18222F?style=flat-square&logo=python&logoColor=35D399)
![C#](https://img.shields.io/badge/C%23-18222F?style=flat-square&logo=dotnet&logoColor=35D399)
![Playwright](https://img.shields.io/badge/Playwright-18222F?style=flat-square&logo=playwright&logoColor=35D399)
![Selenium](https://img.shields.io/badge/Selenium-18222F?style=flat-square&logo=selenium&logoColor=35D399)
![Cypress](https://img.shields.io/badge/Cypress-18222F?style=flat-square&logo=cypress&logoColor=35D399)
![PyTest](https://img.shields.io/badge/PyTest-18222F?style=flat-square&logo=pytest&logoColor=35D399)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-18222F?style=flat-square&logo=azuredevops&logoColor=35D399)
![Jenkins](https://img.shields.io/badge/Jenkins-18222F?style=flat-square&logo=jenkins&logoColor=35D399)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-18222F?style=flat-square&logo=githubactions&logoColor=35D399)
![Kubernetes](https://img.shields.io/badge/Kubernetes-18222F?style=flat-square&logo=kubernetes&logoColor=35D399)
![Kafka](https://img.shields.io/badge/Kafka-18222F?style=flat-square&logo=apachekafka&logoColor=35D399)
![Appium](https://img.shields.io/badge/Appium-18222F?style=flat-square&logo=appium&logoColor=35D399)
![Docker](https://img.shields.io/badge/Docker-18222F?style=flat-square&logo=docker&logoColor=35D399)
![JMeter](https://img.shields.io/badge/JMeter-18222F?style=flat-square&logo=apache&logoColor=35D399)
![RAGAS](https://img.shields.io/badge/RAGAS-18222F?style=flat-square&logoColor=A78BFA)
![DeepEval](https://img.shields.io/badge/DeepEval-18222F?style=flat-square&logoColor=A78BFA)
![LangSmith](https://img.shields.io/badge/LangSmith-18222F?style=flat-square&logo=langchain&logoColor=A78BFA)

---

## This repo

Source for [iamzakirzr.github.io](https://iamzakirzr.github.io/). Plain HTML and CSS in a
single file, no framework and no build step. Clone it and open `index.html`.

```
index.html      page, styles, and a small scroll-spy script
assets/         photo, link-preview card, favicon
robots.txt
sitemap.xml
.nojekyll
```

### Notes to self

Two columns above 1024px, sticky left column beside the scrolling content. Under that it
stacks and the nav moves to a fixed bar at the bottom. Colours are CSS variables on
`:root`, so a palette change is one block.

Sections in `index.html` run in the order they appear on the page: `#about`, `#impact`,
`#engineering`, `#ai`, `#experience`, `#recognition`, `#contact`. The JSON-LD at the bottom
repeats the same facts, so update both together.

Work is organised by company, not by product. Each project card sits inside the employer
block it belongs to, so nothing floats loose — IQVIA, Mindtree and Indium are employers,
the products underneath them are what I tested there. Every card carries at least two
bullets and its own stack; a card that is only a title is not worth the space. The
"selected work" chips at the top of that section are the shortcut straight to them, so
every chip has to point at a card that exists. Any number that goes on this page has to be
one I can back when someone asks how I measured it.

Page Object Model, BDD and iSAFE are framework *designs*, not tools. They live in prose and
in the Design row of the skill matrix — never chipped in a tag list beside Selenium.

The impact section has exactly one hero figure and everything else is a smaller stat tile,
so there is one number the eye lands on first. Meter tracks are a translucent step of the
fill's own colour rather than a flat grey, which keeps the state readable across the whole
bar. Stat values are set in Inter, not Space Grotesk — a display face on a number reads as
decoration.

The years-of-experience tile carries `data-since="2018-03-01"` and a short script works the
figure out at load. The text in the markup is the fallback for anyone without JavaScript, so
it reads `since Mar 2018` and stays true on its own — don't put a number there.

No phone number, no address, no CV to download. The page is public and gets crawled, so
contact runs through email.

The avatar is a square crop rendered as an 88px circle, so keep the face centred and export
at 352px or better. `assets/og-image.png` is the LinkedIn preview at 1200x630; LinkedIn
caches it hard, so run any replacement through Post Inspector before sharing the link
again.
