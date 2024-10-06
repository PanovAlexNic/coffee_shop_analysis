# Исследование рынка заведений общественного питания Москвы

## Введение

Цель данного исследования — проанализировать рынок заведений общественного питания Москвы с целью предоставления инвесторам фонда «Shut Up and Take My Money» рекомендаций по открытию нового заведения. Исследование охватывает ключевые аспекты ресторанного бизнеса в столице, начиная от количества заведений в различных категориях, таких как кафе, рестораны, пиццерии и кофейни, до анализа факторов, влияющих на успех и популярность этих заведений.

В ходе исследования будут рассмотрены следующие вопросы: распределение заведений по категориям и административным округам, анализ сетевых и несетевых заведений, исследование рейтингов и средних цен по районам, а также определение категорий заведений, которые чаще всего являются сетевыми.

Особое внимание будет уделено анализу кофеен, включая их количество, расположение, рейтинг, а также стоимость чашки капучино. Этот анализ поможет инвесторам оценить перспективы открытия новой кофейни и принять обоснованное решение, основанное на данных о текущем рынке.

Исследование предполагает использование методов визуализации данных и статистического анализа для выявления ключевых закономерностей и тенденций в ресторанной индустрии Москвы.

## План работы

### 1. Загрузка и изучение данных:
Загружаем данные о заведениях общественного питания Москвы и проводим первичный анализ для получения общего представления о содержимом.

### 2. Предобработка данных:
Очистка данных, удаление дубликатов и пропусков, создание новых столбцов для улучшения анализа данных.

### 3. Анализ данных:
Анализ категорий заведений, исследование количества посадочных мест, соотношение сетевых и несетевых заведений, выявление наиболее популярных сетей, группировка данных по административным районам и визуализация.

### 4. Исследование для открытия кофейни:
Анализ рынка кофеен в Москве — количество заведений, их расположение, рейтинги и стоимость чашки капучино. Рекомендации для инвесторов по открытию кофейни.

## Описание столбцов данных

- `name` — название заведения;
- `address` — адрес заведения;
- `category` — категория заведения (например, кафе, ресторан, пиццерия);
- `hours` — время работы заведения;
- `lat` — широта местоположения;
- `lng` — долгота местоположения;
- `rating` — рейтинг заведения по оценкам пользователей (макс. 5.0);
- `price` — ценовая категория (средняя, выше или ниже среднего);
- `avg_bill` — средняя стоимость заказа (в рублях);
- `middle_avg_bill` — числовое значение среднего чека;
- `middle_coffee_cup` — стоимость чашки капучино;
- `chain` — сетевое заведение (0 — нет, 1 — да);
- `district` — административный округ Москвы;
- `seats` — количество посадочных мест.

## Используемые библиотеки

- Pandas
- Matplotlib
- Seaborn
- Folium

## Результаты исследования

Исследование выявило ключевые закономерности в распределении заведений общественного питания Москвы, а также предоставило рекомендации для инвесторов по выбору наиболее подходящего района и формата заведения для открытия кофейни.

