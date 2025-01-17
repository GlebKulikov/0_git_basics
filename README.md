<!----- Conversion time: 1.115 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β17
* Wed Sep 18 2019 01:01:48 GMT-0700 (PDT)
* Source doc: https://docs.google.com/open?id=1sIorEva0JHPGjUlZBihoiGIootksj8HqQUjW8Vota0c
----->

## 3. Работа с удаленными репозиториями и GitHub


### Цель работы

Освоить основные навыки работы с облачными и распределенными системами контроля версий, получить навыки работы с инструментальными средствами, обеспечивающими командную работу над разработкой ПО.


### Задания для выполнения



1. Зарегистрироваться на сайте github.com
2. Установить на компьютере программу Git
3. Форкнуть данный репозиторий в свой аккаунт

![image](https://user-images.githubusercontent.com/70904778/140100760-e82ade7a-1752-4e30-9583-648a0aca71d4.png)

4. Склонировать созданный удаленный репозиторий в директорию ~/git/test

![image](https://user-images.githubusercontent.com/70904778/140102168-af5a0d77-c26d-41cf-b70b-715c84e7ed13.png)

5. На локальной машине пишем скрипт ~/git/test/backup.sh, с произвольным содержанием

![zekNrShkOuc](https://user-images.githubusercontent.com/70904778/140171753-4a43e5f5-d262-43c0-aafa-db00cf72b88d.jpg)


6. Фиксируем скрипт в репозитории (делаем коммит)

![image](https://user-images.githubusercontent.com/70904778/140136035-4c797d1c-5837-4d10-b0e8-5d53953d446a.png)
![image](https://user-images.githubusercontent.com/70904778/140136454-3d21cb0a-449f-4afc-9a59-70dd8e06e843.png)

7. Обновляем удаленный репозиторий репозиторий (делаем пуш)

![14](https://user-images.githubusercontent.com/70904778/140168810-dd1abd1a-759a-40c2-b063-a29c945942a4.jpg)

8. Через текстовый редактор добавить любую новую строку с комментарием

![image](https://user-images.githubusercontent.com/70904778/140163180-7d614928-43d4-468c-ad29-5ce4f4d2b3a3.png)

9. Сделать коммит

![14(1)](https://user-images.githubusercontent.com/70904778/140168921-f680d4a9-c3ef-4120-9ae9-84f6c0effb8c.jpg)

10. Вности синтаксическую ошибку в скрипт

![16](https://user-images.githubusercontent.com/70904778/140168991-bde744b5-06e8-47d7-af09-22c82484256d.jpg)

11. Сделать коммит ошибочного скрипта

![18](https://user-images.githubusercontent.com/70904778/140169152-cb068750-5a08-444e-8bbc-0c54485921f6.jpg)

12. Откатываем до последней рабочей версии

![ip2rczhRDVc](https://user-images.githubusercontent.com/70904778/140169223-4613f878-1466-40f3-bbfd-cd5b66b24788.jpg)
![i5SryzRNvGA](https://user-images.githubusercontent.com/70904778/140169230-fdf7ef6d-9e58-487d-a93b-99b91b17daa7.jpg)

13. Просмотреть историю коммитов

![kg1CHAftNtM](https://user-images.githubusercontent.com/70904778/140169264-92b8eeed-8f59-4342-8987-8d6f5db61975.jpg)

14. Добавить несколько коммитов произвольного содержимого

![YIlS7jOLNmM](https://user-images.githubusercontent.com/70904778/140169363-af81783b-6c29-4f42-a6f0-f2f67cd6951a.jpg)
![SQd45dGAXro](https://user-images.githubusercontent.com/70904778/140170914-2e5c665b-d077-4a06-8321-3025922f30d6.jpg)

15. Создать пулл реквест в данный репозиторий


### Контрольные вопросы



1. Зачем нужен облачный хостинг репозиториев?

Облачный хостинг репозиториев нужен для того, чтобы группа людей имела доступ к общему репозиторию и могла с ним работать.

3. Какими основными функциями обладает сайт github.com?

Помимо основоного функционала git, сайт github.com позволяет делать форки (копирование чужодого репозитория к себе), пулл реквесты (запрос на внесение измененеий в чужой репозиторий из своей модифицированныной копии), при нахождении багов можно открыть тему с проблемой (issues) и многое другое.

5. Как организовать командную работу над открытым проектом?

В ветке main должена быть только рабочая версия проекта. Разработка должна вестись в нескольких ветках. Когда работа в какой-либо ветке заканчивается, тот, кто работал над ней, делает пулл реквест в ветку main. Далее происходит код ревью: назначется ревьюеер, который проверяет корретность кода, выявляет все ошибки. Когда все выявленные проблемы решены, код попадает в ветку main. Также в командной разработке обычно пользуются вопросами о проблеме (issues). Если в проекте есть проблема, открывается вопрос. На него ставят метки категорий (к какой части проекта относится вопрос). Далее вопрос рассматривается, и в случае выявления проблемы, она исправляется.

### Дополнительные задания



1. Дополнительно оценивается, если студент продемонстрирует работу с ветками в процессе написания более-сложного программного проекта (не менее трех файлов, двух веток, десяти коммитов, как минимум одно объединение).
2. Дополнительно оценивается демонстрация командной работы. Для этого нужно склонировать репозиторий другому члену команды и коммитить от своего имени. При отправке истории на удаленный сервер (push) на сайте будет отображаться общая история. При скачивании истории с сервера (pull) общая история будет отображаться на локальном компьютере.
3. Настройте работу с git вашей интегрированной среды разработки по выбору. Для работы с python рекомендуется использовать PyCharm. Выполните задания лабораторной работы в IDE используя встроенные средства работы с системами контроля версий.

<!-- Docs to Markdown version 1.0β17 -->
