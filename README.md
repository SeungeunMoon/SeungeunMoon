<div align="center">
  <h2>안녕하세요, 문승은입니다 👋</h2>
  <p><b>끊임없이 더 나은 방향을 탐구하며, 서비스의 실질적인 가치를 증명하는 개발자입니다.</b></p>
  <p>Backend · AI Pipeline · Data Analysis</p>
  <a href="mailto:harin0375@gmail.com"><img src="https://img.shields.io/badge/Email-harin0375@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://solved.ac/neptun"><img src="https://img.shields.io/badge/solved.ac-neptun-17CE3A?style=flat-square"/></a>
</div>

<br>

## 🚀 대표 프로젝트

### ✅ Checkmate — 유튜브 팩트체크 크롬 확장 프로그램
> 삼성청년SW·AI아카데미 · 2026.04 ~ 05 · **AI 서버 담당**

영상 자막에서 주장을 뽑아 근거와 대조하고 신뢰도 등급을 매기는 서비스입니다.

- 주장 추출 → 시맨틱 라우팅 → RAG 검증으로 이어지는 **6단계 LCEL 파이프라인** 설계
- 정확도 문제를 모델이 아닌 **검색 단계**에서 찾아 쿼리와 청킹을 다시 설계
- 오래 걸리는 분석 요청을 **Kafka 비동기 워커**로 전환 (AI 서버 소비자 쪽)

`Python` `FastAPI` `LangChain` `Qdrant` `Kafka` `Redis`

<br>

### 🐾 Petfolio — 반려동물 공동 가계부
> 삼성청년SW·AI아카데미 · 2026.02 ~ 03 · **백엔드 · 인프라 · AI 서버 연동**

여러 보호자의 결제 내역에서 반려동물 지출을 AI가 골라내 하나의 가계부로 합쳐 주는 서비스입니다.

- GPU 서버의 인바운드 제한을 **Redis 큐로 통신 방향을 뒤집어** 해결하고, `BLMOVE` 기반 Reliable Queue로 고도화
- 거래 고유번호 검증 + DB Unique 제약으로 **중복 거래 저장 방지**, 낙관적 락으로 동시 수정 처리

`Java` `Spring Boot` `JPA` `MySQL` `Redis` `Docker` `Jenkins` `AWS`

<br>

### 🌱 곁(Gyeot) — 아동·청소년 심리상담 서비스 · 🏆 공통 프로젝트 우수상
> 삼성청년SW·AI아카데미 · 2026.01 ~ 02 · **팀장 · AI 챗봇 전담**

그림·아바타 같은 비언어적 표현으로 청소년이 부담 없이 상담을 시작하도록 돕는 WebRTC 기반 서비스입니다.

- RoBERTa 파인튜닝 **위기 단계 분류기**에 Focal Loss를 적용해 소수 클래스(응급·학대의심) 놓침을 줄임 <!-- TODO: 위기 단계 수(4 vs 5), 최종 지표 확인 -->
- 위기 신호별로 다른 매뉴얼을 검색하는 **RAG 챗봇**, 분류 신뢰도가 낮을 땐 일반 대화로 처리하는 안전장치

`Python` `PyTorch` `Transformers` `FastAPI` `LangChain` `ChromaDB`

<br>

### 🏠 집사(Zipsa) — AI 전세계약 분석 서비스
> 종합설계 · 2025.03 ~ 06 · **프론트엔드 총괄 · 기획 · 프롬프트 검증** · A+

전세 계약이 처음인 사회초년생에게 계약서의 위험 요소와 시세 정보를 알려 주는 웹 서비스입니다.

- 항목별 프롬프트 템플릿과 **JSON 출력 제한**으로 LLM 결과의 일관성을 확보해 AI 기능 요구사항 **90% 충족**
- 기획–개발 간 전달 문제를 **요구사항·피드백 템플릿**으로 해결

`Vue.js` `OpenAI API` `Prompt Engineering`

<br>

### 🧬 유전 알고리즘 기반 기호 회귀 (Symbolic Regression)
> University of Ljubljana 교환학생 · 2023-2 · **Intelligent Systems**

x, y 데이터만 보고 원래 수식을 찾아내는 Genetic Programming 구현입니다.

- 수식을 **트리로 표현해 정수 유전자로 인코딩**하고 변이·교차 연산 구현
- 적합도를 **MSE와 수식 길이의 가중합**으로 설계해 정확도와 간결함의 균형을 조절

`Python` `PyGAD` `SymPy` `NumPy`

<br>

<details>
<summary><b>📂 그 밖의 경험</b></summary>
<br>

| 프로젝트 | 내용 | 역할 · 결과 |
|---|---|---|
| **ARGUS** — 반도체 팹 설비교체 승인 PoC | 승인 서류 준비 시간과 반려 왕복을 줄이는 AI 에이전트 PoC · SKALA 4기 2026 | 서비스·AI 기획 · 프론트 · UI/UX |
| 공공기관 이전 정책 효과 분석 | 패널 데이터 구축 후 이중차분(DID)으로 정책 효과 추정 · 2024 | 데이터 구축 · 계량 모델 · **A+** |
| 재정 공공데이터 활용 공모전 | 지방교육재정교부금의 끈끈이 효과를 R로 검정 | 데이터 분석 · **한국재정정보원장상(2등)** |
| 웹툰 리플레이 | 웹툰 줄거리 요약 서비스 기획·프로토타입 · 카카오 빅테크 과정 | 기획 · 프로토타입 · **교육 우수상** |
| 뉴스 헤드라인 분류 (교환학생) | 전처리·특성 추출 후 다중 클래스 분류 · University of Ljubljana | NLP |
| Ripplify (교환학생) | 유저 인터뷰 기반 UX 설계 · Graphic Design 수업 | 인터뷰 · Figma 프로토타입 |

</details>

## 🏆 수상 · 교육

- **공통 프로젝트 우수상** — 삼성청년SW·AI아카데미 (2026.02)
- **성적우수상** — 삼성청년SW·AI아카데미 (2025.12)
- **Deep Dive Fullstack + GenAI 교육 우수상** — 카카오 빅테크 프로그램 (2024.09)
- **재정 공공데이터 활용 보고서 공모전 2등** — 한국재정정보원장상 (2022.12)
- **교육** — 삼성청년SW·AI아카데미 · University of Ljubljana 교환학생
- **자격** — 정보처리기사 · SQLD · Adsp · 컴퓨터활용능력1급

## 🛠️ Tech Stack

| 분야 | 기술 |
|---|---|
| Backend | <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> |
| AI | <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square"/> <img src="https://img.shields.io/badge/ChromaDB-FF4F00?style=flat-square"/> |
| Data | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white"/> |
| Infra | <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/> <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/> |
| Frontend | <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/> |

## 📊 Activity

<div align="center">
  <img src="https://raw.githubusercontent.com/SeungeunMoon/SeungeunMoon/main/metrics.svg" alt="GitHub metrics" />
  <br><br>
  <a href="https://solved.ac/neptun"><img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=neptun" /></a>
</div>
