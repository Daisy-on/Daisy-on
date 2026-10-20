<div align="center">

# Yi Wang

Frontend-focused full-stack developer building local-first applications and practical AI features.

[![GitHub followers](https://img.shields.io/github/followers/Daisy-on?style=flat-square&label=Followers)](https://github.com/Daisy-on?tab=followers)
[![Focus](https://img.shields.io/badge/Focus-Frontend%20%26%20Full%20Stack-2563EB?style=flat-square)](#featured-work)

</div>

## About

I build web applications with a focus on editing experiences, reliable data flows, and responsive interfaces. I enjoy following a feature from its UI through the API and database, then checking how it behaves in real use.

- **Frontend:** React, TypeScript, Vue 3, Zustand, and Pinia.
- **Backend:** Python with FastAPI, Java with Spring Boot, PostgreSQL, and MySQL.
- **Current interests:** rich-text editors, local-first storage and sync, browser-side AI, tool calling, and RAG.
- **Working style:** read the code, reproduce the problem, make a focused change, and verify the result. I use AI coding tools as part of that process.

## Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vuedotjs&logoColor=4FC08D)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## Featured Work

| Project | Direction | What it shows |
| --- | --- | --- |
| [Duet - Frontend](https://github.com/Daisy-on/duet-doc-app) | Local-first AI document editor | Tiptap / ProseMirror customization, IndexedDB persistence, inline AI suggestions, citation navigation, and virtualized chat. |
| [Duet - Backend](https://github.com/Daisy-on/duet-doc-backend) | FastAPI, PostgreSQL, and pgvector | Incremental sync with revision checks, streaming model responses, image-description indexing, and knowledge retrieval. |
| [Xinqing Map](https://github.com/Daisy-on/xinqing_map) | Campus mood map and social application | Vue 3 and TypeScript interfaces for map-based content, mood tracking, charts, and social interactions. |
| [Jikeyuan](https://github.com/Daisy-on/jikeyuan) | React forum project | Component-based frontend development and forum page interactions. |

### Duet: From Writing to Knowledge Retrieval

Duet is my independently developed document editor for personal knowledge management. It combines local editing and persistence with optional cloud sync and AI assistance.

- **Editing:** local image nodes, syntax-highlighted code blocks, outline navigation, and inline completion previews that stay out of the document until accepted.
- **Data reliability:** document and image storage are separate; local changes and sync tasks are saved together, with version history and explicit conflict handling.
- **Browser-side AI:** Transformers.js runs completion and embedding models in Web Workers with WebGPU acceleration, model caching, and runtime switching.
- **Grounded answers:** tool-driven retrieval combines local BM25 and vector search with cloud text and image-description search, and links answers back to their sources.
- **Performance:** batched streaming updates, incremental Markdown rendering, and dynamically measured virtual lists for long conversations.

[Explore the frontend](https://github.com/Daisy-on/duet-doc-app) · [Explore the backend](https://github.com/Daisy-on/duet-doc-backend)

## Current Focus

1. Building useful interfaces with clear interactions and predictable state.
2. Making offline edits, version history, and cloud sync work together reliably.
3. Integrating browser-side models and cloud APIs into everyday writing workflows.
4. Measuring retrieval quality and frontend performance, including the limits of each test.

## How I Think About Projects

For each project, I want the code and documentation to explain:

- What problem does it solve, and who is it for?
- How does the main flow work across the UI, API, and storage?
- What happens when a request fails, data changes, or a user interrupts an operation?
- How can another developer run it and verify its behavior?
- What trade-offs remain, and what would I improve next?

## GitHub Activity

[Repositories](https://github.com/Daisy-on?tab=repositories) · [Contributions](https://github.com/Daisy-on?tab=overview) · [Starred projects](https://github.com/Daisy-on?tab=stars)
