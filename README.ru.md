<h1 align="center">Привет, я Наталья Вегман</h1>

<h3 align="center">ИИ-архитектор: системы для бизнеса и для поиска по архивам</h3>

<p align="center">
  <a href="mailto:nata@vegman.dev">nata@vegman.dev</a>,
  <a href="https://t.me/natroot">Telegram @natroot</a>,
  <a href="https://vegman.dev">vegman.dev</a>
</p>

<p align="center">
  <a href="README.md">Read in English</a>
</p>

---

Я проектирую и внедряю ИИ-системы, которые работают в продакшне. За этим 19 лет практики в IT: от руководства службой ИТ из 40 человек в одном из крупнейших морских пароходств России до RAG-пайплайнов, мультиагентных архитектур и корпоративных хранилищ данных для нынешних клиентов. Я проектирую систему, пишу код, разворачиваю его и отвечаю за результат.

Второе мое направление: генеалогия. Ищу семьи в архивах России и Европы: Петербург, Рязань и Пенза, федеральные архивы, Arolsen Archives и немецкие книги ЗАГС, эстонские и еврейские архивы. Работа с архивами требует того же, что хорошая система: каждый вывод опирается на источник, каждый пустой результат записан. Поэтому и для нее я делаю ИИ-инструменты.

---

### Чем я занимаюсь

**Бизнес**

- **ИИ-архитектурный консалтинг:** аудит бизнес-процессов, подбор LLM-стека, архитектурная схема с обоснованием каждого решения и поэтапный план внедрения
- **Мультиагентные системы:** оркестратор, исследователь, разработчик и дизайнер с маршрутизацией по доменам, общим состоянием и резервными LLM-провайдерами через OpenRouter
- **RAG-пайплайны:** мультимодальный поиск по тексту, изображениям и аудио на FAISS и ChromaDB
- **Корпоративные DWH:** PostgreSQL, SQLAlchemy 2.0, миграции Alembic, оркестрация ETL в n8n
- **Автоматизация бизнеса:** разрозненные SaaS, PMS и CRM в одном рабочем процессе с ИИ

**Генеалогия**

- **Российские архивы:** метрические книги и ревизские сказки в Петербурге, Рязани и Пензе, запросы в федеральные архивы
- **Европа:** Arolsen Archives и немецкие книги ЗАГС по угнанным в Германию, эстонские архивы, еврейские архивные коллекции
- **Инструменты для архивов:** OCR рукописных метрических книг, выкачка оплаченных архивных дел, реестр из 300+ онлайн-источников, таблицы вариантов имен для немецкой транслитерации
- **Слой доказательств:** древо на 2 400+ человек, где у каждого факта есть источник, дословная цитата и статус доказанности

---

### Технологический стек

| Слой | Инструменты |
|---|---|
| **Языки и фреймворки** | Python (FastAPI, SQLAlchemy 2.0, Alembic, pandas, Flask, PyQt6) |
| **Базы данных и векторный поиск** | PostgreSQL, ChromaDB, FAISS, Docker, Docker Compose |
| **Парсинг и автоматизация** | Playwright, Selenium (headless), BeautifulSoup, n8n |
| **AI / LLM** | OpenAI (GPT-4o, Vision), Anthropic Claude, Google Gemini 2.5, GigaChat, OpenRouter |
| **Обучение моделей** | Hugging Face (Transformers, PEFT/LoRA, TRL, BitsAndBytes), Yandex SpeechKit |
| **ИИ-агенты** | Claude Code, Hermes, OpenClaw, MCP, маршрутизация по доменам |
| **OCR и документы** | Yandex Vision, GEDCOM, Gemini Vision |
| **Инфраструктура** | nginx, systemd, certbot (Let's Encrypt), GitHub Pages |
| **Корпоративные системы** | Bnovo PMS, Bitrix24, AmoCRM, SAP, 1С, UN Comtrade API |

---

### Проекты

**Бизнес**

| Проект | Стек | Ссылки |
|---|---|---|
| **DWH и аналитика рыбной отрасли** | PostgreSQL, SQLAlchemy, n8n, Notion API | [GitHub](https://github.com/natavegman/ships_analytic) |
| **ИИ-ассистент для отелей** (мультимодальный бот для сети отелей) | FastAPI, ChromaDB, GigaChat, GPT-4o Vision, Bnovo PMS, Yandex SpeechKit | |
| **Система мониторинга конкурентов** (рыбная отрасль) | PyQt6, Selenium, GPT-4o, PostgreSQL, PyInstaller | |
| **Дообучение LLM** (LoRA, PEFT) | Hugging Face, TRL, BitsAndBytes, Google Colab | |
| **Мультиагентная система для консалтинга** | Hermes, OpenClaw, MCP, OpenRouter, Telegram, systemd | |
| **Персональный HR-агент** (это портфолио) | FastAPI, FAISS, OpenAI, GitHub Pages, nginx | [GitHub](https://github.com/natavegman/portfolio-site), [Сайт](https://vegman.dev) |
| **Smart Style Bot** (ИИ-стилист с виртуальной примеркой) | Gemini Vision, fal.ai, Telegram, PostgreSQL | [GitHub](https://github.com/natavegman/Smart-Style-Bot) |

**Генеалогия**

| Проект | Стек | Ссылки |
|---|---|---|
| **ex-ussr-kinship-research** (участник): раздел про Arolsen Archives и немецкие книги ЗАГС | Markdown, скилл для Claude Code и Codex | [Pull request](PR_LINK) |
| **Семейная история: поиск по архивам** (закрытый): архивы России и Европы, OCR метрических книг, слой доказательств для древа на 2 400+ человек | Python, Playwright, Yandex Vision, GEDCOM, Notion API | |

Заметки о генеалогии: [Telegram @nat_roots](https://t.me/nat_roots)

---

### Образование

- **Инженер**, Программное обеспечение вычислительной техники и автоматизированных систем *(специализация: ПО автоматизированных систем в науке, производстве и бизнесе)*
  Мурманский государственный технический университет, 1999-2004, **диплом с отличием**

- **Экономист**, Финансы и кредит *(специализация: Финансовый менеджмент)*
  Мурманский государственный технический университет, 2002-2005, **диплом с отличием**

- **Профессиональный Prompt Engineer**, Zerocoder Университет, 5-месячный профессиональный курс
  Дополнительно: Claude Code (Anthropic), инструменты Google AI (Gemini, NotebookLM, Google Cloud AI)

---

### Статистика GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=natavegman&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&text_color=c9d1d9&icon_color=58a6ff&title_color=58a6ff" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=natavegman&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&text_color=c9d1d9&title_color=58a6ff" width="48%" />
</div>
