# KT&G 주간 AI 동향 브리핑 메모리

이 파일은 이 Skill의 장기 기억이다. 실행할 때 확인하고, 브리핑 초안 저장 후에만 보고 이력을 갱신한다. `[확인 필요]` 내용은 사용자가 확인하기 전까지 사실로 단정하지 않는다.

## 사용자 및 보고

- 대상: KT&G
- 사용자 역할: AI·BigData 컨설턴트 (PMP, BABOK, ITIL/ITSM, SAFe)
- 언어: 한국어
- 주기: 사용자가 요청할 때 수동 실행
- 보고 형식: Markdown 초안 (기본 저장 위치: `reports/ktng-ai-weekly-brief/YYYY.MM.DD.md`)
- 최종 검토와 발송: 사용자

## KT&G 사업 맥락

아래는 기획서에 제공된 초기 맥락이며 최신성·정확성은 운영 전 확인이 필요하다.

| 구분 | 현재 메모 | 상태 |
|---|---|---|
| 주요 사업 영역 | 담배(궐련·차세대 제품), 건강기능식품(KGC인삼공사), 부동산 등 | 사용자 확인 필요 |
| 현재 추진 중인 AI/데이터 과제 | 기재된 내용 없음 | 확인 필요 |
| 관심 부서/이해관계자 | 기재된 내용 없음 (예: DT, 생산, 마케팅, R&D) | 확인 필요 |
| 보고 시 민감 주제 | 기재된 내용 없음 (예: 규제, 건강 관련 표현) | 확인 필요 |
| 사내 시스템/제약 | 기재된 내용 없음 (예: 망분리, 사용 가능 클라우드) | 확인 필요 |

### 분석 관점

1. 제조·생산: 스마트팩토리, 품질검사, 설비 예지보전
2. 공급망·물류: 수요예측, 재고 최적화
3. 마케팅·고객: 개인화, 고객 데이터 분석, 콘텐츠 생성
4. R&D: 소재·제품 연구, 문헌 분석
5. 경영지원·업무 생산성: 생성형 AI, Agent, 문서 자동화
6. 거버넌스·리스크: AI 규제, 보안, 데이터 주권, 컴플라이언스
7. 글로벌 사업: 해외 시장 규제·동향

## 신뢰 소스 목록

아래는 우선 확인할 채널의 탐색 목록이다. 경로 예시는 실제 접근 여부를 보장하지 않는다. 검색으로 확인한 공식 게시물이나 페이지 URL만 보고서에 기록한다.

### 국외 공식 블로그·뉴스룸

| 분야 | 기업/브랜드 | 확인할 채널 또는 주제 |
|---|---|---|
| 파운데이션 모델 | OpenAI | 공식 뉴스룸, 모델·제품·엔터프라이즈 기능 |
| 파운데이션 모델 | Anthropic | 공식 뉴스룸, Claude·Agent·안전성 |
| 파운데이션 모델 | Google DeepMind | 공식 블로그, Gemini·연구 |
| 빅테크 | Google | 공식 AI 블로그, 제품·Cloud AI |
| 빅테크 | Microsoft | 공식 AI 블로그·Microsoft Research, Copilot·Azure AI |
| 빅테크 | Meta | 공식 AI 블로그, Llama·모델 |
| 빅테크 | Amazon / AWS | AWS Machine Learning 블로그·Amazon Science |
| 빅테크 | Apple | Apple Machine Learning Research |
| 인프라 | NVIDIA | 공식 블로그·개발자 블로그, AI 인프라·산업용 AI |
| 인프라 | IBM | IBM Research 블로그, 기업 AI·거버넌스 |
| 오픈소스·플랫폼 | Hugging Face | 공식 블로그, 오픈 모델·도구 |
| 유럽 | Mistral AI | 공식 뉴스, 모델·제품·정책 |
| 엔터프라이즈 | Cohere | 공식 블로그, 기업용 LLM·검색 |
| 신흥 | xAI | 공식 뉴스, Grok 모델 |
| 중국 | DeepSeek | 공식 발표 채널, 모델·보안·규제 맥락 |
| 중국 | Alibaba / Qwen | 공식 발표 채널, 모델·보안·규제 맥락 |

기획서에는 15개사로 적혀 있으나 실제 열거된 브랜드는 16개다. 별도 확인 전까지 이 표의 16개 브랜드를 모두 확인한다. 기업별 조회 결과가 없을 때는 기간 내 게시물 없음과 조회 실패를 구분한다.

### 국외 언론·분석

- Reuters (Technology), TechCrunch, The Verge, MIT Technology Review
- 전문가·뉴스레터: The Batch (DeepLearning.AI), Simon Willison's Weblog, Import AI

### 국내 공식·정책·언론

- 기업 공식 채널: 네이버, 카카오, LG AI연구원, 삼성, SK텔레콤, KT, 업스테이지
- 정책기관: 과학기술정보통신부, 한국지능정보사회진흥원(NIA)
- 언론: AI타임스, 전자신문, ZDNet Korea, 디지털데일리

## 신뢰도 기준

- 상: 기간 내 발행일 및 기업·기관 공식 1차 출처 확인
- 중: 신뢰 매체 단독 보도, 1차 출처 미확인 또는 교차 확인이 충분하지 않음
- 하: 그 외 확인 필요 자료. 본문에서 제외하고 검증 로그에만 기록
- 독립된 2개 이상 출처로 핵심 사실을 확인하는 것을 우선하되, 교차 확인 여부를 정확히 표시한다.

## 제외 소스

- 출처 불명 SNS 게시물, 커뮤니티 루머, 익명 소식통 단독 보도
- 보도자료를 재가공했으나 원출처를 확인할 수 없는 게시물
- 유료 구독벽으로 원문 확인이 불가능한 기사
- 실제 원문 URL 또는 발행일을 확인할 수 없는 자료

## 보고 이력

초안 저장을 마친 보고서만 추가한다. 상세 이력은 최근 8주로 유지하고 이전 기록은 분기별 요약으로 압축한다.

| 보고일 | 수집 기간 | 뉴스 제목(요약) | 출처 URL |
|---|---|---|---|
| 2026.10.01 | 2026.09.25~2026.10.01 | 과기정통부, 민·관 합동 국가 AI 안전 종합계획 수립 착수 | https://www.korea.kr/news/policyNewsView.do?newsId=148972829&pWise=sub&pWiseSub=R3 |
| 2026.10.01 | 2026.09.25~2026.10.01 | 삼성전자, KT·SK텔레콤과 AI RAN 계약 체결 | https://news.samsung.com/medialibrary/global/photo/63097 |
| 2026.10.01 | 2026.09.25~2026.10.01 | 카카오, 부산에 AI 돛 센터 조성 | https://www.sedaily.com/article/20095221 |
| 2026.10.01 | 2026.09.25~2026.10.01 | 네이버, 멕시코 정부와 AI 협력 추진 | https://www.mk.co.kr/news/business/12164019 |
| 2026.10.01 | 2026.09.25~2026.10.01 | 엔비디아, Open Agent Safety Platform 공개 | https://apnews.com/article/nvidia-ai-agent-artificial-intelligence-safety-3c4d7c1cfde82851c0577d1fa29b8621 |
| 2026.10.01 | 2026.09.25~2026.10.01 | 오픈AI, GPT-6.1 Astra 출시 보류(WSJ 보도) | https://www.reuters.com/business/openai-shelves-new-ai-model-after-internal-safety-tests-wsj-reports-2026-09-28 |
| 2026.10.01 | 2026.09.25~2026.10.01 | 앤트로픽, Claude Sonnet 5.5 출시 | https://techcrunch.com/2026/09/28/anthropic-releases-sonnet-5-5-which-it-calls-a-significantly-cheaper-faster-work-partner |
| 2026.10.01 | 2026.09.25~2026.10.01 | 앤트로픽, IPO 투자설명서에 AI 실존적 위험 경고 | https://www.reuters.com/business/finance/anthropic-warns-ai-may-pose-existential-risks-humanity-ipo-filing-2026-09-29 |
| 2026.10.01 | 2026.09.25~2026.10.01 | 제조업 AI 도입 확산에 따른 데이터 보안 위험(Thales 보고서) | https://www.themanufacturer.com/articles/manufacturers-face-new-data-security-risks-as-ai-adoption-accelerates |

## 사용자 피드백

| 일자 | 피드백 | 반영 방법 |
|---|---|---|

## 용어 및 운영 메모

- 날짜: `YYYY.MM.DD`; 기본 기간은 KST 실행일 포함 최근 7개 달력 날짜
- 기업·제품명: 국문 표기 후 최초 1회 원어 병기 (예: 앤트로픽(Anthropic))
- 신뢰도: 상 / 중 / 하
- 내부 용어·금지 표현: 확인 필요
- 실행 환경: 웹 검색이 가능한 환경 필요. 사내망 외부 차단 여부와 실행 위치는 확인 필요
- 웹 검색: 시작 시 `TAVILY_API_KEY`가 설정되어 있으면 `tavily_search` 도구가 등록됨; MCP 검색은 서버 설정에 따라 다름
- URL은 실제로 조회한 주소만 쓴다. 목록의 회사명·채널명으로 URL을 추측해 만들지 않는다.