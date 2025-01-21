# Terminal History

## create vue project by vue3

- `npm create vue@latest`
- Project name: winny-app-habits
- Add TypeScript? Yes
    - TypeScript 提供靜態類型檢查，有助於提高代碼質量和可維護性。
- Add JSX Support?Yes
    - 如果您不打算在 Vue 中使用 JSX 語法，可以不選擇這個選項。
- Add Vue Router for Single Page Application development? Yes
    - Vue Router 是構建單頁應用程序（SPA）必不可少的工具。
-  Add Pinia for state management? Yes
    - Pinia 是 Vue 的狀態管理工具，對於管理應用程序狀態非常有用。
- Add Vitest for Unit Testing? Yes
    - Vitest 是一個快速的單元測試框架，有助於確保代碼質量。
- Add an End-to-End Testing Solution? Playwright
    - Playwright 支持多瀏覽器測試，提供強大的自動化功能和並行測試支持。
- Add ESLint for code quality? Yes
    - ESLint 是一個流行的代碼質量工具，有助於保持代碼風格一致並捕捉潛在錯誤。
    - Oxlint 是一個實驗性功能，可能不夠穩定。如果您希望使用穩定的工具，建議選擇普通的 ESLint。
- Add Prettier for code formatting? Yes
    - Prettier 是一個流行的代碼格式化工具，可以自動統一代碼風格，提升代碼可讀性和維護性。

```
@wanyutang ➜ /workspaces/winny-app-habits (main) $ npm create vue@latest
Need to install the following packages:
create-vue@3.13.0
Ok to proceed? (y) y


> npx
> create-vue

RangeError: Incorrect locale information provided


Vue.js - The Progressive JavaScript Framework

✔ Project name: … winny-app-habits
✔ Add TypeScript? … No / Yes
✔ Add JSX Support? … No / Yes
✔ Add Vue Router for Single Page Application development? … No / Yes
✔ Add Pinia for state management? … No / Yes
✔ Add Vitest for Unit Testing? … No / Yes
✔ Add an End-to-End Testing Solution? › Playwright
✔ Add ESLint for code quality? › Yes
✔ Add Prettier for code formatting? … No / Yes

Scaffolding project in /workspaces/winny-app-habits/winny-app-habits...

Done. Now run:

  cd winny-app-habits
  npm install
  npm run format
  npm run dev

npm notice
npm notice New major version of npm available! 10.8.2 -> 11.0.0
npm notice Changelog: https://github.com/npm/cli/releases/tag/v11.0.0
npm notice To update run: npm install -g npm@11.0.0
npm notice
```