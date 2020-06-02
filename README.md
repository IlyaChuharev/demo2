# Twitter Bootstrap
![Bootstrap logo](https://i.imgur.com/qhtywl2.png)
**Twitter Bootstrap** - популярный набор компонентов для фронтенд-разработки. [Twitter Bootstrap](https://bootstrap-ru.com/)
Построен на базе следующих технологий:
* HTML
* CSS
* JavaScript

## Начало работы

Есть несколько вариантов подключения:

1. Пакетный менеджер [npm](https://npmjs.com);
1. CDN.

Есть несколько вариантов подключения:
### Установка при помощи npm
Откройте консоль и выполните следующую команду: `npm install bootstrap`
### Установка при помощи CDN
Если вы хотите подключить только CSS (без JavaScript-плагинов),
добавьте в ваши html-файлы следующий код:
``` html
<link rel="stylesheet"href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css"integrity="sha284-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkF0JwJ8ERdknLPMO"crossorigin="anonymous">
```
---------------

Для JavaScript необходимо добавить следующий код:
```javascript
<script src="https://localhost/neuro.sdk.min.js"></script>
```

Java (Maven):
```xml
<dependency>
  <groupId>neuro</groupId>
  <artifactId>sdk</artifactId>
  <version>1.0.0</version>
</dependency>
```

iOS (добавьте код в ваш Podfile):
```
platform :ios, '8.0'
pod "neuro-ios-sdk"
```

---------------
## Использование
Все возможности по использованию описаны в официальной документации.