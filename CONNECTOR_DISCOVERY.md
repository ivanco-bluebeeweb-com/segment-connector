# Segment Connector — Discovery

**Vendor:** Segment (https://segment.com)  
**API Base URL:** `https://api.segmentapis.com`  
**Authentication:** Segment Public API Token (Bearer <token>)

## Архитектура API
- **Ключевые сущности:** источники данных (/sources), назначения (/destinations), планы трекинга (/tracking-plans), серверные функции (/functions)
- **Формат обмена данными:** JSON / HTTPS REST.
- **Обработка ошибок:** Стандартные HTTP-коды (400, 401, 403, 404, 429, 500) с типизацией ответа.
- **Тестовая точка проверки подключения:** `GET /sources`.
