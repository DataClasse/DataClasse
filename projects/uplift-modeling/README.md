# 📈 Uplift-моделирование

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-Production-success.svg)]()

## 📋 Описание проекта

Uplift-модель для определения наиболее эффективной аудитории для маркетинговых кампаний. Проект включает A/B тестирование, развертывание в облаке и мониторинг качества модели в продакшне.

### Бизнес-задача

Оптимизация маркетинговых кампаний через таргетирование только тех клиентов, которые положительно отреагируют на воздействие. Это позволяет снизить затраты на рекламу и повысить ROI кампаний.

**Бизнес-ценность:**
- Увеличение эффективности маркетинговых кампаний
- Снижение затрат на рекламу
- Повышение конверсии

### Задача машинного обучения

**Тип задачи:** Uplift Modeling (Causal Inference)

**Целевая метрика:**
- **Uplift: 12%** (против 3% в контрольной группе)
- ATE (Average Treatment Effect)
- Qini coefficient

## 🎯 Ключевые достижения

- ✅ **Uplift 12%** — значительное улучшение по сравнению с контролем (3%)
- ✅ **A/B тестирование** — валидация модели на реальных данных
- ✅ **Cloud deployment** — развертывание в Yandex Cloud с автоскейлингом
- ✅ **Мониторинг** — отслеживание качества модели в продакшне

## 🛠 Технологический стек

- **Python** 3.8+, **Scikit-uplift**, **Scikit-learn**, **Pandas**, **NumPy**
- **Kubernetes**, **Yandex Cloud**
- **MLflow**, **Grafana**

## 📊 Метрики качества

| Метрика | Значение | Описание |
|---------|----------|----------|
| **Uplift** | 12% | Улучшение конверсии в тестовой группе |
| **ATE** | 0.09 | Average Treatment Effect |
| **Qini coefficient** | 0.15 | Качество ранжирования |

## 🏗 Архитектура решения

```
Data (PostgreSQL) → Uplift Model (Scikit-uplift) → A/B Validation → Kubernetes (Yandex Cloud) → Monitoring (Grafana)
```

## 👤 Автор

**Дмитрий Щербаков**

- 🔗 **Код:** [github.com/DataClasse/uplift-modeling](https://github.com/DataClasse/uplift-modeling)
- 📧 Email: [aiopendata@gmail.com](mailto:aiopendata@gmail.com)
- 💻 GitHub: [@DataClasse](https://github.com/DataClasse)

---

⭐ Если проект был полезен, поставьте звезду!
