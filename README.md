# Финальный проект по машинному обучению

## Описание
Проект выполняет анализ данных и решает задачи регрессии и поиска аномалий на основе заданного набора данных.

## Структура данных
- **Country Name:** Название страны на русском языке.
- **Country Name English:** Название страны на английском языке.
- **AI Index:** Оценка искусственного интеллекта (баллы 1-100).
- **Management Remuneration:** Вознаграждение менеджмента (тыс. долл.).
- **Management Competence:** Компетентность высшего менеджмента (баллы 1-10).
- **Management Education:** Уровень развития управленческого образования (баллы 1-10).
- **Digital Skills:** Уровень развития цифровых компетенций (баллы 1-10).

## Разведочный анализ данных (EDA)
- Гистограммы: [histograms.png](histograms.png)
- Коробчатые диаграммы: [boxplots.png](boxplots.png)
- Тепловая карта корреляций: [heatmap.png](heatmap.png)

## Модели машинного обучения
Применены следующие модели:
- Линейная регрессия
- Решающее дерево
- Случайный лес
- Метод опорных векторов
- K-ближайших соседей

### Результаты моделей
| Модель                | MSE   | R2    |
|-----------------------|-------|-------|
| Линейная регрессия    | значение | значение |
| Решающее дерево       | значение | значение |
| Случайный лес         | значение | значение |
| Метод опорных векторов| значение | значение |
| K-ближайших соседей   | значение | значение |

Визуализация сравнения MSE: [mse_comparison.png](mse_comparison.png)

## Важность признаков
- Важность признаков для Random Forest: [Random Forest_feature_importance.png](Random Forest_feature_importance.png)
- Важность признаков для Decision Tree: [Decision Tree_feature_importance.png](Decision Tree_feature_importance.png)

## Поиск аномалий
Аномалии найдены в следующих данных:
