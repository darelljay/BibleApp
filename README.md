# 🌿 Daily Grace – 감사 일기장 웹앱

> _“범사에 감사하라” (데살로니가전서 5:18)_

Daily Grace는 하루를 돌아보며 감사한 일들을 기록하고, 성경 말씀과 함께 마음을 정리할 수 있는 **감성 일기장 웹 애플리케이션**입니다.  
자신만의 태그로 일기를 정리하고, 랜덤한 말씀을 통해 위로와 은혜를 누려보세요.  
Frontend는 **React + TailwindCSS**, Backend는 **NestJS + JWT 인증** 기반으로 구성되었습니다.

---

## 🧩 주요 기능

### ✍️ 감사 일기
- 하루 동안 감사한 일을 텍스트로 기록
- 사용자 정의 태그로 일기 분류 가능
- 랜덤한 성경 말씀 자동 삽입 (선택 가능)

### 🔍 일기 조회 및 검색
- 날짜, 키워드, 태그 기반 검색/필터링
- "말씀이 포함된 일기만 보기" 기능 제공

### 📊 통계/시각화 (옵션)
- 감사 히트맵: 일기 작성 빈도 시각화
- 자주 사용된 단어 & 태그 집계

### 💌 보너스 기능
- 미래의 나에게 보내는 감사 편지 (이메일 예약 전송)
- 비공개 모드 일기 (비밀번호 보호)
- 감정 분석 기반 태그 추천 (긍정/부정)

---

## ⚙️ 기술 스택

| 역할 | 기술 |
|------|------|
| 프론트엔드 | React.js, Next.js, TailwindCSS |
| 백엔드 | NestJS, TypeScript, REST API |
| 인증 | JWT + Passport.js |
| 데이터베이스 | MongoDB or PostgreSQL |
| 배포 | Vercel (FE), Railway/Render (BE) |
| 기타 | Swagger API 문서, dotenv, ESLint |

---

## 📁 디렉터리 구조 (예시)

```bash
daily-grace/
├── frontend/         # React 앱 (Next.js)
│   ├── components/
│   ├── pages/
│   ├── styles/
│   └── ...
├── backend/          # NestJS API 서버
│   ├── src/
│   │   ├── auth/
│   │   ├── journal/
│   │   ├── verse/
│   │   └── ...
│   └── ...
├── .env.example
└── README.md
