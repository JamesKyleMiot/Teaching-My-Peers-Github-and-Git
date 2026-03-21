<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,100:1F6FEB&height=140&section=header" width="100%"/>

<h1 align="center">Miot's Learning Branch</h1>

<p align="center">
  <img src="https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/actions/workflows/java-compile-check.yml/badge.svg?branch=miot-learning" alt="Build Status"/>
</p>

<p align="center">`░░░░░░░░░░` **0/7** exercises passing</p>

---

## ❌ Compilation Errors — 7/7 File(s) Failed

Don't worry — **errors are how we learn!** Here's what went wrong:


### `HelloWorld.java`
```
exercises/exercise01_hello_world/HelloWorld.java:15: error: ';' expected
        System.out.printl("Hello, World!")
                                          ^
1 error
```

### `FavoriteMovie.java`
```
exercises/exercise01_naming/FavoriteMovie.java:3: error: class favoritEmovie is public, should be declared in a file named favoritEmovie.java
public class favoritEmovie {
       ^
exercises/exercise01_naming/FavoriteMovie.java:10: error: incompatible types: String cannot be converted to int
        int age = "0";
                  ^
exercises/exercise01_naming/FavoriteMovie.java:12: error: incompatible types: int cannot be converted to boolean
        boolean gender = 0;
                         ^
exercises/exercise01_naming/FavoriteMovie.java:14: error: cannot find symbol
        System.out.println(Name);
                           ^
  symbol:   variable Name
  location: class favoritEmovie
4 errors
```

### `Variables.java`
```
exercises/exercise03_variables/Variables.java:7: error: incompatible types: String cannot be converted to int
        int message = "Hello, Learning!";
                      ^
1 error
```

### `BasicMath.java`
```
exercises/exercise04_math/BasicMath.java:7: error: incompatible types: possible lossy conversion from double to int
        int score = 5.5;
                    ^
1 error
```

### `Greeting.java`
```
exercises/exercise05_strings/Greeting.java:9: error: ')' expected
        System.out.println("Hello, " firstName + " " + lastName);
                                    ^
exercises/exercise05_strings/Greeting.java:9: error: not a statement
        System.out.println("Hello, " firstName + " " + lastName);
                                                     ^
exercises/exercise05_strings/Greeting.java:9: error: ';' expected
        System.out.println("Hello, " firstName + " " + lastName);
                                                               ^
3 errors
```

### `AgeCheck.java`
```
exercises/exercise06_logic/AgeCheck.java:8: error: incompatible types: int cannot be converted to boolean
        if (age = 18) {
                ^
1 error
```

### `Counter.java`
```
exercises/exercise07_loops/Counter.java:6: error: ';' expected
        for (int i = 1; i <= 5 i++) {
                              ^
1 error
```

> 🔗 **[Open the failing file in github.dev](https://github.dev/Rust-Frog/Teaching-My-Peers-Github-and-Git/blob/miot-learning/exercises/exercise01_hello_world/HelloWorld.java)** — fix it right in your browser!

> 💪 **You got this!** Fix the errors above, commit, and push again.
> The badge will turn green when your code compiles.
>
> **Stuck?** Ask Jan for help — that's what a trainer is for!

---

## 📝 How to Solve Exercises

Pick whichever method works best for you:

<details open>
<summary><strong>🌐 Option 1 — Edit on GitHub (Easiest, No Setup)</strong></summary>

<br/>

1. Navigate to your file in the [`exercises/`](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/tree/miot-learning/exercises) folder
2. Click the **✏️ pencil icon** (top right of the file)
3. Fix the code right in the browser
4. Scroll down and click **"Commit changes"**
5. Done! CI will check your code automatically

</details>

<details>
<summary><strong>💻 Option 2 — Use github.dev (VS Code in Your Browser)</strong></summary>

<br/>

1. Go to [this repo](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git)
2. Make sure you're on branch `miot-learning`
3. Press the **`.`** key (period) on your keyboard — this opens **VS Code in your browser**!
4. Edit the file, save it (`Ctrl+S`)
5. Click the **Source Control** icon (left sidebar) → stage, commit, and push

> 💡 Or go directly: [github.dev/Rust-Frog/Teaching-My-Peers-Github-and-Git/tree/miot-learning](https://github.dev/Rust-Frog/Teaching-My-Peers-Github-and-Git/tree/miot-learning)

</details>

<details>
<summary><strong>🖥️ Option 3 — Clone Locally (Full Dev Setup)</strong></summary>

<br/>

```bash
# Clone the repo
git clone https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git.git
cd Teaching-My-Peers-Github-and-Git

# Switch to your branch
git checkout miot-learning

# Open in your editor, fix the code, then:
git add .
git commit -m "Fix: describe what you fixed"
git push origin miot-learning
```

</details>

---

## 📋 Your Exercises

**0/7 exercises compiling**

| # | Folder | File | Status |
|:--|:-------|:-----|:------:|
| 1 | `exercises/exercise01_hello_world` | [HelloWorld.java](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/blob/miot-learning/exercises/exercise01_hello_world/HelloWorld.java) | ❌ |
| 2 | `exercises/exercise01_naming` | [FavoriteMovie.java](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/blob/miot-learning/exercises/exercise01_naming/FavoriteMovie.java) | ❌ |
| 3 | `exercises/exercise03_variables` | [Variables.java](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/blob/miot-learning/exercises/exercise03_variables/Variables.java) | ❌ |
| 4 | `exercises/exercise04_math` | [BasicMath.java](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/blob/miot-learning/exercises/exercise04_math/BasicMath.java) | ❌ |
| 5 | `exercises/exercise05_strings` | [Greeting.java](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/blob/miot-learning/exercises/exercise05_strings/Greeting.java) | ❌ |
| 6 | `exercises/exercise06_logic` | [AgeCheck.java](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/blob/miot-learning/exercises/exercise06_logic/AgeCheck.java) | ❌ |
| 7 | `exercises/exercise07_loops` | [Counter.java](https://github.com/Rust-Frog/Teaching-My-Peers-Github-and-Git/blob/miot-learning/exercises/exercise07_loops/Counter.java) | ❌ |

---

## 📌 Quick Commands

| Command | What It Does |
|:---|:---|
| `git checkout miot-learning` | Switch to your branch |
| `git pull origin miot-learning` | Get latest changes |
| `javac YourFile.java` | Compile locally |
| `java YourFile` | Run your code |
| `git add . && git commit -m "msg"` | Save your work |
| `git push origin miot-learning` | Upload to GitHub |

---

<p align="center">
  <em>This README is automatically updated by GitHub Actions after every push.</em><br/>
  <strong>Keep coding, keep learning! 🚀</strong>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,100:1F6FEB&height=100&section=footer" width="100%"/>
