Книжный список для DevOps-инженера: подборка по уровням и темам (база → архитектура → DevOps/SRE → практики → культура/процессы). Источник — статья «Книжная полка DevOps-инженера» (Сергей Задорожный, Яндекс Практикум/финтех).

# Книжная полка DevOps-инженера

> [!abstract] Подборка книг для роста DevOps-инженера, разбитая по логике развития: базовые навыки → архитектура распределённых систем → DevOps/SRE → практики (CI/CD, IaC, Observability) → культура и процессы внедрения.

---

## Базовый уровень

• Начинай с простых и понятных книг, потому что тяжёлая академика на старте даёт мало практической пользы.
• Заходишь из разработки — выбирай Head First и язык из своего стека, чтобы сразу применять на работе.
• Паттерны проектирования на старте — Head First Design Patterns, потому что вход проще, чем в GOF.
• Git — Head First Git, чтобы понимать механику, а не только команды.
• Заходишь из администрирования — не начинай с “энциклопедий” уровня Linux API; сначала концепции и базовые команды.
• Docker — обязателен; бери актуальные издания, потому что старые быстро устаревают.
• После Docker — безопасность контейнеров, потому что важно понимать атаки и хардeнинг от сборки образа до рантайма.

---

## Архитектура

• Считай распределённость нормой: без архитектурной базы системы будут “сыпаться” в реальном проде.
• Изучи разные архитектурные стили, потому что выбор не сводится к “монолит vs микросервисы”.
• Для фундаментальной базы ориентируйся на Нила Форда и Марка Ричардса (подходы, свойства, компромиссы).
• Микросервисы удобно начинать с Сэма Ньюмана; новые издания могут быть сильно расширены.
• Следи за качеством перевода: плохая локализация ломает терминологию и мешает учиться.
• Академические книги по микросервисам оставляй на позже, когда появится опыт и контекст.
• “Обзорные/спидран”-книги полезны как карта пути “от архитектуры до релиза”, но могут объяснять неровно.

---

## DevOps и SRE как методологии

• DevOps нужен, чтобы сокращать ручную поставку, релизные ошибки и аварии, потому что это не даёт бизнес-ценности.
• Начни с базовой книги по DevOps-культуре, чтобы понять смысл изменений, а не только инструменты.
• SRE от Google используй как источник идей и ориентиров, но не копируй механически, потому что контекст компаний разный (карго-культ вреден).
• Дополняй картину другими SRE-книгами (воркбуки, сборники опыта, надёжность БД, roadmap).

---

## Практики: CI/CD, Observability, IaC

• Сначала изучай принципы практик без привязки к инструментам, чтобы понимать “почему так”, а не “как в конкретной тулзе”.
• CI/CD — выбирай книги с жизненными примерами и обоснованиями решений, потому что это делает подход переносимым.
• Observability — держи отдельную базу по мониторингу, чтобы строить наблюдаемость как систему, а не набор графиков.
• IaC — изучай “инфра как код” как подход, потому что он про управляемость и адаптивность систем.
• Переход к инструментам делай через практику, иначе знания останутся теорией.

---

## Культура и процессы внедрения

• DevOps называют культурой, но в организации его внедряют конкретные инженеры — учитывай этот “человеческий слой”.
• Закладывай сопротивление изменениям: даже хорошее техническое решение не взлетит без процессов и культуры.
• Изучай, как устроены высокопроизводительные организации, чтобы понимать, что масштабируется.
• Смотри на топологию команд (platform/enabling и т.п.), потому что структура команд влияет на скорость поставки.
• Используй идеи из книг как варианты и гипотезы, а не как догму — адаптируй под контекст компании.

---

#devops #books #architecture #sre #cicd #iac #observability

## Ссылки и источники

* Head First Kotlin. A Brain-Friendly Guide — Dawn Griffiths, David Griffiths
* Head First Design Patterns — Eric Freeman, Elisabeth Robson, Kathy Sierra, Bert Bates
* Head First Git: A Learner's Guide to Understanding Git from the Inside Out — Raju Gandhi
* Docker in Action, Second Edition — Jeff Nickoloff, Stephen Kuenzli
* Container Security: Fundamental Technology Concepts that Protect Containerized Applications — Liz Rice
* Fundamentals of Software Architecture: An Engineering Approach — Mark Richards, Neal Ford
* Software Architecture: The Hard Parts: Modern Trade-Off Analyses for Distributed Architectures — Neal Ford, Mark Richards, Pramod Sadalage, Zhamak Dehghani
* Building Evolutionary Architectures: Automated Software Governance — Neal Ford, Rebecca Parsons, Patrick Kua, Pramod Sadalage
* Head First Software Architecture: A Learner's Guide to Architectural Thinking — Raju Gandhi, Mark Richards, Neal Ford
* Building Microservices: Designing Fine-Grained Systems — Sam Newman
* Monolith to Microservices: Evolutionary Patterns to Transform Your Monolith — Sam Newman
* Microservices in Action — Morgan Bruce, Paulo A. Pereira
* Microservices Up and Running: A Step-by-step Guide to Building a Microservices Architecture — Ronnie Mitra, Irakli Nadareishvili
* The DevOps Handbook: How to Create World-Class Agility, Reliability, & Security in Technology Organizations — Gene Kim, Patrick Debois, John Willis, Jez Humble
* Site Reliability Engineering: How Google Runs Production Systems — Jennifer Petoff, Betsy Beyer, Chris Jones, Niall Richard Murphy
* The Site Reliability Workbook — Betsy Beyer, Niall Richard Murphy, David K. Rensin, Kent Kawahara, Stephen Thorne
* Seeking SRE: Conversations About Running Production Systems at Scale — David N. Blank-Edelman
* Database Reliability Engineering: Designing and Operating Resilient Database Systems — Laine Campbell, Charity Majors
* Enterprise Roadmap to SRE: How to Build and Sustain an SRE Function — James Brookbank, Steve McGhee
* Building Secure and Reliable Systems: Best Practices for Designing, Implementing, and Maintaining Systems — Heather Adkins et al.
* Grokking Continuous Delivery — Christie Wilson
* Continuous Deployment: Enable Faster Feedback, Safer Releases, and More Reliable Software — Valentina Servile
* Practical Monitoring. Effective Strategies For The Real World — Mike Julian
* Infrastructure as Code: Dynamic Systems for the Cloud Age — Kief Morris
* Accelerate: The Science of Lean Software and DevOps — Nicole Forsgren, Jez Humble, Gene Kim
* Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation — Jez Humble, David Farley
* Team Topologies: Organizing Business and Technology Teams for Fast Flow — Manuel Pais, Matthew Skelton
* Using Docker: Developing and Deploying Software with Containers — Adrian Mouat
