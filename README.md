# Introduction to GitHub
### Version control for data professionals

**I-AIR SEO — May 2026**
**Presenters:** James Anderson (Kaskaskia College) · Joel Swenddal (University of Illinois Urbana-Champaign)

---

## 📁 What's in this repository

This repo contains the slides and reference materials from our presentation on Git and GitHub for data professionals.

---

## ⬇️ How to get these files on your computer (the Git way)

You're going to **clone** this repository — which is exactly one of the concepts we covered in the presentation! Cloning means copying the entire repo from GitHub down to your local machine. Once cloned, you could even make your own changes and contribute back. Note that the steps below use the **command-line interface (CLI)**, but if you prefer clicking over typing, see the [GUI option](#prefer-a-visual-interface) at the end of this section.

### Step 1 — Install Git

If you haven't used Git before, you'll need to install it first.

- **Windows:** Download and run the installer from [git-scm.com/download/win](https://git-scm.com/download/win). Accept all the defaults.
- **Mac:** Open Terminal and type `git --version`. If Git isn't installed, macOS will prompt you to install it automatically.

To confirm Git is installed, open a terminal (Terminal on Mac, Git Bash or Command Prompt on Windows) and run:

```
git --version
```

You should see something like `git version 2.x.x`. If you do, you're good to go.

---

### Step 2 — Copy the repository URL

On this GitHub page, click the green **`< > Code`** button near the top right of the file list. Make sure **HTTPS** is selected, then click the copy icon to copy the URL to your clipboard.

It will look something like:
```
https://github.com/<username>/<repo-name>.git
```

---

### Step 3 — Open a terminal and navigate to where you want the files

Open a terminal window. By default you'll land in your home folder, which is fine. If you'd like the files somewhere specific (like your Desktop), navigate there first:

```bash
# Example: go to your Desktop
cd ~/Desktop
```

> **New to the terminal?** `cd` stands for "change directory." Think of it like clicking into a folder, but with text.

---

### Step 4 — Clone the repository

Run the following command, replacing the URL with the one you copied in Step 2:

```bash
git clone https://github.com/<username>/<repo-name>.git
```

Git will create a new folder with the repository name and download everything into it. You'll see output like:

```
Cloning into 'repo-name'...
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
Receiving objects: 100% (12/12), done.
```

---

### Step 5 — Open the folder

Navigate into the newly created folder:

```bash
cd <repo-name>
```

From here you can list the files to confirm everything downloaded:

```bash
# Mac/Linux
ls

# Windows Command Prompt
dir
```

You should see the presentation files listed. You can also just open the folder normally in File Explorer (Windows) or Finder (Mac) — it will be wherever you ran the `git clone` command.

---

### 🖱️ Prefer a visual interface?

If the terminal isn't your thing, **GitHub Desktop** ([desktop.github.com](https://desktop.github.com)) is a free GUI tool made by GitHub that lets you clone, commit, push, and pull using buttons and menus instead of commands. It uses all the same concepts from the presentation — just without the typing. It's a great starting point and works on both Windows and Mac.

---

## 🔄 Getting updates later

If we update the materials after the session, you can pull the latest changes without re-downloading everything. Just open your terminal, navigate back into the repo folder, and run:

```bash
git pull
```

That's it — Git will fetch only what changed.

---

## 📚 Want to learn more?

Here are the free resources we recommended in the presentation:

| Resource | Link |
|---|---|
| W3Schools Git Tutorial | [w3schools.com/git](https://www.w3schools.com/git) |
| GitHub Skills (interactive) | [skills.github.com](https://skills.github.com) |
| Atlassian Git Tutorials | [atlassian.com/git/tutorials](https://www.atlassian.com/git/tutorials) |
| GitHub Cheat Sheet (PDF) | [education.github.com/git-cheat-sheet-education.pdf](https://education.github.com/git-cheat-sheet-education.pdf) |

---

## 🙋 Questions?

Feel free to reach out to either presenter — contact info below.

**James Anderson** — Kaskaskia College — janderson@kaskaskia.edu

**Joel Swenddal** — University of Illinois Urbana-Champaign — jswen@illinois.edu
