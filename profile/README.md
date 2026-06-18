<div align="center">

# 창업할지도 (ChangUp)

### 서울 개인·로컬 카페를 위한 상권 비교 진단 & AI 운영 전략 추천 서비스

매출을 "예측"하는 것이 아니라, 서울시 공공 상권 데이터의 지역 평균과 내 매장을 비교해<br/>
**지금 어디에 서 있는지**를 진단하고, AI로 실행 가능한 운영 전략을 제안합니다.

조선대학교 캡스톤(산학) 프로젝트

<a href="https://youtu.be/yjHWuMHYMto">🎬 데모 영상</a>
&nbsp; | &nbsp;
<a href="https://github.com/Chosun-univ-changup/changup-backend">Backend</a>
&nbsp; | &nbsp;
<a href="https://github.com/Chosun-univ-changup/changup-frontend">Frontend</a>

</div>

<br/>

<div align="center">
  <a href="https://youtu.be/yjHWuMHYMto">
    <img src="https://img.youtube.com/vi/yjHWuMHYMto/maxresdefault.jpg" alt="창업할지도 시연 영상" width="720"/>
  </a>
  <p><sub>▶️ 썸네일을 클릭하면 YouTube 시연 영상으로 이동합니다.</sub></p>
</div>

---

## ✍️ 프로젝트 개요

- **프로젝트명:** 창업할지도 (ChangUp)
- **프로젝트 형태:** 조선대학교 캡스톤(산학) 프로젝트
- **프로젝트 기간:** 2026.03 ~ 2026.06
- **대상 사용자:** 서울 개인·로컬 카페 — 기존 점포 사장(OWNER) / 예비 창업자(FOUNDER)
- **핵심 가치:** 매출 예측이 아닌 **상권 평균 대비 비교 진단** + AI 운영 전략 추천

대부분의 상권 분석이 "이 자리 월 매출 얼마"를 맞히려 한다면, 창업할지도는 **"내 매장이 주변 평균 대비 어디에 있고, 내 의도와 상권이 정렬돼 있는가"** 를 보여주는 의사결정 지원 서비스입니다. 데이터는 서울시 열린데이터광장의 상권 단위 공공 통계와 사용자 매장 운영 정보를 융합해 사용합니다.

---

## 📌 주요 기능

- **3축 카페 진단** — 포지셔닝(오피스 타깃 / 카공족 / 인스타 감성) · 상권 프로파일 4종 · 진단 플래그 8종을 **상권 평균 대비**로 자동 분류
- **갭 진단** — 기존 점포 사장은 "의도 ↔ 실제 ↔ 상권" 3중 갭, 예비 창업자는 "의도 ↔ 상권" 매칭 점수 산출
- **AI 운영 전략 추천** — 지표·진단 결과 기반의 카페 컨설턴트 톤 전략 (대시보드 요약 + 섹션별 심층)
- **결과 저장·조회 & 자연어 Q&A** — 분석 이력 관리 + 분석 결과에 대한 추가 질의응답

<!-- (권장) 기능별 스크린샷/GIF 를 .github/assets/ 에 추가한 뒤 아래처럼 삽입하면 완성도가 올라갑니다 -->
<!-- <div align="center"><img src="./assets/dashboard.png" width="720"/></div> -->

---

## 🧩 레포지토리

| 레포 | 설명 |
|---|---|
| [changup-backend](https://github.com/Chosun-univ-changup/changup-backend) | 데이터 수집·융합, 지표 분석, AI 추천, 인증·저장 (FastAPI + Spring Boot) |
| [changup-frontend](https://github.com/Chosun-univ-changup/changup-frontend) | 웹 클라이언트 — 입력 → 진단 → 전략 → Q&A (React) |

---

## ⚙️ 기술 스택

<table>
  <tbody>
    <tr>
      <td><b>프론트엔드</b></td>
      <td>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white"/>
        <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td><b>분석 · AI</b></td>
      <td>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td><b>인증 · 저장</b></td>
      <td>
        <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white"/>
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white"/>
        <img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td><b>데이터베이스</b></td>
      <td>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td><b>인프라</b></td>
      <td>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
        <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white"/>
        <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white"/>
      </td>
    </tr>
  </tbody>
</table>

---

## 🧑‍💻 팀

<table>
  <thead>
    <tr>
      <th>이름</th>
      <th>역할</th>
      <th>GitHub</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>김문영</td>
      <td>팀장 & FE</td>
      <td><a href="https://github.com/KimMunyoung">@KimMunyoung</a></td>
    </tr>
    <tr>
      <td>김도연</td>
      <td>FE / UI</td>
      <td><a href="https://github.com/d0ye0n">@d0ye0n</a></td>
    </tr>
    <tr>
      <td>유다희</td>
      <td>BE / Data</td>
      <td><a href="https://github.com/dahee17">@dahee17</a></td>
    </tr>
    <tr>
      <td>임휘훈</td>
      <td>BE / AI</td>
      <td><a href="https://github.com/iimmuunnee">@iimmuunnee</a></td>
    </tr>
    <tr>
      <td>백지혜</td>
      <td>BE / Infra</td>
      <td><a href="https://github.com/zye1oo">@zye1oo</a></td>
    </tr>
  </tbody>
</table>
