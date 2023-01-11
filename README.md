:black_square_button:# Шпоргалка с нужными мне командами (как я считаю, наиболее полезными).

1.  Создайте репозиторий git init

2.  Проверьте состояние репозитория git status

3.  Cнять индексацию этих изменений git reset

4.   co = checkout  --Альясы
     ci = commit (--amend - для того, чтобы не создавать новый коммит - можно просто изменить существующий)
     st = status
     br = branch
     hist = log --pretty=format:\"%h %ad | %s%d [%an]\" --graph --date=short
     type = cat-file -t
     dump = cat-file -p
     
5.  git revert - отмена и редакт коммита ( --hard - обновление в соответствии с новым head ветки)

6.  git hist - история коммитов ( --all - и ошибочные и действующие и удалённые коммиты) (git hist --max-count=1 поиск последнего коммита)

7.  git log - фильтрация и просматривание истории проекта

8.  git cat - provide content or type n size info for rep objects

9.  git checkout -b - create new branch

10. rebase и merge / rebase - для локальных веток, а merge для веток в публичном репозитории (но лучше не использовать rebase)

11. git clone - клонирование репозитория 

12. git clone <name repository, that need to be cloned> <name new cloned repository>

13. git branch -a  - увидеть список всех удалённых веток

14.	git fetch - штука которая  будет извлекать новые коммиты из удаленного репозитория, но не будет сливать их с вашими наработками в локальных ветках

15. git pull эквивалентна комбинации git fetch и git merge

16. git clone --bare <name repository, that need to be cloned> <name new cloned repository> - в комб с .git созд чистый репозиторий
