# Среда исполнения JS файлов - игровая площадка

### Инструкция по установке:

1. Скачайте репозиторий. ВАЖНО! Необходимо именно скачать zip-архив, а не клонировать.
2. Разархивируйте репозиторий и откройте его в терминале.
3. Наберите компанду ```npm install``` (при этом, Вы должны находиться в корне репозитория!)
4. Дождитесь установки зависимостей.

### Где писать код и как проверять?

Писать код Вы можете в файле ```src/index.js```.

Чтобы запустить код используйте команду ```make start```.

Чтобы код запускался автоматически после сохранения, используйте команду ```make play```

### **Важно!** 

Старайтесь не перемещать и не копировать весь репозиторий из одного места на диске - в другое. После установки зависимостей у Вас будет много файлов, которые копируются очень долго. Но если Вы все таки хоитите переместить, то нужно перемещать файлы без директории ```node_modules```, а затем запускать команду ```npm install``` в новом репозитории, чтобы зависимости установились в новом проекте.
