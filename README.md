# A-B-testing-result-analyze
Оценка корректности проведения A/B теста и оценка результатов теста новой платежной воронки

Используемые библиотеки: `pandas`, `numpy`, `stats`, `math`, `plotly`

# Задачи
- Оценить корректность проведения теста
  - проверить пересечения тестовой аудитории с другим тестом
  - проверить совпадение с маркетинговыми событиями
  - оценить другие проблемы временных границ теста 
- Проанализировать результаты теста: проверить статистическую разницу долей конверсии z-критерием

![Количество уникальных пользователей по группам по типу событий](<https://raw.githubusercontent.com/paraseusse/A-B-testing-result-analyze/main/%D0%9A%D0%BE%D0%BB%D0%B8%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%BE%20%D1%83%D0%BD%D0%B8%D0%BA%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D1%85%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D0%BF%D0%BE%20%D0%B3%D1%80%D1%83%D0%BF%D0%BF%D0%B0%D0%BC%20%D0%BF%D0%BE%20%D1%82%D0%B8%D0%BF%D1%83%20%D1%81%D0%BE%D0%B1%D1%8B%D1%82%D0%B8%D0%B9.png?token=AMTEIGADAH4E5CVTDGIMGMC7YIUU6>)

## Содержание
- Задачи проекта
- Описание набора данных
- Календарь маркетинговых событий на 2020 год
- Таблица пользователей, зарегистрировавшихся с 7 по 21 декабря 2020 года
- Таблица действий новых пользователей в период с 7 декабря 2020 по 4 января 2021 года
- Участники тестов
- Проверка данных
- Воронка для уникальных пользователей
- Анализ результатов A/B-теста
- Выводы
- Рекомендации
