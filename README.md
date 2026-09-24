# AV Control WEB UI/UX

Репозиторий веб-интерфейсов AV Control: конфигуратор, клиент комнаты, admin UI и сквозной UX.

## Структура

| Путь | Назначение |
|------|------------|
| `src_req/` | Исходные требования и разбиение по capabilities (до OpenSpec) |
| `code/` | Реализация WEB UI (пока пусто) |
| `Консолидированный пакет/` | Авторитетные продуктовые документы (PRD, PSD, Scope, …) |
| `openspec/` | Vendored-клон [OpenSpec](https://github.com/Fission-AI/OpenSpec): CLI, схемы, skills |

Артефакты планирования **продукта** AV Control (`openspec init`) не кладут в этот каталог — инициализируйте отдельный путь, например `planning/` (`openspec init planning --tools cursor`). Черновик `config.yaml` — `src_req/openspec-config.yaml`.

## Методология

Spec-driven development (SDD) + OpenSpec: `src_req` → change (`proposal`, `specs`, `design`, `tasks`) → `code/`.
