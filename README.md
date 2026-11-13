## 이승욱

고객 현장의 데이터를 AI 에이전트와 시스템으로 연결하는 엔지니어입니다.
조선·해양, 반도체 건설 현장에서 Oracle Primavera Unifier 데이터를 RAG·에이전트·웹앱으로 연결하고 폐쇄망까지 배포합니다.

포트폴리오: https://wookidoki.github.io

### 대표 프로젝트

| 프로젝트 | 내용 | 기술 |
|---|---|---|
| Unifier AI Agent | Unifier 데이터를 자연어로 조회·가공하는 하이브리드 Agentic RAG. 정형 데이터는 REST 툴 콜, 첨부 문서는 벡터·전문 검색(RRF)으로 처리하고, 모호한 지표 요청은 되묻습니다. 프로젝트·BP 단위 권한 반영 | Next.js, Anthropic SDK, PostgreSQL + pgvector, BGE-m3, next-auth |
| [DTS 3D Progress](https://dts-viewer-one.vercel.app) | Unifier AWP 데이터를 플랜트 3D 모델 위에 작업패키지별 진척 히트맵으로 표시. 대시보드, EVM 분석, 폐쇄망용 내부 뷰어, 한·영·일 | Next.js, Three.js, Babylon.js, xeokit |
| 기성 기반 일정 에이전트 | 현장 담당자가 말로 물으면 지연 작업과 후행 영향을 답하는 에이전트. 계산은 EVM·CPM 결정론 엔진, LLM 키 없으면 오프라인 라우터 | Node.js, Anthropic SDK (tool-use), Web Speech |
| 도란 (현대자동차 Pleos 앱 공모전, 진행 중) | 차량용 가족 여행 음성 AI 앱. 호출어로 경로상 장소를 찾아 경유지로 넣고, 정차 지점의 목소리를 3D 지도 앨범으로 남김 | Android, Kotlin, Python, OpenAI API |
| [AI 주식 매매 모델](https://quant-lab-eta.vercel.app) | 10년치 데이터 수집, LightGBM walk-forward 검증, 매일 자동 수집·신호 게시·모의 매매 | Python, LightGBM, FastAPI, Next.js |

### 업무

- B2B 전자조달 플랫폼 풀스택 개발 (개인정보 암호화, N+1 개선, 폐쇄망 3단계 배포)
- Unifier BP 설계, REST API 연동, 데이터 이관, BI Publisher 리포트
- 반도체 FAB 건설 현장 시스템 운영과 업무 자동화 도구

### 기술

- AI: Anthropic SDK, tool-use 에이전트, RAG(pgvector, BGE-m3), LightGBM
- TypeScript, Next.js, React, Node.js, PostgreSQL, Drizzle ORM
- Python, FastAPI, pandas
- Oracle Primavera Unifier, REST API, SQL, PowerShell, VBA
