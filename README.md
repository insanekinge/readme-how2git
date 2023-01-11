# Шпоргалка с нужными мне командами (как я считаю, наиболее полезными).:black_square_button:
____

### 1.  Создайте репозиторий git init
____

### 2.  Проверьте состояние репозитория git status
____

### 3.  Cнять индексацию этих изменений git reset
____

### 4. Альясы 
     - co = checkout  
     - ci = commit _(--amend - для того, чтобы не создавать новый коммит - можно просто изменить существующий)_
     - st = status
     - br = branch
     - hist = log --pretty=format:\"%h %ad | %s%d [%an]\" --graph --date=short
     - type = cat-file -t
     - dump = cat-file -p
____

### 5.  git revert - отмена и редакт коммита _( --hard - обновление в соответствии с новым head ветки)_
____

### 6.  git hist - история коммитов _( --all - и ошибочные и действующие и удалённые коммиты) (git hist --max-count=1 поиск последнего коммита)_
____

### 7.  git log - фильтрация и просматривание истории проекта
____

### 8.  git cat - provide content or type n size info for rep objects
____

### 9.  git checkout -b - create new branch
____

### 10. rebase и merge / rebase - для локальных веток, а merge для веток в публичном репозитории _(но лучше не использовать rebase)_
____

### 11. git clone - клонирование репозитория 
____

### 12. git clone <name repository, that need to be cloned> <name new cloned repository>
____
     
### 13. git branch -a  - увидеть список всех удалённых веток
____
     
### 14.	git fetch - штука которая  будет извлекать новые коммиты из удаленного репозитория, но не будет сливать их с вашими наработками в локальных ветках
____
     
### 15. git pull эквивалентна комбинации git fetch и git merge
____
     
### 16. git clone --bare <name repository, that need to be cloned> <name new cloned repository> - в комб с .git созд чистый репозиторий
____
