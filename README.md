<div align="center">

# 오지수

**Frontend · Backend · Mobile**

`Spring Boot` `React` `React Native` `Django` `Vue` `TypeScript` `Python`

</div>

---

## About

미디어커뮤니케이션을 전공하고 디지털 마케팅 업무를 경험한 뒤 개발로 전향했습니다.

사용자 행동 데이터를 분석하는 것에서 시작해,  
지금은 화면부터 서버, 데이터베이스까지 직접 구현하고 있습니다.

특정 영역에만 머무르기보다 **사용자의 요청이 화면에서 서버를 거쳐 실제 결과로 돌아오는 전체 흐름**을 이해하는 개발을 지향합니다.

최근에는 Spring Boot 기반 백엔드와 React·React Native 기반 클라이언트 개발을 중심으로,  
AI 모델과 서비스를 연결하는 프로젝트를 진행해왔습니다.

- 신한커리어넥스트 1기 · 금융 AI 에이전트 서비스 개발 과정
- 삼성청년SW·AI아카데미(SSAFY) 14기
- 서울디지털인재개발원 · 빅데이터 서비스 엔지니어 양성과정

---

## Tech Stack

### Languages

`Java` `Python` `TypeScript` `JavaScript` `SQL`

### Frontend / Mobile

`React` `React Native` `Expo` `Vue.js` `Pinia`

### Backend

`Spring Boot` `Django` `Django REST Framework` `FastAPI`

### Database / Storage

`PostgreSQL` `Redis` `MinIO` `MongoDB`

### Realtime / Media

`WebRTC` `LiveKit` `Web Audio API`

### Tools

`Git` `GitHub` `Swagger` `Docker`

---

## Projects

### BATANG
**생성형 AI 기반 건축 도면 협업 플랫폼**

`Spring Boot` `React` `TypeScript` `Redis`

7명이 함께 개발한 프로젝트에서 인증·권한 구조와 시스템 간 연동을 담당했습니다.

- 프론트엔드·백엔드·AI 간 데이터 흐름 및 API 명세 설계
- 인증 코드 → 검증 토큰 → JWT로 이어지는 단계별 인증 구조 설계
- 자동 저장 중 발생한 상태 불일치 문제를 버전 비교 기반 후속 저장 구조로 개선
- AI 도면 수정 이후 편집 이력과 Undo/Redo가 동작하지 않던 문제를 FE-BE-AI 이벤트 흐름까지 추적해 해결

**Result — 9팀 중 3위, 우수상**

---

### AiTime
**유아 자폐 스펙트럼 고위험군 선별 AI 웹 서비스**

`React` `TypeScript` `WebRTC` `LiveKit` `Web Audio API`

보호자 화면과 실시간 검사 환경을 중심으로 프론트엔드를 담당했습니다.

- WebRTC 기반 실시간 검사 화면 및 촬영 흐름 구현
- LiveKit을 이용한 실시간 영상 통신 연동
- AI 서버 응답을 기다리던 음량 게이지를 Web Audio API 기반 클라이언트 처리로 분리
- 약 1초가량 발생하던 체감 지연 제거
- 의료진·접수처·보호자의 역할과 검사 상태에 따른 화면 흐름 설계
- 소아정신과 전문의와 언어치료사 인터뷰를 바탕으로 검사 조건 구체화

**Result — 8팀 중 2위, 우수상**

---

### NumberWON
**해외송금 최적 경로 추천 서비스**

`Django` `Django REST Framework` `Vue.js` `Pinia`

2인 풀스택 프로젝트로, 사용자 기능과 API 설계부터 환율 비교 결과 화면까지 구현했습니다.

- 회원 인증·권한 및 커뮤니티·마이페이지 REST API 구현
- Swagger 기반 API 문서 자동화
- 18개 은행·23개국의 환율 및 송금 수수료 비교 결과 UI 구현
- 약 2,000줄 규모의 컴포넌트를 상태와 기능 단위로 분리해 유지보수 구조 개선

**Result — 10팀 중 1위, 최우수상**

---

### WannaBe
**AI 기반 테니스 자세 교정 모바일 서비스**

`Spring Boot` `React Native` `Expo` `PostgreSQL` `MinIO`

서비스를 직접 기획하고 백엔드 개발을 중심으로 참여했습니다.

- 40분 이상 대용량 영상 업로드를 위한 분할 전송·재조합 구조 구현
- 업로드 진행률 표시 및 실패 요청 자동 재시도 처리
- 실패한 업로드의 잔여 파일이 스토리지에 남는 문제를 발견하고 정리 로직 추가
- 정상 완료와 실패 취소가 충돌하는 엣지케이스를 재검토해 업로드 파이프라인 안정화
- 테니스 경험을 바탕으로 AI 분석 범위를 서브 동작으로 구체화하고 측정 기준 정의

---

### RareField
**희귀질환 정보 공유 플랫폼**

`Python` `FastAPI` `MongoDB` `pandas`

수집한 희귀질환 데이터를 서비스로 연결하는 데이터·백엔드 개발을 담당했습니다.

- 비정형 데이터 수집 및 정제
- MongoDB 기반 데이터 적재 구조 설계
- FastAPI 기반 데이터 제공 파이프라인 구현
- Python에 익숙하지 않은 팀원의 웹 스크래핑 개발 지원

**Result — 팀 최우수상**

---

## Experience

### Digital Marketing → Software Development

디지털 마케팅팀에서 Google Analytics와 사용자 행동 데이터를 분석하며  
이탈이 발생하는 구간을 찾는 업무를 경험했습니다.

데이터로 문제를 발견하는 것에서 그치지 않고  
문제가 발생한 화면과 시스템을 직접 바꾸고 싶어 개발을 시작했습니다.

이 경험 덕분에 기능 구현 자체뿐 아니라  
**사용자가 어디에서 막히는지, 왜 이 기능이 필요한지**를 함께 고민하며 개발하는 편입니다.

---

## Education

**신한커리어넥스트 1기**  
금융 AI 에이전트 서비스 개발 과정

**삼성청년SW·AI아카데미(SSAFY) 14기**  
Software Engineering

**서울디지털인재개발원**  
빅데이터 서비스 엔지니어 양성과정

---

## Contact

**Email**  
ohjisu320@gmail.com
