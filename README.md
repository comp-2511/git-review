# Git Review

## To create a snapshot in the history of your project, you need to:
- [ ] stage changes
- [ ] stage & commit changes
- [ ] commit changes

<details>
<summary>Answer</summary>
<br>

- [ ] stage changes
- [x] stage & commit changes (`git add -A && git commit -m"message"`)
- [ ] commit changes
</details>

---

## Which command merges the `stage` branch into the `dev` branch?

- [ ] `git checkout dev && git merge stage`
- [ ] `git checkout stage && git merge dev`
- [ ] `git checkout dev && git pull stage`

<details>
<summary>Answer</summary>
<br>

- [x] `git checkout dev && git merge stage`
- [ ] `git checkout stage && git merge dev`
- [ ] `git checkout dev && git pull stage`
</details>


---

## What is `origin`?

- [ ] your local copy of a Git repository
- [ ] your remote copy of a Git repository
- [ ] a short name or alias for the remote repository

<details>
<summary>Answer</summary>
<br>

- [ ] your local copy of a Git repository
- [ ] your remote copy of a Git repository
- [x] a short name or alias for the remote repository
</details>


---

## Which command moves all the changes in the `main` branch from the local repo to the remote repo?

- [ ] `git push main`
- [ ] `git push origin`
- [ ] `git push origin main`
- [ ] `git pull origin main`

<details>
<summary>Answer</summary>
<br>

- [ ] `git push main`
- [ ] `git push origin`
- [x] `git push origin main`
- [ ] `git pull origin main`
</details>

---

## To create a PR from branch `feat` to branch `main`:

- [ ] `git pull origin feat`
- [ ] `git pull origin main`
- [ ] `git push origin feat` then create a PR on GitHub
- [ ] `git push origin main` then create a PR on GitHub

<details>
<summary>Answer</summary>
<br>

- [ ] `git pull origin feat`
- [ ] `git pull origin main`
- [x] `git push origin feat` then create a PR on GitHub
- [ ] `git push origin main` then create a PR on GitHub
</details>

---

## What's the purpose of having a `.gitignore` file?

- [ ] to remove certain files/directories right after they're created
- [ ] to have a second repository under the main repository
- [ ] to remove certain files/directories from being tracked by Git

<details>
<summary>Answer</summary>
<br>

- [ ] to remove certain files/directories right after they're created
- [ ] to have a second repository under the main repository
- [x] to remove certain files/directories from being tracked by Git (`*.txt`, `__pycache__`)
</details>

---

## How to create a branch named `feat` and switch to it?

- [ ] `git branch feat && git checkout feat`
- [ ] `git checkout -b feat`
- [ ] both are correct

<details>
<summary>Answer</summary>
<br>

- [ ] `git branch feat && git checkout feat`
- [ ] `git checkout -b feat`
- [x] both are correct
</details>

---

## How to create a new branch named `feat` from the `dev` branch?

- [ ] `git checkout feat && git checkout -b dev`
- [ ] `git checkout dev && git checkout -b feat`
- [ ] both are correct

<details>
<summary>Answer</summary>
<br>

- [ ] `git checkout feat && git checkout -b dev`
- [x] `git checkout dev && git checkout -b feat`
- [ ] both are correct
</details>