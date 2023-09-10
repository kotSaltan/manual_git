# Git manual
## Main commands
* git init - Initialized empty git repository
* git add path_to_file - Update the index with the contents of a new or modified file
* git commit - m "massage" - Create a new commit with your "massage"
* git commit -a -m "massage" - Shortcut to updating the index with a modified file and creating a new commit with your "massage"

## Other commands
* git status - a brief summary of changes
* git diff - difference between the index file and your working directory; changes that would not be included if you ran "commit" now.
* git log - Shows a list of commits

## Branches

* git checkout branch_name - Switch to branch_name branch
* git checkout -b branch_name Create a new branch with branch_name and switch to it
* git branch - List of branches
* git branch branch_name - Create a branch with branch_name
* git merge branch_name - Merges branch_name into current branch
* git branch -d branch_name - Delete branch with branch_name

## Markdown instructions

### Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *вот так* или _так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или знаком нижнего подчеркивания (_). Например, **вот так** или __так__.

Альтернативные способы выделения текста жирным или курсивом необходимы для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом **быть полужирным**_.

Чтобы получить зачеркнутый текст, необходимо обрамить его двумя знаками тильды (~~).
Например ~~вот так~~.

Чтобы получить подчеркнутый текст, необходимо обрамить его тегами.
Например <u>вот так</u>.

Чтобы получить горизонтальную разделительную черту, необходимо отметить пустую строку тремя звезжочками, тремя нижними подчеркиваниями или тремя тире. Приэтом между текстом и строкой расположения знаков должна быть пустая строка.
Например:

---

Первый текст

***
Второй текст
___
Третий текст

### Списки

Чтобы добавить ненумерованный список, необходимо пункты выделить звездочкой (*), минумсом (-) или плюсиком (+).
Например вот так:
* Элемент 1
- Элемент 2
+ Элемент 3

Чтобы добавить нумерованный список, необходимо пункты просто пронумеровать. Главное чтобы первый пункт был под номером 1.
Например вот так:
1. Первый пункт
2. Второй пункт
7. Третий пункт
9. Четвертый пункт

