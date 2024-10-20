# React Toolkit Playground

리액트 개발 환경 구축 및 최신 도구 연습을 위한 플레이그라운드입니다. 커스텀 훅, TSDoc, ESLint, Prettier, Storybook, Vitest 등을 실험하고 학습합니다.

## 주요 기능

1. 리액트 커스텀 훅 구현
2. TSDoc 적용 및 TypeDoc을 이용한 문서화
3. ESLint와 Prettier를 이용한 코드 스타일 관리
4. Storybook을 통한 UI 컴포넌트 개발 및 문서화
5. Vitest(Jest)를 이용한 단위 테스트

## 설치 방법

1. 저장소 클론:
   ```
   git clone https://github.com/your-username/react-toolkit-playground.git
   cd react-toolkit-playground
   ```

2. 의존성 설치:
   ```
   npm install
   ```

## 사용 방법

### 개발 서버 실행
```
npm start
```

### 린트 실행
```
npm run lint
```

### 테스트 실행
```
npm test
```

### Storybook 실행
```
npm run storybook
```

### TypeDoc 문서 생성
```
npm run docs
```

## 프로젝트 구조

```
react-toolkit-playground/
├── src/
│   ├── components/
│   ├── hooks/
│   ├── stories/
│   └── tests/
├── .eslintrc.js
├── .prettierrc
├── vite.config.ts
└── tsconfig.json
```