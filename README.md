## CLIQ - CLI with an IQ hehe...
  - Aka Ai Powered Windows Terminal App

## Development

CLIQ is built with [Tauri 2](https://tauri.app/) (Rust backend) and a Vite + React + TypeScript frontend.

### Prerequisites (Windows)

- [Node.js](https://nodejs.org/) LTS: `winget install OpenJS.NodeJS.LTS`
- Rust (stable, MSVC toolchain): `winget install Rustlang.Rustup`, then `rustup default stable-msvc`
- Microsoft C++ Build Tools with the "Desktop development with C++" workload
- WebView2 runtime (preinstalled on Windows 11)

See the [Tauri prerequisites guide](https://tauri.app/start/prerequisites/) for details.

### Run

```sh
npm install
npm run tauri dev
```

## License

[Apache-2.0](LICENSE)
