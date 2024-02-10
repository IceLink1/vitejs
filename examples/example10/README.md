# Example 3 for Vitejs

## **Настройка autoprefixer**
### Обновленная версия. Обновлены пакеты на последние, проект переведен на модули ES

Как подключить postCSS autoprefixer к проекту, который собирается с помощью vitejs

Настройка включает три простых шага:

1. Установка плагина autoprefixer
```
    npm install -D autoprefixer
```
2. Настройка browserslist - добавить в package.json (для поддержки очень старых браузеров):
```
    "browserslist": [
        "Safari >= 5",
        "iOS >= 5",
        "not ie <= 10",
        "> 1%"
    ],
```

 
3. Подключение плагина autoprefixer к сборке.
    - создать файл postcss.config.js в корне проекта
    - добавить следующий код:

```
const exports = {
    plugins: {
        autoprefixer: {
            
        }
    }
}

export default exports;
}
```

## Как пользоваться

```
    npm install
    npm run build
```
или

```
   npm install
   npm run start
```

## Видео с объяснением как это все работает здесь:

[![Видео здесь](https://img.youtube.com/vi/TZN6dC7ZOs0/0.jpg)](https://www.youtube.com/watch?v=TZN6dC7ZOs0)

## Еще по vitejs

[![Видео здесь](https://img.youtube.com/vi/wIEauCguZGI/0.jpg)](https://www.youtube.com/watch?v=wIEauCguZGI)
[![Видео здесь](https://img.youtube.com/vi/t98Q9hliZZo/0.jpg)](https://www.youtube.com/watch?v=t98Q9hliZZo)
[![Видео здесь](https://img.youtube.com/vi/aMzCDR_MHF0/0.jpg)](https://www.youtube.com/watch?v=aMzCDR_MHF0)



## Полезные видео по настройке webpack:


Минимальная конфигурация:

[![Видео здесь](https://img.youtube.com/vi/unEl3Hezwpw/0.jpg)](https://www.youtube.com/watch?v=unEl3Hezwpw)

Настройка горячей перезагрузки:

[![Видео здесь](https://img.youtube.com/vi/oOpzkF2nU0s/0.jpg)](https://www.youtube.com/watch?v=oOpzkF2nU0s)

Настройка сборки проекта с подгрузкой файлов css/scss/изображений:

[![Видео здесь](https://img.youtube.com/vi/3B-NGZmMe-Y/0.jpg)](https://www.youtube.com/watch?v=3B-NGZmMe-Y)

Модульный принцип конфигурации проекта:

[![Видео здесь](https://img.youtube.com/vi/fnUqyWyG5kk/0.jpg)](https://www.youtube.com/watch?v=fnUqyWyG5kk)