# TODO 웹 애플리케이션

개인용 할 일 관리를 위한 현대적인 웹 애플리케이션입니다.

## 🎯 프로젝트 개요

이 프로젝트는 사용자가 효율적으로 할 일을 관리할 수 있는 웹 기반 TODO 애플리케이션입니다. 모바일 우선 반응형 디자인과 직관적인 사용자 인터페이스를 제공합니다.

## ✨ 주요 기능

### 핵심 기능
- ✅ TODO 항목 생성, 조회, 수정, 삭제 (CRUD)
- 🎯 우선순위 설정 (낮음, 중간, 높음)
- 📱 완료/미완료 상태 토글
- 🔍 상태별 필터링 (전체, 미완료, 완료)
- 📊 우선순위별 정렬

### UI/UX 기능
- 📱 모바일 우선 반응형 디자인
- 🌙 다크/라이트 모드 지원
- ♿ 웹 접근성 준수 (WCAG 2.1 AA)
- 🎨 현대적이고 직관적인 인터페이스

## 🛠 기술 스택

### 1단계 (프론트엔드 전용)
- **프레임워크**: React 18
- **빌드 도구**: Vite
- **스타일링**: Tailwind CSS
- **상태 관리**: React Context + useReducer
- **데이터 저장**: 로컬 스토리지
- **테스트**: Jest + React Testing Library

### 2단계 (백엔드 연동)
- **백엔드**: Node.js (TypeScript)
- **인프라**: AWS 서버리스 (API Gateway, Lambda, DynamoDB)
- **IaC**: AWS CDK
- **인증**: AWS Cognito
- **배포**: GitHub Actions + AWS

## 🚀 개발 전략

### 1단계: 프론트엔드 전용 (2024년 12월)
로컬 스토리지를 사용하여 완전히 동작하는 TODO 애플리케이션을 개발합니다.

### 2단계: 백엔드 연동 (2025년 1월)
AWS 서버리스 아키텍처를 구축하여 사용자 인증과 클라우드 데이터 저장을 추가합니다.

## 📁 프로젝트 구조

```
vibecoding-demo/
├── docs/                    # 프로젝트 문서
│   └── requirements.md      # 요구사항 정의서
├── src/                     # 소스 코드 (예정)
├── public/                  # 정적 파일 (예정)
├── task_manage.md          # 작업 관리
├── README.md               # 프로젝트 소개
└── .gitignore             # Git 무시 파일
```

## 🎯 마일스톤

### 1단계 목표
- [x] 요구사항 정의 및 기술 스택 결정
- [ ] React + Vite 프로젝트 초기화
- [ ] 핵심 CRUD 기능 구현
- [ ] 로컬 스토리지 연동
- [ ] 반응형 UI/UX 구현
- [ ] GitHub Pages 배포

### 2단계 목표
- [ ] AWS CDK 인프라 구축
- [ ] Lambda API 개발
- [ ] DynamoDB 연동
- [ ] AWS Cognito 인증 구현
- [ ] 프로덕션 배포

## 🔧 개발 환경 설정

### 필요 조건
- Node.js 18+
- npm 또는 yarn
- Git

### 설치 및 실행 (예정)
```bash
# 저장소 클론
git clone <repository-url>
cd vibecoding-demo

# 의존성 설치
npm install

# 개발 서버 실행
npm run dev

# 빌드
npm run build
```

## 📋 작업 관리

프로젝트의 상세한 작업 진행 상황은 [task_manage.md](./task_manage.md)에서 확인할 수 있습니다.

## 📖 문서

- [요구사항 정의서](./docs/requirements.md)
- [작업 관리](./task_manage.md)

## 🤝 기여하기

이 프로젝트는 데모 목적으로 개발되고 있습니다. 피드백이나 제안사항이 있으시면 이슈를 생성해 주세요.

## 📄 라이선스

MIT License

---

**개발 시작일**: 2024년 12월 19일  
**현재 상태**: 요구사항 정의 완료, 개발 준비 단계  
**다음 단계**: React + Vite 프로젝트 초기화
