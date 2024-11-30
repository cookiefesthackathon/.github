# **Проект "Маркетплейс" для Хакатона Cookie Fest 2024**
К кейсу приложено техническое задание от компании __ООО "Тет-а-тет"__:
## __Техническое задание ООО "Тет-а-тет"__
[Ссылка на техническое задание.](https://docs.google.com/document/d/13FuwL3TOWsvzXE24evj188eex9dDCm3RIU3KN1NVCrI/edit?tab=t.0)
### Проблематика:
Жители Новосибирска - активные пользователи маркетплейсов OZON, WB и пр.
Обычно, прекрасная половина семьи заказывает любимые марки освежителей для белья, зубных паст и пр. бытовой химии. Но при повторном заказе часто обнаруживается, что товар у проверенного поставщика значительно изменил цену и это приводит к необходимости:
- заново искать товар у других продавцов;
- заново изучать отзывы о продавцах;
- заново выбирать продавцов по приемлемому сроку доставки;
- заново находить товар по приемлемой цене.
И вместо одного клика “Повторить заказ” на это тратится существенная часть времени.
### Задачи разрабатываемой системы:
Задача 1. Автоматизировать поиск самых выгодных предложений своего круга товаров.  Как результат: в момент, когда пользователю нужно сделать заказ,  система предлагает наилучший вариант по цене, отзывам, срокам доставки. Пользователю остается по клику перейти в карточку товара и сделать заказ.
Задача 2. Мониторить цены на товары и подсказывать пользователю, когда на его популярные товары максимальные скидки.
## __Теоретическое описание проекта__
В данном разделе описываются теоретические основы проекта, такие как цель создания, проблематика кейса, обоснование выбора и уникальность по сравнению с другими командами, взявшими эту задачу к реализации.
### __Цель создания проекта__
Проект создается с целью автоматизировать отслеживание лучших предложений на избранные товары с маркетплейса "Wildberries". Ожидается, что система будет выполнять задачи, описанные в техническом задании заинтересованного лица.
### __Какую проблему решает проект__
При повторном заказе товара на маркетплейсах (Ozon, Wildberries и др.) цена может существенно измениться. Из этого вытекают проблемы, описанные в техническом задании. 
### __Почему выбран этот кейс__
Нашей командой "Команда" выбран этот кейс, так как для нас является актуальной проблема, поставленная в ТЗ. Решение этой задачи в рамках Хакатона помогло каждому члену команды раскрыть свой потенциал, используя наш стек технологий.
### __Уникальность проекта__
Уникальностью выполненного нами проекта мы считаем акцент на избранном, с помощью которого можно вручную отслеживать изменение цен и оценок на выбранные товары. Наш агрегатор показывает только нужную пользователю для первичной оценки информацию, для получения подробных сведений о товаре пользователь может перейти по url на сайт продавца.
## __Стек__
### Frontend
Для написания интерфейса Frontend-разработчик использовал Figma для дизайна страниц Web-сайта, наброска макетов. Для пользовательского интерфейса использовались фреймворк Vue 3 + Nuxt, язык программирования TypeScript, программная платформа Node.js. 
### Backend + база данных
Программно-аппаратная часть веб-приложения (парсинг, связи с БД, API) написана полностью на языке программирования Python с использованием библиотеки SQLite для создания базы данных.
## __Документация (диаграммы DFD и Use-Case)__
[DFD логическая](DFD-логическая.jpg)
[DFD физическая](DFD-физическая.jpg)
[ER-диаграмма](er.jpg)
[Use-case диаграмма](use-case.jpg)
## __Функции маркетплейса__
## __Перспективы развития__
## __Сведения об авторах__
