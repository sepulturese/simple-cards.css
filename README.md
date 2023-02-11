# simple-cards.css
~~Моя первая CSS мини-библиотека, которую сделал для своих будущих проектов. Представляет из себя карточку с изображением, заголовком, небольшим описанием и несколькими кнопками.~~

*\*Спустя неделю я смог модернизировать эту мини-библиотеку, добавив адаптивность при помощи Flexbox, улучшенный минималистичный дизайн и верстку по методологии БЭМ, объемные тени.*

### Как ее использовать?
#### Подключение.
В начале основного CSS файла прописать:
```css
@import url("simplecards.css");
```

#### Использование.
```html
<section class="card">
    <header class="card-header">
        <img src="https://i.imgur.com/cocH9JH.jpeg" class="card-header__preview">
    </header>
    <div class="card-body">
        <h1 class="card-body__title">Some product title.</h1>
        <h2 class="card-body__subtitle">50.00$</h2>
        <div class="card-body__description">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
            lit non laudantium impedit, necessitatibus odit quae ipsum.
        </div>
    </div>
    <footer class="card-footer">
        <a href="#" class="card-footer__link">Some link</a>
    </footer>
</section>  
```

#### Демонстрация.
##### Нынешняя версия.
![](https://i.imgur.com/6BCEDCB.png)

##### Прошлая версия.
![](https://i.imgur.com/1MEbKTN.png)
