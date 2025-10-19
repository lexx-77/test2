cd /путь/к/проекту/test2
git pull origin main  # если уже привязан удалённый репозиторий
echo "one more commit" >> notes.txt
git add notes.txt
git commit -m "one more public commit"
git push origin main
