# npm 패키지 버전 관리 테스트하기

## 사용법

Run the following commands:

```sh
npm install

npm run create <project-name>
```

Then it will generate a new React project in the current directory that is shipped with the following features:

- TypeScript
- Webpack
- ESLint
- Prettier
- Jest
- React Testing Library

## 참고 스크립트

```sh
# 현재 경로와 하위 경로에 있는 모든 node_modules 삭제
find . -name 'node_modules' -type d -prune -exec rm -rf '{}' +

# npm 패키지 버전 목록 확인
npm show <package-name> versions
```
