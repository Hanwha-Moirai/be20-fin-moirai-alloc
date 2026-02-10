# 🚀 Alloc

**Alloc**은 *메모리를 할당(Allocate)하듯*,  
프로젝트의 **요구사항 · 일정 · 인력 역량**을 종합적으로 고려해  
**인력을 합리적으로 배치하고 전반적인 프로젝트 운영과 리스크 관리를 보조하는 프로젝트 관리 플랫폼**입니다.

IT 프로젝트에서 PM이 겪는  
- 객관적 데이터 기반의 인력 매칭 기준 부재
- 특정 인력 의존도 심화 및 리소스 불균형
- 암묵적인 리스크 관리로 인한 사후 수습 반복과 뒤늦은 후회

을 해결하는 것을 목표로 합니다.

---

## 🧩 핵심 기능

- **프로젝트 관리**
  - 프로젝트 생성 및 기본 정보 관리
  - 기술 스택, 직군, 기간 설정
  - PMO 위험 관리 지침서 PDF 업로드

- **프로젝트 인력 배치**
  - 역할 / 기술 스택 / 일정 기반 인재 추천 
  - 프로젝트 인원 선발 및 추가 배정
  - SSE/SQS를 활용한 실시간 응답 상태 관리 (요청 / 수락 / 면담 / 확정)
  - OpenSearch를 활용한 유사도 기반 인재 DB 검색

- **일정 관리**
  - 팀원 공유 일정 캘린더
  - 스프린트 단위 마일스톤 등록 및 관리
  - 마일스톤 별 태스크 설정
  - Polling 기반 태스크 할당 알림

- **진척 현황 관리**
  - 프로젝트 전체 진행 상태 대시보드
  - 프로젝트 진행 상태 시각화
  - 변경 이력 관리
 
- **리스크 관리**
  - PMO 위험 관리 지침서 기반 리스크 유형 추출
  - RAG 기반 프로젝트 리스크 징후 식별
  - RAG 기반 프로젝트 리스크 PI 점수 평가 (정성적 리스크 평가)

---

## 🏗 시스템 아키텍처

![System Architecture](https://github.com/user-attachments/assets/fd84d7d7-bb27-4f3a-8061-f90eff81c35e)

---

## 🛠 기술 스택
### 🎨 Design
![Figma](https://img.shields.io/badge/Figma-000000?style=for-the-badge&logo=figma&logoColor=white)

### 💻 Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![Pinia](https://img.shields.io/badge/Pinia-FFD54F?style=for-the-badge&logo=vue.js&logoColor=black)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### 🗄 Database
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-FF4F8B?style=for-the-badge)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### ⚙ Backend
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![Uvicorn](https://img.shields.io/badge/Uvicorn-22314E?style=for-the-badge)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-3776AB?style=for-the-badge&logo=python&logoColor=white)

### 🤝 Collaboration
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)

### 🚀 CI/CD
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### 🤖 AI
![Gemini](https://img.shields.io/badge/Gemini_2.0_Flash-4285F4?style=for-the-badge&logo=google&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenAI GPT API](https://img.shields.io/badge/OpenAI-GPT--API-6e6e6e?style=for-the-badge&logo=openai&logoColor=white)


---

## 🗂 문서 링크 모음

### 📘 기획 및 설계
- **프로젝트 기획서**  
  👉 https://docs.google.com/document/d/14nblNrg7cs79-tRuyx1G-IyQSu4VreXTNj0hC7ef214/edit

- **요구사항 정의서**  
  👉 https://docs.google.com/spreadsheets/d/13ujhnsdJ3jMCO3p6hz1_swOi9t_xN-WjZ-ZYx5wCbhk/edit

- **WBS**  
  👉 https://docs.google.com/spreadsheets/d/1mPJ6UKxQZNp0anNGH0AcKaa_K402aaPGrOiU8Jtvq-g/edit

- **ERD**  
  ![ERD](https://github.com/user-attachments/assets/983f517f-2fbd-403b-8952-3e233ffe4445)

---

### 🎨 UI / UX
- **화면 설계서 (Figma)**  
  👉 https://www.figma.com/design/kvcpQG0Ngh2SxiFlUpbg3w/Alloc

- **UI/UX 테스트 결과서**  
  👉 https://docs.google.com/spreadsheets/d/1NMmfMxpjvc9iqrPi6JGYub-fwfCUwp2pQjR5YVK1uVM/edit

---

### 🔗 API & 테스트
- **API 명세서**  
  👉 https://www.notion.so/API-2e0341a375a580d2b655d0b3051eec79

- **단위 테스트 결과**  
  ![Unit Test](https://github.com/user-attachments/assets/b0222600-efe2-4870-9390-6f1b27f3e66c)

- **통합 테스트 결과**  
  👉 https://docs.google.com/spreadsheets/d/1cvhOUu6IkRdQFFf9j1bP0VkYLdPPdypS3vugqQwlVOo/edit?gid=0#gid=0

---

### 🚚 CI/CD 계획서
- **백엔드 CI/CD**

- 백엔드 코드는 GitHub Actions 기반으로 **빌드 → 테스트 → 컨테이너 배포**까지 자동화되어 있습니다.
  ![백엔드CI/CD](docs/cicd/backend_cicd.png)
  ![백엔드CI/CD](docs/cicd/백엔드배포.png)
  ![백엔드CI/CD](docs/cicd/백엔드배포_build.png)
  ![백엔드CI/CD](docs/cicd/백엔드배포_deploy.png)

**Flow**
1. **Commit & Push**: 백엔드 소스 코드 변경 사항을 GitHub에 푸시
2. **CI (GitHub Actions)**: Gradle 빌드 및 테스트 수행
3. **Containerize**: Docker 이미지 빌드
4. **Registry (Amazon ECR)**: Docker 이미지를 ECR에 Push
5. **Release**: 새로운 **ECS Task Definition** 등록(이미지 태그 반영)
6. **Deploy (Amazon ECS)**: ECS Service 업데이트 및 롤링 배포로 신규 태스크 적용



- **프론트엔드 CI/CD**
- 프론트엔드는 GitHub Actions 기반으로 **빌드 → S3 업로드 → CloudFront 배포**까지 자동화되어 있습니다.
  ![프론트엔드CI/CD](docs/cicd/frontend_cicd.png)
  ![프론트엔드CI/CD](docs/cicd/프론트배포.png)

 **Flow**
1. **Commit & Push**: 프론트엔드 소스 코드를 GitHub에 푸시
2. **Build (GitHub Actions)**: 의존성 설치 후 정적 빌드 산출물 생성
3. **Publish (Amazon S3)**: 빌드 결과물을 S3 버킷에 업로드(정적 호스팅)
4. **Deliver (Amazon CloudFront)**: CloudFront를 통해 전 세계 엣지로 정적 리소스 배포  
   - 필요 시 캐시 무효화(Invalidation)로 변경 사항 즉시 반영 
---

### 🔀 협업 및 형상 관리
- **Git 형상 관리 전략**  
  ![Git Strategy](https://github.com/user-attachments/assets/81fd0d0b-7cb7-4def-88c9-7ebdca7774c9)

---

## ✨ 프로젝트 특징 요약

- PM 관점에서 설계된 **인력 중심 프로젝트 관리 도구**
- 추천 → 선발 → 배정 → 확정까지 이어지는 **명확한 인력 관리 흐름**
- 실제 협업을 가정한 **문서 · 테스트 · 형상 관리 체계 포함**

---

## 🎥 기능 미리보기 (GIF)

### 🔐 인증 및 계정 관리
**로그인**  
![PM 로그인](docs/gif/pm로그인.gif)

**비밀번호 재설정**  
![비밀번호 재설정](docs/gif/비밀번호%20재설정.gif)

---

### 📂 프로젝트 관리
**프로젝트 등록**  
![프로젝트 등록](docs/gif/프로젝트등록.gif)

**프로젝트 상세 조회 대시보드**  
![프로젝트 상세 조회](docs/gif/프로젝트상세보기.gif)

---

### 👥 인력 관리
**인재 검색**  
![인재 검색](docs/gif/인재검색.gif)

**인재 추천 (1단계)**  
![인재 추천 1단계](docs/gif/인재추천1.gif)

**인재 추천 (2단계)**  
![인재 추천 상세 2](docs/gif/인재추천2.gif)

---

### 🗓 일정 및 협업 관리
**마일스톤 / 태스크 관리**  
![마일스톤 태스크](docs/gif/마일스톤태스크.gif)

**캘린더 일정 관리**  
![캘린더](docs/gif/캘린더.gif)

---

### 📝 문서 관리
**문서 관리 (주간보고 / 회의록 등)**  
![문서 관리](docs/gif/문서.gif)

---

### ⚠️ 리스크 관리
**리스크 관리 (관리자 지침서 기반 위험 분석 및 자동 리포트 생성)**  
![관리자 위험 관리 지침서 업로드](https://github.com/Hanwha-Moirai/be20-fin-moirai-alloc/blob/7eb890e505d220f8e48de62e85dea22ba48bf73e/docs/gif/%E1%84%80%E1%85%AA%E1%86%AB%E1%84%85%E1%85%B5%E1%84%8C%E1%85%A1%20%E1%84%8C%E1%85%B5%E1%84%8E%E1%85%B5%E1%86%B7%E1%84%89%E1%85%A5%20PDF%20%E1%84%8B%E1%85%A5%E1%86%B8%E1%84%85%E1%85%A9%E1%84%83%E1%85%B3%20%E1%84%89%E1%85%AE%E1%84%8C%E1%85%A5%E1%86%BC.gif)

![리스크 리포트 생성](https://raw.githubusercontent.com/Hanwha-Moirai/be20-fin-moirai-alloc/main/docs/gif/%E1%84%85%E1%85%B5%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%20%E1%84%85%E1%85%B5%E1%84%91%E1%85%A9%E1%84%90%E1%85%B3%20%E1%84%89%E1%85%A2%E1%86%BC%E1%84%89%E1%85%A5%E1%86%BC.gif)

---

## 🧯 트러블 슈팅 (Troubleshooting)

배포/운영 환경에서 실제로 겪었던 이슈를 **현상 → 원인 → 해결 구조 → 결과/회고** 순서로 정리했습니다.

---

### 1) CloudFront(S3) ↔ ECS(ALB) 연동 후 로그인 실패 (401/403/ERR_CONNECTION_REFUSED)

#### 현상

* 로그인 화면은 정상 표시되지만, 로그인 요청 시 **401/403** 또는 **ERR_CONNECTION_REFUSED**가 반복 발생
* 브라우저에서 **Mixed Content(HTTPS 페이지에서 HTTP API 호출)** 이슈 동반

#### 🔍 원인 (단일 원인이 아닌 “구성 불일치 누적”)

* 프론트 API Base URL이 **빌드 타임에 `localhost`로 고정**되어 배포 환경에서 잘못된 주소로 호출
* CloudFront에 **`/api/*` → ALB 라우팅(Behavior)** 이 없어서 API 요청이 정적 오리진(S3)로 흘러감
* ALB에 **HTTPS 리스너 부재**로 인해 보안/프로토콜 정책이 꼬이며 401/403, Mixed Content 유발
* **S3 OAC** 설정/버킷 정책의 ARN 불일치로 정적 리소스 접근 정책이 흔들림
* SPA(history mode)에서 **404/403 발생 시 index.html로 fallback 미처리** → 라우팅 실패

#### 🛠 해결 (CloudFront를 “단일 진입점(Single Entry)”으로 재설계)

* **프론트/백엔드 접근 경로를 동일 오리진으로 통일**

  * 브라우저는 항상 **CloudFront 도메인으로만 요청**
  * API는 `/api` prefix로 고정 (예: `https://{CF_DOMAIN}/api/...`)
* **CloudFront Behavior 추가**

  * Path pattern: `/api/*`
  * Origin: ALB (ECS)
  * Viewer protocol policy: Redirect HTTP to HTTPS
* **TLS 종료(HTTPS Termination)는 CloudFront에서만 담당**

  * 브라우저 입장에서는 항상 HTTPS → Mixed Content 제거
* **SPA 라우팅 보정**

  * CloudFront Custom Error Response로 **403/404 → `/index.html`** 매핑
* 설정 반영 즉시화를 위해 **Cache Invalidation** 수행

#### 🎯 결과

* 로그인/인증 API 정상 동작
* **401/403/Mixed Content 이슈 완전 해소**
* 프론트(S3/CloudFront) – 백엔드(ECS/ALB) **분리 배포 구조 안정화**

---

### 2) SSE 알림 서비스에서 Hikari 커넥션 점유/Pool Exhaustion 발생 (모니터링 기반 개선)

#### 현상

* 배포 환경에서 알림 기능 사용량이 늘어날수록 간헐적으로:

  * **Hikari pool 사용률 증가 / 대기 시간 증가**
  * 특정 시점에 **Too many connections / timeout(지연)** 징후 발생
* 사용자 체감으로는 알림이 늦게 오거나, 일부 요청이 실패하는 현상으로 이어질 수 있었음

#### 🔍 원인 (모니터링으로 “병목 지점”을 특정)

* 대시보드/로그 기반 모니터링 결과, **SSE 구독(장기 연결) 경로가 트래픽 대비 리소스를 과도하게 점유**하는 패턴을 확인
* 재연결/동시 구독이 겹치는 구간에서 **DB 커넥션 풀 점유가 급격히 상승**하며 병목이 발생
* 즉, 운영 관점에서 **장기 연결(SSE) + 서버 리소스(특히 DB 커넥션) 점유 모델이 비효율적**이었음

#### 🛠 해결 (요구사항에 맞춘 전송 방식 선택: SSE → Polling)

* 알림 전달 방식을 **Polling으로 전환**하여 장기 연결을 줄이고, **DB 커넥션 사용을 짧고 예측 가능하게** 만들었음
  *(SSE는 실시간성이 핵심인 경우 좋은 선택이지만, 본 서비스의 알림 특성과 운영 안정성 목표를 고려해 Polling이 더 적합하다고 판단)*
* “전체 조회” 대신 **증분 조회(Incremental Fetch)** 적용

  * `sinceId/cursor` 기반으로 **신규 알림만 조회**
  * 응답에 **new notifications + unread count + latest cursor** 포함
* 변경된 방식에 맞춰 **WebMvc 테스트/검증 기준**을 업데이트

#### 🎯 결과

* 커넥션 풀 점유율/대기 시간 상승 구간이 완화되어 **운영 안정성 개선**
* 트래픽 증가 시에도 리소스를 **더 예측 가능하게 사용**하도록 구조 정리
* 알림 경로가 단순해져 **관측/장애 대응(원인 추적, 재현, 롤백)이 쉬워짐**

---

### 3) 낮은 RAG 검색 품질 개선 (PDF 파싱 강화 + 유형 기반 검색 도입)

####  현상

* 초기 시스템에서 검색 결과(근거)가 **단일/고정 문장 중심**으로 반환되어

  * 근거 청크가 얕거나(정보 밀도 낮음) 설득력이 떨어짐
* **다양한 리스크 시각 부족**

  * 일정/품질/비용 등 **관점별 쿼리 분리 없이** 하나의 방식으로만 검색
  * 주간보고/로그 등도 **단일 관점**으로만 검색되어 결과가 편향됨

#### 🔍 원인 (텍스트 추출/쿼리 설계의 한계)

* **낮은 텍스트 추출 성능 + 원시적 파싱**

  * 목차, 맺음글 등 **리스크 분석에 불필요한 구간이 함께 인덱싱**되어 노이즈가 증가
  * 노이즈가 많아지면서 정작 필요한 근거가 상위에 잘 뜨지 않음
* **쿼리 세밀도 부족**

  * 리스크 유형/평가 요소를 반영하지 않은 **단일·일반 쿼리**로 검색되어
  * 관련성이 낮은 청크가 섞이고 근거 품질이 떨어짐

#### 🛠 해결 (PDF 텍스트 추출 기능 강화 + 유형 기반 검색 구조 도입)

* **PDF 파싱 단계에서 노이즈 제거**

  * 텍스트 추출 시 **목차·헤더 등 불필요 구간을 제거/필터링**하여 인덱싱 품질 개선
* **유형 기반 검색(Type-aware Retrieval) 도입**

  * PDF에서 **리스크 유형/평가 요소를 추출**하고,
  * 이를 기반으로 **유형별로 쿼리를 분리**해 검색 정확도/다양성 향상
    (예: 일정/품질/비용 관점 등으로 분리 검색)

#### 🎯 결과

* 불필요 텍스트 제거로 **벡터 근거 품질 개선(노이즈 감소)**
* 유형 기반 쿼리 분리로 **검색 다양성·정합성 향상**
* 리스크 리포트의 **근거 설득력 및 추적성(왜 이 근거를 썼는지) 강화**

---

### 회고 / 재발 방지 체크리스트

* **단일 진입점**(CloudFront 등)으로 경로를 통일하면 CORS/Mixed Content/라우팅 이슈가 급감

* 배포 환경에서 프론트 API URL은 **빌드 타임/런타임 주입 전략을 명확히** (env 고정값 점검)

* SSE/WebSocket 같은 **장기 연결**은 DB 트랜잭션과 결합하지 않도록 설계 (짧은 쿼리 + 즉시 반환 원칙)

* 재연결 폭주/동시 요청 급증 시나리오를 전제로 **부하 테스트 + 커넥션 풀 관측 지표**를 선제적으로 준비

* RAG는 “모델”보다 **입력 품질(파싱/정제)과 인덱싱 품질**이 검색 성능을 좌우 → PDF 파싱 단계에서 **목차/헤더/푸터 등 노이즈를 제거**한 뒤 임베딩

* 검색 품질 저하를 막기 위해 **Chunking/Overlap 기준을 문서 특성에 맞게 표준화**하고, 변경 시에는 재색인 및 회귀 테스트 수행

* 리스크 분석처럼 다면적인 도메인은 **유형/관점 기반 쿼리 분리(Type-aware Retrieval)** 를 기본 전략으로 두고, 단일 일반 쿼리로만 검색하지 않기

* 운영 단계에서 **Top-K 근거의 관련성/중복률/커버리지(일정·품질·비용 등)** 를 지표로 삼아 정기 점검(샘플링 평가) → 품질 하락 조기 탐지

* 파싱/쿼리 로직 변경 시, “잘 뽑히는지”가 아니라 **리포트 근거의 추적성(왜 이 근거가 선택됐는지)** 까지 확인하도록 검증 기준을 둠


