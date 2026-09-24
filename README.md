# AV Control WEB UI/UX

Репозиторий веб-интерфейсов AV Control: конфигуратор, клиент комнаты, admin UI и сквозной UX.

## Структура

| Путь | Назначение |
|------|------------|
| `src_req/` | Исходные требования и разбиение по capabilities (до OpenSpec) |
| `code/` | Реализация WEB UI (пока пусто) |
| `Консолидированный пакет/` | Авторитетные продуктовые документы (PRD, PSD, Scope, …) |

Планирование изменений — OpenSpec (`openspec init` в корне продукта). Локальный клон CLI [OpenSpec](https://github.com/Fission-AI/OpenSpec) при необходимости держите отдельно; каталог `openspec/` в рабочей копии в этот репозиторий не входит.

## Методология

Spec-driven development (SDD) + OpenSpec: `src_req` → change (`proposal`, `specs`, `design`, `tasks`) → `code/`.
