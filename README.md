<div align="center">

<img src="images/11hz_logo.png" width="154" alt="11Hz">

# Hi, I'm Eleven-Hz 👋

**Data Engineer & AI Developer**<br>
DBA에서 출발해 데이터 엔지니어링을 거쳐, 지금은 LLM으로 "직접 써 보고 싶은 도구"를 만들고 있습니다.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Eleven-Hz)
[![Steam](https://img.shields.io/badge/Steam-000000?style=flat-square&logo=steam&logoColor=white)](https://steamcommunity.com/id/11Hz/)

</div>

---

## 💼 Career

| Stage | What I did | Stack |
|---|---|---|
| **DBA** | 주요 RDBMS 운영 및 성능 최적화 | ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Data Engineer** | 빅데이터 파이프라인 구축·운영 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) |
| **Data Warehouse** | DW 환경 설계·운영 | ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) |

## 🧰 Tech Stack

**Backend & Data** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)

**Frontend & Desktop** &nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PyQt](https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white)

**AI** &nbsp;
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

---

## 🛠️ Projects

### 🎙️ [Solo Stream](https://github.com/Eleven-Hz/solo_stream) &nbsp;<sub>2026.04 – 현재</sub>

> 혼자 게임할 때, 진짜 스트리머처럼 — AI 시청자들이 내 화면과 혼잣말에 실시간으로 채팅하는 오버레이

- 22종의 페르소나 봇이 **게임 화면(Vision)과 음성(STT)** 을 보고 들으며 상황에 맞게 반응
- `silero-vad` 기반 발화 구간 검출, 도배·복붙 필터로 채팅 다양성 유지
- Gemini / OpenAI / Claude 멀티 프로바이더, 단일 실행파일 배포 (GitHub Releases)

`Python` `PyQt6` `Gemini` `OpenAI` `Claude` `silero-vad` `PyInstaller`

### 📖 PromptDex &nbsp;<sub>2026.07</sub>

> AI 이미지 생성 프롬프트를 모아 두는 오프라인 사전

- 용어 사전 + **FTS5 통합 검색**, 궁합·상충 용어 관계 그래프
- ComfyUI / A1111 PNG를 끌어다 놓으면 **프롬프트·시드·LoRA 자동 추출**
- 로컬 LLM(Ollama)으로 용어 설명 자동 채우기, 100% 로컬 데이터 · 단일 exe · 앱 내 업데이트

`Python` `NiceGUI` `SQLite(FTS5)` `Ollama` `PyInstaller`

### 🎮 The Gamer's Compass — 하이브리드 벡터 검색 게임 추천 RAG &nbsp;<sub>2025.04 – 2025.07</sub>

> 17만 개 이상의 Steam 게임 데이터를 기반으로 한 개인화 추천 서비스

- Steam 데이터 수집·품질 필터링 → SBERT/TF-IDF 다차원 임베딩 → Qdrant 하이브리드 검색
- Gemini 기반 추천 이유 생성, 사용자 Steam 라이브러리·플레이 패턴 분석
- **평균 47ms 벡터 검색**, 99.7% 시스템 안정성, 94.7% 구조화 응답률

`Python` `FastAPI` `Qdrant` `PyTorch` `Next.js` `TypeScript` `Gemini`

### 🧪 Chemical Synonyms Finder &nbsp;<sub>2025.07 – 2025.08</sub>

> 동의어 매칭으로 화학물질명에서 CAS 번호를 찾는 검색 시스템

- PubChem REST API로 동의어 자동 수집, 서로 다른 명명 규칙 간 검색
- Gemini로 복잡한 화학물질명 대용량 CSV 배치 정제 (백그라운드 처리 + 실시간 진행률)
- 정제 프롬프트 성능을 비교하는 웹 기반 프롬프트 테스트 도구

`Python` `FastAPI` `SQLite` `Gemini` `PubChem API`

<details>
<summary><b>🔬 Side Projects & Labs</b></summary>

<br>

| Project | Description | Stack |
|---|---|---|
| **Project NS** | 채팅을 읽고 판단하고 말하는 AI 스트리머 파이프라인 (Solo Stream의 역구조) | Python, LLM, TTS |
| **CrossCode Modding** | 최애 게임 CrossCode 모드 제작 + React 기반 맵·데이터 통합 모딩 툴 | JavaScript, React, TypeScript |
| **AI Usage Monitor** | Claude / Codex 구독 사용량·리셋 시각을 바탕화면·트레이에 표시 | Rainmeter, Lua, C# WinForms |
| **Lite Video Upscaler** | Real-ESRGAN + ffmpeg 기반 비디오 업스케일 데스크톱 앱 | Python, PyQt6 |

</details>

---

## 🎮 Gamer Profile

30년 차 게이머. 오픈월드를 돌아다니며 탐험하는 것과 픽셀 아트를 특히 좋아합니다.<br>
게임을 좋아하는 마음이 게임 추천 시스템, 스트리밍 도구, 모딩 같은 프로젝트로 이어지고 있습니다.

**All-time favorite** — [CrossCode](https://store.steampowered.com/app/368340/CrossCode/): 깊이 있는 스토리, 퍼즐, 독특한 전투를 갖춘 픽셀 아트 액션 RPG

[![CrossCode](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/368340/capsule_231x87.jpg)](https://store.steampowered.com/app/368340/CrossCode/)
