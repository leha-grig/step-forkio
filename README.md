# step-forkio
- кросс-браузерность
- адаптивная верстка 
Проект собирается при помощи сборщика gulp. Стили писались с использованием SCSS.
 Для сборки проекта:
- установить Node.js и локально все необходимые модули, согласно package.json
- команда gulp из директории с проектом запускает задачу build, согласно которой в папке проекта создается папка build с рабочим index.html и собранными рабочими .js и .css
- команда gulp dev из директории с проектом запускает задачу dev для дальнейшей разработки и правки, которая открывает index.html (из папки build, собранной предыдущей задачей) в браузере и отслеживает изменения в файлах разработки (папка src), при появлении изменений перегружает страницу.
