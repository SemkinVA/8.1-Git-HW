# 8.1-Git-HW
### Домашнее задание к занятию 8.1 - "Git" - Семкин Вячеслав
***
### Задание 1

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

**Ответ:**

Ссылка на First commit https://github.com/SemkinVA/8.1-Git-HW/commit/261f05b8296ecd918fb77503806bd9545fad2e68

1. Зарегистрируйте аккаунт на [GitHub](https://github.com/). 

![1-1](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-1.png)

2. Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».

![1-2](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-2.png)

3. Склонируйте репозиторий, используя https протокол `git clone ...`.

![1-3](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-3.png)

4. Перейдите в каталог с клоном репозитория.

![1-4](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-4.png)

5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.

![1-5](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-5.png)

6. Выполните команду `git status` и запомните результат.

![1-6](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-6.png)

7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.

![1-7](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-7.png)

8. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.

![1-8](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-8.png)

9. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.

![1-9](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-9.png)

10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.

![1-10](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-10.png)

11. Ещё раз выполните команды `git diff` и `git diff --staged`.

![1-11](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-11.png)

12. Теперь можно сделать коммит `git commit -m 'First commit'`.

![1-12](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-12.png)

13. Сделайте `git push origin master`.

![1-13](https://github.com/SemkinVA/8.1-Git-HW/blob/main/1-13.png)
***
### Задание 2

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

**Ответ:**

Ссылка на Second commit https://github.com/SemkinVA/8.1-Git-HW/commit/0b24a6d30a374c02811326263f26943462d4dab4


1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.

![2-1](https://github.com/SemkinVA/8.1-Git-HW/blob/main/2-1.png)

2. Добавьте файл .gitignore в следующий коммит `git add...`.

![2-2](https://github.com/SemkinVA/8.1-Git-HW/blob/main/2-2.png)

3. Напишите правила в этом файле, чтобы игнорировать любые файлы `.pyc`, а также все файлы в директории `cache`.

![2-3](https://github.com/SemkinVA/8.1-Git-HW/blob/main/2-3.png)

4. Сделайте коммит и пуш.

![2-4](https://github.com/SemkinVA/8.1-Git-HW/blob/main/2-4.png)
***
### Задание 3

В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

**Ответ:**

Сссылка на график коммитов https://github.com/SemkinVA/8.1-Git-HW/network


1. Создайте новую ветку dev и переключитесь на неё.

![3-1](https://github.com/SemkinVA/8.1-Git-HW/blob/main/3-1.png)

2. Создайте файл test.sh с произвольным содержимым.

![3-2](https://github.com/SemkinVA/8.1-Git-HW/blob/main/3-2.png)

3. Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.

![3-3](https://github.com/SemkinVA/8.1-Git-HW/blob/main/3-3.png)

4. Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать `git merge`.

![3-4](https://github.com/SemkinVA/8.1-Git-HW/blob/main/3-4.png)

5. Сделайте коммит и пуш.

![3-5](https://github.com/SemkinVA/8.1-Git-HW/blob/main/3-5.png)

