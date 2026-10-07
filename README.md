# Arduino Manager GUI (Go + Fyne) — CI/CD

Учебный проект: GUI-приложение Arduino Manager на Go (Fyne) с автоматической сборкой под Linux, macOS, Windows через GitHub Actions и публикацией бинарников в GitHub Releases.

## 📸 Скриншоты

### 1. Работающее приложение
![Приложение](app.png)

### 2. GitHub Actions — успешный CI/CD
![Actions](actions.png)

### 3. GitHub Release v1.0.0 — 3 бинарника
![Release](release.png)

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
