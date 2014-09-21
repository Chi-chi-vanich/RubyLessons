##Работа в терминале

Зачастую выполнить какую-либо задачу, так или иначе связанной с программированием, проще и быстрее именно в эмуляторе терминала (далее *терминал*), например, подключиться на удаленныей Linux-сервер и произвести там какие-либо операции. Есть примеры и проще - клонировать репозиторий из системы контроля версий Git и затем открыть директорию, склонированного репозитория, или файл, содержащийся в ней? каким-либо текстовым редактором.

На первый взгляд может показаться, что работа в терминале - участь ретроградов, которые нехотят изучать новые для себя приложения с графическим интерфейсом. Это не так. Да, в некоторых случаях, действительно, удобнее и проще использовать приложения с GUI, но все же совсем отказаться от работы в терминале не представляется возможным, да и не зачем.

Здесь я попытаюьс изложить самые базовые вещи, необходимые вам для прохождения данного курса. 

###Работа с файлововй системой

Для просмотра содержимого текущей директории можно выполнить команду


```bash
ls
```

Результатом выполнения данной команды будет список всех файло и директорий, содержащийхся в текущей директории.

![ls](http://cdn.joxi.ru/uploads/prod/2014/09/20/797/1bc/ca292df94f81bca17a295484bfe82ade9ad96940.jpg)

Для того, чтобы изменить директоию необходимо выполнить команду

```bash
cd directory_name
```

В результате вы перейдете в директорию *directory_name*. Для перехода на уровнь выше следует выполнить это:

```bash
cd ../
```

Именя скрытых файлов и папок начинаются на .

Например, конфигурационный файл для текстового редактора vim находится в домашней дирекории пользователя и называется .vimrc. Это скрытый файл