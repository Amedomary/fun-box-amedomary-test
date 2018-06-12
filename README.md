## Должно быть установлено ##
node.js - https://nodejs.org/ Версию лучше последнюю скачать

**npm**

```bash
$ npm i npm -g —allow-root
```

**gulp**

```bash
$ npm i gulp -g —allow-root
```

## Настройка окружения ###

```bash
$ cd src/js && npm i && cd ../.. 
$ npm i
```

### Сборка ###

----------------------------------------------------------------------------------------------------------------------------

## Собираем проект ###

*для production*
```bash
$ gulp build
```
*для работы*
```bash
$ gulp dev
```

## Основные команды ###

*подключение миксинов инклюдами*
```bash
$ gulp addInc2pug
```
*Создание папки с стилями в bem-blocks*
```bash
$ gulp create-style --name b-block-name
```
*Проверка js*
```bash
$ gulp eslint
```
*Создание переменной с цветов в variables*
```bash
$ gulp color-create --color --ffffff
```