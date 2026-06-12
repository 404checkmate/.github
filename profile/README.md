<div align="center">

<img src="https://avatars.githubusercontent.com/u/275568950?s=400&u=fb26e17e18bb6c9aaa44277cbe910638e3922cf9&v=4" width="170" alt="CHECKMATE logo" />

# ♟️ CHECKMATE

### 준비는 쉽게, 여행은 완벽하게
**Travel prep made simple, trips made perfect.**

해외여행 준비물을 한 곳에서, AI 맞춤 체크리스트로 끝내는 여행 준비 플랫폼
*An AI-powered checklist platform that turns scattered travel-prep into one tailored list.*

<br/>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-checkmate--v.com-3DB4DD?style=for-the-badge)](https://checkmate-v.com)
[![Frontend](https://img.shields.io/badge/Frontend-Repo-FBBF24?style=for-the-badge&logo=github&logoColor=white)](https://github.com/404checkmate/Checkmate-Frontend)
[![Backend](https://img.shields.io/badge/Backend-Repo-04384A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/404checkmate/checkmate-backend)

<br/>

`React 19` · `NestJS 11` · `OpenAI gpt-4o-mini` · `Supabase` · `AWS EC2` · `Vercel`

</div>

---

## 📑 목차 · Table of Contents
- [서비스 소개 · Overview](#-서비스-소개--overview)
- [핵심 기능 · Features](#-핵심-기능--features)
- [기술 스택 · Tech Stack](#-기술-스택--tech-stack)
- [시스템 아키텍처 · Architecture](#-시스템-아키텍처--architecture)
- [레포지토리 · Repositories](#-레포지토리--repositories)
- [팀 404 · Team](#-팀-404--team)
- [프로젝트 방식 · How We Worked](#-프로젝트-방식--how-we-worked)

---

## 🧭 서비스 소개 · Overview

**🇰🇷** 여행 준비의 진짜 문제는 정보 부족이 아니라, *저장한 정보가 실제 짐 싸기로 이어지지 않는 단절*이었습니다. CHECKMATE는 여행 국가·날짜·동행·스타일만 입력하면 AI가 맞춤 체크리스트를 생성하고, 저장부터 실제 준비까지 한 흐름으로 연결합니다.

**🇺🇸** The real problem in travel prep isn't a lack of information — it's the *gap between saving info and actually packing*. CHECKMATE generates a tailored checklist from just your destination, dates, companions, and style, then connects saving all the way through to real preparation.

> 이름 그대로, 여행을 완성하는 **마지막 한 수(Checkmate)** 가 되고자 합니다.
> *Like the chess term, we aim to be the final move that completes your trip.*

---

## ✨ 핵심 기능 · Features

| 기능 · Feature | 설명 · Description |
|---|---|
| 🤖 **AI 맞춤 체크리스트**<br/>AI Tailored Checklist | 최소 입력만으로 조건에 맞는 준비물·주의사항을 자동 생성<br/>Auto-generates items & tips from minimal input |
| 📝 **저장 & 편집**<br/>Save & Edit | 9개 카테고리 구조, 항목 추가·삭제·정렬·메모<br/>9-category structure with full editing |
| ✅ **진행도 & 짐 분류**<br/>Progress & Packing | 준비 진행도 시각화, 기내/위탁 수하물 분류<br/>Progress tracking, carry-on/checked split |
| 🎭 **54가지 여행 스타일 테스트**<br/>54 Travel-Style Test | 체스말 6종 × 스타일 9종, 결과 공유로 바이럴<br/>6 chess pieces × 9 styles, shareable results |
| 👥 **친구와 공동 체크리스트**<br/>Collaborative Checklist | 초대 링크로 친구와 실시간 공동 편집<br/>Real-time co-editing via invite link |
| 🔓 **게스트 프리뷰**<br/>Guest Preview | 로그인 없이 체크리스트 미리보기, 저장 시점에만 로그인<br/>Preview without login; auth only at save |

<!-- 스크린샷/GIF 추가 권장 위치 · Recommended place for screenshots/GIFs
<div align="center">
  <img src="./assets/demo-1.png" width="30%" />
  <img src="./assets/demo-2.png" width="30%" />
  <img src="./assets/demo-3.png" width="30%" />
</div>
-->

---

## 🛠 기술 스택 · Tech Stack

### Frontend
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router_v7-CA4245?style=flat-square&logo=reactrouter&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

### Backend
![NestJS](https://img.shields.io/badge/NestJS_11-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript_5.7-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_6-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis_7_+_BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_gpt--4o--mini-412991?style=flat-square&logo=openai&logoColor=white)

### Infra · Data · Analytics
![Vercel](https://img.shields.io/badge/Vercel_(FE)-000000?style=flat-square&logo=vercel&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2_(BE)-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase_PostgreSQL-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx_+_PM2-009639?style=flat-square&logo=nginx&logoColor=white)
![Notion](https://img.shields.io/badge/Notion_API_(CMS)-000000?style=flat-square&logo=notion&logoColor=white)
![GA4](https://img.shields.io/badge/Google_Analytics_4-E37400?style=flat-square&logo=googleanalytics&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions_CI/CD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 🏗 시스템 아키텍처 · Architecture

```
[ CLIENT ]                 React 19 SPA (Vercel) · GA4 · Vercel Analytics
    │  HTTPS
    ▼
[ CDN / HOSTING ]          Vercel — Static dist · /api Proxy Rewrite
    │  REST (/api) · Polling
    ▼
[ APP SERVER (AWS EC2) ]   NestJS 11 (:8080) · Nginx · PM2
                           Helmet · Rate Limiter · JWT(jose)
    │            │
    │ jobs       │ calls
    ▼            ▼
[ ASYNC ]     [ EXTERNAL ]   OpenAI (LLM) · Supabase Auth (OAuth) · Notion (CMS)
 BullMQ·Redis
    │
    ▼
[ DATA ]                   Supabase PostgreSQL · Prisma ORM

[ CI/CD ]  GitHub → GitHub Actions → Build → rsync over SSH → deploy.sh → Health Check
```

> **🇰🇷** 토이 프로젝트가 아니라 실제 운영 수준으로 설계했습니다 — CI/CD 자동 배포, 퍼널 이벤트 측정 인프라까지 직접 구축.
> **🇺🇸** Built at production grade, not a toy — including automated CI/CD and a custom funnel-event measurement pipeline.

### 주요 API · Key Endpoints
| Method | Endpoint | 설명 · Description |
|---|---|---|
| `POST` | `/trips` | 여행 정보 생성 · Create trip |
| `POST` | `/checklists/generate/:tripId` | AI 체크리스트 생성 · Generate AI checklist |
| `GET` | `/trips/:tripId/guide-archives` | 저장 아카이브 조회 · List saved archives |
| `PATCH` | `/checklists/items/:itemId` | 항목 편집 · Edit item |
| `POST` | `/analytics/events` | 퍼널 이벤트 수집 · Funnel event collection |

---

## 📦 레포지토리 · Repositories

| Repo | 설명 · Description | Link |
|---|---|---|
| 🎨 **Checkmate-Frontend** | React 19 · Vite SPA (Vercel 배포) | [→ Repo](https://github.com/404checkmate/Checkmate-Frontend) |
| ⚙️ **checkmate-backend** | NestJS 11 · Prisma · Supabase (AWS EC2 배포) | [→ Repo](https://github.com/404checkmate/checkmate-backend) |
| 🌐 **Live Service** | 실서비스 · Production | [→ checkmate-v.com](https://checkmate-v.com) |

각 레포의 README에서 로컬 실행법(`.env.example`, 설치·실행 명령)을 확인하세요.
*See each repo's README for local setup (`.env.example`, install & run commands).*

---

## 👥 팀 404 · Team

> **4기 4팀 · 7인** — 기능이 아니라 '의사결정' 단위로 일한 실험 조직
> *Cohort 4, Team 4 · 7 members — organized by decisions, not just features.*

| 이름 · Name | 역할 · Role |
|---|---|
| **오현석** | 팀장(PL) · 개발/PM · 아키텍처·배포 · Lead / Dev / Architecture |
| **김병호** | 개발 서브리드 · 백엔드/DB · 개발 파이프라인 · Backend / DB |
| **이명화** | 문제 정의 · 전략 · 문서 흐름(PDD·SED·DRD·OKR) · Strategy / Docs |
| **신희도** | 시장 조사 · 발표 · 가설 재정의 · Research / Presentation |
| **유수경** | OKR · 백로그 · 시장 리서치 · OKR / Backlog |
| **박아름** | 디자인 · 브랜딩 · 로고·캐릭터·네이밍 · Design / Branding |
| **조수민** | 콘텐츠 · 홍보 · 채널 전략 · 시연 영상 · Content / Marketing |

---

## 🔁 프로젝트 방식 · How We Worked

**🇰🇷** 기능을 먼저 만들지 않았습니다. **가설을 세우고 → 지표로 검증하고 → 피벗하는** 3-Cycle Lean 프로세스로 약 두 달 반을 운영했습니다.

**🇺🇸** We didn't build features first. We ran a **3-Cycle Lean process** — *hypothesize → validate with metrics → pivot* — over ~2.5 months.

| Cycle | 집중 · Focus | 핵심 결과 · Key Result |
|---|---|---|
| **C1** | 문제 정의 · MVP · 측정 인프라 | 측정 체계 구축, 진입 병목 발견 |
| **C2** | 랜딩 개편 · 채널 다변화 | 진입 전환 **20.2% → 34%**, 유입 4배 |
| **C3** | 여행 테스트 · 게스트 프리뷰 · 공동 편집 | 저장 시도 **4.2% → 15%**, 테스트 완료율 93% |

> Draft Session(초안) → 회의록(결정 기록) → 작업 트래커(실행)의 협업 루프로, "무엇을 안 만들지"까지 기록으로 남겼습니다.
> *Every decision — including what we chose **not** to build — was logged.*

---

<div align="center">

**Team 404 · CHECKMATE · 2026**

지금도 라이브로 데이터를 수집하고 있습니다 · Still collecting live data
[**checkmate-v.com →**](https://checkmate-v.com)

</div>
