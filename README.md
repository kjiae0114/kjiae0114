# 안녕하세요, QA 엔지니어 지망생입니다 👋

**개발 경험으로 시스템의 구조와 동작을 이해하고, 제조업 품질검사 경험으로 기준에 따라 정확하게 검증하는 태도를 익혔습니다.**
이 두 경험을 이어 소프트웨어 품질을 책임지는 QA 엔지니어를 목표로 합니다.

*Aspiring QA engineer with web development and manufacturing quality-inspection experience — I understand how systems work, and I verify them against clear criteria.*

[![Gmail](https://img.shields.io/badge/Gmail-kjiae0114%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kjiae0114@gmail.com)

---

## 🙋 About

| 경험 | 내용 |
|---|---|
| **웹 개발·유지보수** (약 1년 8개월) | Java·JSP·PHP 기반 웹 애플리케이션 개발, API 작업과 문서화, DB 조회·관리, 로그 기반 장애 대응, 크로스브라우징·웹 접근성 작업<br>GS인증 LMS의 **테스트 케이스 180개 이상 작성**·QA 보조, PHP/MySQL 응답 시간 **약 70초 → 800ms** 개선 |
| **제조업 품질검사** | 화장품 외관검사, 반도체 기능검사 — 검사 기준에 따른 정상·불량 판정과 결과 보고 |

개발 경험 덕분에 화면 오류가 서버 문제인지 구분하고, API 요청·응답과 DB 정합성, 로그로 원인을 추적해 **결함 재현 조건을 구체적으로 설명**할 수 있습니다.

---

## 🛠 Tech Stack

**Test** &nbsp;
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Locust](https://img.shields.io/badge/Locust-4CAF50?style=flat-square&logoColor=white)

**Language / Backend** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**실무 개발 경험** &nbsp;
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-E76F00?style=flat-square&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-B7202E?style=flat-square&logoColor=white)
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black)
![eGovFrame](https://img.shields.io/badge/eGovFrame-1F6FB2?style=flat-square&logoColor=white)

**CI / Tools** &nbsp;
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📌 Projects

| 프로젝트 | 설명 |
|---|---|
| **QA SHOP · QA_Portfolio** <br>🔒 비공개 — 요청 시 공유 | 직접 만든 가상 패션 쇼핑몰(FastAPI)을 대상으로 **요구사항 → 시나리오 → TC → 자동화 → 결함관리**까지 QA 전 과정을 수행. pytest·Playwright·Locust로 API·E2E·동시성·부하를 검증하고, GitHub Actions가 PR마다 전체 테스트를 실행합니다. |
| **[LONG RUN](https://github.com/kjiae0114/longrun)** | 생산성 극대화가 아니라 **오래 지속하며 일하기(장기근속)** 를 돕는 앱. HP·ENERGY·CONTROL·STRESS로 자기 상태를 돌아보게 하되, AI가 대신 결정하지 않고 한 화면에서 하나의 판단만 하도록 설계했습니다. |
| **[desktop-mcp](https://github.com/kjiae0114/desktop-mcp)** | 로컬 무료 모델(Ollama)이 Git 워크트리에서 코드를 고치고, **네트워크가 끊긴 Docker 안에서 전체 테스트를 통과할 때만** 별도 브랜치에 커밋하는 코딩 에이전트 + Claude용 화면 제어 MCP 서버. 약 280개 pytest 테스트. |

---

## 🔍 QA Focus

- **테스트 설계와 추적성** — 요구사항부터 TC, 실행 결과, 요약 보고서까지 이어서 추적합니다. TC와 자동화 코드는 `@pytest.mark.tc("TC-ID")` 마커로 연결됩니다.
- **테스트 자동화** (개인 프로젝트에서 학습 중) — API는 pytest + httpx, UI·E2E는 Playwright, 동시성·부하는 스레드 요청과 Locust로 검증합니다.
- **CI** — 푸시와 PR마다 GitHub Actions에서 전체 테스트를 실행하고, JUnit XML과 결과 문서를 아티팩트로 남깁니다.
- **결함 관리** — 발견한 결함의 재현 절차, 원인, 조치를 기록하고 회귀 테스트로 다시 확인합니다.
- **"결과로 판정한다"** — 모델이든 사람이든 "됐다"는 말보다 테스트 결과를 기준으로 판단합니다.

---

## 💭 QA를 이렇게 생각합니다

- 품질은 테스트 단계에서만 만들어지지 않습니다. **요구사항 정의부터 개발, 검증, 배포·운영까지** 전체 과정에서 관리되어야 합니다.
- 테스트를 많이 하는 것보다 **무엇을 왜 검증해야 하는지 이해하고, 결과를 명확하게 설명하는 것**이 중요하다고 생각합니다.
- 완벽함보다 **지속적인 개선**을, 말보다 **눈에 보이는 결과물**을 추구합니다.

---

## 🧭 Career Direction

| 단계 | 방향 |
|---|---|
| **지금** | QA Engineer — 요구사항 분석, 테스트 설계, 기능·API·DB 검증, 결함 관리 |
| **다음** | Quality Engineering — 테스트 자동화, 성능 테스트, 품질 프로세스 개선 |
| **장기** | HCI — UX, 정보 구조(IA), 웹 접근성, 사용성 연구. 사람이 디지털 서비스를 정확하고 편리하게 쓰도록 만드는 일 |

**준비 중인 자격증** · 컴퓨터활용능력 1급(진행 중) → SQLD → ISTQB CTFL

`QA Engineer` · `Quality Engineering` · `Software Testing` · `HCI` · `UX Research` · `Information Architecture` · `Accessibility` · `Sustainable Career`

<!--
## 📊 GitHub Stats (선택)
아래 주석을 풀면 통계 카드가 표시됩니다. 공용 서버라 가끔 이미지가 안 뜰 수 있습니다.
비공개 저장소 활동은 집계되지 않습니다.

![stats](https://github-readme-stats.vercel.app/api?username=kjiae0114&show_icons=true&hide_border=true)
![top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kjiae0114&layout=compact&hide_border=true)
-->
