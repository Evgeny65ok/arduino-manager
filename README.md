# Arduino Manager GUI (Go + Fyne) — CI/CD

Учебный проект: GUI-приложение Arduino Manager на Go (Fyne) с автоматической сборкой под Linux, macOS, Windows через GitHub Actions и публикацией бинарников в GitHub Releases.

## 📸 Скриншоты

### 1. Работающее приложение
<img width="1875" height="1020" alt="Снимок экрана 2026-10-07 103520" src="https://github.com/user-attachments/assets/dc941a09-27ff-497a-b40e-b8de607bcb46" />

### 2. GitHub Actions — успешный CI/CD
<img width="1628" height="726" alt="Снимок экрана 2026-10-07 104220" src="https://github.com/user-attachments/assets/f44af85f-c26d-48c1-9b86-3339b56092a8" />


### 3. GitHub Release v1.0.0 — 3 бинарника
<img width="1563" height="822" alt="Снимок экрана 2026-10-07 104228" src="https://github.com/user-attachments/assets/a9e9046f-1ead-475f-81b9-008cc9b5abb2" />


## ⬇️ Скачать

Бинарники в Releases:
- 🐧 Linux x64 — `arduino-manager-linux-x64`
- 🍎 macOS ARM — `arduino-manager-macos-arm64`
- 🪟 Windows x64 — `arduino-manager-windows-x64.exe`

## 🛠 Сборка

git clone https://github.com/Evgeny65ok/arduino-manager.git
cd arduino-manager
go mod tidy
go run .

## 🔁 CI/CD

- Push в main → job test
- Push тега v* → job test + job release (3 бинарника)

## 👤 Автор

Evgeny65ok
