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

5. Склонировать созданный удаленный репозиторий в директорию ~/git/test
![image](https://user-images.githubusercontent.com/70904778/140102168-af5a0d77-c26d-41cf-b70b-715c84e7ed13.png)

7. На локальной машине пишем скрипт ~/git/test/backup.sh, с произвольным содержанием
![image](https://user-images.githubusercontent.com/70904778/140104633-33f50907-b986-4336-a989-f43edde29688.png)

9. Фиксируем скрипт в репозитории (делаем коммит)
![image](https://user-images.githubusercontent.com/70904778/140136035-4c797d1c-5837-4d10-b0e8-5d53953d446a.png)
![image](https://user-images.githubusercontent.com/70904778/140136454-3d21cb0a-449f-4afc-9a59-70dd8e06e843.png)

11. Обновляем удаленный репозиторий репозиторий (делаем пуш)
![14](https://user-images.githubusercontent.com/70904778/140168810-dd1abd1a-759a-40c2-b063-a29c945942a4.jpg)

13. Через текстовый редактор добавить любую новую строку с комментарием
![image](https://user-images.githubusercontent.com/70904778/140163180-7d614928-43d4-468c-ad29-5ce4f4d2b3a3.png)

14. Сделать коммит
![14(1)](https://user-images.githubusercontent.com/70904778/140168921-f680d4a9-c3ef-4120-9ae9-84f6c0effb8c.jpg)

16. Вности синтаксическую ошибку в скрипт
![16](https://user-images.githubusercontent.com/70904778/140168991-bde744b5-06e8-47d7-af09-22c82484256d.jpg)

18. Сделать коммит ошибочного скрипта
![18](https://user-images.githubusercontent.com/70904778/140169152-cb068750-5a08-444e-8bbc-0c54485921f6.jpg)

20. Откатываем до последней рабочей версии
![ip2rczhRDVc](https://user-images.githubusercontent.com/70904778/140169223-4613f878-1466-40f3-bbfd-cd5b66b24788.jpg)
![i5SryzRNvGA](https://user-images.githubusercontent.com/70904778/140169230-fdf7ef6d-9e58-487d-a93b-99b91b17daa7.jpg)

22. Просмотреть историю коммитов
![kg1CHAftNtM](https://user-images.githubusercontent.com/70904778/140169264-92b8eeed-8f59-4342-8987-8d6f5db61975.jpg)

24. Добавить несколько коммитов произвольного содержимого
![YIlS7jOLNmM](https://user-images.githubusercontent.com/70904778/140169363-af81783b-6c29-4f42-a6f0-f2f67cd6951a.jpg)
![SQd45dGAXro](https://user-images.githubusercontent.com/70904778/140170914-2e5c665b-d077-4a06-8321-3025922f30d6.jpg)

26. Создать пулл реквест в данный репозиторий


### Контрольные вопросы



1. Зачем нужен облачный хостинг репозиториев?
2. Какими основными функциями обладает сайт github.com?
3. Как организовать командную работу над открытым проектом?


### Дополнительные задания



1. Дополнительно оценивается, если студент продемонстрирует работу с ветками в процессе написания более-сложного программного проекта (не менее трех файлов, двух веток, десяти коммитов, как минимум одно объединение).
2. Дополнительно оценивается демонстрация командной работы. Для этого нужно склонировать репозиторий другому члену команды и коммитить от своего имени. При отправке истории на удаленный сервер (push) на сайте будет отображаться общая история. При скачивании истории с сервера (pull) общая история будет отображаться на локальном компьютере.
3. Настройте работу с git вашей интегрированной среды разработки по выбору. Для работы с python рекомендуется использовать PyCharm. Выполните задания лабораторной работы в IDE используя встроенные средства работы с системами контроля версий.

<!-- Docs to Markdown version 1.0β17 -->
