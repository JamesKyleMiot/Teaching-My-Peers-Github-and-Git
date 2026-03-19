<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Teaching+My+Peers+Git+%26+GitHub;No+More+Flash+Drives.+We+Code+Like+Pros.;Built+by+Students%2C+for+Students." alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/branches">
    <img src="https://img.shields.io/badge/Peer_Branches-7-blue?style=for-the-badge&logo=git&logoColor=white" alt="Branches"/>
  </a>
  <a href="https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git">
    <img src="https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  </a>
  <a href="https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git">
    <img src="https://img.shields.io/badge/Year-1st_Year_CS-green?style=for-the-badge&logo=graduationcap&logoColor=white" alt="1st Year"/>
  </a>
  <a href="https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git">
    <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge&logo=statuspage&logoColor=white" alt="Status"/>
  </a>
</p>

---

## 🧭 What Is This?

This repository is a **live training ground** where first-year Computer Science students learn **Git**, **GitHub**, and **real-world collaboration workflows**—by actually using them.

Instead of lectures and slideshows, we learn by doing:

> **I push small Java problems to each peer's personal branch → they pull, solve, commit, and push back → they learn Git by living it.**

Every `git pull`, every `git commit`, every merge conflict is a lesson. The codebase is the classroom.

---

## 💡 Why This Exists

<table>
<tr>
<td width="60%">

Most first-year students collaborate through **flash drives, Messenger, and copy-pasting code**. That works—until it doesn't. Overwritten files, lost progress, zero version history.

I'm **Jan Rhian Angulo**, a first-year student myself. Nobody told me to build this. No professor assigned it. I just saw my classmates struggling with the same problems I once had, and I decided to do something about it.

**This is my dedication**: to train my peers in the tools that real software engineers use every single day, so that by the time we hit our stride, we're not playing catch-up—we're already ahead.

If I can give them even a head start on version control and collaboration, that's a **brighter future** they didn't have to wait for.

</td>
<td width="40%">

### 🎯 Core Goals
- ✅ Replace flash drives with `git push`
- ✅ Build muscle memory for Git commands
- ✅ Understand branching & collaboration
- ✅ Experience real GitHub workflows
- ✅ Practice Java through bite-sized problems
- ✅ Learn to read, debug & fix code
- ✅ Build confidence for future team projects

</td>
</tr>
</table>

---

## 👥 The Team

Each peer has their own **personal branch**—their sandbox to learn, make mistakes, and grow. The `main` branch stays stable and is managed by Jan as the training lead.

| Branch | Peer | Role |
|:---|:---|:---|
| `main` | **Jan Rhian Angulo** | 🧑‍🏫 Training Lead |
| `amper-learning` | **Amper** | 🧑‍💻 Trainee |
| `apenas-learning` | **Apenas** | 🧑‍💻 Trainee |
| `miot-learning` | **Miot** | 🧑‍💻 Trainee |
| `nelson-learning` | **Nelson** | 🧑‍💻 Trainee |
| `perez-learning` | **Perez** | 🧑‍💻 Trainee |
| `raven-learning` | **Raven** | 🧑‍💻 Trainee |
| `silva-learning` | **Silva** | 🧑‍💻 Trainee |

> **📌 Rule**: You only work on **your** branch. Never commit directly to `main`.

---

## ⚙️ How It Works

The entire learning process follows a cycle that mirrors real-world software development:

```
┌─────────────────────────────────────────────────────────────────────┐
│                        THE TRAINING CYCLE                           │
│                                                                     │
│   ① Jan pushes a Java problem/buggy code to your branch             │
│                          ↓                                           │
│   ② You pull the latest changes from your branch                    │
│                          ↓                                           │
│   ③ You read, understand, and solve the problem in your IDE         │
│                          ↓                                           │
│   ④ You stage, commit with a descriptive message, and push          │
│                          ↓                                           │
│   ⑤ Jan reviews your commit and gives feedback                      │
│                          ↓                                           │
│   ⑥ Repeat. Each cycle builds your Git muscle memory.               │
└─────────────────────────────────────────────────────────────────────┘
```

This isn't just about learning Java—it's about learning **how developers actually collaborate** using version control. The Java problems are the vehicle; **Git is the destination.**

---

## 🚀 Getting Started (For Peers)

### Prerequisites

| Tool | Why You Need It | Link |
|:---|:---|:---|
| **Git** | Version control on your machine | [git-scm.com](https://git-scm.com/) |
| **GitHub Account** | To access this repository | [github.com](https://github.com/) |
| **Java JDK** | To compile and run exercises | [adoptium.net](https://adoptium.net/) |
| **VS Code or IntelliJ** | To write and test code | [code.visualstudio.com](https://code.visualstudio.com/) |

### First-Time Setup

```bash
# 1. Clone this repository to your computer
git clone https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git.git
cd Teaching-My-Peers-Github-and-Git

# 2. Set up your identity (use your real name and email)
git config --global user.name "Your Full Name"
git config --global user.email "your-email@example.com"

# 3. Switch to YOUR personal branch
git checkout your-branch-name
# Example: git checkout amper-learning
```

> 💡 **Tip**: You only need to do the setup once. After that, it's all about the daily workflow below.

---

## 🔄 Daily Workflow

This is the cycle you will repeat for **every exercise**. Memorize it. It will become second nature.

### Step 1 · Switch to Your Branch
```bash
git checkout your-branch-name
```

### Step 2 · Pull the Latest Exercise
```bash
git pull origin your-branch-name
```
> Jan will have pushed new problems or buggy code for you to work on.

### Step 3 · Solve the Problem
Open the file(s) in your IDE. Read the code. Fix the bug or implement the solution. **Test it** before moving on.

### Step 4 · Stage & Commit
```bash
git add .
git commit -m "Fix: describe what you fixed or solved"
```
> ✍️ Write **meaningful** commit messages. `"Fix: corrected off-by-one error in loop"` is great. `"fixed stuff"` is not.

### Step 5 · Push Your Work
```bash
git push origin your-branch-name
```

### Step 6 · Wait for Feedback
Jan will review your commits on GitHub and provide feedback—either through **GitHub comments** or in person.

---

## 📋 Exercise Types

| Type | What Happens | What You Learn |
|:---|:---|:---|
| 🐛 **Bug Fix** | Jan pushes broken Java code → you fix it | Debugging, reading errors, Java fundamentals |
| ✨ **Feature Build** | Jan assigns a small feature → you implement it | Problem-solving, writing clean code |
| 🔀 **Git Challenge** | Specific Git tasks (merge, resolve conflicts, etc.) | Advanced Git workflows |
| 📝 **Pull Request** | Submit your work via PR to `main` for review | Code review, collaboration etiquette |

---

## 📖 What You'll Learn (Progressively)

```
Phase 1 — The Basics                    Phase 2 — Intermediate
─────────────────────                   ─────────────────────────
☑ Clone a repository                    ☐ Resolve merge conflicts
☑ Checkout a branch                     ☐ Understand Git history (git log)
☑ Pull changes                          ☐ Write proper commit messages
☑ Stage and commit                      ☐ Create Pull Requests
☑ Push to remote                        ☐ Review peer code on GitHub

Phase 3 — Advanced (Future)
─────────────────────────────
☐ Branching strategies (feature branches)
☐ GitHub Actions & CI/CD basics
☐ Collaborative project development
☐ Open source contribution workflow
```

---

## 📌 Quick Reference Card

| Command | What It Does |
|:---|:---|
| `git clone <url>` | Download the repository to your machine |
| `git checkout <branch>` | Switch to a different branch |
| `git pull origin <branch>` | Download the latest changes from GitHub |
| `git status` | See what files have changed |
| `git add .` | Stage all your changes for commit |
| `git commit -m "message"` | Save your changes with a description |
| `git push origin <branch>` | Upload your changes to GitHub |
| `git log --oneline` | View a compact commit history |
| `git diff` | See what changed before committing |

---

## 🤝 Ground Rules

1. **Pull before you code.** Always `git pull` before starting any work.
2. **Stay on your branch.** Never touch `main` directly.
3. **Commit small, commit often.** One fix = one commit. Don't bundle everything.
4. **Write real commit messages.** Describe *what* you changed and *why*.
5. **Ask for help.** Everyone here is learning. There are no dumb questions.
6. **Break things.** That's how you learn. Git can always undo your mistakes.

---

## 📚 Resources to Level Up

| Resource | Description |
|:---|:---|
| [Pro Git Book](https://git-scm.com/book/en/v2) | The definitive guide to Git (free) |
| [GitHub Docs](https://docs.github.com/en) | Official GitHub documentation |
| [Learn Git Branching](https://learngitbranching.js.org/) | Interactive visual Git tutorial |
| [Oh My Git!](https://ohmygit.org/) | A game to learn Git concepts |
| [W3Schools Java](https://www.w3schools.com/java/) | Quick Java reference |
| [Git Cheat Sheet (PDF)](https://education.github.com/git-cheat-sheet-education.pdf) | Printable Git commands |

---

## 🔮 Roadmap

- [x] Set up repository with personal branches for all peers
- [ ] Push initial Java exercises (bug fixes)
- [ ] Introduce feature-building exercises
- [ ] Teach merge conflict resolution
- [ ] Introduce Pull Requests and code review
- [ ] Set up GitHub Actions for auto-testing
- [ ] Collaborative mini-project as final exercise

---

<p align="center">
  <br/>
  <strong>Built with dedication by a first-year student who believes<br/>that the best way to learn is to lift others up with you.</strong>
  <br/><br/>
  <em>"No one told me to do this. I just knew it needed to be done."</em>
  <br/>
  — Jan Rhian Angulo
  <br/><br/>
  <a href="https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git">
    <img src="https://img.shields.io/badge/Let's_Learn_Together-🚀-blue?style=for-the-badge" alt="Let's Learn Together"/>
  </a>
</p>
