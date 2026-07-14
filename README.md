<div align="center">

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:14213D,35:1D5C63,70:2A9D8F,100:2A9D8F&height=220&section=header&text=%EB%85%B8%EC%9C%A4%EC%A2%85&fontSize=52&fontColor=FFFFFF&fontAlignY=32&desc=Yunjong%20Noh-nl-Software%20Engineer%20%C2%B7%20Backend%20%C2%B7%20Full-Stack&descSize=20&descAlignY=58&animation=fadeIn" width="100%" alt="노윤종 · Yunjong Noh" />
</p>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=2A9D8F&center=true&vCenter=true&width=760&lines=Building+reliable+web+and+backend+systems;Designing+practical+data-driven+products;Open+to+opportunities+in+Korea+and+the+United+States)](https://git.io/typing-svg)

![Software Engineering](https://img.shields.io/badge/Focus-Software%20Engineering-1D5C63?style=flat-square)
![CSULB Projects](https://img.shields.io/badge/Academic%20Context-CSULB%20Projects-14213D?style=flat-square)
![Location](https://img.shields.io/badge/Location-Seoul%2C%20South%20Korea-2A9D8F?style=flat-square)

[![Portfolio](https://img.shields.io/badge/Portfolio-nohway.com-1D5C63?style=for-the-badge&logo=safari&logoColor=white)](https://www.nohway.com)
[![Email](https://img.shields.io/badge/Email-dji03120%40gmail.com-14213D?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dji03120@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-dji03120-0B1220?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dji03120)

![Profile Views](https://komarev.com/ghpvc/?username=dji03120&style=flat-square&color=2A9D8F&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/dji03120?style=flat-square&color=14213D&label=FOLLOWERS)

[English](#english-profile) · [한국어](#한국어-프로필)

</div>

---

<a id="english-profile"></a>

## English Profile

## About

I am a software engineer based in Seoul, building practical web applications, backend services, database-driven systems, and developer tooling. My work spans Python and JavaScript services, Kotlin Android development, relational and document databases, and cloud deployment practice.

I care about understandable code, reliable data flows, and products that remain maintainable after the first release. Recent work includes concurrency-safe API design, full-stack community products, mobile applications, and infrastructure experiments across Docker, Kubernetes, AWS EC2, and a personal homelab.

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

<a id="한국어-프로필"></a>

## 한국어 프로필

### 소개

서울을 기반으로 웹 애플리케이션, 백엔드 서비스, 데이터베이스 중심 시스템과 개발 도구를 만드는 소프트웨어 엔지니어입니다. Python과 JavaScript 기반 서비스, Kotlin Android 개발, 관계형·문서형 데이터베이스, 클라우드 배포 환경을 폭넓게 다룹니다.

첫 구현 이후에도 이해하고 유지보수하기 쉬운 코드, 안정적인 데이터 흐름, 실제 사용할 수 있는 제품을 중요하게 생각합니다. 최근에는 동시성을 고려한 API 설계, 풀스택 커뮤니티 서비스, 모바일 애플리케이션, Docker·Kubernetes·AWS EC2 및 개인 홈랩 기반의 인프라 실습에 집중하고 있습니다.

> **구직 분야:** 한국 및 미국의 소프트웨어 엔지니어링, 백엔드, 풀스택 포지션

### AI / ML 탐색

| 분야 | 수준 | 내용 |
| :--- | :---: | :--- |
| 로컬 AI 시스템 | 탐색 중 | 개인 홈랩 환경에서 로컬 AI 워크플로 실험 |
| AI 활용 개발 | 실무 활용 | 구현, 디버깅, 기술 조사를 보조하는 AI 도구 활용 |

### 주요 프로젝트

<details open>
<summary><strong>High Traffic Coupon API</strong> - 동시성 및 인프라 실습</summary>

<br/>

재고 100개에 동시 요청 1,000개가 들어오는 상황을 기준으로 경쟁 상태를 재현하고, Redis 원자 연산과 트래픽 분산, 컨테이너 오케스트레이션, CI 및 모니터링을 단계적으로 적용한 백엔드 프로젝트입니다.

| 항목 | 내용 |
| :--- | :--- |
| 기술 | FastAPI, PostgreSQL, SQLAlchemy, Redis, nginx, Docker, Kubernetes |
| 안정성 | 원자적 재고 차감, 환경 변수 기반 설정, self-healing 및 HPA 실습 |
| 검증 | Locust 부하 테스트 환경을 제공하며 측정되지 않은 성능 수치는 기재하지 않음 |
| 저장소 | [dji03120/high-traffic-coupon-api](https://github.com/dji03120/high-traffic-coupon-api) |

</details>

<details>
<summary><strong>BookNook</strong> - Android 소셜 독서 애플리케이션</summary>

<br/>

Google Books API와 Firebase를 활용해 도서 검색, 개인 서재, 독서 상태, 리뷰, 친구·그룹 기능을 제공하는 4인 팀 Android 프로젝트입니다.

| 항목 | 내용 |
| :--- | :--- |
| 기술 | Kotlin, Android, Firebase Authentication, Firestore, Storage, Retrofit, Glide |
| 보안 | Firebase 실제 설정 파일을 소스 관리에서 제외하고 Firebase 인증 사용 |
| 저장소 | [dji03120/BookNook-App](https://github.com/dji03120/BookNook-App) |

</details>

<details>
<summary><strong>CSULB Rating Web</strong> - 캠퍼스 풀스택 리뷰 플랫폼</summary>

<br/>

평점 게시물, 투표, 북마크와 추천·비추천 기능을 제공하는 캠퍼스 중심 웹 서비스입니다. React 프론트엔드와 Express·MongoDB 백엔드를 각각 배포했습니다.

| 항목 | 내용 |
| :--- | :--- |
| 기술 | React, Vite, Express, MongoDB, Mongoose, JWT, bcrypt, Vercel, Render |
| 보안 | JWT 인증, bcrypt 비밀번호 해싱, 환경 변수 기반 비밀값 관리 |
| 링크 | [소스 코드](https://github.com/dji03120/CSULB_Rating_Web) · [배포 사이트](https://csulb-rating-web.vercel.app) |

</details>

<details>
<summary><strong>Student Enrollment System</strong> - MongoDB 데이터 모델링</summary>

<br/>

학과, 전공, 학생, 강좌, 분반과 수강 관계를 MongoDB validator와 unique index로 모델링한 Python 콘솔 애플리케이션입니다.

| 항목 | 내용 |
| :--- | :--- |
| 기술 | Python, PyMongo, MongoDB Atlas, Poetry |
| 범위 | 여러 컬렉션의 생성·삭제·조회 및 연관 문서 삭제 흐름 |
| 보안 | 데이터베이스 비밀번호를 저장소에 저장하지 않고 실행 시 입력 |
| 저장소 | [dji03120/Student-Enrollment-System](https://github.com/dji03120/Student-Enrollment-System) |

</details>

### 경력

#### 소프트웨어 엔지니어 · SN Corp.

`재직 중` · 대한민국 서울

- 실사용 소프트웨어 제품과 내부 시스템 개발 및 유지보수
- 웹 애플리케이션, 백엔드 서비스, 데이터베이스 및 배포 환경 전반 담당
- Python, JavaScript, SQL, MongoDB, Firebase 및 AWS EC2 기반 개발·운영 실습

`소프트웨어 엔지니어링` `백엔드` `데이터베이스` `클라우드 배포`

### 성과

| 구분 | 내용 |
| :---: | :--- |
| 제품 구현 | 모바일, 웹, 데이터베이스 및 백엔드 시스템을 개발하고 공개 저장소에 문서화 |
| 배포 경험 | 풀스택 캠퍼스 서비스를 배포하고 개인 배포 환경과 홈랩을 운영 |

### 자격증 및 코딩 프로필

검증 가능한 자격증이나 외부 경쟁 프로그래밍 계정은 임의로 기재하지 않았습니다. 실제 엔지니어링 작업은 연결된 GitHub 저장소에서 확인할 수 있습니다.

### 현재 집중 분야

```yaml
학습:
  - 데이터베이스 내부 구조와 안정적인 백엔드 API 설계
  - Android 개발과 보안 기초
개발:
  - 동시성, 배포 및 관측 가능성을 고려한 백엔드 시스템
  - 개인 포트폴리오와 홈랩 서비스
탐색:
  - 로컬 AI 워크플로
  - 클라우드 네이티브 인프라
구직:
  - 소프트웨어 엔지니어링
  - 백엔드 엔지니어링
  - 풀스택 엔지니어링
  - 한국 및 미국 포지션
```

---

## GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=dji03120&show_icons=true&hide_border=true&title_color=2A9D8F&icon_color=1D5C63&text_color=C9D1D9&bg_color=0D1117&rank_icon=github" alt="Yunjong Noh's GitHub statistics" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dji03120&layout=compact&hide_border=true&title_color=2A9D8F&text_color=C9D1D9&bg_color=0D1117" alt="Most used languages" />

<img src="https://streak-stats.demolab.com?user=dji03120&hide_border=true&background=0D1117&ring=2A9D8F&fire=1D5C63&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=2A9D8F&sideLabels=7FB3AE&dates=8B949E&stroke=30363D" alt="GitHub contribution streak" />

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=dji03120&theme=discord&no-frame=true&no-bg=true&margin-w=8&column=6" alt="GitHub trophies" />

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dji03120&bg_color=0D1117&color=7FB3AE&line=2A9D8F&point=E9C46A&area=true&hide_border=true" alt="GitHub contribution activity graph" />

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

[![Gmail](https://img.shields.io/badge/Gmail-dji03120%40gmail.com-14213D?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dji03120@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-dji03120-0B1220?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dji03120)
[![Portfolio](https://img.shields.io/badge/Portfolio-nohway.com-1D5C63?style=for-the-badge&logo=safari&logoColor=white)](https://www.nohway.com)

</div>

---

<div align="center">

**Build clearly. Ship thoughtfully. Keep learning.**

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:2A9D8F,35:1D5C63,70:14213D,100:0B1220&height=120&section=footer)

</div>
