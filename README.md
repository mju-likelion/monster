# [MJU LIKELION OFFICIAL Project](https://mju-likelion.org/)
![screencapture-mju-likelion-org-2024-04-28-22_27_01](https://github.com/mju-likelion/custard-pudding/assets/110520124/8ae90e42-be9b-473e-bab2-4c0c69f019a6)



## 📂 Folder Structure

```
├── 📂 public
│
├── 📂 src
│   ├── 📂 api
│   ├── 📂 assets
│   │    └── 📂 imgs
│   │
│   ├── 📂 atoms
│   ├── 📂 components
│   │    ├── 📂 ChannelTalk
│   │    └── 📂 Footer
│   │
│   ├── 📂 hooks
│   ├── 📂 pages
│   │    ├── 📂 Main
│   │    └── 📂 Networking
│   │
│   └── 📂 styles
│
├── 📝 App.css,App.js,index.css,index.js ...
│
└── 🛠package.json,README.md,gitignore...
```

## 🛠 Tech Stack

- React / JS
- styled-components
- styled-reset
- react-router-dom

## 📠 Convention

### 🤝 Naming Rule

- 컴포넌트, 파일명 ⇒ PascalCase
- 변수, 함수 ⇒ camelCase
- 폴더명 ⇒ camelCase
- 파라미터 ⇒ camelCase
- 상수 ⇒ BIG_SNAKE_CASE
- 이벤트 핸들링 ⇒ handle+명사+동사

### 🤝 Branch Naming Convention

| 머릿말  | 설명                               |
| ------- | ---------------------------------- |
| master  | 서비스 브랜치                      |
| develop | 배포 전 작업 기준                  |
| feature | 기능 단위 구현                     |
| hotfix  | 서비스 중 긴급 수정 건에 대한 처리 |

### 🤝 Commit Convention

| 머릿말   | 설명                                   |
| -------- | -------------------------------------- |
| feat     | 기능 구현, 추가                        |
| setting  | 패키지 설치, 개발 설정                 |
| refactor | 코드 리팩터링                          |
| fix      | 버그 수정, 예외 케이스 대응, 기능 개선 |
| docs     | README.md 작성, 주석 작성              |
| chore    | 기타 작업                              |
