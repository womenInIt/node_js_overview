# Roll up to JavaScript

1. fork git repo
2. clone git project to PC
   `` git clone <repo address> ``
3. in VS code open folder with project files (File => Open Folder)
4. open new terminal (Termina => new Terminal)
5. in terminal add npm to project
   `` npm init ``
   it will add files package.json and package-lock.json
6. install node packages 
   for example nodemon (automatically restart the node application when file changes in the directory are detected)
   `` npm install -g nodemon ``

# for training use:
    https://www.jschallenger.com/start
    https://edabit.com/challenges



# Начинаем работать на  JavaScript

1. если у вас есть аккаунт на GitHub, то сделайте форк данного репозитория (кнопка в верхнем левом углу)
2. далее откройте на вашем компьютере GitBush (терминал) и клонируйте ваш репозиторий на свой локальный компьютер
   `` git clone <repo_address> ``
3. В программе VS code откройте папку. (File => Open Folder) Обратите внимание, у вас в окне експлорера должно быть все содержание папки, а не только один файл
4. откройте терминал (Termina => new Terminal)
5. добавте поддержку менеджера пакетов npm
   `` npm init ``
   после успешного выполнения этой команды в вашем проекте должны быть добавленны 2 новых файла package.json and package-lock.json
6. теперь можно подключать пакеты для разработки. 
   Для начала мы будем использовать nodemon (автоматически перезагружает node.js если вы вносите изменения в файлы)
   `` npm install nodemon -D ``
7. Запустите node.js с помощью команды 
   `` node <file_name> ``
   `` node 01.calculation.js ``
