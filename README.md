#Our first remote repository!
 ## …or create a new repository on the command line

 **echo "# Seminar3" >> README.md**
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ALORRIENAR/Seminar3.git
git push -u origin main


>…or push an existing repository from the command line
git remote add origin https://github.com/ALORRIENAR/Seminar3.git
git branch -M main
git push -u origin main

## Git Teams - Collaborate and update projects

**git fetch** - Команда git fetch связывается с удалённым репозиторием и забирает из него все изменения, которых у вас пока нет и сохраняет их локально.
