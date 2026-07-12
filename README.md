<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:312E81,50:6D28D9,100:8B5CF6&height=220&section=header&text=Yunjong%20Noh&fontSize=52&fontColor=FFFFFF&fontAlignY=38&desc=Software%20Engineer%20%C2%B7%20Backend%20%C2%B7%20Full-Stack&descAlignY=58&animation=fadeIn)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=8B5CF6&center=true&vCenter=true&width=760&lines=Building+reliable+web+and+backend+systems;Designing+practical+data-driven+products;Open+to+opportunities+in+Korea+and+the+United+States)](https://git.io/typing-svg)

![Software Engineering](https://img.shields.io/badge/Focus-Software%20Engineering-4F46E5?style=flat-square)
![CSULB Projects](https://img.shields.io/badge/Academic%20Context-CSULB%20Projects-6D28D9?style=flat-square)
![Location](https://img.shields.io/badge/Location-Seoul%2C%20South%20Korea-7C3AED?style=flat-square)

[![Portfolio](https://img.shields.io/badge/Portfolio-nohway.com-5B21B6?style=for-the-badge&logo=safari&logoColor=white)](https://www.nohway.com)
[![Email](https://img.shields.io/badge/Email-dji03120%40gmail.com-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dji03120@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-dji03120-312E81?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dji03120)

![Profile Views](https://komarev.com/ghpvc/?username=dji03120&style=flat-square&color=7C3AED&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/dji03120?style=flat-square&color=6D28D9&label=FOLLOWERS)

</div>

---

## About

I am a software engineer based in Seoul, building practical web applications, backend services, database-driven systems, and developer tooling. My work spans Python and JavaScript services, Kotlin Android development, relational and document databases, and cloud deployment practice.

I care about understandable code, reliable data flows, and products that remain maintainable after the first release. Recent work includes concurrency-safe API design, full-stack community products, mobile applications, and infrastructure experiments across Docker, Kubernetes, AWS EC2, and a personal homelab.

한국어로도 협업 가능한 소프트웨어 엔지니어입니다. 이해하기 쉬운 코드, 안정적인 데이터 흐름, 실제 사용 가능한 제품을 만드는 데 집중합니다.

> **Open to:** Software Engineering, Backend, and Full-Stack opportunities in South Korea and the United States.

---

## Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,kotlin,js,sql" alt="Python, Kotlin, JavaScript, SQL" />
</p>

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,vite,html,css" alt="React, Vite, HTML, CSS" />
</p>

### Backend & Databases

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,mongodb,redis,firebase" alt="FastAPI, Node.js, Express, PostgreSQL, MongoDB, Redis, Firebase" />
</p>

### Cloud, DevOps & Tooling

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,nginx,githubactions,git,linux,grafana" alt="AWS, Docker, Kubernetes, nginx, GitHub Actions, Git, Linux, Grafana" />
</p>

---

## AI / ML Exploration

| Domain | Proficiency | Details |
| :--- | :---: | :--- |
| Local AI systems | Exploring | Running local AI experiments in a personal homelab environment |
| AI-assisted engineering | Working knowledge | Using AI tools to support implementation, debugging, and technical exploration |

---

## Featured Projects

<details open>
<summary><strong>High Traffic Coupon API</strong> - concurrency and infrastructure study</summary>

<br/>

A staged backend project that reproduces coupon-issuance race conditions and explores their resolution with Redis atomic operations, traffic distribution, container orchestration, CI, and monitoring.

| Area | Details |
| :--- | :--- |
| Stack | FastAPI, PostgreSQL, SQLAlchemy, Redis, nginx, Docker, Kubernetes |
| Scale | A documented test scenario sends 1,000 concurrent requests against 100 coupons |
| Performance | Locust load-testing setup; no unverified benchmark values claimed |
| Security & reliability | Atomic inventory decrement, environment-based configuration, self-healing and HPA exercises |
| Impact | Demonstrates a progression from race-condition reproduction to observable infrastructure |
| Repository | [dji03120/high-traffic-coupon-api](https://github.com/dji03120/high-traffic-coupon-api) |

</details>

<details>
<summary><strong>BookNook</strong> - Android social reading application</summary>

<br/>

A team-built Android app for book discovery, personal collections, reading-status tracking, reviews, and social reading features through the Google Books API and Firebase services.

| Area | Details |
| :--- | :--- |
| Stack | Kotlin, Android, Firebase Authentication, Firestore, Storage, Retrofit, Glide |
| Scale | Multi-screen mobile product covering discovery, collections, profiles, groups, and notifications |
| Performance | Network and image integrations through Retrofit and Glide; no unverified metrics claimed |
| Security | Firebase configuration excluded from source control; authentication handled through Firebase |
| Impact | Delivers an end-to-end reading workflow in a four-person team project |
| Repository | [dji03120/BookNook-App](https://github.com/dji03120/BookNook-App) |

</details>

<details>
<summary><strong>CSULB Rating Web</strong> - full-stack campus review platform</summary>

<br/>

A campus-focused web application for ratings, polls, saved posts, and voting, with a React frontend and an Express/MongoDB backend.

| Area | Details |
| :--- | :--- |
| Stack | React, Vite, Express, MongoDB, Mongoose, JWT, bcrypt, Vercel, Render |
| Scale | Authentication, ratings, polls, media uploads, bookmarks, and voting flows |
| Performance | Independently deployed frontend and backend; no unverified metrics claimed |
| Security | JWT authentication, password hashing with bcrypt, environment-managed secrets |
| Impact | Turns campus feedback and polling into a working, publicly deployed product |
| Repository | [Source](https://github.com/dji03120/CSULB_Rating_Web) · [Live site](https://csulb-rating-web.vercel.app) |

</details>

<details>
<summary><strong>Student Enrollment System</strong> - MongoDB data-modeling project</summary>

<br/>

A Python console application modeling departments, majors, students, courses, sections, and enrollments with MongoDB validators and indexes.

| Area | Details |
| :--- | :--- |
| Stack | Python, PyMongo, MongoDB Atlas, Poetry |
| Scale | Multiple related collections with create, delete, list, and cascading-delete flows |
| Performance | Unique indexes support data integrity; no unverified benchmark values claimed |
| Security | Database password requested at runtime instead of stored in the repository |
| Impact | Applies document-database modeling to a realistic university domain |
| Repository | [dji03120/Student-Enrollment-System](https://github.com/dji03120/Student-Enrollment-System) |

</details>

---

## Experience

### Software Engineer · SN Corp.

`Current` · Seoul, South Korea

- Building and maintaining practical software products and internal systems.
- Working across web applications, backend services, databases, and deployment environments.
- Applying Python, JavaScript, SQL, MongoDB, Firebase, and AWS EC2 in development and operations practice.

`Software Engineering` `Backend` `Databases` `Cloud Deployment`

---

## Achievements

| Recognition | Details |
| :---: | :--- |
| Shipped products | Built and documented public mobile, web, database, and backend systems |
| Production practice | Deployed a full-stack campus application and maintained personal deployment environments |

---

## Certifications

No certifications are listed because no verified public credentials have been provided.

---

## Coding Profiles

No external competitive-programming profile is claimed. Engineering work is available through the linked GitHub repositories.

---

## GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=dji03120&show_icons=true&hide_border=true&theme=midnight-purple&rank_icon=github" alt="Yunjong Noh's GitHub statistics" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dji03120&layout=compact&hide_border=true&theme=midnight-purple" alt="Most used languages" />

<img src="https://streak-stats.demolab.com?user=dji03120&theme=midnight-purple&hide_border=true" alt="GitHub contribution streak" />

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=dji03120&theme=discord&no-frame=true&no-bg=true&margin-w=8&column=6" alt="GitHub trophies" />

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dji03120&bg_color=0D1117&color=A78BFA&line=7C3AED&point=DDD6FE&area=true&hide_border=true" alt="GitHub contribution activity graph" />

</div>

---

## Contribution Snake

<div align="center">

_A generated snake asset is intentionally not embedded until this repository has a verified generation workflow._

</div>

---

## Current Focus

```yaml
learning:
  - Database internals and reliable backend API design
  - Android development and security fundamentals
building:
  - Backend systems with concurrency, deployment, and observability practice
  - Personal portfolio and homelab services
exploring:
  - Local AI workflows
  - Cloud-native infrastructure
open_to:
  - Software Engineering
  - Backend Engineering
  - Full-Stack Engineering
  - Opportunities in South Korea and the United States
```

---

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-dji03120%40gmail.com-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dji03120@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-dji03120-312E81?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dji03120)
[![Portfolio](https://img.shields.io/badge/Portfolio-nohway.com-5B21B6?style=for-the-badge&logo=safari&logoColor=white)](https://www.nohway.com)

</div>

---

<div align="center">

**Build clearly. Ship thoughtfully. Keep learning.**

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:6D28D9,100:312E81&height=120&section=footer)

</div>
