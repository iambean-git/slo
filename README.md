# Slo - 셀프케어 모임 플랫폼

## 프로젝트 소개

일상의 피로를 회복하고 나를 가꾸는 셀프케어 모임 플랫폼

<br>

## 📈 개발 기간

2025.05.15 ~ 2025.06.23

## 👥팀원 소개

<table>
  <thead>
    <tr>
      <th>이름</th>
      <th>역할</th>
      <th>GITHUB</th>
      <th>주요 담당 업무</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="white-space: nowrap;">윤찬기</td>
      <td style="white-space: nowrap;">FE/팀장</td>
      <td><a href="https://github.com/smd995">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a></td>
      <td>프로젝트 구조 설계, 로그인/회원가입 페이지, 마이페이지, 모임 반응기 모달, 메인페이지 리팩토링</td>
    </tr>
    <tr>
      <td style="white-space: nowrap;">조은빈</td>
      <td>FE</td>
      <td><a href="https://github.com/iambean-git">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a></td>
      <td>모임 상세 페이지, 찜한 모임 페이지, 모든 리뷰 페이지</td>
    </tr>
    <tr>
      <td style="white-space: nowrap;">서혜진</td>
      <td>FE</td>
      <td><a href="https://github.com/pluminary">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a></td>
      <td>메인페이지</td>
    </tr>
  </tbody>
</table>

<br>

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
    <img src="https://img.shields.io/badge/React Intersection Library-000000?style=flat-square">
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

<br>

## ✨ 주요기능

### 1️⃣ 모임 찾기 (메인 페이지)

<img src="https://github.com/user-attachments/assets/e12069b4-5668-467d-952b-11649a52a0e1">

> 다른 유저와 함께 참여할 프로그램 모임 목록을 탐색할 수 있습니다.

- 모임은 메인, 서브 카테고리로 분류되어 있습니다. (요가, 명상, 원데이클래스)
- 원하는 지역, 날짜에 대해 `필터링` 및 마감 임박, 참여 인원순으로 `정렬`할 수 있습니다.
- 초기 10개의 목록을 불러오고, 이후 `무한스크롤`을 통해 모임 목록을 추가적으로 확인 가능합니다.

### 2️⃣ 모임 만들기

### 3️⃣ 모임 상세 페이지
> 모임 상세 정보를 확인할 수 있습니다.
- 모임의 정보, 참여 유저, 다른 유저의 리뷰 등을 확인할 수 있습니다.
- 리뷰 목록은 `페이지네이션`으로 구현되어 있습니다.
- "참여하기" 버튼을 통해 모임에 참여할 수 있으며, 비로그인 유저는 팝업과 함께 로그인 페이지로 이동합니다.
- 주최자는 모임을 취소/공유할 수 있습니다.
### 4️⃣ 찜한 모임
> 찜 해놓은 모임 목록을 확인할 수 있습니다.
- 웹 스토리지 활용으로 비로그인 유저도 찜하기 기능을 사용할 수 있습니다.
- 찜하기 버튼을 다시 클릭하여 찜하기를 해제할 수 있습니다.
### 5️⃣ 모든 리뷰
> 원하는 모임 종류에 대해 다른 유저가 작성한 리뷰 점수와 내용을 확인할 수 있습니다.
- 원하는 지역, 날짜 `필터링` 및 최신순, 리뷰 높은 순, 참여 인원 순으로 `정렬`할 수 있습니다.
- `무한 스크롤`을 통해 리뷰 목록을 추가로 확인할 수 있습니다.
### 6️⃣ 마이페이지
> 내 프로필 관리 및 내가 신청한 모임 목록을 확인하고 리뷰를 작성할 수 있습니다.
**프로필 수정**

**나의 모임**
- 내가 신청한 모임들을 목록으로 확인하고 리뷰를 작성할 수 있습니다.
**나의 리뷰**
- 작성 가능한 리뷰 목록과 작성한 리뷰 목록을 확인할 수 있습니다.
**내가 만든 모임**
- 내가 만든 모임들을 목록으로 확인할 수 있습니다.
### 7️⃣ 로그인 및 회원가입
> 계정 생성 및 로그인, 유효성 검사를 수행합니다.


<br>

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
