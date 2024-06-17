# eslint-prettier-setting

## Install Summary

`npm install -D eslint eslint-plugin-jest prettier`

## 🔵 ESLint

### jest 설정

```
 "plugins": ["jest"]
 "rules": {
    "jest/no-disabled-tests": "warn",
    "jest/no-focused-tests": "error",
    "jest/no-identical-title": "error",
    "jest/prefer-to-have-length": "warn",
    "jest/valid-expect": "error"
  }
 "env": {
   "jest/globals": true
  }
```

jest에 특정 조건 제외

```
"overrides": [
  {
    "files": ["__tests__/**/*.js"],
    "rules": {
      "max-lines-per-function": "off",
      "arrow-body-style": "off"
    }
  }
]
```

### 🛠️ command

`npm init @eslint/config` elint 설정 파일 생성

`npm install -D eslint eslint-plugin-jest`

## 🔵 Prettier

### 🛠️ command

`npm install -D prettier`
