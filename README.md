<!-- 헤더 배너 -->

![header](https://capsule-render.vercel.app/api?type=Cylinder\&color=auto\&height=120\&section=header\&text=Dawntea%20Studio%20🍵\&fontSize=42\&animation=twinkling)

<div align="center">

## Hi, I'm **SW** 👋

개발이 취미입니다. 재미로 시작했지만 지금은 일이자 즐거움입니다.

수집욕이 있습니다. 배운 걸 흘려보내지 않고 문서로 차곡차곡 모읍니다.

저는 즐기는 개발자이자 기록하는 수집가입니다.
</div>

<details>
  <summary><b>📑 Table of Contents (click to expand)</b></summary>

- [🧭 About Me](#-about-me)
- [🎓 Education & Training](#-education--training)
- [💼 Experience](#-experience)
- [📂 Projects](#-projects)
  - [🚀 Major Projects](#-major-projects)
  - [Other Projects](#other-projects)
  - [🎓 42Seoul Core Curriculum](#-42seoul-core-curriculum)
- [🛠 Tech Stack](#-tech-stack)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database](#database)
  - [DevOps & Infra](#devops--infra)
  - [Tools & Others](#tools--others)
- [📚 Studying Now](#-studying-now)
- [🧩 Languages](#-languages)
- [📜 Certifications](#-certifications)
- [🌍 Language](#-language)
- [✏️ Problem Solving](#problem-solving)
- [📊 GitHub Stats](#-github-stats)
- [🔗 Links](#-links)
- [📌 Notes](#-notes)

</details>


---

## 🧭 About Me

* 🔭 관심 분야: **백엔드 개발, 데이터 모델링, 실시간 통신**
* 🗂️ 문서화 습관: 설계 → 기록 → 공유 (Notion & GitHub)
* 🎯 목표: **완벽한 테스트 설계해보기** && **시스템 레벨의 오픈소스 만들기**

---

## 🎓 Education & Training

* **Kyung Hee University** (2015 ~ 2022)  
  * Major: 산업경영공학과  
  * Graduation Thesis: *Optimal Parking Lot Location for Gangnam-gu, Seoul*  
  * 학부 프로젝트: Python으로 키워드 기사 수집, 회귀분석 및 시각화

* **Courses & Clubs**  
  * 공학프로그래밍입문 (Java, 2015)  
  * 알기쉬운소프트웨어코딩 (Python, 2021)  
  * OOP (C++, 2022)  
  * Spartacodingclub (2021) – 웹개발 종합반 (HTML, CSS, JavaScript)

* **Bootcamps & Tracks**  
  * **엘리스 SW 트랙 4기** (2023.02 ~ 2023.06) – Node.js, Express, MongoDB  
  * **42 Seoul** (2023.08 ~ 2025.07, 본과정 2023.10 시작) – C, C++, Linux, Docker, Shell, socket  
  * **SSAFY Seoul Embedded** (2025.07 ~ 2025.12) – C/C++, Linux, Vue 3, Express, MySQL, Firebase  
  * **SW마에스트로** (2026) – 우클링 3인 팀 백엔드 담당

---

## 💼 Experience

* **CJ올리브네트웍스 BSE 인턴** (2025.12) – 대한통운2팀  
  샘플 물류 데이터를 바탕으로 택배 수거 가능성을 시간대별로 안내하는 지도 데모 설계, 구현 및 발표. *Python, FastAPI, OpenAI API*

---

## 📂 Projects

### 🚀 Major Projects

- **우클링** (2026)  
  *Java, Spring Boot, PostgreSQL, S3, OpenAPI*  
  - 공방 수업 운영 서비스의 백엔드 담당. 강사 페이지와 공통 수강 관리 기능 제안  
  - 용어사전 → 논리 모델 → 물리 컬럼 → ERD → Swagger 명세 → API 구현  
  - 팀의 [데이터 모델링 하네스](https://ucling-data-model-portal.vercel.app/) 직접 설계: Codex의 제안과 확정 사항을 구분해 기록하고, 승인된 ERD를 버전별로 조회  
  - 회원가입 재시도 시 최초 동의 보존, 프로필 이미지 업로드 복구 및 마이페이지 API 연동

- **TIL / til-studio** (2026)  
  *Next.js, TypeScript, GitHub API, Electron*  
  - 학습 노트와 README 목록을 한 커밋으로 저장하고, 직접 반영 또는 PR 검토 선택  
  - OpenAI와 Gemini를 활용한 초안 작성, macOS 메뉴바 앱 빌드 자동화  
  🔗 [TIL](https://github.com/DawnteaStudio/TIL) / [til-studio](https://github.com/DawnteaStudio/til-studio)

- **ft_transcendence** (2025.03 ~ 2025.07)  
  *Fastify, TypeScript, Docker, SQLite*  
  - 실시간 웹소켓 기반 Ping-Pong 게임  
  - Google OAuth, JWT, 2FA 인증 및 토큰 갱신 처리  
  - WebSocket 접속 상태 관리, Prisma 트랜잭션으로 4인 대진과 경기 생성  
  🔗 [GitHub Repo](https://github.com/DawnteaStudio/ft_transcendence) / [팀 저장소](https://github.com/Good-PingPong-Greate-PingPong/ping_pong/tree/last)

- **ft_irc** (2025.01 ~ 2025.02)  
  *C++, Socket Programming*  
  - IRC 프로토콜 기반 채팅 서버  
  - `poll` 기반 다중 접속, 요청 파싱과 채널 권한 처리. tcpflow로 미응답 원인을 추적해 수신 버퍼 수정  
  🔗 [GitHub Repo](https://github.com/DawnteaStudio/ft_irc)

- **minishell** (2024.03 ~ 2024.05)  
  *C, POSIX*  
  - bash 유사 셸 구현  
  - 실행기 담당: 프로세스 생성과 종료 대기, PATH 탐색, 시그널 처리  
  🔗 [GitHub Repo](https://github.com/DawnteaStudio/Jetty_minishell)

- **JWYH (Just Wait You Will be Happy)** (2023.05 ~ 2023.06)  
  *Node.js, Express, MongoDB*  
  - 미래에 편지를 보내는 웹 서비스  
  - 편지 CRUD와 날짜별 열람 처리, Nginx와 PM2 배포 담당  
  🔗 [GitHub Repo](https://github.com/DawnteaStudio/JWYH)

---

### Other Projects

<details>
<summary>프로젝트와 활동 더 보기</summary>

- **SSAFY 차량 인포테인먼트** (2025) – 차량 로그 전처리, 챗봇 API 연동, Chart.js 시각화 및 EC2/Nginx 배포
- **원데이 AI 아이디어 챌린지** – 만남 장소 추천 데모의 기획과 시연 조율, 발표 담당 (팀 내 MVP)
- **[Review Ops Agent](https://github.com/UpstageAI/sw-maestro-project/pull/147)** (2026) – 소마 5인 팀 리뷰 응대 에이전트 과제 제출 및 변경사항 통합
- **소마 인터페이스 과제** (2026) – [캐릭터 AI 인터페이스 리서치](https://github.com/DawnteaStudio/soma-subject-01), [스마트홈 예시 데이터 기반 대시보드 15종](https://github.com/DawnteaStudio/soma-subject-02)
- **[Dualmode AGV](https://github.com/dualmode-agv-lab/dualmode-agv-platform/pull/3)** (2025) – 팀 개발 규칙과 이슈/PR 템플릿 작성
- **[basicWeb](https://github.com/DawnteaStudio/basicWeb)** (2023) – Express와 MongoDB 기반 팀 쇼핑몰
- **스터디** – 알고리즘 스터디 (2023.09 ~ 12), CS 스터디 DB 발표 담당 (2025.08 ~ 11)
- **교육 및 커뮤니티** – 복지센터와 아동센터 수학 지도, OakBarrelStorage 기록 모임

</details>

---

### 🎓 42Seoul Core Curriculum

> 42서울(42Ecole) 공통과정을 돌파하며, **시스템 프로그래밍 → 그래픽스 → 네트워크 → 풀스택**까지 단계적으로 검증된 프로젝트들입니다.

---

#### 🔹 Foundations (C / Shell / Git)
- **Libft** – C 표준 라이브러리 함수 직접 구현 → **포인터/메모리 관리 심화**  
- **Born2beroot** – Linux VM 보안, 사용자 관리, SSH/UFW 설정 → **시스템 관리 기본기**  
- **get_next_line** – 파일 디스크립터 기반 입력 처리 → **버퍼링/EOF 처리**  
- **ft_printf** – printf 함수 구현 → **가변인자, 출력 포맷 처리**

---

#### 🔹 Algorithms & Problem Solving
- **push_swap** – 제한 연산으로 스택 정렬 알고리즘 구현 → **시간 복잡도 최적화**

---

#### 🔹 Unix & Process Management
- **pipex** – Unix 파이프라인(`|`) 직접 구현 → **IPC / 프로세스 제어**  
- **minishell** – bash 유사 셸 제작 → **파싱, 리다이렉션, 시그널 처리**  
- **philosophers** – Dining Philosophers 문제 해결 → **뮤텍스, 세마포어 동기화**

---

#### 🔹 Graphics & Rendering
- **so_long** – MiniLibX 기반 2D 게임 → **이벤트 루프, 충돌 판정**  
- **[cub3d](https://github.com/DawnteaStudio/Cub3d)** – Raycasting 기반 3D 렌더링 → **저수준 그래픽스 엔진**

---

#### 🔹 Advanced C++
- **CPP Modules (00~09)** – 객체지향 심화 학습 → **상속, 다형성, 템플릿, 스마트 포인터**

---

#### 🔹 Network & System
- **ft_irc** – IRC 프로토콜 채팅 서버 → **소켓 프로그래밍, 비동기 네트워크 처리**

---

### 🔹 DevOps & Infra
- **Inception** – Docker Compose 기반으로 Nginx, WordPress, MariaDB 컨테이너화  
  → **컨테이너 오케스트레이션, 볼륨 관리, 네트워크 구성 경험**


#### 🔹 Final Fullstack Project
- **ft_transcendence** – Fastify + TypeScript + SQLite  
  - 실시간 **웹소켓 기반 Ping-Pong 게임** 구현  
  - **Google OAuth + 2FA 인증**  
  - Prisma ORM + TypeBox로 **타입 안정성과 데이터 정합성 확보**  
  - Docker 기반 컨테이너 환경 → **배포 자동화**

---

#### ✅ Highlights
- **저수준 시스템 프로그래밍** (C, POSIX API, 동기화)  
- **알고리즘 최적화** (push_swap, Exam Rank)  
- **운영체제/보안 기초** (Born2beroot, minishell)  
- **그래픽스 렌더링** (so_long, cub3d, fract-ol)  
- **네트워크 서버 구현** (ft_irc)  
- **풀스택 서비스 구축** (ft_transcendence)
- **동료평가 및 Master-Mind 칭호**  
  🔗 [42 과제 모음](https://github.com/DawnteaStudio/42cursus)

---

## 🛠 Tech Stack

### Frontend

<p>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/🟩Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" />
</p>

### Backend

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=flat&logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=Prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat&logo=firebase&logoColor=white" />
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
</p>

### Database

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" />
  <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white" />
</p>

### DevOps & Infra

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazon-ec2&logoColor=white" />
  <img src="https://img.shields.io/badge/VirtualBox-183A61?style=flat&logo=virtualbox&logoColor=white" />
  <img alt="Docker Compose" src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat&logo=docker&logoColor=white" />
  <img alt="Amazon S3" src="https://img.shields.io/badge/Amazon%20S3-569A31?style=flat&logo=amazons3&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white" />
</p>

### Tools & Others

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white" />
  <img src="https://img.shields.io/badge/Makefile-000000?style=flat&logo=cmake&logoColor=white" />
  <img src="https://img.shields.io/badge/Shell%20Script-4EAA25?style=flat&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=json-web-tokens&logoColor=white" />
  <img alt="OpenAPI" src="https://img.shields.io/badge/OpenAPI-6BA539?style=flat&logo=openapiinitiative&logoColor=white" />
  <img alt="Swagger" src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=white" />
</p>

---

## 📚 Studying Now

<p>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white" />
</p>

---

## 🧩 Languages

<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" />
  <img alt="SQL" src="https://img.shields.io/badge/SQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
</p>

---

## 📜 Certifications

* **TOPCIT Level 4 (문제해결형, 705/1,000)** – 2026.10 평가, 2026.11 발급  
* **SQLD (SQL Developer)** – 2025.04
* **PCCP Level 2 (C++)** – 2024.11
* **정보처리기사** – 2024.09
* **한국사능력검정 1급** – 2017.06
* **워드프로세서** – 2008.04
* **삼성 SW역량 평가 A+** – SSAFY

## 🌍 Language

* **TOEIC Speaking** – Advanced Low (160), 2024.12

---

<a id="problem-solving"></a>

## ✏️ Problem Solving

[![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=krgreenteabro)](https://solved.ac/krgreenteabro)

---

## 📊 GitHub Stats

<div align="center">

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=DawnteaStudio\&layout=compact\&hide=css,html\&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)

[![SW's GitHub stats](https://github-readme-stats.vercel.app/api?username=DawnteaStudio\&show_icons=true\&hide_title=true)](https://github.com/anuraghazra/github-readme-stats)

</div>

---

## 🔗 Links

* [Portfolio](https://dawnteastudio.github.io/portfolio/) / [포트폴리오 소스](https://github.com/DawnteaStudio/portfolio) / [학습 기록](https://github.com/DawnteaStudio/TIL)
* Email: krgreenteabro@gmail.com

---

### 📌 Notes

* 배지는 **Shields.io**와 공개 위젯을 사용합니다.
* `username=DawnteaStudio`는 본인의 GitHub 아이디로 맞춰져 있습니다.
* Solved.ac 및 통계 위젯은 외부 서비스 상황에 따라 로딩이 느릴 수 있습니다.

---

<!-- footer -->

<div align="center">
  Made with ☕ & lots of commits.
</div>
