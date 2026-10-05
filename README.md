### Moses Atia Poston

Portland, OR. I design and build the whole thing, front end, back end, and the boring pipes in between.

Most of what's in here is client work through [Switch Case Studio](https://switchcasestudio.com), mixed in with experiments I never got around to deleting. Fair warning, the ratio is not flattering.

The one I'd actually point at is Jelly Belly Wiki. It started as "there should be an API for jelly bean flavors" and turned into a four-stage pipeline across three repos. A [Python scraper](https://github.com/switchcasestudio/Jelly-Belly-Wiki-API-Data-Collection) pulls flavors, recipes, facts and milestones off the official site with Selenium and BeautifulSoup. The cleaned JSON seeds a MySQL database through EF Core migrations. A [C# / ASP.NET Core API](https://github.com/switchcasestudio/Jelly-Belly-Wiki-API) serves 317 records over 10 documented endpoints with filtering, search and pagination. Then a [React front end](https://github.com/switchcasestudio/Jelly_Belly_Wiki_Client) consumes that same public API, the identical one you could call right now. Three languages, three separately deployed services, nobody else on it.

Live docs are here if you want to poke at it: [jellybellywikiapi.onrender.com](https://jellybellywikiapi.onrender.com/). Give it a second to wake up, it's on a free tier and it sleeps.

The studio site itself is [open too](https://github.com/switchcasestudio/switch-case-studio). React on Vite, statically pre-rendered to 36 routes, which is a fussy way to say it loads fast and Google can read it without running any JavaScript.

Most of my work now is AI-adjacent, a phrase I use with some embarrassment because it has been beaten completely to death. In practice it means I self-host agents on my own VPS and wire them into things people actually use, rather than shipping another chatbot that answers questions nobody asked.

Stack, roughly: JavaScript and TypeScript, React, C# and ASP.NET, Python when there's data to move. Design too. I'm not handing that off to anyone.

Hiring the studio: [switchcasestudio.com](https://switchcasestudio.com) or hello@switchcasestudio.com
