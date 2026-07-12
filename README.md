# Анализ факторов риска рака желудка

## Описание проекта
Проект направлен на оценку факторов риска развития рака желудка и построение модели машинного обучения для прогнозирования заболевания на основе данных пациентов.

## Датасет
- **Источник:** [Gastric Cancer Dataset](https://www.kaggle.com/datasets/datasetengineer/gastric-cancer-gc-dataset) (Kaggle)
- **Размер:** 212 354 записи, 29 признаков
- **Целевая переменная:** `label` (1 — рак, 0 — нет)

## Структура репозитория
- `notebooks/` — Jupyter ноутбуки с анализом и обучением моделей
- `src/` — вспомогательные скрипты
- `results/` — графики и отчёты
- `requirements.txt` — список зависимостей

## Используемые библиотеки
- pandas, numpy — обработка данных
- matplotlib, seaborn — визуализация
- scikit-learn — модели машинного обучения
- xgboost — градиентный бустинг

## Результаты
Лучшая модель — XGBoost:
- **Accuracy:** 0.5909
- **Recall:** 0.3830
- **ROC-AUC:** 0.4972

**Вывод:** Из-за сильного дисбаланса классов (10% больных, 90% здоровых) модели показывают низкую предсказательную способность.

## Ссылки
- [Репозиторий](https://github.com/zaqplm1/gastric-cancer-risk-analysis)
- [Датасет](https://www.kaggle.com/datasets/datasetengineer/gastric-cancer-gc-dataset)
- [Google Colab](https://colab.research.google.com/drive/1AfKB31esw-q6Nlnv2--ik-D0peRsu3C2)
- [Google Документ (отчёт)](https://docs.google.com/document/d/18EFE-dFHSMutU28FbGjywpq88073qMv0XiFkqSvulGA/edit?tab=t.0)

## Автор
Полина Макарова
