# Документация ботов сообщества "Осознанная меркантильность"

## Бот "Найти ментора"
### Полнотекстовый поиск по таблице менторов
Основная цель бота - искать менторов по таблице менторов, поэтому в нём есть кнопка для поиска. При нажатии на неё надо будет написать сферу IT, в которой вы ищете ментора.

![image](https://github.com/M0rtyMerr/-/assets/47274926/34bb4107-2de9-4dce-8780-3b45d94e4135)

Менторов может быть много, поэтому в результатах, присылаемых ботом могут появиться стрелочки для переключения страниц

![image](https://github.com/M0rtyMerr/-/assets/47274926/8347d40a-01f3-4fce-bebf-069badecb0d7)

### Просмотр отзывов на ментора
В боте есть возможность просматривать отзывы на выбранного ментора. Для этого необходимо найти его в таблице и нажать на команду, находящуюся в поле "Отзывы о менторе". Также для просмотра отзывов по telegram ID ментора можно просто написать команду `/info_ник-ментора`.
Просмотр отзывов также управляется стрелочками, на одной странице отображается один отзыв. 

![image](https://github.com/M0rtyMerr/-/assets/47274926/559c538b-1178-4085-bf42-6b46124fe40a)

### Возможность оставлять отзывы
В боте можно оставить отзыв на ментора. Для этого достаточно нажать на кнопку "Оставить отзыв на ментора", и включится сценарий создания отзыва. Для того, чтобы отправить отзыв необходимо во-первых упомянуть ментора в ответ на первое сообщение бота, во-вторых написать отзыв, в-третьих, если ваш телеграм-ник скрыт, то необходимо будет упомянуть себя, потому что *отзывы не анонимны*.

![image](https://github.com/M0rtyMerr/-/assets/47274926/43f32c59-454c-4920-a2d5-74410aa8327f)

### Просмотр статистики поисков по боту для менторов
Для менторов есть возможность просматривать статистику запросов в бота, статистику кликов по отзывам и общую статистику бота. Для этого необходимо написать `/statistics` в чате "IT Менторы" или "ОМ: Элитные менторы", и бот вышлет вам статистику. Также она автоматически отправляется в оба этих чата по воскресеньям.

### Виджет с отзывами из бота для прайсов элитных менторов
Виджет, который позволяет элитным менторам отображать список отзывов из канала "IT Менторы" в своём прайсе в Notion (с помощью embed) или Teletype (с помощью iframe).

Как подключить бота:
1. Получаем свой telegram id любым удобным способом (например можно использовать `/id` в чате элитных менторов)
![image](https://github.com/M0rtyMerr/-/assets/47274926/06393adc-55d8-4d8b-b247-12e0b122507b)
3. Вставляем свой telegram id в ссылку ниже
4. Указываем одну из понравившихся тем (доступные: notion-light, notion-dark, teletype-light, teletype-dark
5. В случае с Notion достаточно будет вставить ссылку `https://www.it-mentors.ru/reviews?id=YOUR_ID_HERE&theme=YOUR_THEME_HERE` с указанной темой и telegram id ментора. В случае с Teletype надо будет зайти на [iframe generator](https://www.iframe-generator.com/), настроить там iframe, скопировать код iframe и вставить его в Teletype.

Выглядит это примерно так:

![image](https://github.com/M0rtyMerr/-/assets/47274926/f5d6504b-efb4-49dd-bde5-0db8c92af179)

## Бот "Помощник ОМ"
### Поиск по контенту сообщества
В любом чате сообщества можно использовать команду `/search` для поиска по контенту сообщества
