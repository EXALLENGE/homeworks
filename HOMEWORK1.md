 Домашняя работа состоит из двух частей.

Первая:
1. Создать репозиторий на GitHub внутри компании(куда мы вас пригласили). Репозиторий нужно назвать в формате фамилия_task_1.
2. Сделать несколько коммитов в master через git.
3. Создать новую ветку, в ней тоже сделать несколько коммитов.
4. Вернуться в master, в нем тоже сделать несколько коммитов, чтобы ветки разошлись.
5. Смержить вторую ветку в master.
6. Отправить изменения на сервер.
Для проверки необходима ссылка на репозиторий.

Вторая:
Требуется реализовать консольную версию игры «Виселица». Программу нужно разместить на github, репозиторий нужно назвать в формате фамилия_task_2.
Предлагается следующий протокол общения компьютера с пользователем:

Пример выигрыша:
```
> Guess a letter:
< a
> Missed, mistake 1 out of 5.
>
> The word: *****
> 
> Guess a letter:
< b
> Missed, mistake 2 out of 5.
> 
> The word: *****
> 
> Guess a letter:
< e
> Hit!
> 
> The word: *e***
> 
> Guess a letter:
< o
> Hit!
>
> The word: *e**o
> 
> Guess a letter:
< l
> Hit!
>
> The word: *ello
> 
> Guess a letter:
< h
> Hit!
>
> The word: hello
>
> You won!
```
Пример проигрыша:
```
> Guess a letter:
< x
> Missed, mistake 1 out of 5.
>
> The word: ******
>
> Guess a letter:
< y
> Missed, mistake 2 out of 5.
>
> The word: ******
>
> Guess a letter:
< z
> Missed, mistake 3 out of 5.
>
> The word: ******
> 
> Guess a letter:
< n
> Hit!
>
> The word: **n*n*
>
> Guess a letter:
< m
> Missed, mistake 4 out of 5.
>
> The word: **n*n*
>
> Guess a letter:
< o
> Missed, mistake 5 out of 5.
>
> The word: **n*n*
>
> You lost!
```

Слово загадывается случайным образом из заранее заданного словаря, в него достаточно разместить всего несколько слов для демонстрации.

Для проверки задания необходимо прислать ссылку на репозиторий.
