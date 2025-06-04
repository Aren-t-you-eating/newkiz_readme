# 📰뉴키즈(NewKiz)
![main](exec/main.png)
---
## 📚 목차 (Table of Contents)

- [🧭 프로젝트 소개](#-프로젝트-소개)
- [🔄 사용자 플로우](#-사용자-플로우)
- [🎯 주요 화면 및 기능 소개 ](#-주요-화면-및-기능-소개)
- [📘 ERD](#-erd)
- [📦 아키텍처 요약](#-아키텍처-요약)
- [🛠 사용된 기술 스택](#-사용된-기술-스택)
- [👥 팀 구성](#-팀-구성)

---

## 🧭 프로젝트 소개

> 서비스 명: AI 어린이 뉴스 플랫폼 </br>
> 기간: 2025.03.04 ~ 2025.04.11


### 💡 기획의도
- 요즘 아이들은 문장을 이해하고 해석하는 문해력이 낮습니다.
- 아이들은 뉴스가 어렵고 복잡하다고 느껴 사회 문제에도 관심이 적습니다.
- **뉴키즈는**  다양한 난이도의 뉴스 읽기와 퀴즈, 게임 요소 및 AI 요약 기능을 제공해 문해력과 사회적 이해를 높이는 뉴스 플랫폼입니다. 

---

## 🔄 사용자 플로우


1. **난이도 설정 및 캐릭터 선택**
2. **뉴스 읽고 퀴즈 풀기**
3. **뉴스 읽고 뉴스 요약**
4. **퀴즈 대결 참여**
5. **나만의 뉴스 작성**

---

## 🎯 주요 화면 및 기능 소개
### 메인 화면 
![메인화면](exec/scenario/recommendation.gif)
- 🗞️ **오늘의 주요 뉴스 10개 추천**
- 🎯 **사용자 설정 카테고리별 맞춤 뉴스 추천**
</br>

### 뉴스 화면 
![뉴스 상세](exec/scenario/difficulty.gif)
- ✍️ **난이도별 기사 내용 제공**

</br>

<div style="display: flex; gap: 16px;">
  <img src="exec/scenario/quiz.gif" alt="뉴스 맞춤 객관식 퀴즈" width="200"/>
  <img src="exec/scenario/summary.gif" alt="뉴스 요약" width="200"/>
  <img src="exec/scenario/chatbot.gif" alt="챗봇" width="200"/>
</div>

- 🧠 **사용자 요약 vs AI 요약 비교** </br>
- 🖊 **객관식 퀴즈로 이해도 점검**</br>
- 🔍 **읽은 기사와 관련된 유사 뉴스 자동 추천**</br>
- 🤖 **모르는 단어/용어 뜻을 알려주는 챗봇**
</br>

### 게임 화면
![게임](exec/scenario/game.gif)

- 🎮 **게임**

### 기자단 화면
![기자단](exec/scenario/reporter.gif)

- 📝 **기사 작성 및 커뮤니티 소통 기능**

---

## 📘 ERD
![ERD](exec/ERD.png)

---

## 📦 아키텍처 요약

![Architecture](exec/Architecture.png)

---

## 🛠 사용된 기술 스택

### 🖥️ Frontend
[![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)](https://redux.js.org/)
[![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat&logo=react-query&logoColor=white)](https://tanstack.com/query/)

### 🛠 Backend
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)](https://redis.io/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)](https://openai.com/)

### ⚙ DevOps & Infra
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![WebSocket](https://img.shields.io/badge/WebSocket-008080?style=flat)](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)](https://nginx.org/)

---
## 👥 팀 구성

<table>
  <tbody>
    <tr align="center">
      <td><img src="https://avatars.githubusercontent.com/u/113484236?v=4" width="100px;" style="border-radius: 50%;" alt=""/><br /></td>
      <td><img src="https://avatars.githubusercontent.com/u/108385400?v=4" width="100px;" style="border-radius: 50%;" alt=""/><br /></td>
      <td><img src="https://avatars.githubusercontent.com/u/105963431?v=4" width="100px;" style="border-radius: 50%;" alt=""/><br /></td>
      <td><img src="https://avatars.githubusercontent.com/u/175383118?v=4" width="100px;" style="border-radius: 50%;" alt=""/><br /></td>
      <td><img src="https://avatars.githubusercontent.com/u/145769307?v=4" width="100px;" style="border-radius: 50%;" alt=""/><br /></td>
      <td><img src="https://avatars.githubusercontent.com/u/105963431?v=4" width="100px;" style="border-radius: 50%;" alt=""/><br /></td>
    </tr>
    <tr align="center">
      <td width="200"><a href="http://github.com/haazz">팀장 : 하지원<br/>BE/AI</a></td>
      <td width="200"><a href="http://github.com/jjoonior">팀원 : 허인주<br/>BE/Infra</a></td>
      <td width="200"><a href="https://github.com/">팀원 : 고태연<br/>FE</a></td>
      <td width="200"><a href="https://github.com/kangansoo">팀원 : 강안수<br/>FE</a></td>
      <td width="200"><a href="https://github.com/arnold714">팀원 : 박재형<br/>BE</a></td>
      <td width="200"><a href="https://github.com/newww-a">팀원 : 신승아<br/>FE</a></td>
    </tr>
    
  </tbody>
</table>
