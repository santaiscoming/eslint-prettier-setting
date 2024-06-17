# eslint-prettier-setting

## 🧱 설치

- <details>
    <summary><b>eslint</b></summary>

  `npm init @eslint/config`

  `npm install --save-dev eslint`

  `npm install --dev eslint eslint-plugin-jest`

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

  </details>

- <details>
    <summary><b>prettier</b></summary>

  `npm install --save-dev prettier`

  </details>
