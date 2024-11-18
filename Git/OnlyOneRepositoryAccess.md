# [Docs](../README.md) / [Git](Index.md) / Настройка доступа только к одному репозиторию через токен в GitKraken

#### 1. **Создаем токен доступа**  
1. Переходим в **Settings** → **Developer settings** → **Personal access tokens** → **Fine-grained personal access tokens** → **Generate new token**.  
2. Вводим имя токена в поле **Token name**.  
3. Устанавливаем срок действия токена в поле **Expiration**.  
4. Выбираем репозиторий для доступа:  
   1. В разделе **Repository access** указываем **Only select repositories**.  
   2. Выбираем нужный репозиторий.  
5. Настраиваем разрешения:  
   1. В разделе **Permissions** → **Repository permissions** выбираем **Contents** и устанавливаем значение **Read and write**.  
6. Генерируем токен, нажав **Generate token**.  
7. Копируем токен в безопасное место (он будет показан только один раз).  

---

#### 2. **Устанавливаем токен доступа в GitKraken**  
1. Клонируем репозиторий:  
   1. Выбираем **Clone a repo**.  
   2. Вставляем URL репозитория.  
   3. Указываем папку для клонирования.  
   4. Нажимаем **Clone the repo**.  
2. Вносим изменения в файлы репозитория.  
3. Создаем коммит:  
   1. Добавляем измененные файлы в коммит.  
   2. Вводим сообщение коммита.  
   3. Нажимаем **Commit changes**.  
4. Выполняем первый **Push**:  
   1. Нажимаем **Push** в верхней панели GitKraken.  
   2. Если нужно, вводим название ветки.  
   3. Нажимаем **Submit**.  
   4. При появлении запроса вводим:  
      1. **Username**: ваш GitHub логин.  
      2. **Password**: токен из пункта 1.  
   5. Нажимаем **Log in**.  