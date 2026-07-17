<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:0D0D0D,50:991B1B,100:DC2626&text=Nikhiel%20Lingard&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20Engineering%20%E2%80%A2%20Fintech%20Operations%20%E2%80%A2%20Suriname&descAlignY=60"/>

<br>

<a href="https://nikhcodes.github.io"><img src="https://img.shields.io/badge/portfolio-991B1B?style=for-the-badge&logo=firefox-browser&logoColor=white"/></a>
<a href="mailto:nikhiel.lingard.dev@gmail.com"><img src="https://img.shields.io/badge/email-B91C1C?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/nikhiel-lingard/"><img src="https://img.shields.io/badge/linkedin-1A1A1A?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/NikhCodes"><img src="https://img.shields.io/badge/github-1A1A1A?style=for-the-badge&logo=github&logoColor=white"/></a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=NikhCodes&style=for-the-badge&color=991B1B&label=profile+views"/>

</div>

<br>

## about

I run IT operations at a fintech bank in Suriname by day, and study software engineering at UNASAT the rest of the time. The two feed each other more than I expected — watching how a production banking environment actually breaks, gets monitored, and gets patched has shaped what I want to build more than any course has.

I started in full-stack because it let me ship things fast. I'm moving toward backend — Java, Spring Boot, PostgreSQL — because I got more interested in what happens when the request lands than in what the button looks like. Authentication flows, state machines, failure modes, the boring infrastructure between an app and the outside world: that's the part I keep coming back to.

I don't collect frameworks. I'd rather spend three months actually understanding Spring Security's filter chain than skim ten tutorials on ten different stacks.

<br>

## currently

```yaml
role:      IT Operator, fintech banking — production systems, incident response
studying:  BSc IT / Software Engineering, UNASAT
building:  Java, Spring Boot, PostgreSQL, Spring Security
reading:   OWASP Top 10, authentication design, caching strategies
next up:   Docker, Nginx, deployment infra
```

<br>

## stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,postgres,nodejs,react,docker,git,idea,vscode,python,fedora&perline=6&theme=dark" />

</div>

<br>

## projects

Each of these started because I wanted to actually understand one specific thing, not because I needed a portfolio filler.

<br>

### [RigSight](https://github.com/NikhCodes/rigsight)
**simulated industrial monitoring platform**

I wanted to know what a backend looks like when it's not just answering CRUD requests but reacting to continuous data — thresholds, state transitions, repeated alerts that need deduplicating instead of spamming. RigSight simulates a telemetry pipeline with scheduled jobs feeding into threshold evaluation and equipment state machines:

```
ACTIVE → WARNING → CRITICAL → RECOVERY
```

JWT-secured, role-based access, Flyway-managed schema, Dockerized Postgres.

`Java 21` `Spring Boot` `Spring Security` `JWT` `Hibernate` `PostgreSQL` `Flyway` `Docker`

<br>

### AGAS
**Academic Group Accountability System**

Built for a university module, but I used it to go deeper on backend security than the assignment asked for: bcrypt hashing, a three-role authorization model, and an append-only audit log using JSONB metadata so nothing gets silently overwritten. UUID primary keys and soft deletes throughout — small decisions, but the kind that matter once real data is on the line.

`Node.js` `Express` `PostgreSQL` `JWT` `bcrypt` `Helmet` `Joi`

<br>

### [NikhOS](https://github.com/NikhCodes/NikhOS)
**student workspace, built as a PWA**

A grade and assignment tracker I actually use, built to feel native rather than like a website — installable, works offline, no loading spinners for basic navigation.

live → https://nikh-os-red.vercel.app

`React` `Vite` `Tailwind CSS` `Framer Motion`

<br>

### [Pose Cam](https://github.com/NikhCodes/face-tracker)
**real-time hand gesture detection**

No trained models — gesture classification purely from landmark geometry via MediaPipe. Wanted to understand computer vision as math and geometry before reaching for anything pretrained.

`Python` `MediaPipe` `OpenCV` `NumPy`

<br>

## github

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=NikhCodes&show_icons=true&theme=transparent&title_color=DC2626&text_color=ffffff&icon_color=DC2626&border_color=2D2D2D&hide_border=false&include_all_commits=true"/>
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NikhCodes&layout=compact&theme=transparent&title_color=DC2626&text_color=ffffff&border_color=2D2D2D"/>

<br><br>

<img src="https://streak-stats.demolab.com?user=NikhCodes&theme=dark&ring=DC2626&fire=DC2626&currStreakLabel=ffffff&border=2D2D2D"/>

</div>

<br>

## contributions

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/NikhCodes/NikhCodes/blob/output/github-contribution-grid-snake-dark.svg">
  <img alt="github contribution graph" src="https://github.com/NikhCodes/NikhCodes/blob/output/github-contribution-grid-snake.svg">
</picture>

</div>

<br><br>

<div align="center">

<sub>trying to understand systems before optimizing them</sub>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0D0D0D,50:991B1B,100:DC2626"/>

</div>
