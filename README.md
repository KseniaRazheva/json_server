# json_server

как запустить локальный сервер для get и post запросов
создается файлы:
1) package.json (нужен экспресс, еще добавили нодемон потому что он удобный)

2) index.cjs (в документации написано как создать сервер на библиотеке для Node.js "экспресс" https://expressjs.com/en/starter/hello-world.html , про fileSystem https://nodejs.org/en/learn/manipulating-files/writing-files-with-nodejs#writing-a-file )

3) db.json (стандарт рест-айпиай, позволяет разделить логику серверную и фронтовую)




открываю терминал
npm install 
(в этот момент самас создается папка node_modules и файл package-lock.json)
потом 
npm run start 
терминал запускает сервер
захожу в браузер пишу http://localhost:3000/
на сайте отображается то, что написано в файле db.json 


создала на гитхабе новый репозиторий
открываю общую папку гитхаба через вскод, надо стянуть изменения
git clone https://github.com/KseniaRazheva/json_server.git
в моей папке гитхаб на компьютере появилась папка которую я создала на гитхабе и теперь туда можно писать код, а потом комитить

создала .gitignore туда вписала
package-lock.json
/node_modules/


как коммитить
git status
git add . 
git status 
git commit -m "add/update/return files" 
git push -u origin main