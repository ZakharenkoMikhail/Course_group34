# HW GitHub
## GIT Homework 2
---
1. На локальном репозитории сделать ветки для:

- Postman === `git branch Postman`
- Jmeter === `git branch Jmeter`
- CheckLists === `git branch CheckLists`
- Bug_Reports === `git branch Bug_Reports`
- SQL === `git branch SQL`
- Charles === `git branch Charles`
- Mobile_testing === `git branch Mobile_testing`

2. Запушить все ветки на внешний репозиторий === `git push origin --all`

3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта === `git checkout Bug_Reports` --> `vim Bug_Report.txt`

4. Запушить структуру багрепорта на внешний репозиторий === `git add Bug_Report.txt` --> `git commit -m "comment"` --> `git push` 

5. Вмержить ветку Bug Reports в Main === `git checkout main` --> `git merge Bug_Reports`

6. Запушить main на внешний репозиторий. === `git push`

7. В ветке CheckLists набросать структуру чек листа. === `git checkout CheckLists` --> `vim CheckLists.txt`

8. Запушить структуру на внешний репозиторий === `git add .` --> `git commit -m "comment"` --> `git push`

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main === На https://github.com Pull requests --> New pull requets --> Create pull request --> Merge pull request --> Confirm merge

10. Синхронизировать Внешнюю и Локальную ветки Main === `git checkout main` --> `git pull`