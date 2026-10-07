# Lianyu Peng

CS junior at the University of Maryland, graduating May 2028. I build full-stack and agentic
AI software, and I keep ending up on the authorization side of it: who is allowed to do
what, and how to prove nothing else slipped through.

<img alt="Visa SWE intern, summer 2026" src="https://img.shields.io/badge/Visa-SWE_intern,_summer_2026-0F766E?labelColor=334155&logo=visa&logoColor=white">
<img alt="UMD Computer Science, May 2028" src="https://img.shields.io/badge/UMD-Computer_Science,_May_2028-0F766E?labelColor=334155">
<img alt="Open to Summer 2027 internships and new-grad roles" src="https://img.shields.io/badge/open_to-Summer_2027_internships_and_new_grad-B45309?labelColor=334155">

## Experience

- **Visa**, software engineer intern, summer 2026. I reworked the RBAC model for an agentic
  AI workforce planning app and pushed authorization checks down from Angular route guards
  into the Spring Boot controllers.
- **Qubi**, a quantum computing education app in Flutter. I built the Firebase storage
  layer and a redesigned navigation.
- **Chosan**. I synced 400+ property listings into Postgres.
- **App Development Club at UMD**, Director of Education. I teach React, FastAPI, and
  Postgres to 45 students a semester, on a curriculum I designed around production stacks.
  18 students moved on from the shadowing program onto active development teams.

## Projects

### [QuietPlate](https://github.com/dpkingii/quietplate)

A Chrome extension that hides calorie numbers on restaurant menu sites.
`JavaScript` `Manifest V3` `Vitest`

- A regex pass catches the plain cases. Two more passes handle menus that split the number
  and unit apart, either across sibling elements like Starbucks or across text nodes inside
  one element like Shake Shack.
- The Shake Shack case blanks each text node in place instead of merging them, so React's
  virtual DOM stays intact.
- A MutationObserver rescans as single-page menus load new items. All scanning happens in
  the browser, and 21 Vitest tests run the content script and popup against jsdom.

### [Professor Rating Predictor](https://github.com/dpkingii/PredictingProfessorRating)

Predicts a UMD professor's star rating from grades and reviews.
`Python` `scikit-learn` `pandas`

- Pulls 4,200+ UMD professors from the PlanetTerp API. The features are grade
  distributions, the GPA students expect based on reviews, and VADER sentiment over the
  review text.
- I ran four models under 10-fold cross-validation. Support vector regression did best at
  R² 0.62, with plain linear regression right behind at 0.61, so most of the signal is
  linear. Random forest came in last.

### [Appaca](https://github.com/dpkingii/Appaca)

Matches App Development Club mentors with students. Built by a team of six at the ADC
bootcamp hackathon.
`TypeScript` `React` `FastAPI` `MongoDB`

- React and TypeScript front end, FastAPI and MongoDB backend.
- My part was the login page and Two Truths and a Bug, an icebreaker where a mentor writes
  three statements, marks one as the bug, and students try to guess which it is.

### [Bootcamp lecture code](https://github.com/dpkingii/bootcamp-lecture-code)

Live-coded lecture demos from the club's spring 2026 bootcamp.
`JavaScript` `React`

- A vanilla JavaScript intro, and a React cookie clicker built up from components, state,
  and upgrades.

## Stack

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=java,python,ts,spring,fastapi,postgres,mongodb,angular,react,flutter,docker&theme=dark">
  <img alt="Java, Python, TypeScript, Spring, FastAPI, PostgreSQL, MongoDB, Angular, React, Flutter, Docker" src="https://skillicons.dev/icons?i=java,python,ts,spring,fastapi,postgres,mongodb,angular,react,flutter,docker&theme=light">
</picture>

| Area | Tools |
| --- | --- |
| Languages | Java, Python, TypeScript/JavaScript, SQL, Dart, C/C++ |
| Backend and data | Spring Boot, FastAPI, Node.js, PostgreSQL, MongoDB, Firebase, Prisma |
| Frontend and mobile | Angular, React, Next.js, Flutter, Tailwind CSS |
| Tools and practices | Docker, Jenkins CI/CD, Linux, Git, unit testing, code review |

## Outside of code

I go by **Nick**. I love to talk, I'll go a long way for a good bowl of Asian noodles, and I
like staring up at the night sky. I find joy in making daily tasks a little more efficient,
which is how most of my side projects start.

## Contact

I'm open to **Summer 2027 software engineering internships and new-grad roles**. LinkedIn is
the best way to reach me. Resume on request.

<a href="https://www.linkedin.com/in/lianyu-peng"><img alt="LinkedIn: lianyu-peng" src="https://img.shields.io/badge/LinkedIn-lianyu--peng-0A66C2?labelColor=334155"></a>
