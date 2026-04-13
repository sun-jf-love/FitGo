# FitGo - uni-app X Project

## Framework
This is a **uni-app X** project (not standard Vue.js). It uses:
- `.uvue` files for Vue-like components with UTS script
- `.uts` files for TypeScript-like code
- `uni.scss` for built-in SCSS variables

## Entry Points
- `App.uvue` - Root application component
- `main.uts` - SSR app factory (`createApp()`)
- `pages/index/index.uvue` - Only page

## Build & Run
uni-app X projects typically require **HBuilderX** IDE or uni-app CLI. No `package.json` or standard npm scripts exist. Build commands are managed through DCloud tooling.

## Platform Targets
Configured in `manifest.json`:
- App-Android
- App-Harmony  
- WeChat mini-program (`mp-weixin`)
- Alipay, Baidu, TikTok mini-programs

## Key Files
- `manifest.json` - App configuration, appid: `__UNI__736815B`
- `pages.json` - Page routing and navigation config
- `uni.scss` - Predefined SCSS variables (not imported in code)

## Style
- Uses flexbox layout (`flex-direction: row/column`)
- No CSS framework detected; uses basic uni-app built-in styles