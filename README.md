### Привет, я Андрей 👋

Java-разработчик — микросервисы, REST API, событийная интеграция. Строю системы production-уровня: от архитектуры и бэкенда до CI/CD и эксплуатации.

🟢 Открыт к предложениям — full-time Java-разработчик, гибрид/удалённо.

**Стек:** Java 8/11/17/21/25 · Kotlin · Spring Boot · Spring Cloud · Spring Security (OAuth2/JWT) · Kafka · PostgreSQL · Redis · Docker · Kubernetes · GitLab CI/Jenkins · LangChain4j

---

#### 🔨 Проекты

**[self-healing-saga](https://github.com/Andrey834/self-healing-saga)** — распределённая обработка заказов: сага на хореографии + transactional outbox, 4 микросервиса на Spring Boot 4.1 (Java 25 и Kotlin). LLM-агент (LangChain4j + Yandex Cloud AI) решает retry/compensate/escalate при неоднозначных сбоях, с жёстким предохранителем и безопасным откатом при недоступности модели. Kafka в режиме KRaft, идемпотентные консьюмеры, Prometheus/Grafana из коробки, Testcontainers-тесты на каждый сервис.

**[telemetry-system](https://github.com/Andrey834/telemetry-system)** — приём и обработка телеметрии парка транспорта в реальном времени: реактивный конвейер Kafka (KRaft, партиционирование по deviceId) → Redis (текущее состояние) + PostgreSQL (история) на Spring Boot 4.1 WebFlux + R2DBC, живой Angular-дашборд с SSE вместо поллинга, кластеризацией маркеров и JWT-авторизацией по ролям. Развёрнут на управляемом Kubernetes в Yandex Cloud (Terraform, GitOps через ArgoCD, автомасштабирование), нагрузочный тест k6 — 62 624 запроса, 99.82% успешных, p95 112 мс.

**[market-microservices](https://github.com/Andrey834/market-microservices)** — e-commerce платформа [podarok86.ru](https://podarok86.ru) с реальными пользователями: 6 backend-сервисов на Spring Boot + Angular-витрина и админ-панель. Микросервисная архитектура с нуля (Eureka, Spring Cloud Gateway), собственный auth-service на Spring Authorization Server (OAuth2/OIDC), реактивный стек WebFlux/R2DBC, Flyway-миграции, независимый CI/CD для 8 репозиториев. Ключевые сервисы (order, product) покрыты unit- и Testcontainers-интеграционными тестами на реальном PostgreSQL.

**[rentcar-user-register](https://github.com/Andrey834/rentcar-user-register)** — REST API для управления автопрокатом: доменная модель на 8 бизнес-сущностей, 30+ эндпоинтов, OpenAPI/Swagger, Docker Compose.

**[devops-shop-platform](https://github.com/Andrey834/devops-shop-platform)** — DevOps-инфраструктура для 3-tier приложения: Terraform (Yandex Cloud), Kubernetes с HPA/VPA, Ansible, Helm, Prometheus/Alertmanager, независимый CI/CD.

**[task-manager-java](https://github.com/Andrey834/task-manager-java)** — REST API с событийными уведомлениями через Kafka: producer/consumer, ручной ack, retry с backoff через `@RetryableTopic`, Kafka в режиме KRaft, тесты на Testcontainers.

---

[![LeetCode Stats](https://leetcard.jacoblin.cool/andrey834)](https://leetcode.com/andrey834/)

---

💬 [Telegram](https://t.me/andrey86m)
