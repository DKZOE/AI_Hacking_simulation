# 해킹 AI 플래그 캡처 시뮬레이션

이 프로젝트는 JavaScript와 Google Gemini API를 사용하여 AI 해킹(프롬프트 인젝션)을 시뮬레이션합니다.

## 기능

- Gemini API 키 입력
- 해킹 시작 버튼을 클릭하여 AI 채팅 인터페이스 시작
- 실제 AI(Gemini)와 대화하며 프롬프트 인젝션으로 플래그 획득
- AI가 보안 시스템으로 설정되어 직접 요청 거부
- 프롬프트 엔지니어링으로 플래그 얻기

## 사용법

1. Google AI Studio에서 Gemini API 키를 얻습니다.
2. 프로젝트를 클론합니다.
3. `npm install`으로 의존성을 설치합니다.
4. `npm run dev`로 개발 서버를 시작합니다.
5. 브라우저에서 http://localhost:5173으로 접속합니다.
6. API 키를 입력하고 "해킹 시작하기"를 클릭합니다.
7. AI와 대화하며 플래그를 얻으세요.

## 빌드

프로덕션 빌드를 위해 `npm run build`를 실행합니다.

## 미리보기

빌드 후 `npm run preview`로 미리보기를 실행합니다.

## 주의

API 키는 안전하게 관리하세요. 이 프로젝트는 교육용입니다.# AI_Hacking_simulation
