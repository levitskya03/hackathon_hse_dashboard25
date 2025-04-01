# hackathon_hse25
Репозиторий с материалами для хакатона в Школе21 4-5 марта.

Уважаемые студенты, хакатон официально будет проведен **4-5 числа**, все нужные материалы будут доступны 4 марта, а сейчас Вы можете подробнее ознакомиться с заданиями!

[Форма регистрации](https://docs.google.com/forms/d/e/1FAIpQLSfctfXZAeodAUzlbw7ZMr1M4445L849MRVswhWzpfqdwSqiDg/viewform?usp=dialog)
![Логотип GitHub](/logo.png)

# 🚀 Hackathon Repo

## 🏆 **Добро пожаловать в репозиторий проекта от команды СП4!**

Мы — команда **СП4**, и наш проект посвящён созданию чат-бота на основе технологии **RAG (Retrieval-Augmented Generation)** (почитать [туть](https://habr.com/ru/articles/779526/ "че такое РАГ?")) с использованием **Gigachat**. Этот бот помогает студентам НИУ ВШЭ находить ответы на вопросы, связанные с учебным процессом, административными вопросами, наукой и внеучебкой.

Наш бот - [Он в телеграме, но скоро будет в HSE APP X!](https://t.me/hse_stud_help_bot)

Наша цель — не только предоставить удобный инструмент для студентов, но и улучшить его, сделав работу модели более точной, эффективной и удобной для использования.

---

## 🌟 **Предлагаем две задачи для участников хакатона:**

### 🟢 **1. Автоматический мониторинг качества модели через дашборд**

**Проблема:**
Мы хотим понимать, насколько хорошо наш чат-бот справляется с задачами. Для этого нужны метрики, которые будут автоматически собираться и визуализироваться.

**Решение:**
Создание сервиса, который:
- Собирает метрики качества работы модели (корректность, релевантность, точность контекста). (Скрипты для метрик мы Вам дадим)
- Анализирует пользовательскую удовлетворённость (лайк/дизлайк).
- Отображает результаты в виде интерактивного дашборда (Streamlit/Dash).

**Ресурсы:**
- Ознакомьтесь с [описанием задачи](./docs/hackathon_dashboard.md).
- Исходный код базовых метрик находится в папке [`metrics/`](./metrics.py).

**Критерии успеха:**
1. Реализация дашборда для демонстрации метрик.
2. Дашборд с визуализацией в реальном времени.
3. (⭐) Придумать свою метрику 

---

## 🛠️ **Структура репозитория**

```bash
├── config             # Файл с system_prompt.yaml
├── metrics            # Скрипты для расчёта метрик
├── docs               # Описание каждого из заданий в соответствующем файле
└── README.md          # Описание проекта
```

---

## 🤝 **Как принять участие?**

1. Форкните репозиторий.
2. Реализуйте решение.
3. Создайте pull request.

Мы будем рады вашим предложениям, улучшениям и готовым решениям!

---

## 📞 **Контакты**

Если у вас возникли вопросы, идеи или предложения, свяжитесь с нами через 

[Телеграм](https://t.me/vlone_l).(разработчик)
[Телеграм](https://t.me/bi_ulitin).(организатор)


🚀 **Спасибо за участие и удачи на хакатоне!** 🚀

