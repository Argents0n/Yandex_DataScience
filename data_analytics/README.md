# Репозиторий: Data Analytics Projects

В этом репозитории представлены три проекта по анализу данных, выполненные в рамках различных кейсов и исследований.

---

## Содержание

1. [Исследовательский анализ данных объявлений о продаже квартир](./research_analisys)
2. [Аналитический кейс: Исследование российского кинопроката](./analytical_case)
3. [Статистический анализ данных сервиса GoFast](./stastical_analysis)

---

## 1. Исследовательский анализ данных объявлений о продаже квартир

**Папка:** [research_analisys](./research_analisys)

**Описание проекта:**  
Анализ архива объявлений **Яндекс.Недвижимости** для определения рыночной стоимости объектов в Санкт-Петербурге и области. Цель — выявление параметров, влияющих на цену, и создание системы обнаружения аномалий.

**Используемые технологии:**  
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%23150458.svg?style=for-the-badge&logo=python&logoColor=white)

**Данные:**  
- Файл: `real_estate_data.csv` (23 699 объектов, 22 параметра)  
- Основные столбцы: цена, площадь, комнаты, этаж, расстояние до центра и др.

**Этапы анализа:**  
1. Загрузка и первичный анализ  
2. Предобработка данных  
3. Расчёт новых параметров  
4. Исследовательский анализ (распределения, скорость продаж, факторы цены)  
5. Региональный анализ  

**Основные выводы:**  
- Средняя цена м² в СПб: ~114 000 ₽, в области значительно ниже  
- Наибольшее влияние на цену оказывают площадь, количество комнат, тип этажа и расстояние до центра  
- 50% квартир продаются за 73 дня или быстрее  

---

## 2. Аналитический кейс: Исследование российского кинопроката

**Папка:** [analytical_case](./analytical_case)

**Описание проекта:**  
Исследование рынка российского кинопроката с фокусом на фильмы, получившие государственную поддержку. Заказчик — **Министерство культуры РФ**.

**Используемые технологии:**  
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%23150458.svg?style=for-the-badge&logo=python&logoColor=white)

**Данные:**  
- `mkrf_movies.csv` — фильмы, студии, бюджеты, рейтинги, жанры  
- `mkrf_shows.csv` — кассовые сборы по прокатным удостоверениям

**Этапы работы:**  
1. Объединение и предобработка данных  
2. Исследовательский анализ  
3. Анализ фильмов с государственной поддержкой  
4. Выводы и визуализация тенденций  

**Основные выводы:**  
- Рост числа фильмов и кассовых сборов с 2010 по 2017 год  
- Государственная поддержка растет, но не всегда гарантирует окупаемость  
- Наиболее популярные жанры: драма и комедия  
- Фильмы «16+» и «12+» наиболее успешны по кассовым сборам  

---

## 3. Статистический анализ данных сервиса GoFast

**Папка:** [stastical_analysis](./stastical_analysis)

**Описание проекта:**  
Анализ данных пользователей сервиса аренды самокатов **GoFast** для проверки гипотез и улучшения бизнес-показателей.

**Используемые технологии:**  
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%23150458.svg?style=for-the-badge&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)

**Данные:**  
- `users_go.csv` — информация о пользователях  
- `rides_go.csv` — данные о поездках  
- `subscriptions_go.csv` — тарифы и условия подписок

**Этапы анализа:**  
1. Загрузка и изучение данных  
2. Предобработка  
3. Исследовательский анализ  
4. Объединение и сегментация данных  
5. Финансовый анализ  
6. Статистическая проверка гипотез  
7. Маркетинговые расчёты и прогнозирование

**Основные выводы:**  
- Целевая аудитория: 22-28 лет, основная география — Пятигорск  
- Ultra-подписчики делают более частые и короткие поездки  
- 55% пользователей — free, 45% — ultra  
- Расчёты выручки и маркетинговые гипотезы позволяют оценить эффективность акций  

---


