# Git commands (each member)

```bash
git clone <repo-link>
cd pet-adoption-system
git checkout -b feature/your-task      # create your branch
# ...do your work...
git add .
git commit -m "Clear message about what you did"
git push origin feature/your-task
```
Then on GitHub: **Compare & pull request** > ask a teammate to review > **Merge**.

Update your local copy:
```bash
git checkout main
git pull
```

First-time upload (only one member):
```bash
git init
git add .
git commit -m "Initial project structure"
git branch -M main
git remote add origin <repo-link>
git push -u origin main
```
