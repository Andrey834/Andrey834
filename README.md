### Привет, я Андрей 👋

Java-разработчик — микросервисы, REST API, событийная интеграция. Строю системы production-уровня: от архитектуры и бэкенда до CI/CD и эксплуатации.

**Стек:** Java 17/21/25 · Kotlin · Spring Boot · Spring Cloud · Spring Security (OAuth2/JWT) · Kafka · PostgreSQL · Redis · Docker · Kubernetes · GitLab CI/Jenkins · LangChain4j

---

#### 🔨 Проекты

**[self-healing-saga](https://github.com/Andrey834/self-healing-saga)** — распределённая обработка заказов: сага на хореографии + transactional outbox, 4 микросервиса на Spring Boot 4.1 (Java 25 и Kotlin). LLM-агент (LangChain4j + Yandex Cloud AI) решает retry/compensate/escalate при неоднозначных сбоях, с жёстким предохранителем и безопасным откатом при недоступности модели. Kafka в режиме KRaft, идемпотентные консьюмеры, Prometheus/Grafana из коробки, Testcontainers-тесты на каждый сервис.

**[market-microservices](https://github.com/Andrey834/market-microservices)** — e-commerce платформа [podarok86.ru](https://podarok86.ru): 6 backend-сервисов на Spring Boot + Angular-витрина и админ-панель. Микросервисная архитектура с нуля (Eureka, Spring Cloud Gateway), собственный auth-service на Spring Authorization Server (OAuth2/OIDC), реактивный стек WebFlux/R2DBC, независимый CI/CD для 8 репозиториев.

**[rentcar-user-register](https://github.com/Andrey834/rentcar-user-register)** — REST API для управления автопрокатом: доменная модель на 8 бизнес-сущностей, 30+ эндпоинтов, OpenAPI/Swagger, Docker Compose.

**[devops-shop-platform](https://github.com/Andrey834/devops-shop-platform)** — DevOps-инфраструктура для 3-tier приложения: Terraform (Yandex Cloud), Kubernetes с HPA/VPA, Ansible, Helm, Prometheus/Alertmanager, независимый CI/CD.

**[task-manager-java](https://github.com/Andrey834/task-manager-java)** — REST API с событийными уведомлениями через Kafka: producer/consumer, ручной ack, retry с backoff через `@RetryableTopic`, Kafka в режиме KRaft, тесты на Testcontainers.

---

💬 [Telegram](https://t.me/andrey86m)
