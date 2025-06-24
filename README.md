# Slo - 셀프케어 모임 플랫폼

## 프로젝트 소개

일상의 피로를 회복하고 나를 가꾸는 셀프케어 모임 플랫폼

## 📈 개발 기간

2025.05.15 ~ 2025.06.23

## 👥팀원 소개

<table>
  <thead>
    <tr>
      <th style="width:15%" >이름</th>
      <th style="width:15%">역할</th>
      <th>GITHUB</th>
      <th>주요 담당 업무</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>윤찬기</td>
      <td>FE/팀장</td>
      <td><a href="https://github.com/smd995">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a></td>
      <td>프로젝트 구조 설계, 로그인/회원가입 페이지, 마이페이지, 모임 반응기 모달, 메인페이지 리팩토링</td>
    </tr>
    <tr>
      <td>조은빈</td>
      <td>FE</td>
      <td><a href="https://github.com/iambean-git">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a></td>
      <td>모임 상세 페이지, 찜한 모임 페이지, 모든 리뷰 페이지</td>
    </tr>
    <tr>
      <td>서혜진</td>
      <td>FE</td>
      <td><a href="https://github.com/pluminary">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a></td>
      <td>메인페이지</td>
    </tr>
  </tbody>
</table>

## 🔧 기술 스택

### 🎯 핵심 프레임워크

- **Next.js 15** - App Router 사용
- **React** 19
- **TypeScript** - 타입 안정성
- **pnpm** - 패키지 매니저

### 📡 라이브러리 및 개발환경도구

<div style='display:flex; align-items:center'>
    <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=flat-square&logo=TailwindCSS&logoColor=white">
    <img src="https://img.shields.io/badge/clsx-000000?style=flat-square&logo=clsx&logoColor=white">
    <img src="https://img.shields.io/badge/Lucide-F56565?style=flat-square&logo=lucide&logoColor=white">
    <img src="https://img.shields.io/badge/Motion-0055FF?style=flat-square&logo=motion&logoColor=white">
    <img src="https://img.shields.io/badge/react toastify-000000?style=flat-square&logo=clsx&logoColor=white">
</div>

<div style='display:flex; align-items:center'>
    <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=Axios&logoColor=white">
    <img src="https://img.shields.io/badge/swr-F05138?style=flat-square&logo=swr&logoColor=white">
    <img src="https://img.shields.io/badge/Zustand-4a2c2a?style=flat-square&logo=Zustand&logoColor=white">
    <img src="https://img.shields.io/badge/dayjs-334455?style=flat-square&logo=dayjs&logoColor=white">
</div>
<div style='display:flex; align-items:center'>
    <img src="https://img.shields.io/badge/React Hook Form-EC5990?style=flat-square&logo=react-hook-form&logoColor=white">
    <img src="https://img.shields.io/badge/React Intersection Library-000000?style=flat-square&logo=React Intersection Library&logoColor=white">
</div>
<div style='display:flex; align-items:center'>
    <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white">
    <img src="https://img.shields.io/badge/Testing Library React-E33332?style=flat-square&logo=testinglibrary&logoColor=white"> 
    <img src="https://img.shields.io/badge/MSW-FF6A33?style=flat-square&logo=mockserviceworker&logoColor=white">
</div>
<div style='display:flex; align-items:center'>
    <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white">
    <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black">
    <img src="https://img.shields.io/badge/husky-273A60?style=flat-square&logo=husky&logoColor=black">
</div>
<div style='display:flex; align-items:center'>
    <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"> 
    <img src="https://img.shields.io/badge/Notion-41454A?style=flat-square&logo=notion&logoColor=white"> 
    <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"> 
</div>

## ⚡ 시작하기

### 필수 조건

- Node.js 18.0.0 이상
- pnpm

### 설치

```bash
pnpm install
```

### 환경변수 설정

```
NEXT_PUBLIC_API_URL = https://fe-adv-project-together-dallaem.vercel.app
NEXT_PUBLIC_TEAM_ID = your_teamId
```

### 개발 서버 실행

```bash
pnpm dev
```

### 빌드

```bash
pnpm build
```

## ✨ 주요기능

###

## 🗂️ 프로젝트 구조

```
src/
├── app/                # Next.js App Router
│   ├── (auth)/
│   ├── (detail)/
│   ├── liked/
│   ├── mypage/
│   ├── reviews/
│   ├── page.tsx
│   └── layout.tsx
├── components/         # React 컴포넌트
│   ├── atom/
│   ├── icons/
│   ├── molecules/
│   ├── organisms/
│   ├── providers/
│   └── skeleton/
├── constants/          # 상수 모음
├── effect/             # API 호출 등 부수효과 함수
├── entity/             # 백엔드 json 매핑 객체
├── hooks/              # 커스텀 훅
├── lib/                # 유틸리티 함수
├── stores/             # Zustand 상태 관리
└── types/              # TypeScript 타입 정의
```
