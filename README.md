# LeadGid biolerplate empty project

### Before build project:

- $ npm install
- Config cropRatio and remSize in gulpfile.js
- $ gulp favicons:create (Create icons (from src/icon.png):) or use https://realfavicongenerator.net/
- $ gulp favicons:build

### build project:
$ gulp

### Clean build folder
$ gulp clean

# Features

## 1
Начал разработку style-гайда по написанию стилей через испольльзоввни линтинга. Линтер работает только в случае коммита, самостоятельн исправляя код.

"stylelint --fix" -> "stylelint --fix --config ./.stylelintrc-format"

- .stylelintrc описывает обязательные правила, которые автоматов фиксятся
- .stylelintrc-format описывает обязательные правила, которые нужно править вручную

https://stylelint.io/user-guide/rules/

Статья http://blog.csssr.ru/2018/12/05/lint-your-css
https://github.com/v1z/linters-example

- $ npm run lint:css for CSS linting
- $ npm run format:css for CSS autofixing

## 2
Use 'px-to-rem' plugin, to watch options go to https://github.com/cuth/postcss-pxtorem

## 3
To use 'gulp-image-resize' plugin to automatically crop images

First install
apt-get install imagemagick
apt-get install graphicsmagick

## 4

