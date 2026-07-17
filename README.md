# Портфолио аналитика данных

Учебные проекты по анализу данных на Python. В ноутбуках есть код, таблицы и
графики — можно смотреть без запуска. Сами датасеты сюда не клал: часть из них
учебные и с ограничениями на распространение.

## Проекты

- [Предобработка данных](notebooks/data_preprocessing.ipynb) — пропуски, дубликаты, категории
- [Аренда самокатов](notebooks/statistical_analysis_scooter_rides.ipynb) — гипотезы и сравнение тарифов
- [Недвижимость](notebooks/real_estate_exploratory_analysis.ipynb) — что влияет на цену квартиры
- [Кинопрокат](notebooks/russian_film_industry_analysis.ipynb) — рынок фильмов и господдержка
- [NPS в телекоме](notebooks/telecom_csi_analysis.ipynb) — SQL + лояльность клиентов
- [Тарифы телефонии](notebooks/telecom_tariff_optimization.ipynb) — поведение клиентов и выручка
- [Маркетинг приложения](notebooks/marketing_business_metrics.ipynb) — LTV, CAC, ROI
- [Общепит Москвы](notebooks/moscow_food_market.ipynb) — заведения и идеи для открытия
- [Вакансии аналитиков](notebooks/hh_vacancies_analysis.ipynb) — DA vs SA на рынке труда
- [TED / Tableau](notebooks/tableau_ted_dashboard.ipynb) — описание дашборда

## Стек

Python, pandas, NumPy, SciPy, Matplotlib, Seaborn, Plotly, Folium, SQL, Tableau.

## Как запустить

```bash
pip install -r requirements.txt
jupyter notebook
```

Файлы данных кладутся в `data/` (см. [data/README.md](data/README.md)).
Пути в ноутбуках вида `../data/...`.
