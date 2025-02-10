📦 next-mui-intial
├── 📂 app # Next.js App Router의 주요 폴더
│ ├── 📂 (public) # 공개적으로 접근 가능한 페이지 (예: 로그인, 회원가입)
│ ├── 📂 (private) # 인증이 필요한 페이지 (예: 대시보드, 프로필)
│ ├── 📂 api # Next.js 서버 액션 및 API 라우트 핸들러
│ ├── 📂 provider # 전역 Provider
│ ├── 📂 layout # 공통 레이아웃 파일 (예: 다크모드, 글로벌 UI)
│ │ ├── layout.tsx # Root layout (헤더, 푸터, 스타일링)
│ ├── 📂 dashboard # 인증된 사용자가 접근하는 페이지
│ │ ├── page.tsx
│ │ ├── settings.tsx
│ ├── 📂 auth # 인증 관련 페이지
│ │ ├── login.tsx
│ │ ├── register.tsx
│ ├── page.tsx # 메인 페이지
├── 📂 components # 재사용 가능한 UI 컴포넌트
│ ├── 📂 ui # 버튼, 카드 등 공통 UI
│ ├── 📂 forms # 로그인, 회원가입 폼
│ ├── 📂 layout # 헤더, 푸터 등 레이아웃 컴포넌트
├── 📂 hooks # 커스텀 훅
│ ├── useAuth.ts # 인증 관련 훅
│ ├── useThemeMode.ts # MUI 다크모드 훅
│ ├── useQueryData.ts # React Query 관련 훅
├── 📂 lib # 외부 라이브러리 관련 설정
│ ├── axios.ts # Axios 인스턴스 설정
│ ├── theme.ts # MUI 테마 설정
│ ├── jotaiStore.ts # Jotai Store 설정
│ ├── queryClient.ts # React Query Client 설정
├── 📂 styles # 전역 스타일 관리
│ ├── global.css
│ ├── mui-overrides.css
├── 📂 types # 타입 정의
│ ├── auth.ts
│ ├── user.ts
│ ├── api.ts
├── next.config.mjs # Next.js 설정
├── tsconfig.json # TypeScript 설정
├── package.json # 패키지 목록
