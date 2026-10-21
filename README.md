<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Nikhiel Lingard: a red sunset over the water with palm silhouettes"/>

<br>

<a href="https://nikhcodes.github.io"><img src="https://img.shields.io/badge/portfolio-0a0405?style=for-the-badge&logo=firefoxbrowser&logoColor=fca5a5"/></a>
<a href="mailto:nikhiel.lingard.dev@gmail.com"><img src="https://img.shields.io/badge/email-0a0405?style=for-the-badge&logo=gmail&logoColor=fca5a5"/></a>
<a href="https://www.linkedin.com/in/nikhiel-lingard/"><img src="https://img.shields.io/badge/linkedin-0a0405?style=for-the-badge&logo=linkedin&logoColor=fca5a5"/></a>
<img src="https://komarev.com/ghpvc/?username=NikhCodes&style=for-the-badge&color=7f1d1d&label=visitors&labelColor=0a0405"/>

</div>

<br>

<img src="./assets/divider.svg" width="100%"/>

### ✦ about

I work as an **IT Operator at a fintech bank** in Suriname by day and study software engineering at **UNASAT** the rest of the time.

The two feed each other more than I expected. Watching how a production banking environment actually breaks, gets monitored, and gets patched has shaped what I want to build more than any course has.

I started in full-stack because it let me ship things quickly. Now I'm moving toward **backend engineering**, and most of my time goes into **Java, Spring Boot and PostgreSQL**. Somewhere along the way I got more interested in what happens when the request lands than in what the button looks like.

**Authentication flows, state machines, failure modes**, and the infrastructure between an application and the outside world are the parts I keep coming back to.

I don't collect frameworks. I'd rather spend three months understanding **Spring Security's filter chain** than skim ten tutorials on ten different stacks.

<br>

<div align="center">
<img src="./assets/now.svg" width="100%" alt="Right now: IT Operator at a fintech bank; BSc IT / Software Engineering at UNASAT; building with Java, Spring Boot, PostgreSQL, Spring Security; reading OWASP Top 10, authentication design, caching; next up Docker, Nginx, deployment infra"/>
</div>

<img src="./assets/divider.svg" width="100%"/>

### ✦ stack

<div align="center">

<table>
<tr>
<td align="center" width="20%"><sub>BACKEND</sub><br><br><img src="https://skillicons.dev/icons?i=java,spring,nodejs,python&theme=dark&perline=2"/></td>
<td align="center" width="20%"><sub>DATA</sub><br><br><img src="https://skillicons.dev/icons?i=postgres,hibernate,prisma&theme=dark&perline=2"/></td>
<td align="center" width="20%"><sub>FRONTEND</sub><br><br><img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind&theme=dark&perline=2"/></td>
<td align="center" width="20%"><sub>INFRA</sub><br><br><img src="https://skillicons.dev/icons?i=docker,git,vercel,fedora&theme=dark&perline=2"/></td>
<td align="center" width="20%"><sub>SECURITY</sub><br><br>
<img src="https://img.shields.io/badge/Spring_Security-1d0a0d?style=flat-square&logo=springsecurity&logoColor=fca5a5"/><br>
<img src="https://img.shields.io/badge/JWT-1d0a0d?style=flat-square&logo=jsonwebtokens&logoColor=fca5a5"/><br>
<img src="https://img.shields.io/badge/bcrypt-1d0a0d?style=flat-square&logoColor=fca5a5"/>
</td>
</tr>
</table>

</div>

<img src="./assets/divider.svg" width="100%"/>

### ✦ projects

Each of these started because I wanted to understand one specific thing properly, not because I needed portfolio filler.

<br>

<a href="https://github.com/NikhCodes/rigsight"><img src="./assets/rigsight.svg" width="100%" alt="RigSight: sensor data flowing through an ingest API, threshold rules, a state machine and deduplicated alerts"/></a>

#### [RigSight](https://github.com/NikhCodes/rigsight) · simulated industrial monitoring platform

I wanted to know what a backend looks like when it isn't just answering CRUD requests but reacting to continuous data: thresholds, state transitions, and repeated alerts that need deduplicating instead of spamming. JWT-secured with role-based access, a Flyway-managed schema, and Dockerized PostgreSQL.

`Java 21` `Spring Boot` `Spring Security` `JWT` `Hibernate` `PostgreSQL` `Flyway` `Docker`

<br>

<table>
<tr>
<td width="50%" valign="top">

<img src="./assets/agas.svg" width="100%" alt="AGAS: a padlock next to an append-only audit log"/>

**AGAS**: built for a university module, but I used it to go deeper on backend security than the assignment asked for. Bcrypt hashing, a three-role authorization model, and an append-only JSONB audit log so nothing gets silently overwritten. UUID keys and soft deletes throughout.

`Node.js` `Express` `PostgreSQL` `JWT` `bcrypt` `Helmet` `Joi`

</td>
<td width="50%" valign="top">

<a href="https://github.com/NikhCodes/nikh-exe"><img src="./assets/nikhexe.svg" width="100%" alt="NIKH.EXE: a browser window with a guestbook filling in"/></a>

**[NIKH.EXE](https://github.com/NikhCodes/nikh-exe)**: my personal corner of the internet. A guestbook backed by Postgres, and a v2 in progress with a private admin panel, a media library and a few easter eggs for anyone who goes looking.

`Vercel` `Neon Postgres`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/NikhCodes/NikhOS"><img src="./assets/nikhos.svg" width="100%" alt="NikhOS: a minimal dashboard with grades and assignments"/></a>

**[NikhOS](https://github.com/NikhCodes/NikhOS)**: a grade and assignment tracker I actually use every day. Local-first with no mandatory login, keyboard-friendly, and built to feel calm rather than busy. [Try it live →](https://nikh-os-red.vercel.app)

`React` `Vite` `Tailwind CSS` `Framer Motion`

</td>
<td width="50%" valign="top">

<a href="https://github.com/NikhCodes/face-tracker"><img src="./assets/posecam.svg" width="100%" alt="Pose Cam: hand landmarks tracked in a camera frame"/></a>

**[Pose Cam](https://github.com/NikhCodes/face-tracker)**: real-time hand gesture detection in the browser. No trained models; gestures are classified purely from landmark geometry, plus a pose editor to add new ones. I wanted to understand computer vision as math before reaching for anything pretrained.

`React` `Vite` `MediaPipe`

</td>
</tr>
</table>

<div align="center">
<img src="./assets/microjobs.svg" width="50%" alt="MicroJobs.sr: floating job cards with Surinamese prices and a yellow star"/>
</div>

<p align="center"><b>MicroJobs.sr</b>: my UNASAT capstone, a freelance marketplace built for Suriname. Next.js with a custom Tailwind design system, Framer Motion, and a bit of local personality in the details.<br><br><code>Next.js</code> <code>Tailwind CSS</code> <code>Framer Motion</code></p>

<img src="./assets/divider.svg" width="100%"/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NikhCodes/NikhCodes/output/github-contribution-grid-snake-dark.svg">
  <img alt="github contribution graph" src="https://raw.githubusercontent.com/NikhCodes/NikhCodes/output/github-contribution-grid-snake.svg">
</picture>

<br><br>

<img src="./assets/footer.svg" width="100%" alt="trying to understand systems before optimizing them"/>

</div>
