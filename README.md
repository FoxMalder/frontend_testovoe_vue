### Тестовое задание
#### на позицию "Front-end developer (Middle/Senior, Vue.js)"


&nbsp;
![](https://cdn-images-1.medium.com/max/1200/1*-8AAdexfOAK9R-AIha_PBQ.png)
&nbsp;


### Цель
Разработать SPA-приложение с использованием `Vue` + `Vuex` + `Vue router`.  
Приложение должно получать данные из API и выводить их в клиентскую часть.  
API: [https://dog.ceo/dog-api](https://dog.ceo/dog-api)  
Макет-пример: [https://www.figma.com/file/qikieeE86iZxUzdj4TpwJM/frontend_test](https://www.figma.com/file/qikieeE86iZxUzdj4TpwJM/frontend_test)


&nbsp;

### Главная страница
* Отображает список изображений всех собак (по умолчанию в рандомном порядке).
* Сверху находится переключатель с рандомного порядка фото на алфавитный.
* По стандарту должно отображаться 20 изображений и реализован бесконечный скролл с подгрузкой следующих 20 изображений.

&nbsp;

### Страницы пород
В шапке располагается селект со списком всех доступных пород.  
При выборе определенной породы происходит роутинг на **app.ru/{breed}**, например app.ru/husky.  
При переходе по таким урлам должны загружаться изображения только выбранной породы.

&nbsp;

### Избранное
Каждое изображение можно лайкнуть (иконка сердца), после чего эти изображения можно будет увидеть на странице **app.ru/favourites**. Информация о лайкнутых фото должна находиться в хранилище браузера. При перезагрузке страницы лайкнутые фото не должны пропадать.

&nbsp;

### Общие требования
* Макет дан для примерного понимания интерфейса. Можно сверстать его, а можно на свой вкус.
* Верстка без использования css-фреймворков типа bootstrap, только чистый SCSS/SASS/LESS
* Проект создан с помощью Vue CLI с пресетом по умолчанию [https://cli.vuejs.org/guide/creating-a-project.html](https://cli.vuejs.org/guide/creating-a-project.html)
* Использование ESLint standart обязательно
* Вся логика работы с API находится во Vuex
* Допустимые к использованию библиотеки только vue, vuex, vue-router, axios
* Исходный код проекта должен быть выложен на GitHub
* Будет плюсом: верстка на `Pug` и `SCSS`, JS на синтаксисе ES6-ES10 (смотреть будем в последнем хроме)

&nbsp;
&nbsp;

![](https://media.giphy.com/media/pDgHg2Lcju3Ty/giphy.gif)
