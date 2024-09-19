# [Docs](../README.md) / [Git](Index.md) / Создание fork

Для создания fork проекта необходимо иметь экканунт github.com и быть залогиненым 

1. Переходим на страницу основного репозитария проекта
```url
https://github.com/vakhnin/Docs
```

2. Справа сверху нажимаем кнопку "Fork"
3. Снимаем галочку с пункта "Copy the master branch only"
4. Жмем кнопку "Create Fork"
5. Оказываемся на странице Вашего fork проекта
6. Жмем кнопку "Code", копируем https репозитария
7. Далее, локально. Клонируем репозитарий (вставляем ссылку из пункта 6). 
В ссылке должен быть Ваш логин
```commandline
git clone https://github.com/<Ваш логин на github>/Docs.git
```
8. Push отправлять в свой fork репозитарий (по умолчанию при выполнении инструкции так и будет)