### Moses Atia Poston

Full-stack developer in Portland, OR. I design and build the whole thing, front end, back end, and the boring pipes in between. Currently open to full-time or part-time roles.

There are 240-odd repos here. Most are client work and old practice projects. These are the ones worth your time.

#### What I've built

**[SwitchSign](https://github.com/switchcasestudio/switchsign-app)** is contract generation and e-signing: branded signing links, canvas signatures, signed PDFs with an audit trail, and an AI agent that drafts the contract. Python, FastAPI, SQLite and WeasyPrint, running in Docker on my own VPS. It has been in production since May 2026. The repo is a cleaned-up showcase copy, because the real one has real contracts in its history.

**[Directcut](https://github.com/switchcasestudio/directcut)** is a self-hosted AI video and image studio. Bring your own OpenRouter key and pick from 14 models: Seedance, Kling, Veo, Wan, Nano Banana, GPT Image, Flux and more. Reference uploads, a guided tour, 36 tests, and error messages written for people instead of pasted from the provider.

**Jelly Belly Wiki** started as "there should be an API for jelly bean flavors" and turned into a pipeline across three repos. A [Python scraper](https://github.com/switchcasestudio/Jelly-Belly-Wiki-API-Data-Collection) pulls flavors, recipes, facts and milestones with Selenium and BeautifulSoup. The cleaned JSON seeds MySQL through EF Core migrations. A [C# / ASP.NET Core API](https://github.com/switchcasestudio/Jelly-Belly-Wiki-API) serves 317 records over 10 documented endpoints with filtering, search and pagination, and a [React front end](https://github.com/switchcasestudio/Jelly_Belly_Wiki_Client) consumes that same public API. [Live docs here](https://jellybellywikiapi.onrender.com/). Give it a second to wake up, it's on a free tier and it sleeps.

**[Unhurried](https://github.com/switchcasestudio/unhurried)** is a WordPress block theme: 27 patterns, 3 style variations, no sideways scrolling anywhere from 320 to 1440 px wide.

The [studio site](https://github.com/switchcasestudio/switch-case-studio) is open too. React on Vite, statically pre-rendered to 36 routes, which is a fussy way to say it loads fast and Google can read it without running any JavaScript. Mobile Lighthouse went from 44 to 87 in the rebuild, 97 on desktop.

#### AI, minus the chatbot

Most of my work now is AI-adjacent, a phrase I use with some embarrassment because it has been beaten completely to death. In practice it means I self-host agents on my own VPS and wire them into things people actually use. SwitchSign's agent drafts contracts. An SMS agent I built for a marketing client handed 43 leads to sales in its first 9 days, against 19 in the whole month before.

#### Stack

JavaScript and TypeScript, React and Next.js, Node. C# and ASP.NET Core. Python and FastAPI when there's data to move. PHP and WordPress. Docker on Linux. Design too. I'm not handing that off to anyone.

[LinkedIn](https://www.linkedin.com/in/moses-a-p/) · [switchcasestudio.com](https://switchcasestudio.com) · hello@switchcasestudio.com
