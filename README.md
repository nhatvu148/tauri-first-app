# Tauri First App

## Normal Setup

- yarn add -D @tauri-apps/cli
- yarn tauri init
- yarn tauri info
- yarn tauri dev
- yarn tauri build --debug
- yarn tauri deps install
- yarn tauri deps update

## Tauri Init

- https://geekjr.github.io/reactTauri.html

## Steps to install Tauri

- cargo install tauri-bundler
- npx create-react-app app-name
- yarn add tauri
- Add scripts to package.json:

```json
"tauri": "tauri",
"dev": "npm run tauri dev",
"bundle": "tauri build",
```

- yarn tauri init
- yarn build
- yarn bundle
