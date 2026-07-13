---
id: ADR-009
title: Workspace as Engineering Object
type: Architecture Decision Record
version: 1.0
status: Active
owner: GES | 00 | Chief Architect
language: ru-RU
---

# ADR-009

# Рабочее пространство как инженерный объект

---

# Context

При развитии GES возник вопрос:

является ли рабочее пространство только организационной единицей или самостоятельным объектом системы.

---

# Decision

Рабочее пространство является полноценным инженерным объектом GES.

---

# Обоснование

Рабочее пространство имеет:

- идентификатор;
- назначение;
- владельца;
- правила;
- процессы;
- историю изменений.

Следовательно, оно управляется как инженерная запись.

---

# Последствия

Каждое рабочее пространство должно иметь:


OM

WP

WO

Lifecycle


---

# Связанные документы

BOOK-03:

- ST-011 Operating Manual
- ST-012 Work Protocol
- ST-013 Framework Initialization
- ST-016 Workspace Lifecycle
