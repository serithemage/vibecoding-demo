# Todo 앱 데모 프로젝트

React와 Bootstrap을 활용한 Todo 앱 프로젝트입니다. 이 프로젝트는 프론트엔드 중심으로 개발되었으며, 추후 백엔드 연동이 가능하도록 설계되었습니다.

## 프로젝트 개요

이 Todo 앱은 다음과 같은 기능을 제공합니다:

- Todo 항목 생성, 조회, 수정, 삭제
- 우선순위 설정 (낮음, 중간, 높음)
- 마감일 설정
- 완료 상태 관리
- 필터링 및 검색 기능

## 기술 스택

- **프레임워크**: React
- **UI 라이브러리**: Bootstrap
- **상태 관리**: React Context + useReducer
- **데이터 저장**: Zustand (로컬 스토리지 연동)

## 프로젝트 구조

```
/src
  /components    # UI 컴포넌트
  /hooks         # 커스텀 훅
  /store         # 상태 관리
  /types         # 타입 정의
  /utils         # 유틸리티 함수
```

## 설치 및 실행

### 필수 조건

- Node.js (v14 이상)
- npm 또는 yarn

### 설치

```bash
# 저장소 클론
git clone https://github.com/serithemage/vibecoding-demo.git
cd vibecoding-demo

# 의존성 설치
npm install
# 또는
yarn install
```

### 개발 서버 실행

```bash
npm start
# 또는
yarn start
```

브라우저에서 `http://localhost:3000`으로 접속하여 앱을 확인할 수 있습니다.

## 문서

프로젝트 설계 및 구현에 관한 문서는 `docs` 디렉토리에서 확인할 수 있습니다:

- [요건 정의](docs/requirements.md)
- [설계 문서](docs/design.md)
- [UI 디자인](docs/ui-design.md)
- [구현 체크리스트](docs/implementation-checklist.md)

## 라이센스

MIT
