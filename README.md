# ZmeyGAR.github.io

Верстка для магазина Успех

1 день. Собрал шапку сайта, пришлось переделывать ее несколько раз). 

    -+ Модульность шапки. Возможно подключение модулей и виджетов.
    -+ Написал скрипт, фиксирующий шапку на "карниз" окна браузера.
    -- Возможно, нужны красивые анимации для UI.
    -- Нужен бургер меню.
    -- Нужен попап для кнопки обратной связи. Может быть связать сайт с телеграмм ботом?
    -- Не закончен адаптив.

2 день. Продолжаю возню с шапкой сайта. 

    -+ Написан скрипт фиксации шапки при скроле
    -+ Привинчен бургер ( ! необходимо расставить ариа атрибуты ! )
    -+ Привинчен меню сайта ( ! необходим годный дизайн. Есть пара шаблонов с codepen для раздумий ! )
    -+ Главный баннер переделан. Оптимизировал графику. 

3 день. Продолжаю возню с шапкой сайта.

    -+ Небольшие изменения по макету. Отказ от кнопки feedback. 
    -+ Собираю сайдбар сайта, руководствуясь идеей у сайта Willdberis

4 день. Правки шапки сайта. Каркас сайдбара

    -+ Правки. Расширил контентную область до 1440px
    -+ Кнопка "Заказать звонок" соответствует макету
    -+ Описал скрипты для сайдбара. 
    -+ Скелет сайдбара готов. Необходимы доп правки, устранение багов. 

5 день. Некоторые правки сайдбара. Также сверстал вторую секцию сайта. Каталог и услуги.

6 день. Правки и модернизация структуры.

    -+ Правки. Исправил баг, сдвигающий макет при фиксации шапки.
    -+ Правки. Графика. Оптимизация и нарезка под необходимые ширину и высоту.
    -+ Модернизация структуры секции каталога и услуг. Воспользовался тем же приемом что и был на сайте, избавился от конструкции с гридами - на флексы. 
        По идее, теперь может быть сколько угодно категорий товаров. 
    -+ Также реализовал всплывающий над основным каталогом -> подкаталог. По идее, теперь может быть огромная вложенность подкатегорий в категории

    -- Необходимо подключить какой нибудь плагин для ленивой загрузки изображений (если будет много картинок в каталоге и их подкаталогах, сайт будет тормозить)
    -- Также есть баг! большой подкаталог (более 8 позиций) отображается со скроллом. Однако, если есть еще один вложенный каталог, он появляется поверх своего родителя, но не перекрывает его полностью. (может быть использовать ссылки с псевдоклассом :target ?)

7 день. Правки и модернизация структуры.

    -+ Правки. В виджетах шапки.
    -+ Правки. В самой шапке. Редизайн и адаптив.
    -+ Привинчен плагин DynamicAdapt.js . Позволяет перебрасывать DOM-узлы в зависимости от разрешения экрана. ( ? Нужен ли ?)
    
8 день. Адаптив. Небольшие правки.

    -+ Адаптив шапки сайта, с небольшим редизайном по части UI.
    -+ Переписал скрипты JS. Для фиксации шапки. 
    -+ Обдумываю структуру и дизайн нижней панели навигации для мобильного меню