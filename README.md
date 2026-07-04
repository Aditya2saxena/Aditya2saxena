<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e293b,100:2563eb&height=220&section=header&text=Aditya%20Saxena&fontSize=48&fontColor=ffffff&fontAlignY=36&desc=Full%20Stack%20Developer%20%C2%B7%20Backend%20Enthusiast%20%C2%B7%20Java%20Developer&descAlignY=56&descSize=17&animation=fadeIn" />

<br/>

<a href="https://github.com/Aditya2saxena">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=1200&color=38BDF8&center=true&vCenter=true&width=680&lines=Building+REST+APIs+with+Node.js+%2B+Express;SQL+and+NoSQL+Data+Modeling;Java+%7C+Data+Structures+%26+Algorithms;Currently+Studying+System+Design" alt="Typing SVG" />
</a>

<br/><br/>

<a href="https://linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/Aditya2saxena"><img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-1E293B?style=for-the-badge&logo=gmail&logoColor=38BDF8" /></a>

</div>

<br/>

## About

I design and build REST APIs and full-stack web applications, working across both relational and document databases rather than defaulting to one. My projects follow MVC conventions with clear separation between routes, models, and views, and I favor parameterized queries and schema validation over shortcuts. I'm methodical about data modeling — choosing MySQL or MongoDB based on the shape of the problem, not habit. Right now I'm extending that foundation into authentication, containerization, and system design, so the things I build hold up past a local environment and into production.

<br/>

## Technical Expertise

<table>
<tr>
<td valign="top" width="50%">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=java,js,mysql,html,css" />

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express" />

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=react" /> &nbsp;
<img src="https://img.shields.io/badge/EJS-1E293B?style=for-the-badge&logo=javascript&logoColor=B4CA65" />

</td>
<td valign="top" width="50%">

**Databases**
<br/>
<img src="https://skillicons.dev/icons?i=mysql,mongodb" />

**Tools**
<br/>
<img src="https://skillicons.dev/icons?i=git,github,vscode,postman" />

**DevOps — In Progress**
<br/>
<img src="https://skillicons.dev/icons?i=docker,githubactions" />

**Learning**
<br/>
<img src="https://img.shields.io/badge/System%20Design-1E293B?style=for-the-badge&logo=architecture&logoColor=38BDF8" />
<img src="https://img.shields.io/badge/JWT%20Auth-1E293B?style=for-the-badge&logo=jsonwebtokens&logoColor=EFEFEF" />

</td>
</tr>
</table>

<br/>

## GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Aditya2saxena&show_icons=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=38BDF8&icon_color=38BDF8&text_color=C9D1D9&ring_color=38BDF8" />
<img height="165" src="https://streak-stats.demolab.com?user=Aditya2saxena&hide_border=true&background=0D1117&stroke=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" />

<br/>

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aditya2saxena&layout=compact&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&langs_count=8" />
<img height="165" src="https://github-profile-trophy.vercel.app/?username=Aditya2saxena&theme=darkhub&no-frame=true&no-bg=true&row=2&column=3&margin-w=8&margin-h=8" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aditya2saxena&theme=react-dark&hide_border=true&bg_color=0D1117&color=38BDF8&line=38BDF8&point=E2E8F0&area=true&area_color=1E293B" width="100%" />

<br/><br/>

<img src="https://raw.githubusercontent.com/Aditya2saxena/Aditya2saxena/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

> Snake animation renders once the [`platane/snk`](https://github.com/Platane/snk) Action is added to this profile repo at `.github/workflows/snake.yml` — it runs on a schedule and commits the SVG automatically.

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Aditya2saxena&color=38BDF8&style=flat-square&label=Profile+Views)

</div>

<br/>

## Featured Projects

### WanderLust

**Overview** — A full-stack travel listing platform in the spirit of Airbnb: users browse, create, and manage property listings end to end.

**Architecture** — MVC pattern with Express handling routing and controllers, Mongoose schemas defining the data layer, and EJS rendering server-side views. Clear separation between `/routes`, `/models`, and `/views`.

**Tech Stack** — Node.js · Express.js · MongoDB · Mongoose · EJS

**Engineering Challenges** — Modeling one-to-many relationships (listings → reviews) in a document database without the join guarantees SQL gives you; enforcing validation server-side since MVC apps can't rely on the client alone.

**Key Features** — Full CRUD on listings · schema-level validation · RESTful route structure

**Future Improvements** — Cloudinary image upload, location-based search/filter, pagination on the listing index, rate limiting on write routes, an automated test suite

**Repository:** [`github.com/Aditya2saxena/WanderLust`](https://github.com/Aditya2saxena/WanderLust) · **Demo:** _add live deployment link_

---

### MySQL REST API
*(rename target for `Express-MySQL-CRUD`)*

**Overview** — A backend service exposing CRUD operations over a MySQL database, deliberately built as the relational counterpart to WanderLust's document-based approach.

**Architecture** — Express route handlers calling a MySQL connection layer directly, with parameterized queries replacing string concatenation to prevent injection.

**Tech Stack** — Node.js · Express.js · MySQL

**Engineering Challenges** — Managing connection lifecycle safely under concurrent requests (pooling vs. single connection); designing a normalized schema instead of a flat table.

**Key Features** — Full CRUD via REST endpoints · parameterized SQL queries · Postman collection for manual endpoint verification

**Future Improvements** — Connection pooling, a committed `schema.sql` for reviewable DB structure, centralized error-handling middleware, a `Dockerfile` + `docker-compose.yml` pairing the app with MySQL, a basic CI workflow running tests on push

**Repository:** [`github.com/Aditya2saxena/Express-MySQL-CRUD`](https://github.com/Aditya2saxena/Express-MySQL-CRUD) · **Demo:** _not yet deployed_

---

### Quora Posts CRUD

**Overview** — A Quora-style question and answer application demonstrating CRUD operations over a content/reply data model.

**Tech Stack** — Node.js · Express.js · MongoDB · EJS

**Key Features** — Full CRUD with RESTful routing · clean separation of routes, models, and views

**Future Improvements** — Nested comments/replies, upvotes, and user authentication would meaningfully differentiate this from WanderLust rather than repeating the same CRUD pattern

**Repository:** [`github.com/Aditya2saxena/Quora-Posts-CRUD`](https://github.com/Aditya2saxena/Quora-Posts-CRUD)

---

### Portfolio

**Overview** — Personal site presenting background, skills, and project case studies with a minimal, typography-first layout.

**Architecture** — Static HTML/CSS/JS, structured around clearly separated sections rather than a single long page.

**Tech Stack** — HTML5 · CSS3 · JavaScript

**Key Features** — Fully responsive layout · lightweight, dependency-free build

**Future Improvements** — Real project case studies (not just links), downloadable resume, Lighthouse performance pass, working contact form

**Repository:** [`github.com/Aditya2saxena/Portfolio`](https://github.com/Aditya2saxena/Portfolio) · **Demo:** _add live site link_

<br/>

## Coding Profiles

<div align="center">

<a href="#"><img src="https://img.shields.io/badge/LeetCode-1E293B?style=for-the-badge&logo=leetcode&logoColor=FFA116" /></a>
<a href="#"><img src="https://img.shields.io/badge/GeeksforGeeks-1E293B?style=for-the-badge&logo=geeksforgeeks&logoColor=2F8D46" /></a>
<a href="#"><img src="https://img.shields.io/badge/HackerRank-1E293B?style=for-the-badge&logo=hackerrank&logoColor=00EA64" /></a>

</div>

<br/>

## Engineering Philosophy

I'd rather ship something small that's correctly validated, properly error-handled, and easy to read than something large that only works on the happy path. I choose the database that fits the data's shape instead of defaulting to one tool everywhere, and I treat a project as unfinished until it's deployed — code that only runs on `localhost` hasn't proven anything yet.

<br/>

## Learning Roadmap

| Stage | Focus | Status |
|---|---|---|
| 1 | REST API design & CRUD fundamentals | Complete |
| 2 | Relational + document database modeling | Complete |
| 3 | Authentication & Authorization (JWT) | In Progress |
| 4 | System Design fundamentals | In Progress |
| 5 | Docker & containerized development | Planned |
| 6 | CI/CD & production deployment workflows | Planned |

<br/>

## Current Focus

- Authentication and authorization patterns, including JWT
- System design fundamentals — scalability and reliability tradeoffs
- Docker for containerized, reproducible environments
- Taking existing CRUD projects from local builds to real deployments

<br/>

## Quote

<div align="center">

> *"Write code that is easy to read, easy to maintain, and easy to scale."*

</div>

<br/>

## Contact

<div align="center">

<a href="https://linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/Aditya2saxena"><img src="https://img.shields.io/badge/GitHub-Follow-171515?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-Reach%20Out-1E293B?style=for-the-badge&logo=gmail&logoColor=38BDF8" /></a>

</div>

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e293b,100:2563eb&height=120&section=footer" />

<div align="center">

© 2026 Aditya Saxena — Built with precision and intent.

</div>
