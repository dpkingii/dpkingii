<div align="center">

<img width="100%" alt="Lianyu Peng, Software Engineer" src="https://capsule-render.vercel.app/api?type=waving&color=0:1C1B18,55:8C1B2B,100:E21833&height=200&section=header&text=Lianyu%20Peng&fontSize=60&fontColor=F5F2EC&animation=fadeIn&fontAlignY=36&desc=Software%20Engineer&descSize=18&descAlignY=57">

<p>
  <img alt="Visa SWE Intern, Summer 2026" src="https://img.shields.io/badge/Visa-SWE_Intern_·_Summer_2026-1A1F71?style=for-the-badge&logo=visa&logoColor=white">
  <img alt="UMD Computer Science, May 2028" src="https://img.shields.io/badge/UMD-Computer_Science_·_May_2028-1C1B18?style=for-the-badge">
  <img alt="Open to Summer 2027 internships and new-grad roles" src="https://img.shields.io/badge/Open_to-Summer_2027_·_new_grad-E21833?style=for-the-badge">
</p>

</div>

## About

I build **full-stack and agentic AI software**, and I keep ending up on the authorization
side of it: who is allowed to do what, and how to prove nothing else slipped through.

This past summer I was a **software engineer intern at Visa**, where I reworked the RBAC
model for an agentic AI workforce planning app and pushed authorization checks down from
Angular route guards into the Spring Boot controllers. Before that I built the Firebase
storage layer and a redesigned navigation for **Qubi**, a quantum computing education app
in Flutter, and synced 400+ property listings into Postgres at **Chosan**.

I'm studying CS at **UMD** (May 2028) and I'm **open to Summer 2027 internships and new-grad
roles**. I also run education for the **App Development Club at UMD**, teaching React,
FastAPI, and Postgres to 45 students a semester.

Outside of code I go by **Nick**. I love hearing people's stories, I'll go a long way for a good bowl of
Asian noodles, and I like staring up at the night sky. I find joy in making daily tasks a
little more efficient, which is how most of my side projects start.

<img width="100%" height="4" alt="" src="https://capsule-render.vercel.app/api?type=rect&color=0:1C1B18,55:8C1B2B,100:E21833&height=4">

## What I built

<table>
<tr>
<td width="50%" valign="top">

### [QuietPlate](https://github.com/dpkingii/quietplate)
**Chrome extension · JavaScript**

Hides calorie numbers on restaurant menu sites. A regex pass catches the plain cases, and
two more passes handle menus that split the number and unit apart: across sibling
elements like Starbucks, or across text nodes inside one element like Shake Shack. A
MutationObserver rescans as single-page menus load new items.

> The Shake Shack case blanks each text node in place instead of merging them, so React's
> virtual DOM stays intact. All scanning happens in the browser, and **21 Vitest tests**
> run the content script and popup against jsdom.

![JavaScript](https://img.shields.io/badge/JavaScript-8C1B2B?style=flat-square&logo=javascript&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest_V3-1C1B18?style=flat-square&logo=googlechrome&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-E21833?style=flat-square&logo=vitest&logoColor=white)

</td>
<td width="50%" valign="top">

### [Professor Rating Predictor](https://github.com/dpkingii/PredictingProfessorRating)
**Machine learning · Python**

Pulls **3,000+ UMD professors and 8,000+ reviews** from the PlanetTerp API and predicts their star rating from
grade distributions, the GPA students expect based on reviews, and VADER sentiment over
the review text.

> Linear regression, random forest, and support vector regression were each scored with
> 10-fold cross-validation on the same held-out split. SVR did best at **R² 0.62**, with
> plain linear regression right behind at 0.61, so most of the signal is linear.

![Python](https://img.shields.io/badge/Python-8C1B2B?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1C1B18?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-E21833?style=flat-square&logo=pandas&logoColor=white)

</td>
</tr>
<tr><td colspan="2"></td></tr>
<tr>
<td colspan="2" valign="top">

### [Teaching](https://github.com/dpkingii/bootcamp-lecture-code)
**App Development Club bootcamp**

Live-coded lecture demos for the club's spring 2026 bootcamp: a vanilla JavaScript intro
and a React cookie clicker built up from components, state, and upgrades.

> As Director of Education I designed the curriculum around production stacks, and
> 18 students moved on from the shadowing program onto active development teams.

![React](https://img.shields.io/badge/React-8C1B2B?style=flat-square&logo=react&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-1C1B18?style=flat-square&logo=javascript&logoColor=white)

</td>
</tr>
</table>

<img width="100%" height="4" alt="" src="https://capsule-render.vercel.app/api?type=rect&color=0:1C1B18,55:8C1B2B,100:E21833&height=4">

## What I work in

**Languages** · Java · Python · TypeScript/JavaScript · SQL · Dart · C/C++

**Backend & data** · Spring Boot · FastAPI · Node.js · PostgreSQL · MongoDB · Firebase · Prisma

**Frontend & mobile** · Angular · React · Next.js · Flutter · Tailwind CSS

**Tools & practices** · Docker · Jenkins CI/CD · Linux · Git · Unit testing · Code review

## Get in touch

I'm looking for **Summer 2027 software engineering internships and new-grad roles**. LinkedIn
is the best way to reach me, and my site at [dpkingii.github.io](https://dpkingii.github.io)
has more on my projects.

<p align="center">
  <a href="https://dpkingii.github.io"><img src="https://img.shields.io/badge/Website-dpkingii.github.io-8C1B2B?style=for-the-badge" alt="Website"></a>
  <a href="https://www.linkedin.com/in/lianyu-peng"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
</p>
