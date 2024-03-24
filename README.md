# Git workflow

Create new directory and cd there:

```bash
mkdir new-project
cd new-project
```

Init Git:

```bash
git init
```

Add README.md and commit it to the **main** branch:

```bash
touch README.md
git add README.md
git commit -m "init"
```

Create new branch:

```bash
git checkout -b development
```

Stage new files or changes:

```bash
git add .
```

Commit staged changes:

```bash
git commit -m "Update instructions"
```

Merge changes:

```bash
git switch main
git merge development
```

Add remote origin:

```bash
git remote add origin https://github.com/damevanderjahr/new-project.git
```

Push changes to remote:

```bash
git push origin
```
