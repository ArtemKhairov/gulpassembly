# Описание

Сборка frontend проекта при помощи Gulp

## Что умеет делать эта сборка?

1. Минификация CSS 
2. Установка префиксов
3. Группировка медиа свойств
4. Удаление комментариев
5. Проверка JavaScript кода
6. Конвертация шрифтов необходимых для проекта
7. Автоматическое обновление браузера при изменении исходных файлов
8. Удаление ненужных файлов
9. Сжатие изображений
10. Переименование файлов в необходимый формат

## Установка

### Требования

-Установите [Node.js] который включает в себя [Node Package Manager][npm]

### Инициализация проекта 

Необходимо скопировать package.json

Для установки всех зависимостей необходимо ипользовать команду 

```
npm install
```


### Использование

Все задачи описаны в gulpfile.js

Для запуска всех задач необходимо использовать главную команду 

```js
gulp watch
```
После запуска будет запущен проект на localhost:3000

При желании порт можно поменять как и любую выполняемую задачу 

### Структура проекта

Исходные данные хранятся в папке #src

Собранный проект находится в папке dist

### Используемые пакеты

- browser-sync 
- del
- gulp
- gulp-autoprefixer
- gulp-clean-css
- gulp-file-include
- gulp-fonter
- gulp-group-css-media-queries
- gulp-imagemin
- gulp-rename
- gulp-sass
- gulp-ttf2woff
- gulp-ttf2woff2
- gulp-uglify-es


## Сотрудничество

Если вы нашли ошибку или хоти помочь сделать эту сборку лучше,свяжитесь со мной :)

## License
[MIT](https://choosealicense.com/licenses/mit/)

[node.js]: https://nodejs.org/
[npm]: https://www.npmjs.com/get-npm
