# Git flow demo project

---

##### How to make it

1. [Create](https://github.com/new) public repository on GitHub with name '`new-project`'.
2. Create initial README.md file <br/>`echo "Some step-by-step instructions" >> README.md`
3. Initialize local repository <br/>`git init`
4. Add file to the index <br/>`git add README.md`
5. Commit first changes <br/>`git commit -m "init"`
6. Rename branch from `master` to `main` <br/>`git branch -M main`
7. Attach your local repository to GitHub repository <br/>`git remote add origin git@github.com:<your_username>/new-project.git`
8. Push changes to main in public repo <br/>`git push -u origin main`
9. Checkout and create `development` branch <br/>`git checkout -b development`
10. Paste text from file you reading right now to README.md
11. Commit changes README.md <br/>`git commit -m "updated README.md"`
12. Publish development branch with changes <br/>`git push -u origin development`
13. Checkout `main` branch <br/>`git checkout main`
14. (Optional) Refresh `main` on local repository <br/>`git fetch origin`
15. Merge changes from `development` into `main` <br/>`git merge development`
16. Verify that `main` has changes from `development` (check last commit) <br/>`git show --summary`
17. Publish changes on `main` <br/>`git push -u origin main`
