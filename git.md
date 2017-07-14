## Git

<img src="https://raw.githubusercontent.com/rayout/presentations/workflow/git.jpg" width="400px" alt="Image-Absolute">

+++

### Создание репозитория

- $ cd some-project-path    |
- $ git init              |
- $ git add *.c           |
- $ git add README        |
- $ git add .             |
- $ git commit            |

### Клонирование существующего репозитория

```bash
$ git clone repo_url [dir]
```

### Запись изменений в репозиторий

![git add](git-1.png)

### Определение состояния файлов

- $ git status

Untracked   |
Modified    |
Added to commit |

### Отмена индексации файла

```bash
git reset
```

git reset --hard HEAD~1 - возврат к прошлому состоянию после коммита    |
git push --force origin master - перезапись истории удаленного репозитория <span style="color:red">!!!ОПАСНО!!!</span>  |

