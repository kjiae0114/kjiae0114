# 안녕하세요, QA 엔지니어 지망생입니다 👋

직접 서비스를 만들고, 그 서비스를 요구사항부터 결함 관리까지 테스트하는 **개발 경험을 가진 QA 엔지니어**를 목표로 합니다.

*Aspiring QA engineer who builds the system under test, then verifies it end to end — from requirements to automated regression in CI.*

[![Gmail](https://img.shields.io/badge/Gmail-kjiae0114%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kjiae0114@gmail.com)

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

**CI / Tools** &nbsp;
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📌 Projects

| 프로젝트 | 설명 |
|---|---|
| **QA SHOP · QA_Portfolio** <br>🔒 비공개 — 요청 시 공유 | 직접 만든 가상 패션 쇼핑몰(FastAPI)을 대상으로 **요구사항 → 시나리오 → TC → 자동화 → 결함관리**까지 QA 전 과정을 수행. pytest·Playwright·Locust로 API·E2E·동시성·부하를 검증하고, GitHub Actions가 PR마다 전체 테스트를 실행합니다. |
| **[desktop-mcp](https://github.com/kjiae0114/desktop-mcp)** | 로컬 무료 모델(Ollama)이 Git 워크트리에서 코드를 고치고, **네트워크가 끊긴 Docker 안에서 전체 테스트를 통과할 때만** 별도 브랜치에 커밋하는 코딩 에이전트 + Claude용 화면 제어 MCP 서버. 약 280개 pytest 테스트. |

---

## 🔍 QA Focus

- **테스트 설계와 추적성** — 요구사항부터 TC, 실행 결과, 요약 보고서까지 이어서 추적합니다. TC와 자동화 코드는 `@pytest.mark.tc("TC-ID")` 마커로 연결됩니다.
- **테스트 자동화** — API는 pytest + httpx, UI·E2E는 Playwright, 동시성·부하는 스레드 요청과 Locust로 검증합니다.
- **CI** — 푸시와 PR마다 GitHub Actions에서 전체 테스트를 실행하고, JUnit XML과 결과 문서를 아티팩트로 남깁니다.
- **결함 관리** — 발견한 결함의 재현 절차, 원인, 조치를 기록하고 회귀 테스트로 다시 확인합니다.
- **"결과로 판정한다"** — 모델이든 사람이든 "됐다"는 말보다 테스트 결과를 기준으로 판단합니다.

<!--
## 📊 GitHub Stats (선택)
아래 주석을 풀면 통계 카드가 표시됩니다. 공용 서버라 가끔 이미지가 안 뜰 수 있습니다.
비공개 저장소 활동은 집계되지 않습니다.

![stats](https://github-readme-stats.vercel.app/api?username=kjiae0114&show_icons=true&hide_border=true)
![top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kjiae0114&layout=compact&hide_border=true)
-->
