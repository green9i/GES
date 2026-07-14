---
id: WO-TEMPLATE
title: Work Order Template
type: Template
version: 1.0
status: Active
owner: GES | 00 | Chief Architect
language: ru-RU
created: 2026-07-13
modified: 2026-07-14
---

# Work Order Template

## 1. Идентификатор

WO-XXX


---

# 2. Назначение

Описание конкретной инженерной задачи.

Ответ на вопрос:

"Что требуется выполнить?"


---

# 3. Инициатор

Рабочее пространство или субъект, инициировавший задачу.


---

# 4. Ответственное рабочее пространство

GES Workspace:

Например:

GES | 07 | Documentation Center


---

# 5. Связанные инженерные записи

Указывается основание задачи:

- RFC
- ADR
- ST
- OM
- WP
- другой WO


---

# 6. Основание создания

Почему появилась необходимость выполнения задачи.


---

# 7. Входящие данные

Материалы, необходимые для выполнения.


---

# 8. Связанный Work Protocol

Какой процесс используется.

Пример:

WP-003 Documentation Process


---

# 9. Маршрут выполнения

Используется совместно с Route Card.


Пример:


Инициатор

↓

Responsible Workspace

↓

Execution

↓

Review

↓

Repository



---

# 10. Ограничения

Что запрещено изменять.


---

# 11. Требуемый результат

Описание ожидаемого результата.


---

# 12. Созданные инженерные записи

Какие объекты появились после выполнения.


---

# 13. Статус

Lifecycle:


Draft

↓

Assigned

↓

In Progress

↓

Review

↓

Completed

↓

Archived



---

# 14. История изменений

| Version | Date | Change |
|-|-|-|
|1.0| | Initial|
|1.1| | Added routing and lifecycle control|
