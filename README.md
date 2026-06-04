<div align="center">

# Jaemin Seo

**Backend-first full-stack developer focused on AI automation, RAG, and operational product systems.**

불필요한 반복 업무를 줄이고, 실제 운영 가능한 도구로 바꾸는 일을 좋아합니다.

<a href="mailto:jeamin5678@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/Email-jeamin5678%40gmail.com-1f6feb?style=flat-square&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/misosiruda">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-misosiruda-24292f?style=flat-square&logo=github&logoColor=white" />
</a>
<img alt="Focus" src="https://img.shields.io/badge/Focus-AI%20Automation%20%7C%20FastAPI%20%7C%20Next.js-0f766e?style=flat-square" />

</div>

---

## What I Build

Java/Spring 기반 웹 서비스와 DB 중심 업무 시스템에서 시작해, 지금은 FastAPI와 Next.js 기반의 AI 자동화, RAG, 운영 도구, 도메인 워크플로를 구현하고 있습니다.

- AI/RAG 기능을 단순 챗봇이 아니라 데이터 검증, 응답 정책, 실패 처리까지 포함한 서비스 흐름으로 설계합니다.
- FastAPI, PostgreSQL, Alembic, Celery, Redis를 사용해 백엔드 계약과 운영 흐름을 정리합니다.
- Next.js, React, TypeScript로 견적, 상담, 결제, 관리자 화면 같은 실제 업무 UI를 구현합니다.
- 반복되는 검증, 배포, 문서화 작업은 스크립트와 GitHub Actions로 자동화합니다.

## Current Focus

| Area | Working on |
| --- | --- |
| AI systems | RAG 검색 품질, Gemini/OpenAI 연동, 응답 guardrail, 미확정 데이터 차단 |
| Backend | FastAPI, SQLAlchemy/SQLModel, PostgreSQL, Alembic, pytest 기반 API 구현 |
| Frontend | Next.js App Router, React, TypeScript, Tailwind CSS, route 기반 UX/IA |
| Operations | Docker, GitHub Actions, 로그 추적, 배포 전 검증, 회귀 테스트 |
| Documentation | Typst, 릴리스 노트, reviewer guide, 재현 가능한 문서 빌드 |

## Selected Public Work

<table>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/misosiruda/eazy-chorus">eazy-chorus</a></h3>
      <p>백엔드 없이 동작하는 프론트엔드 전용 화음 가이드 웹앱입니다. 커스텀 <code>.eazychorus</code> 파일 포맷, 샘플 프로젝트, GitHub Pages 배포, Vitest 검증 흐름을 갖췄습니다.</p>
      <p><code>TypeScript</code> <code>React</code> <code>Vite</code> <code>Vitest</code></p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/misosiruda/jaemin-cosmology">jaemin-cosmology</a></h3>
      <p>한국어 working paper 원고 저장소입니다. Typst 원고, DOI/CITATION 메타데이터, 리뷰어 가이드, 릴리스 체크리스트, CI 기반 문서 빌드 흐름을 정리했습니다.</p>
      <p><code>Typst</code> <code>TeX</code> <code>Makefile</code> <code>GitHub Actions</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/misosiruda/oh_my_car">oh_my_car</a></h3>
      <p>자동차 관리 웹 서비스입니다. 회원/관리자 권한, 차량 부품 교체 주기, 게시판, 지도/위치 API, 관리자 콘텐츠 관리 등 Java 웹 서비스의 기본기를 구현했습니다.</p>
      <p><code>Java</code> <code>Spring</code> <code>Spring Security</code> <code>MyBatis</code> <code>Oracle</code></p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/misosiruda/CordingTest">CordingTest</a></h3>
      <p>BaekjoonHub 기반 알고리즘 풀이 저장소입니다. Java 중심으로 여러 언어를 사용하며 문제 해결 연습을 기록했습니다.</p>
      <p><code>Java</code> <code>Python</code> <code>C++</code> <code>JavaScript</code></p>
    </td>
  </tr>
</table>

## Recent Product Work

공개 저장소로 링크하기 어려운 프로젝트는 세부 내부 정보를 제외하고 기술 책임 중심으로만 정리합니다.

- **AI 기반 도메인 상담/견적 플랫폼**: FastAPI와 Next.js로 견적 플로우, 상담 신청, FAQ/RAG 챗봇 UI, 미확정 데이터 guardrail, seed import, 내부 검수 API를 구현했습니다.
- **콘텐츠·결제·관리자 운영 플랫폼**: reader/editor, 결제 예외 처리, 관리자 입금 화면, 회원 혜택 백필, 회귀 테스트를 다뤘습니다.
- **AI 기업 매칭/비서 시스템**: Spring AI와 FastAPI 기반으로 OpenAI, pgvector, PostgreSQL, Redis를 사용한 B2B 매칭/RAG 흐름을 구현했습니다.
- **OCR 기반 태권도 업무 시스템**: FastAPI, SQLModel, Next.js, Celery를 사용해 단증 OCR, 도장/학생 관리, 대회 신청 플로우를 설계했습니다.
- **견적서 DB 관리 시스템**: Spring Boot, JPA, PostgreSQL 기반으로 견적서 CRUD, 품목명 동의어 사전, 검색/필터링을 구현했습니다.
- **Next.js FSD 프론트엔드**: 바우처/포인트/회원 흐름, TanStack Query, React Hook Form, Zod, Zustand, Storybook, Playwright 기반 UI 검증을 다뤘습니다.

## Tech Stack

<div align="center">

### Core

![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=111827)
![Java](https://img.shields.io/badge/Java-21-b07219?style=for-the-badge)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

### Data & Ops

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

</div>

## Path So Far

```text
2024  Java/Spring, JSP/Thymeleaf, Spring Security, Oracle 기반 웹 서비스 구현
2025  Spring AI, pgvector, Redis, Docker/Nginx, Next.js 기반 AI/업무 플랫폼 확장
2026  FastAPI + Next.js 제품 워크플로, RAG guardrail, 운영/테스트/문서 자동화 집중
```

## GitHub Snapshot

| Signal | Snapshot |
| --- | --- |
| Public work | TypeScript product app, Typst manuscript workflow, Java/Spring web service, algorithm practice |
| Recent stack | FastAPI, Next.js, React, PostgreSQL, Redis, Docker, GitHub Actions |
| 2026 direction | RAG guardrails, estimate workflows, AI operations tooling, test-backed UI/API contracts |
| Earlier foundation | Java/Spring MVC, Spring Security, MyBatis/JPA, Oracle/PostgreSQL, JSP/Thymeleaf |

## Contribution Graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/misosiruda/misosiruda/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)" srcset="https://raw.githubusercontent.com/misosiruda/misosiruda/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/misosiruda/misosiruda/output/github-contribution-grid-snake.svg" />
</picture>

---

<div align="center">

> 비효율을 줄이고, 사람에게 집중할 수 있는 시스템을 만든다.

</div>
