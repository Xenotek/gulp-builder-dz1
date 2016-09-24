#Учебная сборка Loftschool (выпускной проект №1) 

Stack:
 - Gulp 4.0
 
Getting started:

1. clone this repo
2. cd path/to/
3. npm install gulpjs/gulp-cli -g  // Install the latest Gulp CLI tools globally
4. npm install
6. run "gulp" command to start

Корепанов Иван Николаевич

Добавлен плагин gulp.spritesmith

Созданы таски:
1) Первый таск - генерация спрайтов из графических файлов (png).
Вызов:
gulp sprite:image

2) Второй таск - копирование файлов из папки с исходниками в папку для продакшена (картинки, шрифты).
Вызов:
gulp copy:fonts

