# dotfiles

개인 프로젝트 설정 파일 모음입니다.

## 📁 구조

```
dotfiles/
├── next/
│   ├── eslint.config.mjs
│   └── .prettierrc
├── nest/
│   ├── .eslintrc.js
│   └── .prettierrc
├── common/
│   ├── .gitignore
│   ├── .gitattributes
│   └── .prettierignore
└── README.md
```

## 📦 필수 패키지

### Next.js

```bash
pnpm add -D \
  prettier \
  prettier-plugin-tailwindcss \
  eslint \
  @eslint/eslintrc
```

### NestJS

```bash
pnpm add -D \
  prettier \
  eslint \
  @typescript-eslint/parser \
  @typescript-eslint/eslint-plugin \
  eslint-plugin-prettier \
  eslint-config-prettier
```

## 🚀 사용 방법

### 직접 복사

필요한 파일을 프로젝트 루트에 복붙해서 사용합니다.  
`common/` 폴더 파일은 Next.js / NestJS 공통으로 사용합니다.

### curl로 바로 받기

> `유저명` 부분을 본인 GitHub 유저명으로 변경해주세요.

**Next.js**

```bash
curl -O https://raw.githubusercontent.com/JiYooon19/dotfiles/main/next/eslint.config.mjs
curl -O https://raw.githubusercontent.com/JiYooon19/dotfiles/main/next/.prettierrc
```

**NestJS**

```bash
curl -O https://raw.githubusercontent.com/JiYooon19/dotfiles/main/nest/.eslintrc.js
curl -O https://raw.githubusercontent.com/JiYooon19/dotfiles/main/nest/.prettierrc
```

**공통**

```bash
curl -O https://raw.githubusercontent.com/JiYooon19/dotfiles/main/common/.gitignore
curl -O https://raw.githubusercontent.com/JiYooon19/dotfiles/main/common/.gitattributes
curl -O https://raw.githubusercontent.com/JiYooon19/dotfiles/main/common/.prettierignore
```

## 🛠 기술 스택

| 구분 | 스택 |
|------|------|
| Frontend | Next.js, TypeScript, Tailwind CSS |
| Backend | NestJS, TypeScript |

## 📝 버전 히스토리

| 버전 | 내용 |
|------|------|
| v1.0.0 | 초기 설정 (Next.js / NestJS 분리) |
