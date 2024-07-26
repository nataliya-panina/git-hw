# Домашнее задание к занятию "`GIT`" - `Panina Nataliya`

### Задание 1

    `Что нужно сделать:
    Зарегистрируйте аккаунт на GitHub.
    Создайте новый отдельный публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
    Склонируйте репозиторий, используя https протокол git clone ....
    Перейдите в каталог с клоном репозитория.
    Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.
    Выполните команду git status и запомните результат.
    Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
    Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.
    Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.
    Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.
    Ещё раз выполните команды git diff и git diff --staged.
    Теперь можно сделать коммит git commit -m 'First commit'.
    Сделайте git push origin master.

    В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.`

**Решение**

1. `Зарегистрировав аккаунт, я сделала fork предложенного репозитория в свой`
2. `Сначала я на своей машине установила git и создала каталог для работы, затем cd git && git init`
3. `git clone https://github.com/nataliya-panina/git-hw`
4. `git config --global user.name nataliya-panina && git config --global user.email nataliya.sabathier@gmail.com`
5. `git status, git diff, git diff --staged`
6. `git add .`
7. `Теперь можно сделать коммит git commit -m 'First commit'.`
8. `git push --set-upstream origin git1`

	`commit 2f2610a56199f35a92cd72bf4d3168e95de1c3e6 (HEAD -> git1, origin/git1)
	![git img1](https://github.com/nataliya-panina/git-hw/blob/git1/git_status1.png)`


---

### Задание 2

`Что нужно сделать:

    Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
    Добавьте файл .gitignore в следующий коммит git add....
    Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
    Сделайте коммит и пуш.

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.`

**Решение**

1. `nano .gitignore:`
	moi@vmubu:~/git-1/git-hw$ git status
	Текущая ветка: git1
	Эта ветка соответствует «origin/git1».

	Неотслеживаемые файлы:
	  (используйте «git add <файл>...», чтобы добавить в то, что будет включено в коммит)
	..gitignore.swp

	индекс пуст, но есть неотслеживаемые файлы
	(используйте «git add», чтобы проиндексировать их)
`
2. `git status, git diff`
3. `git add .gitignore`
4. `git commit -m "gitignore"`
5. `git push`
6. ``

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота 2](ссылка на скриншот 2)`


---

### Задание 3

`Что нужно сделать:

    Создайте новую ветку dev и переключитесь на неё.
    Создайте в ветке dev файл test.sh с произвольным содержимым.
    Сделайте несколько коммитов и пушей в ветку dev, имитируя активную работу над файлом в процессе разработки.
    Переключитесь на основную ветку.
    Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev ветке.
    Сделайте мердж dev ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.
    Сделайте пуш в основной ветке.
    Не удаляйте ветку dev.

В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

### Задание 4 *

`Сэмулируем конфликт. Перед выполнением изучите документацию.

Что нужно сделать:

    Создайте ветку conflict и переключитесь на неё.
    Внесите изменения в файл test.sh.
    Сделайте коммит и пуш.
    Переключитесь на основную ветку.
    Измените ту же самую строчку в файле test.sh.
    Сделайте коммит и пуш.
    Сделайте мердж ветки conflict в основную ветку и решите конфликт так, чтобы в результате в файле оказался код из ветки conflict.

В качестве ответа на задание прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл
с решением.`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`
