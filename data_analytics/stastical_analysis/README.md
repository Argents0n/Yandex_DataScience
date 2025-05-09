# Проект: Статистический анализ данных сервиса GoFast

## Описание проекта
Анализ данных пользователей сервиса аренды самокатов GoFast для проверки гипотез, направленных на рост бизнеса. Включает обработку данных, исследовательский анализ, проверку статистических гипотез и расчёт выручки.

## Данные
### Основные таблицы:
1. **users_go.csv** - информация о пользователях:
   - `user_id` - уникальный идентификатор
   - `name` - имя
   - `age` - возраст
   - `city` - город
   - `subscription_type` - тип подписки (free/ultra)

2. **rides_go.csv** - данные о поездках:
   - `user_id` - ID пользователя
   - `distance` - расстояние (метры)
   - `duration` - продолжительность (минуты)
   - `date` - дата поездки

3. **subscriptions_go.csv** - условия подписок:
   - `subscription_type` - тип подписки
   - `minute_price` - цена минуты
   - `start_ride_price` - цена старта
   - `subscription_fee` - абонплата

## Этапы анализа

### 1. Загрузка данных
- Чтение CSV-файлов в pandas DataFrame
- Изучение структуры данных

### 2. Предобработка
- Приведение типов данных
- Создание столбца с месяцем
- Обработка пропусков и дубликатов

### 3. Исследовательский анализ
- Распределение пользователей по городам
- Соотношение типов подписок
- Анализ возраста пользователей
- Распределение расстояний и времени поездок

### 4. Объединение данных
- Слияние таблиц в единый датафрейм
- Разделение на пользователей с подпиской и без
- Визуализация сравнения групп

### 5. Расчёт выручки
- Агрегация данных по пользователям и месяцам
- Расчёт помесячной выручки с учётом:
  - Округления времени поездки
  - Условий подписок

### 6. Проверка гипотез
1. Сравнение времени поездок между группами
2. Проверка среднего расстояния поездки у подписчиков (≤3130 м)
3. Сравнение выручки от разных групп пользователей
4. Выбор теста для оценки изменений после обновления серверов

### 7. Дополнительные задачи (опционально)
1. Расчёт минимального количества промокодов для акции
   - Параметры: 10% конверсия, ≤5% риска невыполнения плана
2. Оценка открытий push-уведомлений (40% rate)
   - Аппроксимация для 1 млн отправок

## Используемые технологии
- Python
- Pandas
- Matplotlib/Seaborn
- SciPy (статистические тесты)

## Результаты
Анализ позволит:
- Оценить profitability разных групп пользователей
- Определить перспективные направления для маркетинговых акций
- Подтвердить или опровергнуть ключевые бизнес-гипотезы

> Примечание: Полный код реализации доступен в Jupyter Notebook проекта.
