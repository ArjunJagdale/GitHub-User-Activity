# GitHub User Activity
# 🧰 GitHub User Activity CLI

A lightweight and user-friendly CLI tool built in Go to fetch and display recent public activity for any GitHub user.

## ✨ Features
- Fetches recent GitHub events using the GitHub REST API
- Stylish terminal output using [Lipgloss](https://github.com/charmbracelet/lipgloss)
- Clean CLI interface built with [Cobra](https://github.com/spf13/cobra)

## How to run

Clone the repository and run the following command:

```bash
git clone https://github.com/arikchakma/backend-projects.git
cd backend-projects/github-user-activity
```

Run the following command to build and run the project:

```bash
go build -o github-activity
./github-activity ArjunJagdale
```
## Project ScreenShots 
<img width="1919" height="1016" alt="Screenshot 2025-08-05 120214" src="https://github.com/user-attachments/assets/5cdb6c3d-737d-4ad1-8a7b-4f09e04c83e6" />

---

## 🛠️ Tech Stack

* **Language:** Go (v1.21)
* **Libraries:** Cobra (CLI), Lipgloss (terminal UI), net/http (API calls), encoding/json (parsing)


## 📸 Sample Output

```
ArjunJagdale's recent activity(s)

- Pushed 1 commit(s) to ArjunJagdale/Verilog-Compiler-Using-Flask-and-React
───────────────────────────────────────────────────────────────────────────
- Created repository in ArjunJagdale/ArjunJagdale.github.io
──────────────────────────────────────────────────────────────
```

## 📦 Installation (Optional)

```bash
git clone https://github.com/arikchakma/backend-projects.git
cd backend-projects/github-user-activity
go build -o github-activity
```

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
