# Snippets
Odds and ends
## Git
#### Fork a repository from Gitlab to Github
```bash
git clone new.repo.git
cd my_repo
git remote add upstream repo.to.fork.git
git pull upstream main --rebase=False --allow-unrelated-histories
git commit -a
git push
```
