# 📈 Проект: Анализ и оптимизация Retention Rate пользователей

**Роль:** Data Analyst / Product Analyst

## 📌 Саммари

Провел комплексный анализ поведения пользователей для выявления ключевых факторов удержания с помощью метрики Retention Rate (удержание пользователей). Это одна из ключевых метрик в стартапе или продукте, показывающая, насколько хорошо продукт удерживает своих пользователей со временем.

1. **Анализ кривой удержания**: Выявил критические точки оттока на 1-2 и 4-5 неделях
2. **Рекомендации**: Подготовил roadmap оптимизации пользовательского опыта

## ⚙️ Технический стек

- **Аналитика**:  
  ![SQL](https://img.shields.io/badge/-SQL-4479A1?logo=postgresql&logoColor=white&style=flat) ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat)

- **Визуализация**:  
  ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white&style=flat) ![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?logo=matplotlib&logoColor=white&style=flat) ![Seaborn](https://img.shields.io/badge/-Seaborn-1A3E5B?logo=seaborn&logoColor=white&style=flat)

## 📊 Ключевые метрики

| Период    | Retention Rate | Изменение | Индустриальный benchmark |
| --------- | -------------- | --------- | ------------------------ |
| 1 неделя  | 70.6%          | -         | 65-75%                   |
| 2 неделя  | 53.5%          | ▼ 24.1%   | ▼ 20-25%                 |
| 4 неделя  | 36.6%          | ▼ 14.3%   | ▼ 12-15%                 |
| 12 неделя | 27.1%          | ▼ 0.4%    | 25-30%                   |

## 🎯 Основные этапы работы

| Этап                    | Действия                                                  | Инструменты            |
| ----------------------- | --------------------------------------------------------- | ---------------------- |
| **1. Сбор данных**      | • Построение SQL-запросов<br>• Верификация данных         | PostgreSQL, ClickHouse |
| **2. Анализ удержания** | • Построение кривой retention<br>• Выявление точек оттока | Python, Pandas         |

## 🏆 Ключевые инсайты

### 🔍 Точки роста

- **Неделя 1-2**: Потеря 24.1% пользователей → проблемы с онбордингом
- **Неделя 4-5**: Дополнительный отток 11% → недостаток релевантного контента

### 🌟 Успешные практики

- **Ядро аудитории**: 27% показывают стабильную активность
- **Превышение benchmark'а**: +2.1% к среднерыночному показателю на 12 неделе

## 🚀 Рекомендации по улучшению

### Для новых пользователей (0-1 неделя)

- ✉️ Персонализированные welcome-пуш уведомления
- 🧪 A/B тест разных сценариев первого взаимодействия

### Для 4-5 недели

- 🔔 Триггерные сообщения при снижении активности
- 📊 Персональные рекомендации на основе поведения

### Для лояльных пользователей

- 🏆 Программа лояльности с бейджами
- 📢 Реферальная программа
