# 🐚 Custom Linux Shell in C++

## 🎯 Objective
Build a **custom Linux shell** in C++ that can execute commands, manage processes, handle I/O redirection and piping, and provide enhanced shell features — similar to Bash or Zsh — with your own logic and user interface.

---

## 🗓️ 5-Day Assignment Plan

| Day | Task | Status |
|-----|------|---------|
| **Day 1** | Plan the shell features and parse user input | ✅ |
| **Day 2** | Implement execution of basic commands through the shell | ✅ |
| **Day 3** | Add support for process management (foreground & background processes) | ✅ |
| **Day 4** | Implement piping and redirection features | ✅ |
| **Day 5** | Incorporate job control (listing jobs, bringing jobs to foreground/background) | ✅ |

---

## ⚙️ Features Implemented

### 🔐 Password Authentication
- Shell starts only after entering a password (`admin123` by default).

### 📜 Command History
- Tracks all previously executed commands.
- View history by typing:
  ```bash
  history
