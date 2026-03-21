<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,100:1F6FEB&height=140&section=header" width="100%"/>

<h1 align="center">{{STUDENT_NAME}}'s Learning Branch</h1>

<p align="center">
  <img src="https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/actions/workflows/java-compile-check.yml/badge.svg?branch={{BRANCH_NAME}}" alt="Build Status"/>
</p>

---

{{STATUS_SECTION}}

---

## 📝 How to Solve Exercises

Pick whichever method works best for you:

<details open>
<summary><strong>🌐 Option 1 — Edit on GitHub (Easiest, No Setup)</strong></summary>

<br/>

1. Navigate to your file in the [`exercises/`](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/tree/{{BRANCH_NAME}}/exercises) folder
2. Click the **✏️ pencil icon** (top right of the file)
3. Fix the code right in the browser
4. Scroll down and click **"Commit changes"**
5. Done! CI will check your code automatically

</details>

<details>
<summary><strong>💻 Option 2 — Use github.dev (VS Code in Your Browser)</strong></summary>

<br/>

1. Go to [this repo](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git)
2. Make sure you're on branch `{{BRANCH_NAME}}`
3. Press the **`.`** key (period) on your keyboard — this opens **VS Code in your browser**!
4. Edit the file, save it (`Ctrl+S`)
5. Click the **Source Control** icon (left sidebar) → stage, commit, and push

> 💡 Or go directly: [github.dev/Rust-Frog/Teaching-My-Peers-Github-and-Git/tree/{{BRANCH_NAME}}](https://github.dev/Rust-Frog/Teaching-My-Peers-Github-and-Git/tree/{{BRANCH_NAME}})

</details>

<details>
<summary><strong>🖥️ Option 3 — Clone Locally (Full Dev Setup)</strong></summary>

<br/>

```bash
# Clone the repo
git clone https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git.git
cd Teaching-My-Peers-Github-and-Git

# Switch to your branch
git checkout {{BRANCH_NAME}}

# Open in your editor, fix the code, then:
git add .
git commit -m "Fix: describe what you fixed"
git push origin {{BRANCH_NAME}}
```

</details>

---

## 📋 Your Exercises

{{EXERCISE_SUMMARY}}

{{EXERCISE_TABLE}}

---

## 📌 Quick Commands

| Command | What It Does |
|:---|:---|
| `git checkout {{BRANCH_NAME}}` | Switch to your branch |
| `git pull origin {{BRANCH_NAME}}` | Get latest changes |
| `javac YourFile.java` | Compile locally |
| `java YourFile` | Run your code |
| `git add . && git commit -m "msg"` | Save your work |
| `git push origin {{BRANCH_NAME}}` | Upload to GitHub |

---

<p align="center">
  <em>This README is automatically updated by GitHub Actions after every push.</em><br/>
  <strong>Keep coding, keep learning! 🚀</strong>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,100:1F6FEB&height=100&section=footer" width="100%"/>
