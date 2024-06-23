# Анализ основных данных о футболистах
Спорт является неотъемлемой частью жизни многих людей. Одни занимаются спортом сами, другие же смотрят игру профессиональных спортсменов. Для удобства наблюдения за футболистами и их результатами в матчах мы создали интерактивный многостраничный дашборд. 

---

## Основное содержание дашборда: ##
Дашборд содержит следующие страницы:
1. Общая статистика
2. Деятельность футболистов по странам
3. Статистика по клубам
4. Параметры футболиста
### Подробнее о каждой из страниц: 
1. На странице **"Общая статистика"** представлено две диаграммы. На первой диаграмме показывается общая деятельность всех футболистов по странам, которые выбирает пользователь. Для нее он может выбрать интересующий его показатель, а также посмотреть данные за несколько лет. На второй диаграмме показана карта мира, на которой отображаются страны, где происходили интересующие пользователя события.
2. На странице **"Деятельность футболистов по странам"** в зависимости от выбранной пользователем страны, по годам отслеживаются хронологические достижения футболиста.
3. На странице **"Статистика по клубам"** пользователь выбирает интересующий его футбольный клуб и имеет возможность наглядно увидеть долю привнесенного игроками вклада в этот клуб, а также суммарную деятельность футболистов в выбранном клубе.
4. На странице **"Параметры футболиста"** пользователь выбирает интересующий его футбольный клуб, а также футболиста из этого клуба, после чего отображаются карточки с показателями выбранного футболиста, а также показывается лучший игрок в этом клубе.

---

## Данные для дашборда ##
Данные, которые содержит дашборд, мы взяли на известной платформе kaggle, где содержится множество датасетов. После тщательного анализа ~всех существующих на этой платформе~ датасетов на эту тематику, был выбран именно этот [Датасет про футболистов](https://docs.google.com/spreadsheets/d/e/2PACX-1vTaSitw4fUqP_GgSp1VXwT6NqCXSUY9xIK_vx3LZk6GZbNlM_N1efmyvjQ6qdZCGoPCTEQYhZoW3NDA/pub?output=csv), так как он содержит все необходимые данные для анализа футболистов.

---

[![Видео](https://disk.yandex.ru/i/pjXwA4gGY2wjfw)](https://disk.yandex.ru/d/d9ZC36fmc9P-4A/IMG_5029.MOV)

[Видео](https://disk.yandex.ru/d/d9ZC36fmc9P-4A/IMG_5029.MOV)

---

## Используемые библиотеки ##

```python
import dash_bootstrap_components as dbc
import pandas as pd
import plotly.express as px
```

---

## Вопросы, на которые могут получить ответ пользователи нашего дашборда: ##
1. Насколько хорошо играет футболист?
2. Какой вклад вносит футболист в клуб?
3. Выгодно ли будет сделать ставку на игрока?
4. Какой игрок самый лучший в клубе?
5. Как меняется прогресс игрока с течением лет? 
