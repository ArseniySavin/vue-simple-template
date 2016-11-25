# vue-simple-template

Простой шаблон для консольной утилиты [vue-cli](https://github.com/vuejs/vue-cli), в который входит:
- [Vue.js](http://vuejs.org/) (версия 2.1.3)
- [Webpack](http://webpack.github.io/docs/what-is-webpack.html) (версия 2.1.0-beta.27)
- [vue-loader](http://vue-loader.vuejs.org/en/index.html)
- [SASS](http://sass-lang.com/)
- [Pug](https://pugjs.org/) (он же Jade)

Так же в шаблон встроена поддержка ES6 синтаксиса и Hot Reloading.

### Установка

``` bash
# Устанавливаем vue-cli, если еще этого не делали
npm install -g vue-cli
# Загружаем шаблон в любую папку
vue init GitHubTochkaDev/vue-simple-template my-project
# Переходим в созданную папку
cd my-project
# Устанавливаем зависимости
npm install
```

### Использование

Для разработки используется `webpack-dev-server`, в котором по умолчанию включена функция hot reload.

``` bash
# Запускаем одновременно сервер и сборку
npm run dev
```

Для финальной сборки используется команда:
``` bash
# Делаем сборку с одновременной минификацией всего кода
npm run build
```

### Альтернативы

Вы можете сделать форк данного репозитория и сделать на его основе собственный шаблон и так же использовать его вместе с vue-cli.

Либо использовать один из официальных шаблонов:

- [webpack](https://github.com/vuejs-templates/webpack) - Webpack + vue-loader установка включающая в себя hot reload, jslint и тесты.
- [webpack-simple](https://github.com/vuejs-templates/webpack-simple) - Простая Webpack + vue-loader установка для быстрого прототипирования.
- [browserify](https://github.com/vuejs-templates/browserify) - Browserify + vueify установка включающая в себя hot-reload, jslint и юнит-тесты.
- [browserify-simple](https://github.com/vuejs-templates/browserify-simple) - Простая Browserify + vueify установка для быстрого прототипирования.
- [simple](https://github.com/vuejs-templates/simple) - Самая простая из возможных Vue установка из одного HTML файла.