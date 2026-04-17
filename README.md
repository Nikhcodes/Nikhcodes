<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=180&section=header&text=Nikhiel%20Lingard&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Backend%20Engineer%20in%20Progress%20%7C%20Paramaribo%2C%20Suriname%20%F0%9F%87%B8%F0%9F%87%B7&descAlignY=60&descColor=A78BFA" />

<br/>

<a href="mailto:nikhiel.lingard.dev@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="www.linkedin.com/in/nikhiel-lingard">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/NikhCodes">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<img src="https://komarev.com/ghpvc/?username=NikhCodes&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS" />

<br/><br/>

![Status](https://img.shields.io/badge/Status-Building%20Toward%20Hireable-brightgreen?style=flat-square)
![Location](https://img.shields.io/badge/📍-Paramaribo%2C%20Suriname-A78BFA?style=flat-square)
![Open To](https://img.shields.io/badge/Open%20To-Internships%20%26%20Collabs-blue?style=flat-square)
![Studying](https://img.shields.io/badge/BSc%20IT-Software%20Engineering%20@%20UNASAT-A78BFA?style=flat-square)

</div>

---

## who i am

Software engineering student from Suriname, working toward a BSc in IT at UNASAT.

I started with fullstack — built things in React, learned how it all connects. But the more I built, the more I cared about what's underneath: how systems are structured, why certain decisions break things later, how security fits in from the start and not as an afterthought.

So I shifted focus. Backend is where I'm going — specifically Java and Spring Boot. That's what I'm building toward being hireable in. I want to understand it properly, not just get it working.

I grew up mostly figuring things out on my own, and that's still how I learn. I don't rush to the next tool. I'd rather understand one thing well.

---

## what i'm actually working on right now

```ts
const nikhiel = {
  degree:    "BSc IT — Software Engineering @ UNASAT",
  direction: "Backend engineering (Java / Spring Boot)",

  currentlyStudying: [
    "Java + Spring Boot — main focus, building toward hireable",
    "OWASP Top 10 — understanding it to apply it, not just cite it",
    "TDD — reading Kent Beck, trying to actually write tests first",
    "24 Deadly Sins of Software Security — software security fundamentals",
  ],

  wantToLearnNext: [
    "Nginx — reverse proxy, load balancing, the infrastructure layer",
    "Caching strategies",
    "More of what sits between the app and the world",
  ],

  honest: "I'm early. I understand more than I've shipped — and I'm fixing that.",
};
```

---

## tech i actually use

<div align="center">

**backend — what i build with**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**frontend — comfortable, not my focus**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-black?style=for-the-badge&logo=framer&logoColor=blue)

**tools & environment**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Fedora](https://img.shields.io/badge/Fedora-51A2DA?style=for-the-badge&logo=fedora&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

**exploring**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## projects

Things I actually built. Some are polished, some are learning exercises — but they're real.

---

### 🏗️ AGAS — Academic Group Accountability System
> Role-based web app for managing academic group work, with a full audit trail

Built with a team as part of my software engineering programme. I handled backend and security.

- Module-based Node.js + Express API with PostgreSQL
- JWT auth, bcrypt (12 rounds), role-based access control across three roles
- Append-only audit log with JSONB metadata — every action is traceable and survives entity deletion
- OWASP principles applied throughout: rate limiting, Helmet.js, Joi validation, enumeration-safe error messages
- UUID primary keys, soft deletes, database-level triggers enforcing group membership and assignment integrity

The security wasn't an afterthought — it was designed in from the schema up.

`Node.js` `Express` `PostgreSQL` `JWT` `bcrypt` `Joi` `Helmet`

---

### ✦ NikhOS — Student Dashboard
> A minimal student workspace that behaves like a native app

Personal project. Wanted something that loads fast and stays out of the way — not another cluttered productivity tool.

- Grades, assignments, calendar, focus mode — all local, no accounts, no sync
- Installable as a PWA, works offline
- Framer Motion for interaction feel

**[live demo ↗](https://nikh-os-red.vercel.app)** · **[repo ↗](https://github.com/Nikhcodes/NikhOS)**

`React 18` `Vite 6` `Tailwind v4` `Framer Motion` `localStorage`

---

### 🖐️ pose cam — Real-Time Hand Gesture Detector
> Python tool that reads hand poses via webcam and overlays images in real time

Built because I was curious about computer vision and wanted to actually use MediaPipe properly — not just run the example.

- 9 classified poses using finger landmark geometry — no ML training, just geometry
- Auto brightness/contrast, warmth tone, vignette — built to look good for photos not just demos
- Runs entirely local, no servers, no accounts

**[repo ↗](https://github.com/Nikhcodes/face-tracker)**

`Python 3.12` `MediaPipe Tasks API` `OpenCV` `NumPy`

---

### ☕ Task API — Spring Boot REST Service
> Minimal CRUD API for task management using Spring Boot and PostgreSQL

First real Java/Spring Boot project. Built to learn the stack properly — layered architecture, JPA/Hibernate, PostgreSQL integration. Small scope intentionally.

I documented every issue I hit along the way: schema permissions, Hibernate DDL config, endpoint mapping errors. Understanding what breaks and why matters more to me than having it work first try.

`Java` `Spring Boot` `Spring Data JPA` `Hibernate` `PostgreSQL` `Maven`

---

## github stats

<div align="center">

<img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=NikhCodes&show_icons=true&theme=tokyonight&border_radius=10&bg_color=0D1117&hide_border=true&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=NikhCodes&layout=compact&theme=tokyonight&border_radius=10&bg_color=0D1117&hide_border=true"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=NikhCodes&theme=tokyonight&border_radius=10&hide_border=true&background=0D1117" />

</div>

---

## contribution snake

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/NikhCodes/NikhCodes/blob/output/github-contribution-grid-snake-dark.svg">
  <img alt="github contribution snake" src="https://github.com/NikhCodes/NikhCodes/blob/output/github-contribution-grid-snake.svg">
</picture>
</div>

---

## get in touch

| | |
|--|--|
| 📧 Email | [nikhiel.lingard.dev@gmail.com](mailto:nikhiel.lingard.dev@gmail.com) |
| 💼 LinkedIn | [linkedin.com](https://linkedin.com/) |
| 🐙 GitHub | [@NikhCodes](https://github.com/NikhCodes) |

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer&animation=twinkling"/>

*Building toward hireable — one properly understood system at a time.*

</div>
