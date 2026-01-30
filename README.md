# rust-test

Minimal **Rust** project template with multiplatform CI/CD setup.

---

## 📦 Project Structure

```
rust-test-mirror/
├── src/
│ └── main.rs <- Main Rust code
├── Cargo.toml <- Rust configuration / dependencies
├── Cargo.lock <- Locked crate versions
├── .github/
│ └── workflows/ <- GitHub Actions CI/CD workflow
└── README.md <- This file
```

---

## ⚡ Build

### Requirements

- Rust stable ([https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install))
- Cargo (included with Rust)
- Optional: Docker for cross-compilation in CI

### Local build

`cargo build --release`

Artifact generated: target/release/rust-test (Linux/macOS) or rust-test.exe (Windows)

---


## 🤖 CI/CD

### This repo comes with GitHub Actions configured for:

- Linux (Ubuntu latest)
- Windows (Windows latest)
- macOS (macOS latest)

**Every push to main automatically builds the project and uploads the binaries as Artifacts, ready to download.**

---

## 🧪 Run

### Linux / macOS
./target/release/rust-test

### Windows
.\target\release\rust-test.exe


Expected output:

Hello, world!

---

📄 License

MIT License © ImTassingg

---

## 🔗 Links

- Original Codeberg repo: [rust-test]("https://codeberg.org/imtassingg/rust-test")
- GitHub mirror: [rust-test-mirror]("https://github.com/imtassingg/rust-test-mirror")
- Rust: https://www.rust-lang.org/
- GitHub Actions Docs: https://docs.github.com/actions

---
