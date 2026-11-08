# AI 2026: Global & France v3 — MVP 35%

**Статус на 2026-11-08:** предварительный исследовательский рейтинг, НЕ доказательство PMF и НЕ инвестиционная рекомендация.

## Что изменилось

Из исходных **401** организаций Crunchbase (AI, founded 2026 по Crunchbase, For Profit, Active, Pre-Seed/Seed/A, Total Funding ≥$1, Growth Score Tier High):
- **202** получили предварительные баллы на основании доступного описания продукта.
- **57** повторно разобраны вручную с конкретным продуктом, узким MVP и источником; только из этого ручного пула построены v3 Top 40 Global / France.
- Для **199** описание/идентичность недостаточно подтверждены: **баллы оставлены пустыми**, а компании остаются в очереди на проверку, не объявляются неперспективными.
- Funding и CB Trend не приравниваются к спросу. Балл за traction — сила **публичных свидетельств**, а не независимо заверенная выручка.
- Полная таблица остаётся в Excel в текущем ChatGPT-чате: `ai_2026_research_v3_mvp35_global_france_401.xlsx`. Перепись проприетарного Crunchbase-реестра в публичный GitHub не загружается.

## Весовые коэффициенты, v3

### Global
- **Скорость и стоимость узкого MVP — 35%** (ранее 20%).
- Потенциал масштабирования — 25%.
- Сила публичных признаков спроса — 20%.
- Доступность первых продаж / GTM — 15%.
- Защищённость модели — 5%.

### France (отдельный рейтинг, не фильтр по стране регистрации)
- **MVP — 35%**.
- Французский спрос — 20%.
- Конкурентный зазор — 15%.
- Простота локализации — 10%.
- Лёгкость комплаенса — 10%.
- Французский GTM — 10%.

Оценки 1–5, нормированы к 100. Баллы — субъективные приоритеты тестирования, не вероятность успеха. Для каждого кандидата нужен чётко названный MVP на 4–12 недель, хотя некоторые сложнее. Открытая цена, funding и пользовательские метрики сами по себе не означают платящую аудиторию.

## Лидеры Global v3

1. **Trellis** — AI-операции краткосрочной аренды; self-reported $500k ARR / 35 компаний / 3000 объектов. Узкий тест: сообщения гостей и диспетчеризация клининга. https://www.ycombinator.com/companies/trellistech
2. **Sherpa** — AI-эксперименты и CRO сайтов. Заявленный кейс Lindy: 40 A/B за месяц, +30% conversion; причинность не подтверждена. https://www.ycombinator.com/companies/sherpa
3. **Grocalo** — AI-операции контента creators; клиенты поимённо, просмотры ≠ revenue. https://www.ycombinator.com/companies/grocalo
4. **Ontora** — AI-интервью сотрудников; заявлено 5 enterprise design partners и 150+ inbound demos; не доказаны оплаты. https://www.ycombinator.com/companies/ontora
5. **Discoverable** — GEO/AI-поиск; очень быстрый MVP, но нет проверенного PMF и большая конкуренция.
6. **LemonLime** — автоматизация GTM малого бизнеса; широкий рынок, но crowded.
7. **Herdr** — open source агентный runtime; более высокий технический барьер, не доказана монетизация.
8. **Alloovium** — поиск и цитируемая проверка строительных документов. Заявлено применение на проектах суммарной стоимостью $400 млн; не revenue. https://www.ycombinator.com/companies/alloovium
9. **OpenTag** — Slack AI coworker; публичные тарифы есть, оплаты не подтверждены. https://www.ycombinator.com/companies/opentag
10. **Poth Labs** — AI-аналитика клиентского поведения и оттока.
11. **14.ai** — AI-native customer-support service, есть именованные клиенты, ручной труд влияет на маржу.
12. **Kyndred** — AI-companions с голосом/памятью. Dealroom сообщает >150 платящих клиентов, $24/мес или $199/год; независимый аудит отсутствует. https://dealroom.co/news/157521-kyndred-raises-500-000-pre-seed-for-ai-companions-with-face-voice-and-me/

## Лидеры France v3

Предварительные лидеры по скорости теста и предполагаемому fit (НЕ по доказанной незанятой нише):
1. **Wondering** — AI-обучение. Большая конкуренция и пока нет доказанных оплат.
2. **Poth Labs** — AI-аналитика оттока/клиентского поведения. Французскую конкуренцию проверить.
3. **Pavoot** — AI follow-ups после B2B-мероприятий. Быстрый продукт, платность неизвестна.
4. **Discoverable** — GEO. Высокая конкуренция, отсутствие validation.
5. **Miracly** — GEO. Высокая конкуренция, отсутствие validation.

Для France сильнее опираться на конкретный сегмент, каналы продаж и локальную конкуренцию, а не на локализацию интерфейса.

## Существенные проверки и ошибки данных

- **Palisade**: у YC есть два разных продукта с этим названием, один — персональные e-commerce AI agents с заявленным >$2.7m GMV (GMV клиентов, не revenue стартапа). До сверки идентичности не помещать в строгий Top40. https://www.ycombinator.com/companies/palisade
- **Touchy → Tokenless**: текущий YC-профиль полностью другой — RL/evals security, а не iOS companion. Устаревшее описание следует считать ошибкой. https://www.ycombinator.com/companies/tokenless
- **CopperPilot**: несколько независимых источников указывают основание **в октябре 2025**, хотя наш исходный Crunchbase фильтр 2026. Не включать в строгую когорту до сверки. https://www.eetimes.com/copperpilot-raises-pre-seed-to-develop-ai-agent-for-pcb-design/
- **Kontext**: конфликт 2025/2026 по году основания; не включать без проверки. https://www.securityweek.com/kontext-security-emerges-with-4-million-for-ai-agent-runtime-controls/
- **Weflayr**: французская AI-gateway компания с $2.5m pre-seed (октябрь 2026), находится в стадии ограниченной беты; не утверждать, что маршрутизация inference — свободная французская ниша. https://weflayr.com/blog/weflayr-raises-2-5m/
- **Французский short-term rental**: Guesty в сентябре 2026 приобрёл Smily; сектор конкурентный. https://www.guesty.com/press/guesty-acquires-smily-deepening-its-investment-in-frances-booming-short-term-rental-market/
- **Французский CRO**: AB Tasty, Kameleoon — incumbents, Sherpa требует отличимого wedge.
- **Legifrance**: есть официальный API; возможность для узкого RegTech MVP. https://www.data.gouv.fr/dataservices/legifrance

## Следующие исследования

1. Закрыть **199** неподтверждённых профилей не фиктивными нулевыми баллами, а поиском первоисточников. Рассматривать top40 как временное ранжирование исследованного набора.
2. Проверить клиенты/оплаты/retention/COGS и конкурентов у Trellis, Sherpa, Ontora, Grocalo, Kyndred, Poth Labs, Regbase.
3. Провести короткие эксперименты: 2–3 платных B2B пилота или подтверждённый consumer retention и первые подписки.
4. Не фокусироваться только на Франции: Global — основной трек, France — независимый.
